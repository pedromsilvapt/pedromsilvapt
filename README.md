## About Me
My name is Pedro Silva. I've started programming from a very young age, since I was 13 years old, on my own free time. I am 24 now, and I have a Bachelor's Degree in Computer Science and (am currently finishing) a Master's in Computer Engineering. I have lot's of experience with PHP, C#, JavaScript/TypeScript and Python. I've worked with AngularJS/Angular2, Vue, Laravel, ASP.NET Core and more. But more than what I already am familiar with, I'm always eager to know what I can learn more.

## Work Showcase
I've worked on countless projects: at Blip during my internship there, at school and in college, and in my own free time. You can see some of them below.

### Unicast
For the last five years, I've been developing, as a hobby alongside my brother, a web-based media center, inspired by the Kodi project, that is responsive (mobile friendly), can be remotely controlled on the smartphone, and player agnostic (extensible, with out-of-the-box support for streaming to Chromecast devices, to a MPV player and to a Kodi media center). As a result of this, I've also learned a lot about working with FFmpeg.

 - **Tech Stack** NodeJS backend written in TypeScript, backed by a RethinkDB database with an Angular 2+ frontend
 
 [![Screenshot](http://pedromsilvapt.github.io/unicast/images/screenshots/alpha/shows-list.png)](http://pedromsilvapt.github.io/unicast/screenshots.html#lg=1&slide=2)

> See more screenshots [here](http://pedromsilvapt.github.io/unicast/screenshots.html#lg=1&slide=2) :camera:, repositories available [here (backend)](https://github.com/pedromsilvapt/unicast) and [here (frontend)](https://gitlab.com/unicast/unicast-interface) :memo:

### Assiduidade
When I was 18 years old, for my individual high school Professional Aptitude Project, I developed a web application to manage the logistics of tracking absentee teachers and finding replacements for their classes, which required managing teachers, students, courses, classrooms and class schedules.

 - **Tech Stack** PHP backend (custom made framework w/ Routing, DB, REST, DI, ACL and more), backed by a MySQL database with an Angular JS frontend
 
 [![Screenshot](https://github.com/pedromsilvapt/pedromsilvapt/raw/master/assiduidade-screenshot.jpg)](https://www.youtube.com/watch?v=UaVlAQFEcIM&list=PLt5ao-eCbVn3kK2h63uE7F2ggw7CXYRIR&index=4)

> See a quick **demo video** [here](https://www.youtube.com/watch?v=UaVlAQFEcIM&list=PLt5ao-eCbVn3kK2h63uE7F2ggw7CXYRIR&index=4) :clapper:

### MusiKLa - Music and Keyboard Language
For my Master's dissertation, I've designed and developed a Domain Specific Language for creating music algorithmically. It features variables, loops and other control structures, functions, modular files, declaring reactive virtual musical keyboards and much more. It can play the sounds live, save the music sheets or export as MIDI events, among others.

- **Tech Stack** Python command line application, with a LALR grammar

<p align="center">
  <a href="https://tenor.com/view/dogs-cats-gif-8707712">
  <img src="https://github.com/pedromsilvapt/pedromsilvapt/raw/master/musikla.png" alt="Musikla Code Sample">
  </a>
</p>

> See the repository [here](https://github.com/pedromsilvapt/miei-dissertation) :memo:

### Async Iterators
I program in TypeScript a lot, and have extensive experience with it's async nature. One of the projects I've developed contains a fair bit of utility functions designed to work with the recent async iterators added to the ECMAScript specification. Many of the operators are fairly simple (such as `map` and `filter`) while others are fairly more complex (such as the `flattenConcurrent` operator, whose source code is available [here](https://github.com/pedromsilvapt/data-async-iterator/blob/master/src/combinators/flatMap.ts#L38-L215) :point_left:).

```typescript
import { from, delay, map, flatMapConcurrent } from 'data-async-iterators';

// Create an asynchonous iterable stream
const source = delay( from( [ 1, 2, 3, 4 ] ), 1000 );

// A closure that takes a number and slowly returns the number and it's square
const mapper = number => delay( from( [ number, number * number ] ), 4000 );

// Run mapper concurrently only twice
const flatMapConcurrent( source, mapper, 2 );

// And finally consume the values (returns a promise notifying when the iterator ends)
forEach( source, res => console.log( res ) );
```
> See the full repository [here](https://github.com/pedromsilvapt/data-async-iterator) :memo:

#### Pinned Repositories
For reading this far, here is a cute GIF of a cat and a dog as a thank you! :heart:

<p align="center">
  <a href="https://tenor.com/view/dogs-cats-gif-8707712">
      <img width="460" src="https://github.com/pedromsilvapt/pedromsilvapt/raw/master/cat-and-dog.gif" alt="Kitten and Dog">
  </a>
</p>

Below :point_down: you can also find a list of my pinned repositories, or you can also look at the [complete repository list](https://github.com/pedromsilvapt?tab=repositories).
