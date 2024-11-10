function Character(name, age, hobby) {
  this.name = name;
  this.age = age;
  this.hobby = hobby;
}

Character.prototype.bio = function() {
  return `Hi there, I'm ${this.name}, a ${this.age}-year-old who loves working with ${this.hobby}!`;
}

Character.prototype.interests = ['programming', 'workout', 'hanging out with friends'];

const sourav = new Character('Sourav', 16, 'Node.js');
console.log(sourav.bio());
console.log(`My interests include: ${sourav.interests.join(', ')}.`);


<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>
