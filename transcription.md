# Angular

## Introduction
Hello, my name is Misha. I study on courses in the Rolling Scopes School. And in this video I want to talk about one of the most popular frameworks Angular.

1. About Angular
Angular introduces Google's framework for building client applications. First of all, it targets the application of SPA solutions, that is single page applications. In this regard, Angular is the inheritor to another AngularJS framework. At the same time Angular is not a new version of AngularJS, but a fundamentally new framework.
Angular provides functionality such as two-way binding to dynamically change data in one place in the interface when model data changes in another, templates, routing, and so on.
One of the key features of Angular is that it uses TypeScript as its programming language.

2. Advantages
Angular has the following advantages
- Large community:
Let's start with the fact that Angular has a huge community. It includes members of the permanent development team, as well as those who want to contribute to the development of the open source framework. There are many conferences about Angular, they talk about it at hackathons and argue about it in the thematic IT community. There are many Angular books and online resources for developers. For clients, this means: by choosing Angular.js, you will not only be on trend, but you will always be able to find developers to support your project.
Now learning Angular has become convenient for Russian-speaking developers, because quite recently the Russian community was officially added to the developer site angular.io. There are many different Angular streams in Russian, people can send their pull-request(s) or developments and become members of the Angular-RU developer community.
- Angular is used together with Typescript. He has exceptional support for this.
- Angular-language-service – Provides smart capabilities and autocomplete HTML component template.
- New features such as generation Angular using npm libraries from the CLI, and component development using Angular.
- Detailed documentation allowing the developer to get all the necessary information without resorting to the help of his colleagues. However, this takes longer to learn.
- One-way data binding, which provides exceptional application behavior that minimizes the risk of potential errors.
- MVVM (Model-View-ViewModel), which allows developers to work separately on the same section of an application using the same dataset.
- Component Dependency Injection, related to modules and modularity in general.
- A structure and architecture specially tailored for large project scalability.

3.	Disadvantages
However, it is worth noting the cons of this framework
- Higher entry threshold due to Observable (RxJS) and Dependency Injection;
- For everything to work well and quickly, you need to spend time on additional optimizations (it is not super fast, by default, but is many times faster  than AngularJS and with each new version it becomes faster);
- In fact, if you plan to develop a large enterprise application, then in this case you do not have an architecture for managing state out of the box – you need to add Mobx, Redux, CQRS / CQS or another state manager
- Dynamically creating components is not a trivial task.

4.	Angular concepts
In fact, all these disadvantages are leveled by the developer's own experience. Everything you need to learn in Angular to develop productive and fast-working applications of any complexity is described in the following concepts:
- Form Builder - to develop truly complex forms, you should know reactive forms, or rather basically forget about declarative forms.
-	Change Detection - Since Angular uses two-way data model binding by default, your applications will run slower when working with large amounts of such data, so in some cases it is worth taking care of the correct change detection strategy. You can look at various OpenSource projects: PrimeNG, Angular Material, Clarity UI, Angular Bootstrap and others, they all use ChangeDetection.OnPush.
-	Templating - from the point of view of abstraction, the syntax of templates has not changed too much compared to AngularJS, that is, we can also write conditions, loops, bind a data model, and so on. All you need to have a good understanding of Angular templates is what structural and declarative directives are, and what Input parameters and Output events are.
-	Routing is probably one of the fundamental phenomena in web application development. It is just important to understand that routing, just like components, has its own life cycle, understanding this, you can write really cool applications. It is also worth noting: if on any of the routes you hang a module, and not a component that is responsible for displaying the page along this route, then the module will be loaded on the page on demand.
-	Annotations - by the way, many beginners don't know, but it's worth noting. Decorators, which are used in abundance when writing Angular applications, are not some hard-core TypeScript magic. Decorators are a specification of  EcmaScript and when browsers start supporting them, they will be executed natively in the browser runtime. In fact, decorators are quite useful and make your code quite readable.
-	Observables - in fact, it's only worth noting here that Observables will soon be an EcmaScript specification and all of this will be natively supported in browsers. From a theoretical point of view, if you expand the concept of Observer (observer) - this is a behavioral design pattern. Also known as Dependents. Creates a mechanism for a class that allows an object instance of this class to receive notifications from other objects about a change in their state, thereby observing them.
-	Shadow DOM is a means for creating a separate DOM tree inside an element, which is not visible from the outside without the use of special methods, is a W3C specification. Roughly speaking, it is a convenient way to create isolated and reusable web components. Technically, if browsers already supported many of the concepts that Angular uses today, we would not need transpilers and other build systems, everything that we wrote in Angular would already work natively.

## Conclusion
For a seasoned developer, it doesn't really make a big difference which framework to use, it just takes a while to get used to the new one. Each framework has its own pros and cons, which means that when developing a product, you need to make the right choice for each case.
Thanks for watching this video, I wish you productive programming!