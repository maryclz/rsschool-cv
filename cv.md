# Klishina Mary

UI/UX, graphic. digital designer

## Contact information

**Phone:** +38 095 3856 689

**E-mail:** klishinamary@gmail.com

**Telegram:** @marie_kli

[Behance](https://www.behance.net/klishinama255b)

## Briefly About Myself

Good day! I am a web designer, UI / UX and graphic designer, I have experience with raster and vector graphic editors for more than 2 years, I know the principles of preparing layouts for printing. I also know how to draw by hand on a graphics tablet.
I am looking for work in a friendly and professional team to improve my design skills.

## Skills and Proficiency

- HTML5, CSS3
- Figma
- Adobe Photoshop, Illustrator, InDesign, After Effects

## Courses

- "UX / UI. Design and design of interfaces" from  [Creative Practice](https://cases.media/cert/UVDT5Q) (completed)

## Code example

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}

## Languages

- English \- Intermediate
- Russian \- Native
- Ukrainian \- Native
