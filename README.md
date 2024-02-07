<h1 align='center'>Hi devs 👋, I'm Muhammed Fasil</h1>
<h3 align="center">Developer | Photographer | Cinephile</h3>


### /about-me
```javascript

app.get("/about-me", (req, res) => {
  res.send({
    firstName: "muhammed",
    lastName: "fasil",
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
      programming: ["c", "c++", "java", "python", "php", "ruby", "bash", "typescript"],
      frontEnd: ["html", "css", "javascript", "reactjs", "nextjs"],
      backEnd: ["nodejs", "expressjs"],
      database: ["mongodb", "mysql", "postgresql"],
      testing: ["jest"],
      other: ["redux toolkit", "tailwind", "bootstrap", "framer motion", "aos", "pug", "ejs", "framer-motion"]
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
      city: "nilambur",
      state: "kerala",
      county: "india",
    },
    company: "brototype, kochi",
    jobTitle: "mern stack intern",
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
