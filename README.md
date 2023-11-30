<h1 align='center'>Hi devs 👋, I'm Muhammed Fasil</h1>
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

### Checkout my latest Medium post
[Unlocking the Power of JavaScript ES6: Features You Should Be Using in Your Projects](https://medium.com/@mfasilofficial/unlocking-the-power-of-javascript-es6-features-you-should-be-using-in-your-projects-d1d31562a87e)
<br><br>
<h2 align='center'>
  🏃 Okay, bye!
</h2>
