<!--Actually 2:14 -->

<!--Hook: So now you know Angular 2+ pretty well, well enough to build a full-stack Single Page App with it.  Lots of dev shops now are switching from Angular 1.x, though, so you'll want to get some exposure to it.  If you are looking at jobs now that require Angular 2+, I highly encourage you to take this brief introduction to the next level.  You should probably choose Angular 1 or an Angular topic for your lightning talk in Unit 4, and try to use Angular 4 in your Project 4.  -->

<!--WDI6 9:12 -->
<!--WDI3 11:01 -->
<!--1:30 15 minutes -->

<!--WDI4 9:04 -->

# Angular 2+ vs Angular 1

## Objectives
*By the end of this lesson, developers will be able to:*

- **Describe** the major improvements between Angular 1 and Angular 2+
- **Describe** some of the most important syntax changes between Angular 1 and Angular 2+

## A little history

Angular 2 was a highly anticipated release.  When it came out on September 15, 2016 a lot of developers, many of whom were already using Angular 2 in a Beta- or Release-Candidate-version, let out a resounding "finally!"  Almost exactly two years after development was announced, front-end developers finally had a stable enough version to bring Angular 2 to their production apps.  Why were they so excited?

## Components

Angular 2+ is entirely component based. Controllers and $scope are no longer used. They have been replaced by components and directives. Components are just directives with a template.

Components play a really big part in React development as well, which we will get to soon.  Basically, components are a major change in website design.  Rather than separate concerns by language or place in the stack, components separate concerns by object.  So, for instance, we bundle HTML, CSS, and JS together to create a `student` component.

## TypeScript

As mentioned earlier, TypeScript brings all of the modern functionality of ES6 into Angular 2+.  In addition, it provides powerful error checking and ensures code integrity through the use of types, classes, and more.

## Performance Improvements

Many of the things in Angular 1, like two-way binding updates, filtering, and ordering, were inefficient.  Angular 2+ tightens up a lot of these issues so even very large apps can scale with fast page loads and data synching.

## Mobile Support

Angular 2+ was designed with mobile development in mind.  There are two tools in particular that make Angular 2+ more powerful for mobile development

- NativeScript, which compiles Angular 2+ directly into *native* iOS and Android apps -- as in, it actually creates an app in Objective-C or Java, respectively.  This simply does not exist for Angular 1.
- Ionic 2+ which creates *hybrid* apps from Angular 2+ code -- as in, it uses the native web view on a mobile device to render a web page that can access the phone's API (for example accelerometer and camera).  This is vastly improved in Ionic 2+, and provides a powerful mechanism for adding new custom API integrations.

## Much More

There are lots of other exciting features in Angular 2+, like `$scope`less data binding, better form building and validation, and improved dependency injection, to name a few.  I highly encourage you to run through the Angular [Tour of Heroes Tutorial](https://angular.io/tutorial) if you haven't already, and pick up some tutorials and sample projects from the Angular team if you are looking to join an Angular 2+ team.

<!--Actually 2:22 -->

<!--11:10 WDI3-->
<!--1:45 15 minutes -->

## The Code

I know what you're thinking.  "Wait, this class is called 'Web Development Immersive' not 'Web Talking Immersive', what does the code look like?"  Excellent question, let's take a look at [the major differences in the code](https://angular.io/guide/ajs-quick-reference), and let that drive the refactoring lab we will do next.

<!--WDI4 9:15, coming back 9:20 to talk, 9:24 done -->
<!--11:26 WDI3 -->
<!--Actually 2:40 -->
<!--WDI6, turning over to devs 9:21, coming back 9:30 -->

## Resources

- [Angular 1 to 2 Quick Reference](https://angular.io/guide/ajs-quick-reference)
- [Quora post on Angular 2 differences](https://www.quora.com/What-is-the-difference-between-AngularJs-and-Angular-2)
- [Blog Post on Angular 2 differences](https://dzone.com/articles/typed-front-end-with-angular-2)
- [Angular 2 Tour of Heroes](https://angular.io/tutorial)
