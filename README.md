# ReadMePro
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://opensource.org/licenses/MIT)

[GitHub Repo](https://github.com/lonewolfco/readmegen)



## Table of Contents
- [Description](#description)
- [UI & Video Walkthrough of Application](#video)
- [User Story](#userstory)
- [Acceptance Criteria](#ac)
- [Languages Used](#languages)
- [License](#license)

---

## [Description](#description)
<a name="description"></a>
ReadMeGen is a command line application that does the legwork for developers when it comes to generating a ReadMe file for their source projects on GitHub so developers can spend more time building their projects. 

ReadMeGen will help the user build a dynamic ReadMe file containing the following key points:
- What the App is used For
- How to use the app
- How to install the app
- How to Report Issues
- How to make Contributions

In order to utilize ReadMeGen, the user will interact with the generator via node.js by entering the syntax node index.js on an integrated terminal.


## [UI & Video Walkthrough of Application](#video)
<a name="video"></a>

[![Watch the video](https://cdn.loom.com/sessions/thumbnails/eb4710d5ec10446a8fea149dd94e5b7e-with-play.gif)](https://www.loom.com/share/eb4710d5ec10446a8fea149dd94e5b7e)



## [User Story](#userstory)
<a name="userstory"></a>
```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```


## [Acceptance Criteria](#ac)
<a name="ac"></a>
``` md
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```



## [Languages Used](#languages)
<a name="languages"></a>
HTML, JavaScript, Node.JS, Inquirer npm package




## [License](#license)
<a name="license"></a>

© 2022 LoneWolfCo
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
