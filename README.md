# Angular Resources

**Attention:** This repo is ooooold. I am not maintaining it any more. If anybody wants to take it over let me know.

---

A collection of resources that help you learn Angular.js.

Please send PRs if you have anything to add! &hearts;

## From The Official Docs

[Tutorial](http://docs.angularjs.org/tutorial)

> A great way to get introduced to AngularJS is to work through this tutorial, which walks you through the construction of an AngularJS web app.

I agree. I found the tutorial very efficient in communicating the point of Angular and some of TEH AWESOME aswell.

[Guide](http://docs.angularjs.org/guide/)

The starting point for diving into the Angular docs.

## Videos

[Egghead.io](http://egghead.io)

John Lindquist's site filled to the brim with short screencasts on how Angular works.

[John Lindquist (Egghead.io) on Youtube](https://www.youtube.com/user/johnlindquist)

This is Johns Youtube channel. Appearantly you occasionally find videos here that are not on egghead.io.

[Angular.js Youtube Channel](https://www.youtube.com/angularjs)

This is Angular.js official Youtube channel with screencasts and talks.

[RailsCasts: Angular.js](http://railscasts.com/episodes/405-angularjs)

A screencast on Angular. Not free, though.

[Angular.js Communicating Between Controllers](http://onehungrymind.com/angularjs-communicating-between-controllers/)

A screencast on how controllers communicate in Angular.js

[AngularJS G+ Hangouts](https://www.youtube.com/results?search_query=angularjs+hangout)

## Articles

[Angular.js for Developers](http://blog.artlogic.com/2013/03/06/angularjs-for-jquery-developers/)

An introduction article on Angular targeted to jQuery developers.

[Getting Started with Angular.js (Adobe)](http://www.adobe.com/devnet/html5/articles/getting-started-with-angularjs.html)

> This tutorial  explores the AngularJS framework by Google. It starts by briefly describing the design philosophy that the framework embodies and then quickly moves onto building a simple but nontrivial application to demonstrate the basics as well as some of AngularJS's most distinctive features including data binding, dependency injection, loosely coupled code, and conciseness.

[Briant Ford's blog](http://briantford.com/blog/)

Briant Ford writes a lot about Angular.js.

[8 Tips for Angular.js Beginners](http://vxtindia.com/blog/8-tips-for-angular-js-beginners/)

> We started working with Angular.js recently and after spending a few days on it, I realised that there a big need for beginner tutorials on it. I’ve tried to document some of the things you might need on day 1.

An excellent article for AngularJS beginners.

[Angular.js on Google+](https://plus.google.com/u/0/+AngularJS/posts)

The official Google+ account.

[Using JSFiddle with Angular.js](http://pkozlowskios.wordpress.com/2012/08/12/using-jsfiddle-with-angularjs/)

> This post tries to dive into several usage scenarios of jsfiddle with AngularJS framework. The aim here is to make sure that people can quickly and easily prepare their jsfiddle which is crucial for getting help from  the AngularJS community.

[AngularJS - Dependency Injection, Modules, and Services](http://roytruelove.blogspot.de/2012/09/angularjs-dependency-injection-modules.html)

An article about the relationship between Dependency Injection, Modules and Services and an implementation.

[Full-Spectrum Testing with Angular.js and Testacular](http://www.yearofmoo.com/2013/01/full-spectrum-testing-with-angularjs-and-testacular.html)

A thorough article on testing in Angular.js.

[An tips and tricks article draft by @knalli](https://gist.github.com/kahlil/5245859#comment-807209)

When I first started this document on Gist @knalli gave some great hints and advice. He started formulating it into article that he will be fleshing out in the future.

[Angular UI Google Group](https://groups.google.com/forum/#!forum/angular-ui)

[Communication between directives](http://thesmithfam.org/blog/2012/12/17/communicating-between-directives-in-angularjs/)

A comprehensive article on how directes can speak to each other in Angular.js.

[Server-side Angular](https://github.com/ithkuil/angular-on-server/wiki/Running-AngularJS-on-the-server-with-Node.js-and-jsdom)

[Scope and Prototypal inheritance](https://github.com/angular/angular.js/wiki/The-Nuances-of-Scope-Prototypal-Inheritance)

> In AngularJS, a child scope normally prototypically inherits from its parent scope. One exception to this rule is a directive that uses scope: { ... } -- this creates an "isolate" scope that does not prototypically inherit. This construct is often used when creating a "reusable component" directive.

Deep dive into understanding directives.

[Animation in AngularJS](http://www.yearofmoo.com/2013/04/animation-in-angularjs.html)

> Up until now, it was safe to say that native animations were not present in AngularJS. Well animation is here and yearofmoo is well prepared to hook you up. So lets take a look at how exactly make use of this great new feature with the world's best JavaScript MVC framework.

[Angular Cats! An AngularJS Adventure Anthology](http://ericterpstra.com/2012/09/angular-cats-an-angularjs-adventure-anthology/)

> Detailed step-by-step on how creating a real-word app with AngularJS. Shows progress and changes as he gets deeper in development.

[Transclude](http://blog.omkarpatil.com/2012/11/transclude-in-angularjs.html)

An article that explains transclusion.

[6 Common Pitfalls Using Scopes](http://thenittygritty.co/angularjs-pitfalls-using-scopes)

> […] six main pitfalls when it comes to working with scopes in AngularJS. Six points which are actually easy if you understand the underlying concepts behind Angular.

## Code

[Yeoman: generator-angular](https://github.com/yeoman/generator-angular)

Yeoman's awesome Angular generator.

[Karma the new testrunner for Angular.js](https://github.com/karma-runner/karma)

Testacular is now Karma.

[JSFiddle Examples](https://github.com/angular/angular.js/wiki/JSFiddle-Examples)

A list of jsFiddle examples.

[ngmodules.org](http://ngmodules.org/)

A site that lists many modules for Angular.

[angular-js.in](http://angular-js.in/)

A curated list of angular modules, directives and services.

[Cary Landholt / AngularFun](https://github.com/CaryLandholt/AngularFun)

> AngularFun is an AngularJS large application Reference Architecture. The intent is to provide a base for creating your own AngularJS applications with minimal boilerplate setup and ceremony.

[ngmin](https://github.com/btford/ngmin)

Special Pre-Minifier for AngularJS

This one tries to solve the problem compressing/uglifying code will break the dependency injection because of variable naming optimizations. Alternatively, you have to use a workaround defining an array with preceding injections. Sad to say, `ngmin` does not work with AMD (RequireJS) atm.

Also available as a [grunt plugin](https://github.com/btford/grunt-ngmin).

[Cool AngularJS Snippets](http://project-fifo.net/display/PF/Cool+AngularJS+Snippets)

Small but useful collection of AngularJS snippets.

[Currency Converter](http://www.programming-free.com/p/currency-converter-using-angularjs.html)

Cool Currency Converter Application built using AngularJS with Tutorial.


## Books

[AngularJS in Action (Early Access Edition)](http://www.manning.com/bford/)

By Brian Ford and Lukas Ruebbelke

> AngularJS in Action covers everything you need to know to get started with the AngularJS framework. As you read, you'll explore all the individual components of the framework and learn how to customize and extend them. You'll discover the emerging patterns for web application architecture and tackle required tasks like communicating with a web server back-end. Along the way, you'll see AngularJS in action by building real world applications with thoroughly-commented code.

[AngularJS (Release: April 2013)](http://shop.oreilly.com/product/0636920028055.do)

By Brad Green and Shyam Seshadri

> Guided by two engineers who worked on AngularJS at Google, you’ll walk through the framework’s key features, and then build a working AngularJS app—from layout to testing, compiling, and debugging. You’ll learn how AngularJS helps reduce the complexity of your web app.

## Updates: Newsletters & More

[AngularJS Weekly](http://paper.li/RaminZamani/1366929635)
> Every week, a nice summary of all AngularJS related content and news.

[ng-newsletter](http://www.ng-newsletter.com/)
> Weekly sent mail newsletter.

## Cheat Sheets

[Cheat Sheet](http://www.cheatography.com/proloser/cheat-sheets/angularjs/)

## Slides

[AngularJS - Extend your Browser](https://speakerdeck.com/petebd/devox-uk-2013-angularjs?slide=2) by @petebacondarwin

[AngularJS Insights](http://pascalprecht.github.com/slides/angularjs-insights/#/) by @PascalPrecht

A great little introduction and teaser into Angular.

[Mastering AngularJS Directives](http://pascalprecht.github.com/slides/mastering-angularjs-directives/) by @PascalPrecht

Diving into directives.

## Snippets

[Angular.js Snippets for Sublime Text 2](https://github.com/maxhoffmann/angular-snippets)

> A collection of Angular.js completions and snippets for JavaScript and HTML files. Be sure to read the README.

## Insights

@[knalli](http://github.com/knalli) says:

> Actually, https://groups.google.com/forum/#!forum/angular is the very valuable source of information about AngularJS.
>
> The official docs aren't always up to date, won't reflect both stable (1.0.x) and unstable (1.1.x) and don't contain so much examples (which you will notice after days/weeks).
>
> So, indeed: Using Google the right way is important because Google indices both Groups and Stackoverflow very, very deep. And sometimes, you should look just at https://github.com/angular/angular.js (including isssues and PRs)...
>
> I'm working with AngularJS since October last year when we'd ported our app in a bigger rework process.
>
> And: Don't forget Angular UI http://angular-ui.github.com/
