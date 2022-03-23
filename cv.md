![foto](/images/foto.jpg)
# Gainanov Nikita
---
### Contact informations:
**Phone:** +79274324400<br>
**E-mail:** slesher35@gmail.com<br>
**Discord:** Nikita (@CNikita)<br>
**Telegram:** [username_ru](https://t.me/username_ru)

---
### About myself:
I do analytics and marketing. Lately I have been solving many problems related to front-end development. I want to change my job and become a front-end developer

---
### Skills:
- HTML, CSS
- JavaScript
- Git, GitHub
- VS Code
- React
---

### Code example:
**Human readable duration format KATA from CODEWARS:**
*Your task in order to complete this Kata is to write a function which formats a duration, given as a number of seconds, in a human-friendly way*
```javascript
function formatDuration (seconds) {
  if (seconds == 0) {
    return 'now'
  }
  let [seconds1, resultSeconds] = calcDuration(seconds, 60, 'second')
  let [seconds2, minutes] = calcDuration(seconds1, 60, 'minute')
  let [seconds3, hours] = calcDuration(seconds2, 24, 'hour')
  let [seconds4, days] = calcDuration(seconds3, 365, 'day')
  let [seconds5, years] = calcDuration(seconds4, 1, 'year')
  let resArr = [years, days, hours, minutes, resultSeconds]
  resArr = resArr.filter(element => element != '')
  let resStr = resArr.join(', ')
  if (resStr.lastIndexOf(',') > 0) {
      resStr = resStr.slice(0, resStr.lastIndexOf(',')) 
        + " and" + resStr.slice(resStr.lastIndexOf(',')+1)
  }
  return resStr
}
  
function calcDuration (seconds, number, str) {
  let result = seconds % number
  seconds = Math.trunc(seconds / number)
  if (str=='year') {result = seconds}
  switch (result) {
      case 0: result = ''
        break;
      case 1: result = `${result} ${str}`
        break;
      default: result = `${result} ${str}s`
  }  
  return [seconds, result]
}
```
---
### Courses:
- HTML and CSS Tutorials on the [Htmlacademy](https://htmlacademy.ru/)<br>
- JavaScript on [learnjavascript.ru](https://learn.javascript.ru/) and [codewars](https://www.codewars.com)
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
---
### Languages:
- English \- Elemntary <br>
- Russian \- Native
