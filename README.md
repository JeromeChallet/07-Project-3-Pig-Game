document.getElementById('score--1');
document.querySelector('.dice').src = `dice-${dice}.png`;
const dice = Math.trunc(Math.random() \* 6) + 1;
