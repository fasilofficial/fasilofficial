<h1 align='center'>Hi devs 👋, I'm Muhammed Fasil</h1>
<h3 align="center">Developer | Photographer | Cinephile</h3>


### /about-me
```javascript

app.get("/about-me", (req, res) => {
  res.send({
    firstName: "Muhammed",
    lastName: "Fasil",
    interests: [
      "coding 💻",
      "movie 🎬",
      "music 🎧",
      "photography 📷",
      "travel 🧳",
      "coffee ☕",
    ],
    askMeAbout: ["Web dev", "MERN", "Movies"],
    technologies: {
      programming: ["C", "C++", "Java", "Python", "PHP", "Ruby", "Bash", "TypeScript"],
      frontEnd: ["HTML", "CSS", "JavaScript", "React", "Next"],
      backEnd: ["node.js", "express.js"],
      database: ["mongoDB", "mySQL", "PostgreSQL"],
      testing: ["Jest"],
      other: ["redux toolkit", "Tailwind", "Bootstrap", "Framer Motion", "AOS", "pug", "ejs"]
    },
  });
});

```

### /contact
```javascript

app.get("/contact", (req, res) => {
  res.send({
    email: "muhammedfasilofficial@gmail.com",
    location: {
      city: "Nilambur",
      state: "Kerala",
      county: "India",
    },
    company: "Brototype, Kochi",
    jobTitle: "MERN stack intern",
    website: "https://fasils.vercel.app",
    socialMedia: {
      linkedin: "https://www.linkedin.com/in/mfasilofficial",
      medium: "https://medium.com/@mfasilofficial",
    },
  });
});

```

### Checkout my latest Medium post
[Deep Dive into deeperjs: A Powerful Deep Cloning npm Package](https://medium.com/@mfasilofficial/deep-dive-into-deeperjs-a-powerful-deep-cloning-npm-package-b127a7b7b887)
<br><br>
<h2 align='center'>
  🏃 Okay, bye!
</h2>
