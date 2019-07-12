---
layout: post
title: "Web Scraping 101 🔪"
permalink: angular-journey
---

{{ any javascirpt stuff in scope of class }}
[query]="hello" => `hello` is a varible in the scope of the class connected with the component.
(click)="search()" => `search()` is a function called onclick
`*` => means template. you can have only one template in a tag
\*ngIf="card.type == 'blog-post'" => if true, the tag renders, otherwise, no
\*ngFor="let card of cards" => JS for loop.

To use <ng-container \*ngFor="let card of cards"> tag for for loops and such, in the app.module.ts, make the imports include: `imports: [BrowserModule, CommonModule, FormsModule]`

@Input gets a property from the element. For example, if I have this in my class:
`@Input() query: string;`
Then, in the tag, you have a query property like this: <app-mine query="this is cool">

@Output
