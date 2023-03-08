# Khrustalev Nikita 👋

## 🛠 Contacts
- **Email**: nikita.khrustalev.work@gmail.com
- **Phone/Telegram**: +375 (25) 902-49-42
- **Discord**: SadMearise#0536
- **Linkedin**: [Nikita Khrustalev](https://www.linkedin.com/in/nikita-khrustalev-358a12241/)
- **GitHub**: [@SadMearise](https://github.com/SadMearise)

## 🚀 About Me
3 years of experience in IT, the last year of which is in web development.

## 🛠 Skills
JavaScript, HTML5, CSS3, Sass(SCSS), BEM methodology, Gulp, Webpack, Git, Github, npm, yarn. Have basic expirience with PHP and WordPress. Previously worked with Python and MySQL

## ⌨️ Code examples
#### Decription:
Complete the function scramble(str1, str2) that returns true if a portion of str1 characters can be rearranged to match str2, otherwise returns false.
#### Notes:
- Only lower case letters will be used (a-z). No punctuation or digits will be included.
- Performance needs to be considered.
```
function scramble(str1, str2) {
    let occ = str1.split('').reduce((total, curr) => {total[curr] ? total[curr]++ : total[curr] = 1; return total}, {})

    return str2.split('').every((character) => --occ[character] >= 0 )
}
```
## 💼 Work Experience

### 2022
Working on training projects. Some of them:
- [**Webpack & Gulp build**](https://github.com/SadMearise/gulp-and-webpack-bundle-v.2.0). Build for small web projects. Technologies: HTML, JS, SCSS, Gulp, Webpack.
- [**Antytila**](https://sadmearise.github.io/antytila/dist/). A multi-page website with the following components and features: slider based on Swiper framework, audio player, video connection, album filter, burger menu, smooth transitions to anchors, cross-browser compatibility, adaptive design, etc. Technologies: HTML, JS, SCSS, Gulp, Swiper.
- [**GAO**](https://sadmearise.github.io/registration/dist/). Registration form with various controls: checkboxes, radio buttons, text fields, image uploading, dynamic progress bar, etc. It includes compatibility with different platforms and browsers and adaptive design. Technologies: HTML, JS, SCSS, Gulp, Swiper.

### 2020-2021
Worked on my own Python bot projects for VKontakte and Telegram with connection to the MySQL database. Implemented scripts for working with Chrome and Discord, as well as parsers for collecting information from websites.

## 🎓 Education

**Belarusian State University of Informatics and Radioelectronics (2015-2018)**  
**Faculty**: Engineering and Economics  
**Speciality**: Information systems and technologies in economics

**Courses**: The Modern JavaScript Tutorial, Codecademy: Learn JavaScript, Learn CSS, Learn HTML, Stepik: Python Programming, PHP - first meeting

## 💪 Soft Skills
- **Self-organization**. The long time working from home.  
- **Customer focus**. The projects I've been involved with have ultimately involved working with a client.  
- **Teamwork**. Worked with a designer. Also, when developing the Telegram bot worked in tandem with a targetologist.  
- **Purposefulness**. Interested in bringing projects to completion.  

## 📢 Languages
**English**. A2. Reading technical documentation.  
**Russian**. Native.