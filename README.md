<h1 align='center'>Hey <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="32" height="32">, I'm Fasil </h1>
<h4 align="center">DEVELOPER. PHOTOGRAPHER. CINEPHILE.</h4>


### About Me
```typescript

import express, { Express, Request, Response, NextFunction } from "express";
import cors from "cors";

const PORT = 3000;

const app: Express = express();

app.use(cors());
app.use(express.json());

app.get("/about", (req: Request, res: Response) => {
  res.status(200).json({
    fullName: "Muhammed Fasil K",
    interests: [
      "coding 💻",
      "movie 🎬",
      "music 🎧",
      "photography 📷",
      "travel 🧳",
      "coffee ☕",
    ],
    askMeAbout: ["web dev", "mobile dev", "movies"],
    technologies: {
      programmingLanguages: [
        "C",
        "C++",
        "Java",
        "Python",
        "PHP",
        "Ruby",
        "Bash",
        "TypeScript",
      ],
      frontEnd: ["HTML", "CSS", "JavaScript", "ReactJS", "Next.js"],
      backEnd: ["Node.js", "Express.js", "NestJS"],
      databases: ["MongoDB", "MySQL", "PostgreSQL"],
      testing: ["Jest"],
      animationLibraries: ["Framer Motion", "GSAP", "AOS"],
      apiTechnologies: ["REST", "GraphQL"],
      otherLibraries: [
        "Redux Toolkit",
        "Tailwind CSS",
        "Bootstrap",
        "Figma",
        "Pug",
        "EJS",
        "JSON",
        "Data Structures and Algorithms",
        "Zod",
      ],
    },
  });
});

app.get("/contact", (req: Request, res: Response) => {
  res.status(200).json({
    email: "muhammedfasilofficial@gmail.com",
    portfolio: "https://fasils.vercel.app",
    links: {
      linkedin: "https://www.linkedin.com/in/mfasilofficial",
      leetcode: "https://leetcode.com/fasilofficial",
      medium: "https://medium.com/@mfasilofficial",
    },
  });
});

app.use((req: Request, res: Response, next: NextFunction) => {
  res.status(404).json({ message: "Oops! Route not found" });
});

app.use((err: any, req: Request, res: Response, next: NextFunction) => {
  console.error(err.stack);
  res.status(500).json({ message: "Internal Server Error" });
});

app.listen(PORT, () => {
  console.log(`Server is running on http://localhost:${PORT}`);
});


```
