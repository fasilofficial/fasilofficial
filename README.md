<h1 align='center'>Hello devs <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="32" height="32">, Fasil here</h1>
<h4 align="center">DEVELOPER. PHOTOGRAPHER. CINEPHILE.</h4>


### About Me
```typescript

import express, { Express, Request, Response } from "express";

const app: Express = express();

app.get("/about", (req: Request, res: Response) => {
  res.status(200).json({
    fullName: "muhammed fasil k",
    interests: [
      "coding 💻",
      "movie 🎬",
      "music 🎧",
      "photography 📷",
      "travel 🧳",
      "coffee ☕",
    ],
    askMeAbout: ["web dev", "mern", "movies"],
    technologies: {
      programming: [
        "c",
        "c++",
        "java",
        "python",
        "php",
        "ruby",
        "bash",
        "typescript",
      ],
      frontEnd: ["html", "css", "javascript", "reactjs", "nextjs"],
      backEnd: ["nodejs", "expressjs"],
      database: ["mongodb", "mysql", "postgresql"],
      testing: ["jest"],
      animation: ["framer motion", "gsap", "aos"],
      api: ['rest', 'graphql'],
      other: [
        "redux toolkit",
        "tailwind",
        "bootstrap",
        "figma",
        "pug",
        "ejs",
        "json",
        "dsa",
        "zod",
      ],
    },
  });
});

app.get("/contact", (req: Request, res: Response) => {
  res.status(200).json({
    email: "muhammedfasilofficial@gmail.com",
    portfolio: "https://fasils.vercel.app",
    links: {
      linkedin: "https://www.linkedin.com/in/fasilofficial",
      medium: "https://medium.com/@mfasilofficial",
      leetcode: "https://leetcode.com/fasilofficial",
    },
  });
});

export default app;

```

[about](https://shorturl.at/ckCSW) <br />
[contact](https://shorturl.at/iF239)
