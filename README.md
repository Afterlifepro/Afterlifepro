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
