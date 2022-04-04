# Kerryalina Delman

## Contact information
* **E-mail:** [daisy.brkn@gmail.com](http://mailto:daisy.brkn@gmail.com)
* **GitHub:** [bndaisy](https://github.com/bndaisy)

## Skills
* HTML5
* CSS3
* JavaScript

## Languages
* **English** - B2
* **Russian** - Native

## Code example
```
const myLanguages = (results) => Object.entries(results)
  .sort(([ , prev], [ , next]) => next - prev)
  .reduce((current, [result, value]) => {
    if (value >= 60) current.push(result);
    return current;
  }, []);
```