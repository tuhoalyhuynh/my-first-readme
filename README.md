# My First ReadME



Repo explaining README.md

## Steps to install on local computer
1. Go to [repo](https://github.com/SEI-ATL/tic-tac-toe) on Github profile
2. `fork` and `clone` repo
3. Clone to local machine
```text
git clone https://github.com/SEI-ATL/tic-tac-toe.git
```
4. Go to `tic-tac-toe` directory
5. Open `index.html` in browser
```text
open index.html
```


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

| Syntax       | Description |
| ------------ | ------------ |
| Header       | Title |
| Paragraph    | Text |

## Steps to installing Tic-Tac-Toe on local machine

1. Go to my [repo](https://github.com/tuhoalyhuynh?tab=repositories)
2. Go to repository for [Tic-Tac-Toe](https://github.com/tuhoalyhuynh/tic-tac-toe)
3. `fork` repository and `clone`
4. In terminal: 
```text
git clone https://github.com/tuhoalyhuynh/tic-tac-toe` (with your clone link)
```
5. `cd` into directory and 
```text
open index.html
```

Body of `index.html`

```html
<body>
  <h1>Tic-Tac-Toe</h1>

  <div class="container">
    <div id="top-left">
      
    </div>
    <div id="top-mid">
      
    </div>
    <div id="top-right">
    
    </div>
    <div id="mid-left">
      
    </div>
    <div id="mid-mid">
      
    </div>
    <div id="mid-right">
      
    </div>
    <div id="bot-left">
      
    </div>
    <div id="bot-mid">
      
    </div>
    <div id="bot-right">
      
    </div>
  </div>

  <h2></h2>

  <footer id="reset">Play Again!</footer>

  <script src="js/app.js"></script>
</body>
```
Some styling used
```css
body{
  background-color: lightcyan;
}

h1 {
  margin: 0 auto 25px auto;
  max-width: 700px;
  font-family: 'Permanent Marker', cursive;
  font-size: 60px;
  text-align: center;
}

.container {
  margin: 0 auto;
  display: grid;
  grid-template-columns: 300px 300px 300px;
  grid-template-rows: 300px 300px 300px;
  background: gray;
  width: 900px;
  height: 900px;
}

#top-left {
  border: 10px solid black;
  text-align: center;
  font-size: 350px;
  line-height: 250px;
  font-family: 'Permanent Marker', cursive;
}
#top-mid {
  border: 10px solid black;
  text-align: center;
  font-size: 350px;
  line-height: 250px;
  font-family: 'Permanent Marker', cursive;
}
```
Sample js function
```js
function winner() {
    if (botLeft === 'X' && botMid === 'X' && botRight ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (midLeft === 'X' && midMid === 'X' && midRight ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (topLeft === 'X' && topMid === 'X' && topRight ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (topLeft === 'X' && midLeft === 'X' && botLeft ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (topMid === 'X' && midMid === 'X' && botMid ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (topRight === 'X' && midRight === 'X' && botRight ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (topLeft === 'X' && midMid === 'X' && botRight ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (topRight === 'X' && midMid === 'X' && botLeft ==='X') {
        document.querySelector('h2').innerHTML = "Player 1 is the winner!";
    } else if (botLeft === 'O' && botMid === 'O' && botRight ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (midLeft === 'O' && midMid === 'O' && midRight ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (topLeft === 'O' && topMid === 'O' && topRight ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (topLeft === 'O' && midLeft === 'O' && botLeft ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (topMid === 'O' && midMid === 'O' && botMid ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (topRight === 'O' && midRight === 'O' && botRight ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (topLeft === 'O' && midMid === 'O' && botRight ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    } else if (topRight === 'O' && midMid === 'O' && botLeft ==='O') {
        document.querySelector('h2').innerHTML = "Player 2 is the winner!";
    }
}
```

| Functions            | Description |
| ------------         | ------------ |
| draw()               | Sets conditions for draw |
| playerTurn()         | Sets conditions for player turns |
| winner())            | Sets conditions for which player wins |
| assignPlayerOne()    | Assigns 'player-one' to class of cell selected |
| assignPlayerTwo()    | Assigns 'player-two' to class of cell selected |