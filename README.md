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

## 𝗪𝗵𝗮𝘁 𝗜 𝗨𝘀𝗲

<table>
  <tbody>
    <tr valign="top">
      <td width="25%" align="center">
        <span>𝗖</span><br><br><br>
        <img height="64px" src="https://cdn.svgporn.com/logos/c.svg">
      </td>
      <td width="25%" align="center">
        <span>𝗖#</span><br><br><br>
        <img height="64px" src="https://cdn.svgporn.com/logos/c-sharp.svg">
      </td>
      <td width="25%" align="center">
        <span>𝗝𝗮𝘃𝗮</span><br><br><br>
        <img height="64px" src="https://cdn.svgporn.com/logos/java.svg">
      </td>
      <td width="25%" align="center">
        <span>𝗣𝘆𝘁𝗵𝗼𝗻</span><br><br><br>
        <img height="64px" src="https://cdn.svgporn.com/logos/python.svg">
      </td>
    </tr>
    <tr valign="top">
      <td width="25%" align="center">
        <span>𝗦𝘂𝗯𝗹𝗶𝗺𝗲 𝗧𝗲𝘅𝘁 𝟯</span><br><br><br>
        <img height="64px" src="https://cdn.worldvectorlogo.com/logos/sublime-text.svg">
      </td>
      <td width="25%" align="center">
        <span>𝗚𝗶𝘁</span><br><br><br>
        <img height="64px" src="https://cdn.svgporn.com/logos/git-icon.svg">
      </td>
      <td width="25%" align="center">
        <span>𝗩𝗶𝘀𝘂𝗮𝗹 𝗦𝘁𝘂𝗱𝗶𝗼 𝗖𝗼𝗱𝗲</span><br><br><br>
        <img height="64px" src="https://cdn.svgporn.com/logos/visual-studio-code.svg">
      </td>
    </tr>
  </tbody>
</table>
