<h1 align='center'>Hi devs <picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="32" height="32">
</picture>, I'm Muhammed Fasil</h1>
<h3 align="center">Developer | Photographer | Cinephile</h3>


### /about-me
```javascript

app.get("/about-me", (req, res) => {
  res.send({
    firstName: "Muhammed",
    lastName: "Fasil",
    pronouns: "He" | "Him",
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
      programming: ["C", "C++", "Java", "Python"],
      frontEnd: ["HTML", "CSS", "JavaScript", "React", "Tailwind"],
      backEnd: ["node.js", "express.js"],
      database: ["mongoDB", "mySql"],
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
    jobTitle: "Full stack intern",
    website: "https://fasils.vercel.app",
    socialMedia: {
      linkedin: "https://www.linkedin.com/in/mfasilofficial",
      medium: "https://medium.com/@mfasilofficial",
    },
  });
});

```
<br><br>
<h2 align='center'>
  <picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1fabf/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1fabf/512.gif" alt="🪿" width="32" height="32">
</picture> Okay, bye!
</h2>
