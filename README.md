# css

```css
:root {
  --background-color: yellow;
  --color--red: red;
  --color--white: white;
  --color--gray: #212121;
  --color--black: black;
  --font-style: "Secular One";
  --font-size-large: 55px;
  --font-size-medium: 40px;
  --margin: 20px;
  --radius: 10px;
  --border--height: 50px;
  --imge-size: 30px;
  --pepole-size: 40px;
}

* {
  padding: 0px;
  margin: 0px;
}

.start {
  width: 100%;
  height: 100vh;
  display: flex;
  text-align: center;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--background-color);
}

.start .start_tile {
  width: 100%;
  height: 200px;
  margin-bottom: 50px;
  font-size: var(--font-size-large);
  text-shadow: 2px 2px var(--color--red);
}

.start .start_tile h6 {
  cursor: pointer;
  transition-duration: 0.3s;
  border-radius: var(--radius);
}

.start .start_tile h6:hover {
  color: var(--color--white);
  background-color: var(--color--red);
}

.start .start_list h1 {
  cursor: pointer;
  transition-duration: 0.3s;
  margin: var(--margin);
  border-radius: var(--radius);
  font-family: var(--font-style);
  font-size: var(--font-size-medium);
}

.start .start_list h1:hover {
  color: var(--color--white);
  background-color: var(--color--red);
}

.rankbox {
  display: flex;
  position: absolute;
  width: 30%;
  height: 50%;
  bottom: 10px;
  text-align: left;
  justify-content: center;
  border-radius: var(--radius);
  background-color: var(--color--white);
  font-family: "Secular One";
  font-size: 20px;
  overflow-y: scroll;
}

.rankbox::-webkit-scrollbar {
  display: none !important;
}

.main {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: space-evenly;
  background-image: url("img/bg.jpg");
  background-size: 700px;
}

.main .keytext {
  position: absolute;
  left: 13%;
  top: 8%;
  color: var(--color--white);
}

.main .key {
  position: absolute;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  width: 100px;
  height: 100px;
  left: 10%;
  top: 15%;
  color: var(--color--gray);
  border-radius: var(--radius);
  font-size: var(--font-size-medium);
  background-color: var(--color--white);
}

.main .colock {
  color: var(--color--white);
  font-family: var(--font-style);
  font-size: var(--font-size-large);
}

.main .game {
  width: 80%;
  height: 200px;
  border-radius: var(--radius);
  background-color: var(--color--white);
  background-image: url(img/bgg.png);
  background-size: var(--border--height);
}

.main .game .border {
  display: flex;
  height: var(--border--height);
}

.pepole {
  position: relative;
  right: 0px;
  left: 10%;
  top: 0px;
  font-size: var(--pepole-size);
}

.block {
  position: relative;
  width: 20px;
  height: 20px;
  top: 0px;
  left: 90%;
  color: var(--ball-color);
  font-size: var(--imge-size);
  animation: block infinite linear forwards 1s;
}

.block_2 {
  position: relative;
  width: 20px;
  height: 20px;
  top: 0px;
  left: 90%;
  color: var(--ball-color);
  font-size: var(--imge-size);
  animation: block infinite linear forwards 2s;
}

.block_3 {
  position: relative;
  width: 20px;
  height: 20px;
  top: 0px;
  left: 90%;
  color: var(--ball-color);
  font-size: var(--imge-size);
  animation: block infinite linear forwards 3s;
}

@keyframes block {
  0% {
    left: 90%;
  }
  50% {
    left: 50%;
  }
  100% {
    left: 0%;
  }
}

/*동적 움직임*/
.gamepage {
  display: none;
}

.page_back {
  display: none;
}

.list {
  display: none;
}

.fa-caret-square-up.up {
  color: red;
}

.fa-caret-square-down.down {
  color: red;
}


```
