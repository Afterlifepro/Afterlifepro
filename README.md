## Hiya!  
<img src="https://afterlifepro.neocities.org/static/media/dw%20gayyyy.b8c4c128d2dc55072edc.png" align="right" width="100px" />
I like doing react stuff!  

I think doctor who, neocities, and dnd are pretty neato  
### [Heres my neocities](https://afterlifepro.neocities.org/)
### Heres an ascii spinner in html
```html
<div id="spinner" onclick="nextStep()">/</div>

<style>
  body, html { margin: 0; color-scheme: dark light;
    #spinner {
      width: 100vw; height: 100vh;
      display: flex;
      align-items: center; justify-content: center;
      font-family: monospace; font-size: 120pt;
    }
  }
</style>

<script>
  const steps = [
    "\\|/-", [":)", ":|", ":(", ":|"],
    "⣾⣽⣻⢿⡿⣟⣯⣷", "\\-/|",
    ["⢎⡰", "⢎⡡", "⢎⡑", "⢎⠱", "⠎⡱", "⢊⡱", "⢌⡱", "⢆⡱"],
    "▁▃▄▅▆▇█▇▆▅▄▃", ["◜ ", " ◝", " ◞", "◟ "],
  ];

  let cycle = 1;
  const spinner = document.getElementById("spinner");
  const spins = (step) => {
    spinner.innerHTML = steps[cycle][step];
    setTimeout(() => { spins((step + 1) % steps[cycle].length); }, 100);
  };
  const nextStep = () => { cycle = (cycle + 1) % steps.length; };
  spins(0);
</script>

```

# 💻 Tech Stack:
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220) ![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api/top-langs/?username=afterlifepro&theme=radical&hide_border=false&include_all_commits=true&count_private=false&layout=compact)
---
[![](https://visitcount.itsvg.in/api?id=afterlifepro&icon=0&color=0)](https://visitcount.itsvg.in)
