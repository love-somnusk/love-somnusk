### Hi there š

<!--
**love-somnusk/love-somnusk** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
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
