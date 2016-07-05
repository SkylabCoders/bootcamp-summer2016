# Full Stack Web Development Bootcamp
## Summer2016 - SkylabCoders Academy

by [JuanMa Garrido](#trainer)

<!-- ######################## COVER ######################## --> 

!SLIDE #MainCover no-bullet-list
 
## Full Stack Web Development Bootcamp
### Summer2016

- GIT & GITHUB
- Javascript
- HTML5
- CSS3
- Bootstrap
- jQuery
- Angular
- Node
- ES2015
- Express
- MongoDB

<!-- ######################## TEACHER ######################## --> 

!SLIDE #trainer no-bullet-list

## Teacher: JuanMa Garrido
 
<ul>
<li><a class="icon-envelope" href="mailto:JuanMa.Garrido@gmail.com" target="_blank">JuanMa.Garrido@gmail.com</a></li>
<li><a class="icon-twitter" href="https://twitter.com/juanmaguitar" target="_blank">@juanmaguitar</a></li>
<li><a class="icon-linkedin" href="http://www.linkedin.com/in/juanmagarrido" target="_blank">http://www.linkedin.com/in/juanmagarrido</a></li>
<li><a class="icon-github" href="https://github.com/juanmaguitar" target="_blank">https://github.com/juanmaguitar</a></li>
</ul>

<ul>
<li><a class="icon-pixelovers" href="http://pixelovers.com" target="_blank">https://pixelovers.com</a></li>
<li><a class="icon-twitter" href="https://twitter.com/pixelovers" target="_blank">@pixelovers</a></li>
<li><a class="icon-book" href="http://apuntesjs.com" target="_blank">Apuntes de Javascript</a></li>

</ul>

<!-- ######################## CONTENTS ######################## --> 

!SLIDE contents general list-contents 

## Contents

<ul>
  <li><span class="icon-calendar-empty"> [Basic Tools](#git)</li>
  <li><span class="icon-calendar-empty"> [Javascript](#javascript)</li>
  <li><span class="icon-calendar-empty"> [HTML5](#html5)</li>
  <li><span class="icon-calendar-empty"> [CSS3](#css3) </li>
  <li><span class="icon-calendar-empty"> [Bootstrap](#bootstrap)</li>
  <li><span class="icon-calendar-empty"> [jQuery](#jquery)</li>
  <li><span class="icon-calendar-empty"> [angular.js](#angular)</li>
  <li><span class="icon-calendar-empty"> [Node](#node)</li>
  <li><span class="icon-calendar-empty"> [ES2015](#es2015)</li>
  <li><span class="icon-calendar-empty"> [Express](#express)</li>
  <li><span class="icon-calendar-empty"> [MongoDB](#mongo)</li>
  <li><span class="icon-calendar-empty"> [Projects](#projects)</li>
  
</ul>

<!-- ######################## BASIC TOOLS ######################## --> 

!SLIDE #git coverSession git 

<section class="logos">
  <div class="box">
    ![git logo](img/git_logo.png)
    ![github logo](img/Octocat.png)
    ![sublime logo](img/Sublime_Text_Logo.png)
    ![chrome logo](img/chrome-logo.png)
  <div>
</section>
 
## Web Development Bootcamp 
### **Basic** Tools  

!SLIDE git

## Sublime Text

- [**Sublime Text**](https://www.sublimetext.com/)
  - [Installation, Package Control, Command Palette, Edition](https://scotch.io/bar-talk/the-complete-visual-guide-to-sublime-text-3-getting-started-and-keyboard-shortcuts)
  - [Change Theme, Search, MiniMap](https://scotch.io/bar-talk/the-complete-visual-guide-to-sublime-text-3-themes-color-schemes-and-cool-features)
    - Theme Monokai
  - [Plugins](https://scotch.io/bar-talk/the-complete-visual-guide-to-sublime-text-3-plugins-part-1)
    - Emmet
    - Markdown Editing & Markdown Preview
  - Use the alias `subl` from command line <a class="icon-windows ml-xl" href="http://wesbos.com/subl-on-windows/"></a> <a style="margin-left:40px !important;" class="icon-apple ml-xl" href="http://www.tunnelsup.com/how-to-open-sublime-text-from-the-command-line-using-mac-osx"></a>

<!-- ######################## CONTENTS ######################## --> 

!SLIDE git

## Command Line

- [The Command Line](http://cli.learncodethehardway.org/book/)
  - Make A Directory `mkdir`
  - Change Directory `cd` 
  - List Directory `ls` 

- [**Cmder**](http://cmder.net/) => Command line for Windows Users
  - [Guide for setting up Sublime](http://laravel.io/forum/02-24-2014-a-neat-way-integrate-cmder-and-sublime-text-seamlessly) 
  - [Sublime 3 Portable](https://download.sublimetext.com/Sublime%20Text%20Build%203083.zip) 


- [**Learn the Command Line** | codeCademy](https://www.codecademy.com/learn/learn-the-command-line)

!SLIDE git

## Markdown

- [**Markdown**](https://daringfireball.net/projects/markdown/syntax)
  - [Markdown Guide](https://blog.ghost.org/markdown/) [[1]](http://markdown-guide.readthedocs.org/en/latest/basics.html)

!SLIDE git

## Developer Tools

- [**Chrome Developer Tools**](https://developers.google.com/web/tools/chrome-devtools/)
  - [Edit Styles](https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/edit-styles)
  - [Edit the DOM](https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/edit-dom)

!SLIDE git exercise

## <span class="icon-laptop"></span> Markdow practice

Do the following exercises to practice the markdown syntax [http://markdowntutorial.com/lesson/1/](http://markdowntutorial.com/lesson/1/)

!SLIDE git install

## Git

- [Version Control](http://git-scm.com/video/what-is-version-control). [What?](https://diigo.com/08braq) [Why?](https://diigo.com/08brk8)
- [**Git**](http://git-scm.com/)
  - Installation from [http://git-scm.com/downloads](http://git-scm.com/downloads) <div class="block-icons"><a class="icon-windows ml-xl" href="http://git-for-windows.github.io/"></a> <a class="icon icon-warning-sign ml-m" href="https://github.com/bower/bower#windows-users"></a></div>   
  - [Command Line or GUI](https://www.git-tower.com/learn/git/ebook/command-line/basics/getting-ready#chapter) <div class="block-icons"><a class="icon-windows ml-xl" href="https://tortoisegit.org/"></a> <a style="margin-left:40px !important;" class="icon-apple ml-xl" href="https://www.git-tower.com/"></a> <a class="icon-" href="https://www.sourcetreeapp.com/"> <span class="icon-windows ml-xl"></span><span class="icon-apple ml-xl"></span></a> </div>
  - [Basic Configuration](https://www.git-tower.com/learn/git/ebook/command-line/basics/getting-ready#chapter) `git config`
  - [Git Workflow](https://diigo.com/08brpz) <a class="icon-tasks" href="http://rogerdudler.github.io/git-guide/"></a>
  - [Local Repository (and first steps)](https://www.git-tower.com/learn/git/ebook/command-line/basics/starting-with-an-unversioned-project#start) `git init`
  - [Working w/ existing Project on a Server](https://www.git-tower.com/learn/git/ebook/command-line/basics/starting-with-a-remote-project#start) `git clone`

!SLIDE git setup

## Setting up our Git environment

Colors in the git commands 
```bash
  git config --global color.ui true
```

<span class="icon-apple ml-xl"></span> Only for Mac  

- Execute this in your terminal : `git clone https://github.com/addyosmani/dotfiles.git && cd dotfiles && ./sync.sh`
- More [dotfiles](https://dotfiles.github.io/)

!SLIDE git

## Git

* [Working on Your Git Project](https://www.git-tower.com/learn/git/ebook/command-line/basics/working-on-your-project#start) 
  * Staging Area `git add`
  * View your changes `git status`
  * Committing Your Work `git commit`
  * Commit History `git log`

!SLIDE git image workflow

![staging-area-file-status](img/staging-area-file-status.png)

!SLIDE git

## Git

- Remote repositories
  - [Connecting a Remote Repository](https://www.atlassian.com/git/tutorials/syncing/git-remote) `git remote add` [[1]](https://diigo.com/08brzy)
  - [_Uploading_ data to a Remote Repository](https://www.atlassian.com/git/tutorials/syncing/git-push) `git push`
  - [_Integrating_ remote changes](https://www.atlassian.com/git/tutorials/syncing/git-pull) `git pull` => [`git fetch`](https://www.atlassian.com/git/tutorials/syncing/git-fetch) + `git merge`

!SLIDE git image remote

![basic-remote-workflow](img/basic-remote-workflow.png)

!SLIDE git exercise

## <span class="icon-laptop"></span> Git practice

Complete the following step-by-step exercise to practice the git commands and workflow [https://try.github.io/levels/1/challenges/1](https://try.github.io/levels/1/challenges/1)

!SLIDE git

## Git

- [Undo changes](https://www.atlassian.com/git/tutorials/undoing-changes/) [[1]](http://justinhileman.info/article/git-pretty/git-pretty.png)
  - `git reset` => remove from the staging area
  - `git checkout master` => get back to the “current” state (latest commit) of the project


!SLIDE git

## GitHub

- [GitHub](https://github.com/)
  - [Set Up Git](https://help.github.com/articles/set-up-git/)
  - [Authentication with GitHub from Git](https://help.github.com/articles/set-up-git/#next-steps-authenticating-with-github-from-git)
  - [Create a Repository](https://help.github.com/articles/create-a-repo/)
  - [**Fork a Repository**](https://help.github.com/articles/fork-a-repo/)

<span class="fa fa-github-alt"></span> [Find interesting projects on GitHub to clone and fork](https://github.com/explore )  

!SLIDE git exercise small

## <span class="icon-laptop"></span> Git practice

Create a folder called `notes-bootcamp` and inside of it create a file named `README.md` containing 3 interesting ideas you have learned today and then:

- initiliaze a git repository
- `add` this new file to the repo
- `commit` the change
- add 2 more interesting ideas to the `README.md`
- `add` this new file to staging
- `commit` this new change
- check the `log` of commits 

!SLIDE git exercise

## <span class="icon-laptop"></span> Git practice

- Create a remote repo on github called `notes-bootcamp` 
- Add this remote repo (`git remote add`) to your local repo
- `push` your changes to the remote repo
- add 4 more interesting ideas to the `README.md`
- `add` & `commit`  your change to the local repo
- sync w/ the remote repo (`push`ing your latest changes)


!SLIDE git

## Basic Tools _cheatsheets_

<span class="fa fa-file-pdf-o"></span> [Git Cheat Sheet | GitHub](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)  
<span class="fa fa-external-link"></span> [Emmet](http://docs.emmet.io/cheat-sheet/)  
- [Git CheatSheet | git-tower.com](http://www.git-tower.com/blog/git-cheat-sheet/)
- [Git Every Day | kernel.org](https://www.kernel.org/pub/software/scm/git/docs/giteveryday.html)
- [Basic Git Commands | atlassian](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)  


!SLIDE git

## More resources for this Unit

- [**Learn Git** | codeCademy](https://www.codecademy.com/es/learn/learn-git)
- [**Learn the Command Line** | codeCademy](https://www.codecademy.com/learn/learn-the-command-line)

- [_Sublime Text Tutorials_](https://www.youtube.com/watch?v=k01udDD-UwI&list=PLLnpHn493BHEYF4EX3sAhVG2rTqCvLnsP) | [Sublime Tutor](https://sublimetutor.com/)
- [Sublime Text Book](https://sublimetextbook.com/)

- [Git tutorials | atlassian](https://www.atlassian.com/git/tutorials/setting-up-a-repository) | [Tutorial Videos | git-tower.com](https://www.git-tower.com/learn/git/videos#episodes) 
- [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)


!SLIDE git

## Free Books for this Unit

- [Pro GIT, 2nd Edition](http://www.etnassoft.com/biblioteca/pro-git-2nd-edition/)
- [GIT Community Book](http://www.etnassoft.com/biblioteca/git-community-book/)


<!-- ######################## JAVASCRIPT ######################## --> 

!SLIDE #javascript coverSession javascript

<section class="logos">
  <div class="box">
    ![Javascript Logo](img/JavaScript-logo.png)
  <div>
</section>
 
## Web Development Bootcamp 
### **Javascript**

!SLIDE javascript

## Javascript Basics

- [Clear Ideas, JS History, ECMAScript](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/01-clear-ideas)
- [Variables, Data Types and Operators](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/02-variables-data-types-operators)
- [Conditions and Loops](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/03-conditions-loops)
- [Functions (Predefined, Callback, Closures...)](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/04-functions)
- [Arrays and Objects (Constructors)](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/05-arrays-objects)
- [Global Objects (Object, Function, Array, Number, Boolean, Math and Date)](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/06-global-objects)


!SLIDE javascript

## Working w/ Primitives vs Objects

![Reference vs Value](img/pass-by-reference-vs-pass-by-value-animation.gif)


!SLIDE javascript smallcode

```javascript
>>> var number = 10;
>>> var newNumber = number;
>>> newNumber = newNumber + 1000;
>>> number
10

>>> var arrayNumbers = [1,2,3,4]
>>> var newArrayNumbers = arrayNumbers
>>> newArrayNumbers.push(10)
>>> arrayNumbers
[1, 2, 3, 4, 10]

>>> var book = { title: "1984", author: "Orwell" }
>>> var newBook = book
>>> newBook.title = "Old Man and the Sea"
>>> book.title
"Old Man and the Sea"
```

!SLIDE javascript

```javascript
>>> var book = { title: "1984", author: "Orwell" }
>>> var newBook = book
>>> newBook.title = "Old Man and the Sea"
>>> book.title
"Old Man and the Sea"
```


!SLIDE javascript exercise

## <span class="icon-laptop"></span> Practice Javascript

Choose a partner and do the following exercises online (in pairs) to practice Javascript

- Do exercises from [Comment your JavaScript Code](https://www.freecodecamp.com/challenges/comment-your-javascript-code) to [Invert Regular Expression Matches with JavaScript](https://www.freecodecamp.com/challenges/invert-regular-expression-matches-with-javascript)


!SLIDE javascript smallcode

```javascript
var a; typeof a;
var s = '1s'; s++; 
!!"false"
!!undefined
undefined == null
false == ""
false === ""
typeof "2E+2"
a = 3e+3; a++;
```

What will be the result of executing these lines in the console? Why?

!SLIDE javascript smallcode

```javascript
var v = v || 10;
var v = 100; 
var v = v || 10; 
var v = 0; 
var v = v || 10;
var v = null; 
var v = v || 10;
```

What is the value of `v` after this?

!SLIDE javascript smallcode

```
var x = 'Hello World';
function foo(){
    var x;
    alert( x );
    x = 'New Value';
    alert( x );
}
foo();
```

What will return the `alert`s? Why?

!SLIDE javascript smallcode

```
function test() {
    foo();
    bar();
    var foo = function () {
        alert("this won't run!");
    }
    function bar() {
        alert("this will run!");
    }
}
test();

```

What will return the execution of `test()`? Why?

!SLIDE javascript smallcode

```
var a = 1;
function f() {
    var a = 2;
    function n() {
        alert(a);
    }
    n();
}
f();

```

What will show this code in the `alert()`? Why?

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Challenge 1

- Do the exercises suggested at https://github.com/juanmaguitar/exercises-javascript/tree/master/01-first-steps

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Challenge 1** Extra

- Do the exercises suggested at https://github.com/juanmaguitar/exercises-javascript/tree/master/06-extra-exercises


!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Challenge 2

- Do the exercises suggested at https://github.com/juanmaguitar/exercises-javascript/tree/master/02-more-steps

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Challenge 3

- Do the exercises suggested at https://github.com/juanmaguitar/exercises-javascript/tree/master/03-and-more

!SLIDE javascript

## Javascript Advanced

- [Functions Scope in depth](https://toddmotto.com/everything-you-wanted-to-know-about-javascript-scope/)
- [Array Object and Higher Order Functions (Functional Programming)](https://github.com/juanmaguitar/javascript-notes/blob/master/markdown-en/06-global-objects/arrays)
- [Regular Expressions](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/08-regular-expressions)
- [El valor de `this`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this) [[1]](http://unschooled.org/2012/03/understanding-javascript-this/)

!SLIDE javascript

## TDD

- [Unit Testings](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/07-TDD#1--unit-testings)
- [TDD y BDD](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/07-TDD#2--tdd-y-bdd)
- [Testing Frameworks](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/07-TDD#3--testing-frameworks) 
- [Testing Runners](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/07-TDD#4--testing-runners) 

!SLIDE javascript

## Jasmine

- [Jasmine](http://jasmine.github.io/edge/introduction.html) [[1]](http://addyosmani.github.com/backbone-fundamentals/#jasmine)
  - [Suites `describe` & Specs `it`](http://jasmine.github.io/edge/introduction.html#section-It&rsquo;s_Just_Functions) [1](http://addyosmani.github.com/backbone-fundamentals/#suites-specs-spies)
  - [Expectations & Matchers `expect(true).toBe(true)`](http://jasmine.github.io/edge/introduction.html#section-Matchers)
  
!SLIDE javascript

## Jasmine Advanced

- [Grouping Related Specs with `describe`](http://jasmine.github.io/edge/introduction.html#section-Grouping_Related_Specs_with_<code>describe</code>)
    - [Setup `beforeEach` and Teardown `afterEach`](http://jasmine.github.io/edge/introduction.html#section-Setup_and_Teardown)
* [Spies](http://jasmine.github.io/edge/introduction.html#section-Spies)
  * [Spy cheatsheet](http://tobyho.com/2011/12/15/jasmine-spy-cheatsheet/)
* [jQuery matchers and fixture loader](https://github.com/velesin/jasmine-jquery)
* [Faking response AJAX](https://github.com/jasmine/jasmine-ajax)

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Koan

- Group yourselves in pairs
- Read the following tutorial together: http://javascript.didacto.net/
- Do the exercises together when suggested
- Reach till the _Fibonacci Challenge_ (included)

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Kata: Drink About

- Group yourselves in pairs
- Do the following kata by doing pair programming and applying TDD: https://github.com/juanmaguitar/exercises-katas-js/tree/master/DrinkAbout
- Use Jasmine as test runner

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Kata: Grade Boook

- Group yourselves in pairs
- Do the following kata by doing pair programming and applying TDD: https://github.com/juanmaguitar/exercises-katas-js/tree/master/GradeBook
- Use Jasmine as test runner

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Kata: Fizz Buzz

- Group yourselves in pairs
- Do the following kata by doing pair programming and applying TDD: https://github.com/juanmaguitar/exercises-katas-js/tree/master/FizzBuzz
- Use Jasmine as test runner

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Kata: Rock Paper Scissors

- Group yourselves in pairs
- Do the following kata by doing pair programming and applying TDD: https://github.com/juanmaguitar/exercises-katas-js/tree/master/RockPaperScissors
- Use Jasmine as test runner

!SLIDE javascript exercise

## <span class="icon-laptop"></span> Javascript Kata: Password Validation

- Group yourselves in pairs
- Do the following kata by doing pair programming and applying TDD: https://github.com/juanmaguitar/exercises-katas-js/tree/master/PasswordValidation
- Use Jasmine as test runner


!SLIDE javascript no-bullet-list resources

## More resources for this Unit

- <span class="fa fa-youtube"></span> [Javascript fundamentals](https://www.youtube.com/watch?v=JTpjqYjrPyU) _7h_  
- <span class="fa fa-book"></span> [Test Driven JavaScript Development](http://www.amazon.es/Driven-JavaScript-Development-Developers-Library/dp/0321683919)
- <span class="fa fa-link"></span> [Testing Your JavaScript with Jasmine](http://code.tutsplus.com/tutorials/testing-your-javascript-with-jasmine--net-21229)
- <span class="fa fa-github"></span> [JS Unit Testing Guide](https://github.com/mawrkus/js-unit-testing-guide)
- <span class="fa fa-external-link"></span> [Advanced Javascript](http://ejohn.org/apps/learn/)
- <span class="fa fa-github"></span> [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript)
- <span class="fa fa-external-link"></span> [RegExr](http://regexr.com/)
- <span class="fa fa-external-link"></span> [JS Standards](http://bguiz.github.io/js-standards/intro/) 

!SLIDE javascript no-bullet-list resources

## Katas

- <span class="fa fa-link"></span> [Code Kata | pernix](http://katas.softwarecraftsmanship.org/)  
- <span class="fa fa-link"></span> [Code Kata | Dave Thomas](http://codekata.com/)  
- <span class="fa fa-link"></span> [Project Euler](https://projecteuler.net/archives)  
- <span class="fa fa-link"></span> [codekatas.org](http://www.codekatas.org/)  
- <span class="fa fa-link"></span> [Javascript Katas](http://www.javascriptkata.com/)  
- <span class="fa fa-link"></span> [Cyber Dojo](http://cyber-dojo.org/)  
- <span class="fa fa-link"></span> [CodeWars](http://www.codewars.com/)  


<!-- ######################## HTML5 ######################## --> 

!SLIDE #html5 coverSession html5

<section class="logos">
  <div class="box">
    ![HTML5 Logo](img/html5-logo.png)
  <div>
</section>
 
## Web Development Bootcamp 
### **HTML5**  


!SLIDE html5

## Clear Ideas

- [The Three Layers of Web Design](https://www.diigo.com/annotated/d95c68479ed8691b39e7e12951343e12)
  - [CSS Zen Garden](http://www.csszengarden.com/) (layer separation example) 

- [Structure of an HTML document](https://www.w3.org/TR/html401/struct/global.html) [[1]](http://www.sitepoint.com/web-foundations/basic-structure-of-a-web-page/) [[2]](https://css-tricks.com/snippets/html/html5-page-structure/)

- [Review of basic HTML tags](https://www.lehigh.edu/~inwww/old_seminar/tagreview.html) [[1]](http://www.html5-tutorials.org/html-basics/block-inline-elements/)

!SLIDE html5

## Semantic Web

- [Getting to Know HTML](http://learn.shayhowe.com/html-css/getting-to-know-html/)
- [HTML5 Semantics](https://diigo.com/08bwdw) [[1]](http://juanmaguitar.github.io/training-laSalle/docs/html5css3_HTML5.pdf) 
- [Layouts w/ HTML5](http://www.developer.com/lang/understanding-the-proper-way-to-lay-out-a-page-with-html5.html)
  - [The importance of sections](http://coding.smashingmagazine.com/2013/01/18/the-importance-of-sections/)
  - [Example: Blog layout](http://line25.com/tutorials/create-a-typography-based-blog-layout-in-html5) 

!SLIDE html5

## Semantic Web

- [Extending Semantics & Accessibility](http://learn.shayhowe.com/advanced-html-css/semantics-accessibility/)
- [Lists](http://learn.shayhowe.com/html-css/creating-lists/)
- [Tables](http://learn.shayhowe.com/html-css/organizing-data-with-tables/) 


!SLIDE html5 exercise

## <span class="icon-laptop"></span> Semantic Markup challenge

- Create a new repository called `html5-layouts` on your github account and clone it on your machine
- Create `index.html` and inside of it do the markup (only the markup, not the css part) explained in [this article](https://www.smashingmagazine.com/2009/08/designing-a-html-5-layout-from-scratch/)
- Do different commits as you finish the different parts of the file
- `push` your changes to the remote repository when you complete the markup


!SLIDE html5 exercise todo

## <span class="icon-laptop"></span> Layout Challenges



!SLIDE html5

## Semantic Forms

- [Forms](http://learn.shayhowe.com/html-css/building-forms/) [[1]](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms) [[2]](http://www.html5rocks.com/es/tutorials/forms/html5forms/) [[Demo]](http://people.opera.com/brucel/demo/html5-forms-demo.html)
  + [My First HTML Form | mdn](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms/My_first_HTML_form) [[1]](http://www.html5-tutorials.org/forms/introduction/) 
  + [How to structure a Form | mdn](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms/How_to_structure_an_HTML_form) 
  + [The native widgets | mdn](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms/The_native_form_widgets)
- [Form Validation](http://www.html5-tutorials.org/form-validation/introduction/)
- [Forms | Dive into HTML5](http://diveintohtml5.info/forms.html)

!SLIDE html5 exercise todo

## <span class="icon-laptop"></span> Form Challenges


!SLIDE html5

## Media

- [The `figure` & `figcaption` elements](http://html5doctor.com/the-figure-figcaption-elements/)
- [HTML5 Video & Audio](https://developer.mozilla.org/en-US/docs/HTML/Using_HTML5_audio_and_video)
  - [Video (MDN)](https://developer.mozilla.org/en-US/docs/HTML/Element/video)
    * [Demo Video Basic (jsFiddle)](http://jsfiddle.net/Flocke/NpgD5/)
    * [HTML5 Demos: Videos](http://html5demos.com/video)
  - [HTML5 Audio](http://html5doctor.com/html5-audio-the-state-of-play/)
    - [Demo Audio Basic (jsFiddle)](http://jsfiddle.net/lastrose/vkMqR/)

!SLIDE html5 exercise todo

## <span class="icon-laptop"></span> Media Challenges


!SLIDE html5

## HTML5 tags _cheatsheets_

<span class="fa fa-file-pdf-o"></span> [HTML5 tags](http://media.smashingmagazine.com/wp-content/uploads/images/html5-cheat-sheet/html5-cheat-sheet.pdf)  
<span class="fa fa-external-link"></span> [HTML semantics](http://learn-the-web.algonquindesign.ca/topics/html-semantics-cheat-sheet/)  
<span class="fa fa-external-link"></span> [HTML semantics checklist](http://learn-the-web.algonquindesign.ca/topics/html-semantics-checklist/)

- [HTML5 Element Index](http://html5doctor.com/element-index/)  
- [HTML5 Element Flowchart](http://html5doctor.com/downloads/h5d-sectioning-flowchart.png)

!SLIDE html5

## More resources for this Unit

- [Markup Validation Service | W3C](https://validator.w3.org/)
- [HTML 5 Outliner](https://gsnedders.html5.org/outliner/)
- [Styling HTML forms](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms/Styling_HTML_forms)
- [HTML5 Rocks](http://www.html5rocks.com/en/)
- [HTML5 Doctor](http://html5doctor.com/)


<!-- ######################## CSS3 ######################## --> 

!SLIDE #css3 coverSession css3

<section class="logos">
  <div class="box">
    ![CSS3 Logo](img/css3-logo.png)
  <div>
</section>
 
## Web Development Bootcamp 
### **CSS3**  


!SLIDE css3

## CSS3 Basics & Selectors

- [CSS Basics](http://learn.shayhowe.com/html-css/building-your-first-web-page/)
  - _[css terms](http://learn.shayhowe.com/html-css/building-your-first-web-page/#common-css-terms) [[1]](http://www.impressivewebs.com/css-terms-definitions/), [basic selectors](http://learn.shayhowe.com/html-css/building-your-first-web-page/#working-with-selectors), [referencing CSS](http://learn.shayhowe.com/html-css/building-your-first-web-page/#referencing-css), [resets](http://learn.shayhowe.com/html-css/building-your-first-web-page/#using-css-resets)_
* [The Cascade](http://learn.shayhowe.com/html-css/getting-to-know-css/#cascade)
* [**Selectors**](https://www.w3.org/TR/css3-selectors/#selectors) [[1]](http://learn.shayhowe.com/advanced-html-css/complex-selectors/) [[2]](https://www.smashingmagazine.com/2009/08/taming-advanced-css-selectors/)
  * [`:nth-child`](http://nthmaster.com/) ([nth-test](http://nth-test.com/))
* [**Specificity**](https://diigo.com/08bywl) [[1]](https://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/) [[2]](https://stuffandnonsense.co.uk/archives/css_specificity_wars.html) [[3]](https://css-tricks.com/specifics-on-css-specificity/)
  * [Specificity Calculator](https://specificity.keegan.st/)


!SLIDE css3

## CSS3 Properties & Values

- [Fonts](http://learn.shayhowe.com/html-css/working-with-typography/)
- [Colors & Measures](http://learn.shayhowe.com/html-css/getting-to-know-css/#css-property-values)
  - [Color Wheel](https://color.adobe.com/es/create/color-wheel/)
- [CSS Units](https://developer.mozilla.org/en-US/docs/Web/CSS/length) [[1]](https://www.w3.org/Style/Examples/007/units.en.html#units) [[2]](http://webdesign.tutsplus.com/articles/7-css-units-you-might-not-know-about--cms-22573) [[3]](https://www.sitepoint.com/look-at-length-units-in-css/)
  - [vw & vh](http://thenewcode.com/48/CSS-Measurement-Units)
- [CSS Shorthand](https://perishablepress.com/top-5-css-shorthand-properties/#lists) [[1]](http://www.eddiewelker.com/wp-content/uploads/2007/09/csscheatsheet.pdf) [[2]](https://www.kobzarev.com/wp-content/uploads/cheatsheets/css/css-cheat-sheet.pdf) [[3]](http://www.catchmyfame.com/wp-content/uploads/2009/07/CSS-Shorthand-Cheat-Sheet.pdf) [[4]](http://www.dustindiaz.com/css-shorthand/)
  - [`background`](https://css-tricks.com/almanac/properties/b/background/) | [`font`](http://www.impressivewebs.com/css-font-shorthand-cheat-sheet.pdf) 



!SLIDE css3

## <span class="icon-laptop"></span> CSS3 Selectors

Choose a partner and do the following exercise online (in pairs) to practice Selectors: http://flukeout.github.io/  
  
- (_you need to select with CSS the element that is moving_ )

!SLIDE css3

## CSS3 Positioning

- [**The Box Model**](http://learn.shayhowe.com/html-css/opening-the-box-model/) [[1]](https://css-tricks.com/the-css-box-model/)
  - `width`, `height`, `padding`, `margin`, `border`
  - `box-sizing: border-box;`
- [Normal Document Flow](https://diigo.com/08aye5)
- [Positioning Content](http://learn.shayhowe.com/html-css/positioning-content/) [[1]](http://learn.shayhowe.com/advanced-html-css/detailed-css-positioning/) [[2]](https://codemyviews.com/blog/the-lowdown-on-absolute-vs-relative-positioning)
  - [Examples](http://www.barelyfitz.com/screencast/html-training/css/positioning/)
- [Centering Elements](https://css-tricks.com/centering-css-complete-guide/)


!SLIDE css3

## CSS3

See boxes w/ your own eyes

```css
* {
   border: 1px solid red !important;
}
```

!SLIDE css3 exercise todo

## <span class="icon-laptop"></span> Box Model Challenges


!SLIDE css3  exercise todo

## <span class="icon-laptop"></span> Positioning Challenges



!SLIDE css3

## CSS3 MediaQuery & Flexbox

- [MediaQuery](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/) [[1]](https://css-tricks.com/css-media-queries/) [[2]](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
  - [Examples](http://mediaqueri.es/)
  - [Meta Viewport](https://dev.opera.com/articles/an-introduction-to-meta-viewport-and-viewport/)
  - [Responsive Web Design](http://alistapart.com/article/responsive-web-design)
- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) [[1]](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
  - [Cheatsheet](http://apps.workflower.fi/css-cheats/?name=flexbox) | [**Examples**](http://www.sketchingwithcss.com/samplechapter/cheatsheet.html) 
  - [**Playground**](http://codepen.io/enxaneta/full/adLPwv/) | [[1]](http://the-echoplex.net/flexyboxes/) [[2]](https://demos.scotch.io/visual-guide-to-css3-flexbox-flexbox-playground/demos/) [[3]](http://flexboxin5.com/)
  - [Solved by Flexbox](https://philipwalton.github.io/solved-by-flexbox/) | [Grids](http://flexboxgrid.com/) | [Resources](https://gist.github.com/nucliweb/920dae103fd17422eb1f)

!SLIDE css3

![flexbox](img/flexbox.png)

!SLIDE css3 exercise

## <span class="icon-laptop"></span> Practice Flexbox

Choose a partner and do the following exercise online (in pairs) to practice Flexbox: http://flexboxfroggy.com/


!SLIDE css3  exercise todo

## <span class="icon-laptop"></span> Media Query Challenges


!SLIDE css3  exercise todo

## <span class="icon-laptop"></span> Flexbox Challenges



!SLIDE css3

## CSS3 Effects & Animation

- Some special properties:
  * [`@font-face`](http://css3files.com/font/) [[1]](https://css-tricks.com/snippets/css/using-font-face/), [`text-overflow`](http://css3files.com/text/#textoverflow) & [`word-wrap`](http://css3files.com/text/#overflowwrap), [`box-shadow`](http://css3files.com/shadow/#boxshadow) & [`text-shadow`](http://css3files.com/shadow/#textshadow), [`border-radius`](http://css3files.com/border/#borderradius), [`opacity`](http://css3files.com/color/#opacity)
- Image filters => [`filter`](http://www.paulund.co.uk/css3-image-filters) ([Examples](http://bennettfeely.com/filters/) [[1]](http://www.paulund.co.uk/playground/demo/css-filters/) [[2]](https://davidwalsh.name/demo/css-filters.php))
- [**Gradients**](http://css3files.com/gradient/) [[1]](https://css-tricks.com/css3-gradients/) _([Examples](https://css-tricks.com/examples/CSS3Gradient/) [[1]](http://demo.hongkiat.com/css3-linear-gradient/) [[2]](http://demo.hongkiat.com/css3-repeating-gradients/))_
- [**Transformations**](http://learn.shayhowe.com/advanced-html-css/css-transforms/) [[1]](http://css3files.com/transform/) [[2]](https://css-tricks.com/almanac/properties/t/transform/) _([Examples](http://desandro.github.io/3dtransforms/))_
- [**Transitions & Animations**](http://learn.shayhowe.com/advanced-html-css/transitions-animations/) [[1]](http://css3files.com/transition/) [[2]](http://www.leemunroe.com/css3-animations/) _([Example](http://www.impressivewebs.com/demo-files/css3-animated-scene/))_

!SLIDE css3 exercise todo

## <span class="icon-laptop"></span> CSS Effects Challenges


!SLIDE css3

## CSS3 _cheatsheets_

<span class="fa fa-external-link"></span> [CSS Reference](http://tympanus.net/codrops/css_reference/)  
<span class="fa fa-file-pdf-o"></span> [CSS3 CheatSheet](https://media-mediatemple.netdna-ssl.com/wp-content/uploads/images/css3-cheat-sheet/css3-cheat-sheet.pdf)  
<span class="fa fa-external-link"></span> [CSS selectors & units](http://learn-the-web.algonquindesign.ca/topics/css-selectors-units-cheat-sheet/)  
<span class="fa fa-file-pdf-o"></span> [Positioning CheatSheet](http://thewc.co/storage/goodies/codagogy_css_positioning_cheat_sheet.pdf)  
<span class="fa fa-file-pdf-o"></span> [Flexbox CheatSheet](http://jonibologna.com/content/images/flexboxsheet.pdf)  
<span class="fa fa-external-link"></span> [CSS Layout](http://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/)  


!SLIDE css3

## More resources for this Unit

<span class="fa fa-youtube"></span> [HTML5 CSS3 fundamentals](https://www.youtube.com/watch?v=4Oggpc9gl5g) _7h_
- [WebFonts.info](http://webfonts.info/)  
- [Learn the Web](http://learn-the-web.algonquindesign.ca/topics/)  
- [**Learn to Code HTML & CSS**](http://learn.shayhowe.com/html-css/)
- [**Learn to Code Advanced HTML & CSS**](http://learn.shayhowe.com/advanced-html-css/)
- [Flexbox without flexbox](https://kyusuf.com/post/almost-complete-guide-to-flexbox-without-flexbox)

!SLIDE css3

## [Recommended Sublime Packages](http://aslanbakan.com/en/blog/33-essential-sublime-text-plugins-for-all-developers/)

- to check code: [Sublime Linter](https://packagecontrol.io/packages/SublimeLinter) [[1]](http://www.hongkiat.com/blog/identify-code-errors-sublime-linter/)
  + [for HTML](https://packagecontrol.io/packages/SublimeLinter-contrib-htmlhint)  `npm install -g htmlhint@latest`
  + [for CSS](https://packagecontrol.io/packages/SublimeLinter-csslint) `npm install -g csslint`  
- [to create files easily](https://packagecontrol.io/packages/AdvancedNewFile) | [file names autocompletion](https://packagecontrol.io/packages/AutoFileName)
- [to mark brackets](https://packagecontrol.io/packages/BracketHighlighter) | [to show colors](https://packagecontrol.io/packages/Color%20Highlighter)
- [to write random content](https://packagecontrol.io/packages/Random%20Everything)

!SLIDE css3 small exercise

## <span class="icon-laptop"></span> Extra CSS3 Challenges *

- Download the `CSS3-challenges` from [here](https://github.com/juanmaguitar/CSS3-challenges/archive/master.zip) and unzip it under the name of `CSS3-challenges` in your _projects_ folder
- Go inside `CSS3-challenges` and initialize the local git repo (`git init`)
- CREATE a repository in your GitHub account called `CSS3-challenges`
- Connect your local repository w/ your remote repository (`git remote add <your-repository-url>`)
- Do ALL the challenges **02 to 16**
- Do different commits as you finish the different parts of the challenges
- `push` your changes to your remote respository

!SLIDE css3 small exercise

## <span class="icon-laptop"></span> Extra HTML5 CSS3 Challenges *

- Download the `html5-css3-extra-challenges` from [here](https://github.com/Code-Institute-Org/html5-css3-extra-challenges/archive/master.zip) and unzip it under the name of `html5-css3-extra-challenges` in your _projects_ folder
- Go inside `html5-css3-extra-challenges` and initialize the local git repo (`git init`)
- CREATE a repository in your GitHub account called `html5-css3-extra-challenges`
- Connect your local repository w/ your remote repository (`git remote add <your-repository-url>`)
- Do the challenges
- Commit your changes and sync them w/ your remote repository from time to time


<!-- ######################## BOOTSTRAP ######################## --> 

!SLIDE #bootstrap coverSession bootstrap

<section class="logos">
  <div class="box">
    ![bootstrap logo](img/bootstrap.png)
  <div>
</section>
 
## Web Development Bootcamp 
### **Bootstrap**


!SLIDE bootstrap

## Contents 

- [Bootstrap](http://getbootstrap.com/) 
  - [Download it](http://getbootstrap.com/) or use it [via CDN](http://getbootstrap.com/getting-started/#download-cdn)
  - [Files Structure](http://getbootstrap.com/getting-started/#whats-included-precompiled)
  - Start over the [basic template](http://getbootstrap.com/getting-started/#template) or use any of the [examples](http://getbootstrap.com/getting-started/#examples)

- [First Steps](http://learntocodewith.me/getting-started/topics/bootstrap/) [[1]](http://www.toptal.com/front-end/what-is-bootstrap-a-short-tutorial-on-the-what-why-and-how)
  - [Grid](http://getbootstrap.com/css/#grid) [[1]](https://scotch.io/tutorials/understanding-the-bootstrap-3-grid-system) 
    - [Examples](http://getbootstrap.com/examples/grid/) [[1]](http://codepen.io/SitePoint/pen/raBPeo) [[2]](http://codepen.io/SitePoint/full/dPbaXo/)
    - [Grid options](http://getbootstrap.com/css/#grid-options)
    - [Centering elements](http://stackoverflow.com/a/18153551)

!SLIDE bootstrap

## Contents 

- [**Bootstrap CSS elements**](http://getbootstrap.com/css/) | [Examples](http://getbootstrap.com/examples/theme/)
  - Buttons

!SLIDE bootstrap

## Contents 

- [Sites done w/ Bootstrap](http://expo.getbootstrap.com/) [[1]](http://builtwithbootstrap.com/)
- [Resources](http://bootsnipp.com/resources) [[1]](http://presentation.creative-tim.com/)
  + [Themes](http://bootswatch.com/) [[1]](http://startbootstrap.com/) [[2]](http://www.initializr.com/) [[3]](https://wrapbootstrap.com/) [[4]](https://shapebootstrap.net/free-templates)
  + [Extensions](http://www.webdesignerdepot.com/2014/10/the-ultimate-guide-to-bootstrap/)
  + [Tips & Tricks](https://scotch.io/bar-talk/bootstrap-3-tips-and-tricks-you-might-not-know) [[1]](https://scotch.io/bar-talk/bootstrap-3-tips-and-tricks-you-still-might-not-know)

!SLIDE bootstrap small

## To take into account 

- [Design w/ grids](http://www.creativebloq.com/web-design/grid-theory-41411345) [[1]](http://www.sitepoint.com/grid-theory/) [[2]](http://designmodo.com/grid-design-theory/)
- [`<meta charset="utf-8">`](http://stackoverflow.com/questions/16505367/what-happens-when-we-dont-specify-meta-charset-utf-8) 
- [`<meta http-equiv="X-UA-Compatible" content="IE=edge">`](http://stackoverflow.com/questions/14611264/x-ua-compatible-content-ie-9-ie-8-ie-7-ie-edge) [[1]](https://msdn.microsoft.com/en-us/library/jj676915.aspx)
- [`<meta name="viewport" content="width=device-width, initial-scale=1">`]( http://webdesign.tutsplus.com/es/articles/quick-tip-dont-forget-the-viewport-meta-tag--webdesign-5972)

- [`bootstrap-theme.css`](http://stackoverflow.com/questions/18327543/how-to-use-bootstrap-theme-css-with-bootstrap-3#23522301)

!SLIDE bootstrap exercise

## <span class="icon-laptop"></span> Practice Bootstrap

Choose a partner and do the following exercises online (in pairs) to practice Bootstrap: [Responsive Design with Bootstrap](https://www.freecodecamp.com/map-aside)

- Do exercises from [Use Responsive Design with Bootstrap Fluid Containers](https://www.freecodecamp.com/challenges/use-responsive-design-with-bootstrap-fluid-containers) to [Use Comments to Clarify Code](https://www.freecodecamp.com/challenges/use-comments-to-clarify-code)


!SLIDE bootstrap exercise todo

## <span class="icon-laptop"></span> Bootstrap Challenges

!SLIDE bootstrap exercise

## <span class="icon-laptop"></span> Extra Bootstrap Challenges *

- Do the foollowing codeCademy course that will guide through the process of creating a full website: https://www.codecademy.com/skills/make-a-website

!SLIDE bootstrap exercise todo

## <span class="icon-laptop"></span> Bootstrap Teams Challenge

!SLIDE bootstrap 

## Bootstrap Resources

_Useful resources for working on responsive design & bootstrap projects_

  + [Device Mode](https://developer.chrome.com/devtools/docs/device-mode)
  + [Bootstrap Grid](https://chrome.google.com/webstore/detail/bootstrap-grid/gmoboekiodfcajledjijioecfimliddo)
  + [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh)



<!-- ######################## JQUERY ######################## --> 

!SLIDE #jquery coverSession jquery

<section class="logos">
  <div class="box">
    ![jQuery Logo](img/jquery-logo.gif)
  <div>
</section>

## Web Development Bootcamp 
### **jQuery**  


!SLIDE jquery

## The Browser Environment (BOM y DOM)

- [The Browser Environment](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment)
- [BOM | `window`](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment/BOM)
- [DOM | `document`](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment/DOM)
  - [Accesing](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment/DOM#accesing-the-nodes), [Modifying](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment/DOM#modifying-los-nodos) and [Creating](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment/DOM#creating-and-modifying-nodes) nodes
  - [Advanced selection of elements](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/11-browser-environment/DOM#advanced-selection-of-elements)
  
!SLIDE jquery

## jQuery

- [About jQuery](http://learn.jquery.com/about-jquery/)
  
- [Using jQuery Core](http://learn.jquery.com/using-jquery-core/)
    - [**Selecting Elements**](http://learn.jquery.com/using-jquery-core/selecting-elements/)
    - [Manipulating Elements](http://learn.jquery.com/using-jquery-core/manipulating-elements/)
    - [The jQuery Object](http://learn.jquery.com/using-jquery-core/jquery-object/)
    - [Traversing](http://learn.jquery.com/using-jquery-core/traversing/)
      - [Examples](http://jsfiddle.net/juanma/pp3h1hpo/)
    - [Utility Methods](http://learn.jquery.com/using-jquery-core/utility-methods/)
  

!SLIDE jquery

## jQuery

- [Using jQuery Core](http://learn.jquery.com/using-jquery-core/)
  - [`$.each()`  and `.each()`](http://learn.jquery.com/using-jquery-core/iterating/)
- [Events](http://learn.jquery.com/events/)
  - [How do the events work in the DOM?](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/12-events#eventss)
  - [Capturing events](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/12-events#capturing-events) 
  - [Stopping the flow of the events](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/12-events#stopping-the-flow-of-the-events)
  - [Events delegation](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/12-events#events-delegation)
  - [jQuery events](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/12-events#jquery-events) 
  
!SLIDE jquery exercise todo

## <span class="icon-laptop"></span> jQuery Challenge


!SLIDE jquery exercise

## <span class="icon-laptop"></span> KOAN jQuery

- Group yourselves in pairs
- Do the following [KOAN](https://github.com/juanmaguitar/jquery-koans) to assure the understanding of jquery concepts

!SLIDE jquery

## JSON & AJAX

- [JSON](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/13-JSON)
  - [Example JSON files](http://www.sitepoint.com/10-example-json-files/) [[1]](http://rgb.to/)
- [AJAX](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/14-AJAX)
- [Same Origin Policy](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/15-same-origin-policy)
  - [JSONP](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/15-same-origin-policy/JSONP)
  - [CORS](https://github.com/juanmaguitar/javascript-notes/tree/master/markdown-en/15-same-origin-policy/CORS)

!SLIDE jquery

## Local Web Server

- Try `sudo python -m SimpleHTTPServer 80`
  - Or via [node](https://github.com/indexzero/http-server), [XAMPP](https://www.apachefriends.org/index.html), [MAMP](https://www.mamp.info/en/)

!SLIDE jquery exercise

## <span class="icon-laptop"></span> Challenge: jQuery JSON

- Do the following challenge: https://github.com/juanmaguitar/exercises-javascript/tree/master/05-youtube-json


!SLIDE jquery exercise

## <span class="icon-laptop"></span> Challenge: Spotify API

- Do the following app with jQuery and the Spotify API: https://github.com/juanmaguitar/exercises-javascript/tree/master/04-jquery-spotify-API


!SLIDE jquery

## Practice

- [jQuery | codeCademy](https://www.codecademy.com/learn/jquery)
- [jQuery Beginner](http://jqexercise.droppages.com/)
- [Try jQuery](http://try.jquery.com/levels/1/challenges/1) 
- [jQuery Exercises](https://github.com/macloo/jquery_exercises)

!SLIDE jquery

## More resources for this Unit

- [9 jQuery samples](http://johnpapa.net/9-jquery-samples/)
- [Pulling JSON data from a public data API](http://themarklee.com/2014/04/03/pulling-json-data-open-data-api/)
- [JSONP example](https://jsfiddle.net/juanma/az6rvze2/1/)
- [API Discovery: 11 Ways to Find APIs](http://nordicapis.com/api-discovery-11-ways-to-find-apis/)


!SLIDE jquery

## Public API's

- [API Directory](http://www.programmableweb.com/apis/directory)
- [Lyrics Wikia API](http://lyric-api.herokuapp.com/api) [[1]](http://lyric-api.herokuapp.com/api/find/John%20Lennon/Imagine) [[2]](http://lyric-api.herokuapp.com/api/find/The%20Beatles/Get%20Back)
- [Google API's](https://developers.google.com/api-client-library/javascript/start/start-js)
- [Bing Maps](http://www.earthware.co.uk/blog/using-jquery-with-the-bing-maps-rest-api/#.VsDFOpPJxE4)
- [data.gov](http://www.data.gov/)
- [Socrata Open Data API](https://dev.socrata.com/)
- [Public APIs](https://www.publicapis.com/)
- [APIs marketplace](https://market.mashape.com/explore)



<!-- ######################## ANGULAR ######################## --> 

!SLIDE #angular coverSession angular

<section class="logos">
  <div class="box">
    ![Angular Logo](img/angular-logo.png)
  <div>
</section>
 
## Web Development Bootcamp 
### **Angular**

!SLIDE angular

## Contents

- [Introduction to angular (notes)](https://gist.github.com/juanmaguitar/c538d6cb108d27a37c73)
- [**angular.js**](https://angularjs.org/) [**[1]**](https://docs.angularjs.org/tutorial) [**[2]**](https://thinkster.io/a-better-way-to-learn-angularjs)
  - $scope, Controllers, Templates, Filters
  - Routing
  - API calls | Services
  
!SLIDE angular

## To take into account
 
- [`ng-bind` vs `ng-bind-html` vs `ng-bind-template`](http://stackoverflow.com/a/21086745) [[1]](http://plnkr.co/edit/HcRmCyrigRVvLckFJXzN?p=preview)
- [`factory` vs `service`](http://blog.thoughtram.io/angular/2015/07/07/service-vs-factory-once-and-for-all.html)
- [`$resource`](https://docs.angularjs.org/api/ngResource/service/$resource)
- [directives](https://docs.angularjs.org/guide/directive) [[1]](http://www.ng-newsletter.com/posts/directives.html)
 [[2]](http://tutorials.jenkov.com/angularjs/custom-directives.html) [[3]](http://www.undefinednull.com/2014/02/11/mastering-the-scope-of-a-directive-in-angularjs/) [[4]](http://www.ng-newsletter.com/posts/directives.html)
  - [Examples](https://jsfiddle.net/juanma/a5wbt7d2/) 
    - [`scope: false`](http://jsfiddle.net/shidhincr/eyNYw/4/)
    - [`scope: true`](http://jsfiddle.net/shidhincr/q3kex/3/)
    - [Isolated scope](http://jsfiddle.net/shidhincr/pJLT8/10/) | [`scope: {}`](http://jsfiddle.net/shidhincr/q3kex/4/) 

!SLIDE angular

## Advanced Angular


- [Webpack & Angular](http://blog.teamtreehouse.com/26017-2)
  - [[1]](http://www.shmck.com/webpack-angular-part-1/) [[2]](http://www.shmck.com/webpack-angular-part-2/) [[3]](http://www.shmck.com/webpack-angular-part-3/)
  - [Starter](https://github.com/preboot/angular-webpack)
- [`controllerAs`](https://daveceddia.com/convert-scope-to-controlleras/)
- [**Angular Style Guide**](https://github.com/johnpapa/angular-styleguide) 

!SLIDE angular

## More resources for this Unit

- [Sites made w/ angular](https://www.madewithangular.com/#/)
- Angular [Examples](https://github.com/curran/screencasts/tree/gh-pages/introToAngular#examples) & [Cheatsheet](http://www.cheatography.com/proloser/cheat-sheets/angularjs/)
- [AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning) [[1]](http://stackoverflow.com/a/17363901)

!SLIDE angular

## More resources for this Unit

- [5 practical examples](http://tutorialzine.com/2013/08/learn-angularjs-5-examples/)
- [AngularJS Fundamentals In 60-ish Minutes](http://www.slant.co/topics/760/viewpoints/13/~resources-to-learn-angularjs~angularjs-fundamentals-in-60-ish-minutes-video)
- [Learn Angular | codeCademy](https://www.codecademy.com/learn/learn-angularjs)
- Quick Guides [[1]](http://www.tutorialspoint.com/angularjs/angularjs_quick_guide.htm) [[2]](http://www.hongkiat.com/blog/angularjs-basic/) [**[3]**](http://www.ng-newsletter.com/posts/beginner2expert-how_to_start.html)

- [First App](http://www.tutorialspoint.com/angularjs/angularjs_first_application.htm) [[1](http://www.toptal.com/angular-js/a-step-by-step-guide-to-your-first-angularjs-app) & [2](http://www.toptal.com/angular-js/your-first-angularjs-app-part-2-scaffolding-building-and-testing)] [[1]](https://medium.com/@minipai/angularjs-tutorial-for-designers-8c7dc63ca65f#.yvzh6dilh) [[2]](https://www.airpair.com/angularjs/posts/angularjs-tutorial)

!SLIDE angular exercise

## <span class="icon-laptop"></span> Challenge: Angular phoneCat

- Do (on your own) the angular app **phoneCat** by following the steps explained at: https://docs.angularjs.org/tutorial
- Try to also do the _Experiments_ suggested (but only those that are not related to testing)

!SLIDE angular exercise todo

## <span class="icon-laptop"></span> Challenge: Angular

Practice:
- `ng-app`
- models
- controllers
- views
- native directives (`ng-repeat`, `filter`...)

!SLIDE angular exercise todo

## <span class="icon-laptop"></span> Challenge: Angular (advanced)

Practice:
- services / factories
- directives
- archirecture?


!SLIDE angular exercise

## <span class="icon-laptop"></span> Challenge: Angular Spotify API

- Take the finished version of the Spotify API app done w/ jquery and transform it into an angular app

<!-- ######################## NODE.JS ######################## --> 

!SLIDE #node coverSession node

<section class="logos">
  <div class="box">
    ![Node Logo](img/nodejs-icon.svg)
  <div>
</section>

## Web Development Bootcamp 
### **Node.js**

!SLIDE node

## Contents

- [Node.js](https://blog.risingstack.com/node-hero-tutorial-getting-started-with-node-js/)

<!-- ######################## ES2015 ######################## --> 

!SLIDE #es2015 coverSession es2015

<section class="logos">
  <div class="box">
    ![es2015 Logo](img/es6-logo.png)
  <div>
</section>

## Web Development Bootcamp 
### **ES2015**


!SLIDE es2015 history

- [TC39](http://ecma-international.org/memento/TC39.htm)
  - ECMA Technical Committee evolving JavaScript
  - Members: companies (all major browser vendors, ...)

- [ECMAScript](http://www.ecmascript.org/index.php)
  + The name of the language standardized by ECMA
  + ECMAScript 1 => 1997
  + ECMAScript 2 => 1998
  + ECMAScript 3 => 1999
  + ~~ECMAScript 4~~ => abandoned
  + ECMAScript 5 => 2009
  + ~~ECMAScript 6~~ => rebaptised ECMAScript 2015

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript?redirectlocale=en-US&redirectslug=JavaScript)
  - Colloquially: the language
  - Formally: one implementation of ECMAScript


!SLIDE es2015

## ES2015 Overview

- Approved in @@June 2015@@, 1st update since 2009!
- A lot of @@new syntax features@@
- @@Backwards compatible@@ (mostly syntactic sugar that can be desugared to older versions of the language)
- Current support: [Kangax compatibility table](http://kangax.github.io/compat-table/es6/)
- We can use them @@right now@@ with a source to source compiler (transpiler) : see [Babel](https://babeljs.io/), [Traceur](https://github.com/google/traceur-compiler) and [TypeScript](http://www.typescriptlang.org/)

!SLIDE es2015

## [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

- Shorter syntax using `=>`
- Always anonymous
- Lexically bind `this`
- Really useful for event handlers and callbacks
- Really neat when using functional programming

!SLIDE es2015

## Arrow Functions

- [ECMAScript 6 equivalents in ES5: Arrow Functions](https://github.com/addyosmani/es6-equivalents-in-es5#arrow-functions)  
- [ES6 In Depth: Arrow functions](https://hacks.mozilla.org/2015/06/es6-in-depth-arrow-functions/)  
- [Understanding ECMAScript 6 arrow functions](https://www.nczonline.net/blog/2013/09/10/understanding-ecmascript-6-arrow-functions/)

!SLIDE es2015 smallcode

## Arrow Functions

Four versions:

```javascript
    (arg1, arg2, ...) => expr
    (arg1, arg2, ...) => { stmt1; stmt2; ... }
    singleArg => expr
    singleArg => { stmt1; stmt2; ... }
```

!SLIDE es2015 smallcode

## Arrow Functions

BEFORE (ES5)

```javascript
var self = this;
this.element.addEventListener('click', function(event) {
  self.registerClick(event.target.id);
});
```

!SLIDE es2015 smallcode

## Arrow Functions

AFTER (ES2015)

```javascript
this.element.addEventListener('click', event => {
  this.registerClick(event.target.id);
});
```

!SLIDE es2015 smallcode

## Arrow Functions

BEFORE (ES5)

```javascript
[1,3,4,5,6,7].filter(function(n) { return n % 2 } )
  .map(function(n, i) { return n + i } ); 
// [1, 4, 7, 10]
```

!SLIDE es2015 smallcode

## Arrow Functions

AFTER (ES2015)

```javascript
[1,2,3,4,5,6,7].filter(n => n % 2).map((n, i) => n+i);
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Arrow Functions

Do the following katas to assure the understanding of arrow functions
- [basics](http://tddbin.com/#?kata=es6/language/arrow-functions/basics)
- [function binding](http://tddbin.com/#?kata=es6/language/arrow-functions/binding)

!SLIDE es2015

## [Block Scope](https://hacks.mozilla.org/2015/07/es6-in-depth-let-and-const/)

- Two new types of _"variables"_: [`let`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [`const`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
- Both with block scope

!SLIDE es2015

## Block Scope

- [ECMAScript 6 equivalents in ES5: Block Scoping Functions](https://github.com/addyosmani/es6-equivalents-in-es5#block-scoping-functions)  
- [ECMAScript 6 and Block Scope](http://ariya.ofilabs.com/2013/05/es6-and-block-scope.html)


!SLIDE es2015 smallcode

## Block Scope

BEFORE (ES5)

```javascript
var arr = [1, 2, 3];
for (var i = 0; i < arr.length; i++) {
  // i from 0 to 2
}
i; // 3
{
  var TEMPERATURE = 32;
  TEMPERATURE = 16;
  TEMPERATURE // 16
}
TEMPERATURE; // 16
```

!SLIDE es2015 smallcode

## Block Scope

AFTER (ES2015)

```javascript
var arr = [1, 2, 3];
for (let i = 0; i < arr.length; i++) {
  // i from 0 to 2
}
i; // ReferenceError: i is not defined!
{
  const TEMPERATURE = 32;
  TEMPERATURE = 16;
  TEMPERATURE; // 32
}
TEMPERATURE; // ReferenceError: TEMPERATURE is not defined!
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Block Scope

Do the following katas to assure the understanding of Block Scope
- [`let` declaration](http://tddbin.com/#?kata=es6/language/block-scoping/let)
- [`const` declaration](http://tddbin.com/#?kata=es6/language/block-scoping/const)

!SLIDE es2015 smallcode

## [Template Strings](https://hacks.mozilla.org/2015/05/es6-in-depth-template-strings-2/)

- Enclosed by back-ticks @@` `` ` @@
- Multi-line support
- Can contain placeholders `${ expression }`

```javascript
`string text`

`string text line 1
 string text line 2`

`string text ${expression} string text`
```

!SLIDE es2015 smallcode

## Template Strings

BEFORE (ES5)

```javascript
var name = "juanma";
var getSuitableDrink = function(who) {
  return who === 'juanma' ? 'beer' : 'cocktail'
};

console.log( 'Hello, '+name+'!\nFancy a '+getSuitableDrink()+'?' );

// Hello, juanma!
// Fancy a beer?
```

!SLIDE es2015 smallcode

## Template Strings

AFTER (ES2015)

```javascript
var name = "juanma";
var getSuitableDrink = function(who) {
  return who === 'juanma' ? 'beer' : 'cocktail'
};

console.log( `Hello, ${ name }!
  Fancy a ${ getSuitableDrink() }?` );
```


!SLIDE es2015

## Template Strings

- [Template Strings](https://hacks.mozilla.org/2015/05/es6-in-depth-template-strings-2/)
- [ECMAScript 6 equivalents in ES5: Template Literals](https://github.com/addyosmani/es6-equivalents-in-es5#template-literals)  

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Template Strings

Do the following katas to assure the understanding of template strings
- [basics](http://tddbin.com/#?kata=es6/language/template-strings/basics)
- [multiline](http://tddbin.com/#?kata=es6/language/template-strings/multiline)
- [tagged template strings](http://tddbin.com/#?kata=es6/language/template-strings/tagged)
- [`raw` property](http://tddbin.com/#?kata=es6/language/template-strings/raw)

!SLIDE es2015 smallcode

## [Enhanced Object Literals](https://github.com/lukehoban/es6features#enhanced-object-literals)

- Shorthand property names
- Shorthand methods names
- Dynamic property names
- [_getter_](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get) and [_setter_](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/set)


!SLIDE es2015 smallcode

## Enhanced Object Literals

```javascript
var a = "foo",
    b = 42,
    c = {};

function myMethod() {
    console.log('ooOoh!');
}

// Shorthand property names
@@var o = { a, b, c };@@

// Shorthand method name and dynamic property name
var o2 = {
  myMethod,
  @@['myPropertyNum'+b]: 'bar'@@
}
```

!SLIDE es2015 smallcode

## Enhanced Object Literals

```javascript
var messages = {
  @@get latest ()@@ {
    if (this.log.length == 0) return undefined;
    return this.log[this.log.length - 1]
  },
  @@set current (str)@@ {
    this.log[this.log.length] = str;
  },
  log: []
}

messages.current = "hey!";
messages.latest // hey!
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Enhanced Object Literals

Do the following katas to assure the understanding of Enhanced Object Literals
- [basics](http://tddbin.com/#?kata=es6/language/object-literal/basics)
- [computed properties](http://tddbin.com/#?kata=es6/language/object-literal/computed-properties)
- [getter](http://tddbin.com/#?kata=es6/language/object-literal/getter)
- [setter](http://tddbin.com/#?kata=es6/language/object-literal/setter)

!SLIDE es2015 smallcode

## [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)

```javascript
function f(x, y=12) {
  // y is 12 if not passed (or passed as undefined)
  return x + y;
}

f(3) === 15;
f(3, undefined) === 15;
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Default parameters

Do the following katas to assure the understanding of Default parameters
- [basic](http://tddbin.com/#?kata=es6/language/default-parameters/basics)
 


!SLIDE es2015 smallcode

## [Destructuring Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)

- Array destructuring
- Object destructuring

!SLIDE es2015 smallcode

## Destructuring Assignment

```javascript
var [first, second, third, , fifth = 5] = [1, 2];
first // 1
second // 2
third // undefined
fifth // 5

[second, first] = [first, second] // swap values
first // 2
second // 1
```

!SLIDE es2015 smallcode

## Destructuring Assignment

```javascript
var customer = {
  name: 'John',
  surname: 'Doe',
  dateOfBirth: {
    year: 1988
  }
};

var {name, surname, dateOfBirth: {year}, children} = customer;
name // 'John'
surname // 'Doe'
year // 1988
children // undefined
```


!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Destructuring Assignment

Do the following katas to assure the understanding of Destructuring Assignment
- [array](http://tddbin.com/#?kata=es6/language/destructuring/array)
- [string](http://tddbin.com/#?kata=es6/language/destructuring/string)
- [object](http://tddbin.com/#?kata=es6/language/destructuring/object)
- [defaults](http://tddbin.com/#?kata=es6/language/destructuring/defaults)
- [parameters](http://tddbin.com/#?kata=es6/language/destructuring/parameters)
- [assign](http://tddbin.com/#?kata=es6/language/destructuring/rename)

!SLIDE es2015 resources smallcode

## [Rest operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)

- Bind trailing parameters to an array using `...`
- Replaces the need for @@arguments@@

```javascript
function multiply(multiplier, ...numbers) {
  return numbers.map(n => multiplier * n);
}

var arr = multiply(2, 1, 2, 3);
console.log(arr); // [2, 4, 6]
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Rest operator

Do the following katas to assure the understanding of Rest operator
- [as parameter](http://tddbin.com/#?kata=es6/language/rest/as-parameter)
- [with destructuring](http://tddbin.com/#?kata=es6/language/rest/with-destructuring)



!SLIDE es2015 resources smallcode

## [Spread operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_operator)

- For **function calls**: allows an expression to be expanded in places where multiple arguments are expected
- For **array litterals**: allows an expression to be expanded in places where multiple elements are expected

```javascript
function f(x, y, z) {
  return x + y + z;
}

var arr = [1, 2, 3];
f(...arr) === 6; // true

[0, ...arr, 4, 5, 6, 7]; // [0, 1, 2, 3, 4, 5, 6, 7]
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Spread operator

Do the following katas to assure the understanding of Spread operator
- [with arays](http://tddbin.com/#?kata=es6/language/spread/with-arrays)
- [with strings](http://tddbin.com/#?kata=es6/language/spread/with-strings)


!SLIDE es2015 resources smallcode

## [`Set`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)

- New **data structure** for handling collections
- Store unique values of any type, whether primitive values or object references
- Efficient and clean

```javascript
var s = new Set();
s.add("hello").add("goodbye").add("hello");
s.size === 2;
s.has("hello") === true;
s.delete("hello");
s.has("hello") === false;
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Set

Do the following katas to assure the understanding of Set
- [basics](http://tddbin.com/#?kata=es6/language/set/basics)
- [`set.add()`](http://tddbin.com/#?kata=es6/language/set/add)
- [`set.delete()`](http://tddbin.com/#?kata=es6/language/set/delete)
- [the API](http://tddbin.com/#?kata=es6/language/set/api)
- [`set.clear()`](http://tddbin.com/#?kata=es6/language/set/clear)

!SLIDE es2015 resources smallcode

## [`Map`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)

- New **data structure** for handling collections
- Simple key/value map
- Any value (both objects and primitive values) may be used as either a key or a value
- Efficient and clean

!SLIDE es2015 resources smallcode

## Map

```javascript
var m = new Map();
m.set("hello", 42);
m.get("hello") === 42;

var s = { n:4 };
m.set(s, 34);
m.get(s) === 34;
```

!SLIDE es2015 resources smallcode smaller

## Map

```javascript
var myMap = new Map();

var keyString = "a string",
    keyObj = {},
    keyFunc = function () {};

// setting the values
myMap.set(keyString, "value associated with 'a string'");
myMap.set(keyObj, "value associated with keyObj");
myMap.set(keyFunc, "value associated with keyFunc");

myMap.size; // 3

// getting the values
myMap.get(keyString);    // "value associated with 'a string'"
myMap.get(keyObj);       // "value associated with keyObj"
myMap.get(keyFunc);      // "value associated with keyFunc"

myMap.get("a string");   // "value associated with 'a string'"
                         // because keyString === 'a string'
myMap.get({});           // undefined, because keyObj !== {}
myMap.get(function() {}) // undefined, because keyFunc !== function () {}
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Map

Do the following katas to assure the understanding of Map
- [basics](http://tddbin.com/#?kata=es6/language/map/basics)
- [`map.get()`](http://tddbin.com/#?kata=es6/language/map/get)
- [`map.set()`](http://tddbin.com/#?kata=es6/language/map/set)
- [initalize](http://tddbin.com/#?kata=es6/language/map/initialize)
- [`map.has()`](http://tddbin.com/#?kata=es6/language/map/has)

!SLIDE es2015

## [Clases](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

- Basic support
- `class` and [`extends`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/extends) keywords
- [`constructor`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor) definition
- [`static`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/static) method definitions

!SLIDE es2015 resources smallcode smaller

## Classes

BEFORE

```javascript
var Shape = function( id, x, y ) {
  this.id = id;
  this.x = x;
  this.y = y;
};
Shape.prototype.toString = function( x, y ) {
  return "Shape(" + this.id + ")"
};

var Rectangle = function( id, x, y, width, height ) {
  Shape.call( this, id, x, y );
};
Rectangle.prototype = Object.create(Shape.prototype);
Rectangle.prototype.constructor = Rectangle;
Rectangle.prototype.toString = function() {
  return "Rectangle > " + Shape.prototype.toString.call( this );
};
```

!SLIDE es2015 resources smallcode smaller

## Classes

AFTER

```javascript
class Shape {
  constructor (id, x, y) {
    this.id = id;
    this.x = x;
    this.y = y;
    // or Object.assign(this, {id, x, y});
  }
  toString () {
    return `Shape(${this.id})`
  }
}

class Rectangle extends Shape {
  constructor (id, x, y, width, height) {
    super(id, x, y)
  }
  toString () {
    return "Rectangle > " + super.toString()
  }
}
```



!SLIDE es2015

## Classes

- [Examples Classes](https://googlechrome.github.io/samples/classes-es6/index.html)
- [ES6 | Classes and Inheritance](https://medium.com/ecmascript-2015/es6-classes-and-inheritance-607804080906#.yly3wqbsq)  

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Classes

Do the following katas to assure the understanding of Classes
- [creation](http://tddbin.com/#?kata=es6/language/class/creation)
- [accessors](http://tddbin.com/#?kata=es6/language/class/accessors)
- [static](http://tddbin.com/#?kata=es6/language/class/static)
- [extends](http://tddbin.com/#?kata=es6/language/class/extends)
- [more extends](http://tddbin.com/#?kata=es6/language/class/more-extends)
- [super in method](http://tddbin.com/#?kata=es6/language/class/super-in-method)
- [super in constructor](http://tddbin.com/#?kata=es6/language/class/super-in-constructor)

!SLIDE es2015

## [Modules](https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)

- Native modules, alternative to [CommonJS](http://www.commonjs.org/) and [AMD](http://requirejs.org/docs/whyamd.html)
- Modules can export multiple values (unlike the others)
- Statically analyzed to load dependencies
- Dependencies are loaded asynchronously, but can be optimized with a module bundler ([rollup](http://rollupjs.org/) or [webpack](https://webpack.github.io/))

!SLIDE es2015 resources smallcode

## Modules

```javascript
// -------- jquery.js --------
export default function jQuery() {
  /* code */
}

// -------- code.js --------
import $ from 'jquery';
$('body').addClass('yay');

```

!SLIDE es2015 resources smallcode smaller

## Modules

```javascript
// --------- http.js --------
export function get(url) {
  /* code */
}

export function post(url, body) {
  /* code */
}

// -------- code.js --------
import { get, post } from 'http';
import { TIMEOUT as HTTP_TIMEOUT } from 'http';
import * as http from 'http';

get('/my/url').then(function(result) {
  /* code */
});

HTTP_TIMEOUT; // 1000;
http.post('/my/url', 'body');
```


!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Modules

Do the following katas to assure the understanding of Modules
- [`import` statement](http://tddbin.com/#?kata=es6/language/modules/import)

!SLIDE es2015

## [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

Array object extended with:

- New static methods: [`from()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from), [`of()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of)
- New instance methods: [`copyWithin()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin), [`entries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries) , [`fill()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill), [`find()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find), [`findIndex()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex), [`keys()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/keys), [`values()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/values) 


!SLIDE es2015 resources smallcode

## Array

```javascript
Array.from(arguments) // [].slice.call(arguments);
Array.from({0: 'hello', 1: world, length: 2}); // ['hello', 'world']
Array.of(1, 2, 3) // [1, 2, 3]

[1, 2, 3, 4, 5].copyWithin(0, 3, 4) // [4, 2, 3, 4, 5]
[1, 2, 3].fill(4) // [4, 4, 4]
[4, 5, 8, 12].find(isPrime) // 5
[4, 5, 8, 12].findIndex(isPrime) // 2
[4, 5, 8, 12].keys() // iterator from 0 to 3
[4, 5, 8, 12].values() // iterator from 4 to 12
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Array

Do the following katas to assure the understanding of Array
- [`Array.from()`](http://tddbin.com/#?kata=es6/language/array-api/from)
- [`Array.of()`](http://tddbin.com/#?kata=es6/language/array-api/of) 
- [`[].fill()`](http://tddbin.com/#?kata=es6/language/array-api/fill) 
- [`[].find()`](http://tddbin.com/#?kata=es6/language/array-api/find) 
- [`[].findIndex()`](http://tddbin.com/#?kata=es6/language/array-api/findIndex)
- [`[].entries()`](http://tddbin.com/#?kata=es6/language/array-api/entries) 
- [`[].keys()`](http://tddbin.com/#?kata=es6/language/array-api/keys) 
- [`[].values()`](http://tddbin.com/#?kata=es6/language/array-api/values) 

!SLIDE es2015

## [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

String object extended with:

- New static methods: [`raw()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/raw)
- New instance methods: [`startsWith()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith), [`endsWith()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith), [`includes()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes), [`repeat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/repeat), ...


!SLIDE es2015 resources smallcode

## String

```javascript
String.raw`Line 1\nLine 2\nLine 3` // 'Line 1\\nLine 2\\nLine 3'
'Hello world'.startsWith('Hello') // true
'Hello world'.endsWith('world') // true
'Hello world'.includes('orl') // true
'Hello world'.repeat(2) // 'Hello worldHello world'
```

!SLIDE es2015

## [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

- Native implementation of promises. Yay!
- [Promises/A+](https://promisesaplus.com/) spec compliant

!SLIDE es2015 resources smallcode

## Promise

```javascript
var promise = new Promise(function(resolve, reject) {
  // Do something asynchronous and call resolve with the
  // result or reject with the error
});

promise.then(function(result) {
  // Use the result of the async call
}, function(error) {
  // Process the error
});
```

!SLIDE es2015 resources smallcode

## Promise

```javascript
var allPromise = Promise.all([getLocation, getTemperature]);
allPromise.then(function(location, temperature) {
  console.log('The location is ', location,
        'and the temperature is', temperature);
}, function(error) {
  // Process the error
});

var racePromise = Promise.race([getGoogleAds, getYahooAds, getBindAds]);
racePromise.then(function(ads) {
  page.addAds(ads);
});
```

!SLIDE es2015 exercise

## <span class="icon-laptop"></span> ES6 Katas: Promise

Do the following katas to assure the understanding of Promise
- [basics](http://tddbin.com/#?kata=es6/language/promise/basics)
- [creation](http://tddbin.com/#?kata=es6/language/promise/creation) 
- [chaining `then`](http://tddbin.com/#?kata=es6/language/promise/chaining-then) 

!SLIDE es2015 resources

## Resources for this Unit  
  
- [Using Grunt & the ES6 Module Transpiler](http://www.thomasboyt.com/2013/06/21/es6-module-transpiler)
- [ECMAScript 6 equivalents in ES5](https://github.com/addyosmani/es6-equivalents-in-es5)
- [ES6 In Depth](https://hacks.mozilla.org/category/es6-in-depth/)
- [ariya.ofilabs.com | ES6](http://ariya.ofilabs.com/tag/es6) 
- [ECMAScript 2015](https://medium.com/ecmascript-2015)
- [ES6 Katas](http://es6katas.org/)
- [Scratch JS (chrome plugin)](https://chrome.google.com/webstore/detail/scratch-js/alploljligeomonipppgaahpkenfnfkn)
- [Promises](https://www.promisejs.org/)


<!-- ######################## EXPRESS.JS ######################## --> 

!SLIDE #express coverSession express

<section class="logos">
  <div class="box">
    ![Express Logo](img/zfY6lL7eFa-3000x3000.png)
  <div>
</section>

## Web Development Bootcamp 
### **Express.js**


<!-- ######################## MONGO DB ######################## --> 

!SLIDE #mongo coverSession mongo

<section class="logos">
  <div class="box">
    ![Mongo Logo](img/mongodb.png)
  <div>
</section>

## Web Development Bootcamp 
### **Mongo DB**

!SLIDE mongo

## Contents

- [CRUD Operations](https://docs.mongodb.com/manual/crud/)

!SLIDE mongo

## Data Modeling

- [Data Models](https://docs.mongodb.com/manual/core/data-modeling-introduction/)
- [SQL vs MongoDB](http://code.tutsplus.com/articles/mapping-relational-databases-and-sql-to-mongodb--net-35650)
- [Real life examples](http://es.slideshare.net/friedo/data-modeling-examples) | [Use Cases](https://docs.mongodb.com/ecosystem/use-cases/)

!SLIDE mongo

## [Mongoose](http://mongoosejs.com/) 

* [Schema](http://learnmongodbthehardway.com/schema/chapter1/)
  * [Basics](http://learnmongodbthehardway.com/schema/chapter2/)
  * [Referencing schemas in properties](https://alexanderzeitler.com/articles/mongoose-referencing-schema-in-properties-and-arrays/)



!SLIDE mongo

## More resources for this Unit

- [Tips and Tricks](https://www.safaribooksonline.com/library/view/50-tips-and/9781449306779/)


<!-- ######################## (FRONTEND) PROJECTS ######################## --> 

!SLIDE #projects coverSession projects

<section class="logos">
  <div class="box">
    ![Projects Logo](img/rocket-clipart-niBz6aqiA.jpeg)
  <div>
</section>
 
## Web Development Bootcamp 
### Frontend **Projects**

!SLIDE #scrum-img projects

![scrum workflow](img/scrum-overview-mark-hoogveld.jpg)


!SLIDE 

## General Resources

- [Learn The Web](http://learn-the-web.algonquindesign.ca/)
- [How to keep up to date on: Frontend Technologies](http://uptodate.frontendrescue.org/)
- [Smashing Magazine](http://www.smashingmagazine.com/)
- [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript)

