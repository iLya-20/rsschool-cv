# Ilya Shaytor
**+375 (29) 853-18-45**
_For a long time I dreamed of becoming a lawyer, but then I realized that I want to work from anywhere in the world and because of this I decided to take my life with an IT specialty, when I just started to learn about it, this specialty hooked me very much.
sociable and cheerful guy who wants to live. Have experience in working with HTML and CSS_
HTML and CSS

const $buttons = $('.dramm-mashine-box__top button');
const keyMap = new Map();
$buttons.each((i, btn) => {
  keyMap.set(btn.innerHTML, btn);
});

function handleButtonPress() {
  $(this).addClass('pressed');
}

function handleButtonUnPress() {
  $(this).removeClass('pressed');
}

$(document).on('keypress', function (event) {
  const code = event.key;
  const button = keyMap.get(code);
  if(button) handleButtonPress.call(button);
});


$(document).on('keyup', function (event) {
  const code = event.key;
  const button = keyMap.get(code);
  if(button) handleButtonUnPress.call(button);
});
button.pressed {
   outline: 1px solid yellow;
}
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<div class="dramm-mashine-box__top">
    <button type="button" class="btn" id="btn-1">1</button>
    <button type="button" class="btn" id="btn-2">2</button>
    <button type="button" class="btn" id="btn-3">3</button>
    <button type="button" class="btn" id="btn-4">4</button>
    <button type="button" class="btn" id="btn-5">5</button>
    <button type="button" class="btn" id="btn-6">6</button>
    <button type="button" class="btn" id="btn-7">7</button>
    <button type="button" class="btn" id="btn-8">8</button>
    <button type="button" class="btn" id="btn-9">9</button>
    <button type="button" class="btn" id="btn-0">0</button>
</div>
**No Junior Dev experience but i want to get it**
*BIP - University of Law and Social Information Technologies*
__English level: B1__
