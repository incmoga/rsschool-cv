# Semizhonov Maksim #

## Contact information
* Email: m.a.semizhonov@gmail.com
* Phone: +7 913 538 2755
* Telegram: [@semizhonov](https://t.me/semizhonov)
* GitHub: [incmoga](https://github.com/incmoga)

## About me
As beginner in frontend development, I'm building on the foundation my previous career as an engineer. My previous work taught me discipline, which I now use to master new technologies like React and JavaScript. I love the "magic" of turning code into dynamic user experiences. My goal is to become a skilled frontend developer.

## Skills and Proficiency:
* Programming Languages: HTML5, CSS3, JavaScript(ES6+)
* Frameworks and Libraries: React (basic knowledge), React Router, Axios, Ant Design
* Preprocessors: SASS/SCSS
* Methodologies: BEM
* Version Control: Git, GitHub
* Development Tools: VS Code, Figma, Bash/Unix Shell
* Other: Basic understading of Webpack, REST API integration

## Code example
### Implementation of the Kata from Codewars

Task:  
_Coding in function cutIt, function accept 1 parameter:arr. arr is a string array.  
The first mission: Traversing arr, find the shortest string length.  
The second mission: Traversing arr again, intercept all strings to the shortest string length(Start from index0). you can use one of slice() substring() or substr() do it. return the result after finished the work._

Solution:
```javascript
const cutIt = (arr) => {
    const myArr = arr.slice();
    myArr.sort(function(a,b) {
        return a.length - b.length;         
    });
    
    console.log(myArr[0].length); //Log for debugging
    
    arr.forEach((element, index) => {
        arr[index] = element.slice(0, myArr[0].length);  
    });
    
    console.log(arr); //Log for debugging
    
    return arr;
}
```
## Education
### Higher education
* **Specialist Degree (equivalent to a Master's Degree) in Geophysical Methods of Wells Research**  
    * Tomsk Polytechnic University, 2016
### Courses
* **The Odin Project:** (HTML, CSS, JavaScript)
* **RS Schools Course:** «JavaScript/Front-end. Stage 1» (in progress)
## English Language
* **Russian** - native speaker
* **English** - A2