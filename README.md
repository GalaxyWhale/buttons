# buttons
<!doctype html>

<title>Buttons</title>



<style>

button {

  font-size: 24px;

}

#pinkButton {

  background-color: pink;

}

#orangeButton {

  background-color: orange;

}

#clearButton {

  background-color: white;

}

#blueButton {

  background-color: blue;

  color: white;

}

#purpleButton {

  background-color: purple;

  color: white;

}

#redButton {

  background-color: red;

  color: white;

}

#greenButton {

  background-color: green;

  color: white;

}

#yellowButton {

  background-color: yellow;

}

#greyButton {

  background-color: gray;

}

#blackButton {

  background-color: black;

  color: white;

}

</style>



<button id="pinkButton">Pink Button</button>

<button id="orangeButton">Orange Button</button>

<button id="blueButton">Blue Button</button>

<button id="purpleButton">Purple Button</button>

<button id="redButton">Red Button</button>

<button id="greenButton">Green Button</button>

<button id="yellowButton">Yellow Button</button>

<button id="blackButton">Black Button</button>

<button id="greyButton">Grey Button</button>

<button id="clearButton">Clear Button</button>



<script>

function makeBackgroundPink() {

  document.body.style.backgroundColor = 'pink';

}

pinkButton.onclick = makeBackgroundPink;



function makeBackgroundOrange() {

  document.body.style.backgroundColor = 'orange';

}

orangeButton.onclick = makeBackgroundOrange;



function makeBackgroundBlue() {

  document.body.style.backgroundColor = 'blue'

}

blueButton.onclick = makeBackgroundBlue;





function makeBackgroundPurple() {

  document.body.style.backgroundColor = 'purple'

}

purpleButton.onclick = makeBackgroundPurple;



function makeBackgroundRed() {

  document.body.style.backgroundColor = 'red'

}

redButton.onclick = makeBackgroundRed;



function makeBackgroundGreen() {

  document.body.style.backgroundColor = 'green'

}

greenButton.onclick = makeBackgroundGreen;



function makeBackgroundYellow() {

  document.body.style.backgroundColor = 'yellow'

}

yellowButton.onclick = makeBackgroundYellow;



function makeBackgroundBlack() {

  document.body.style.backgroundColor = 'black'

}

blackButton.onclick = makeBackgroundBlack;



function makeBackgroundGrey() {

  document.body.style.backgroundColor = 'grey'

}

greyButton.onclick = makeBackgroundGrey;



function clearBackground() {

  document.body.style.backgroundColor = ''

}

clearButton.onclick = clearBackground;



</script>
