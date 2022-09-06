# Anastasiia Pliuta

## Junior Front-end developer

### Contact information:

##### Phone: +38-062-710-4229
##### Email: <koicheva1996@gmail.com>
##### Telegram: [Anastasiia Pliuta](https://t.me/pliutanastya)
##### GitHub: [Anastasiia Pliuta](https://github.com/PliutaNastya)

### About me:
I am 26 years old and I live in Odessa. I attended the Odessa National University and received my masters degree with honors in Chemistry. I have worked for nearly 3 year as a chemist, but  near 7 month ago I was interested Front-end development . I started to watch educational video on YouTube and successfully completed courses in [Hillel](https://online.ithillel.ua/). I studied HTML, CSS, SASS/SCSS, BEM, GIT. Now I'm taking a new courses, and learning JavaScript, React. 

### Skills:

* HTML
* CSS/SCSS (Bootstrap, BEM)
* GIT/GitHub/GitLab
* JavaScript
* VS Code/WebStorm
* Figma/Photoshop

### Code example:

** Task from CodeWars: ** * Deoxyribonucleic acid (DNA) is a chemical found in the nucleus of cells and carries the "instructions" for the development and functioning of living organisms. In DNA strings, symbols "A" and "T" are complements of each other, as "C" and "G". Your function receives one side of the DNA (string, except for Haskell); you need to return the other complementary side. DNA strand is never empty or there is no DNA at all (again, except for Haskell). *

```javascript
function DNAStrand(dna){
  let str = '';
  for(let letter of dna) {
    if (letter.includes('A')) {
      letter = 'T';
    } else if(letter.includes('C')) {
      letter = 'G';
    } else if(letter.includes('G')) {
      letter = 'C';
    } else if(letter.includes('T')) {
      letter = 'A';
    }
    str = `${str}${letter}`
  }
  return str;
}

console.log(DNAStrand('ATTGC'))
```