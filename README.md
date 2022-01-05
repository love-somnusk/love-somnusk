### Hi there 👋

<!--
**love-somnusk/love-somnusk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```julia
module main

aboutMe :: struct {
  pronouns :: string[];
  languages :: string[];
  hobbies :: string[];
  funFact :: string;
}

main :: func(): void {
  ethan :: aboutMe = {
    pronouns: ["He", "Him"],
    languages: ["C", "C#", "Java", "Python"],
    hobbies: ["Coding", "Gaming", "Talking"],
    funFact: "The first computer virus was created in 1983!"
  };

  println "Pronouns: ${ethan.pronouns}";
  println "Languages I Know: ${ethan.languages}";
  println "My Hobbies: ${ethan.hobbies}";
  println "Fun Fact: ${ethan.funFact}";
}
```
