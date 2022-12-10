# Sergey Lihachev
***
## Contacts 
***
* Phone: +7 (925) 653-64-80
* Email: liha4ev.sergey@gmail.com
* GitHub: [liha4ini](https://github.com/liha4ini)
## About Me
***
I'm 39 years old. I am a goal-oriented and responsible person. I like to work in a team, but if necessary, I alone can achieve the desired results and solve the problem.
## Skills
***
* HTML
* CSS
* JS (basic)
* React (basic)
* Git
* NextJS (basic)
## Code Example
***
```
function slidesPlugin(numSlide) {
    const slides = document.querySelectorAll('.slide');

    slides[numSlide].classList.add('active')

    for (const item of slides) {
        item.addEventListener('click', () => {
            clearActiveClasses();
            item.classList.add('active');
        })
    }

    function clearActiveClasses() {
        slides.forEach((slide) => {
            slide.classList.remove('active');
        })
    }
}

slidesPlugin(3)
```
## Experience
***
I worked for about a year as a trainee in a 
Autonomous Technologies company.
## Languages
***
* Russian (native)
* English (A1)