```typescript

interface DeveloperProps {
    name: string;
    age: number;
    languages: string[];
    role: string;
    university: string;
    email: string;
    linkedin: string;
    instagram: string;
    status: string;
}

class Developer {
    constructor(private props: DeveloperProps) {}

    greet(): void {
        console.log("Hello There! :)");
    }
}

const agustin = new Developer({
    name: "Agustin Lasalvia",
    age: 24,
    languages: ["Spanish", "English"],
    role: "Junior Developer",
    university: "ORT University",
    email: "agus.blumenfeld13@gmail.com",
    linkedin: "https://www.linkedin.com/in/agustin-lasalvia",
    instagram: "https://www.instagram.com/agustin.lasalvia",
    status: "Searching for a Junior Developer Position"
});

agustin.greet();
