# My First ReadME



Repo explaining README.md

```javascript
const handleWin = (letter) => {
  gameIsLive = false;
  if (letter === "x") {
    statusDiv.innerHTML = `${letterToSymbol(letter)} has won!`;
  } else {
    statusDiv.innerHTML = `<span>${letterToSymbol(letter)} has won!</span>`;
  }
};
```

```css
.grid {
    background-color: salmon;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 15px;
    margin-top: 50px;
}
```

```html
<div class="grid">
    <div class="box" id="box-1"></div>
    <div class="box" id="box-2"></div>
    <div class="box" id="box-3"></div>
    <div class="box" id="box-4"></div>
    <div class="box" id="box-5"></div>
    <div class="box" id="box-6"></div>
    <div class="box" id="box-7"></div>
    <div class="box" id="box-8"></div>
    <div class="box" id="box-9"></div>
</div>
```

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

## Steps to installing Tic-Tac-Toe on local machine

1. Go to my [repo](https://github.com/tuhoalyhuynh?tab=repositories)
2. Go to repository for [Tic-Tac-Toe](https://github.com/tuhoalyhuynh/tic-tac-toe)
3. `fork` repository and `clone`
4. In terminal `git clone https://github.com/tuhoalyhuynh/tic-tac-toe` with your clone link
5. `cd` into directory and `open index.html`