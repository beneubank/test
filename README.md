# [Kingdom Hearts Soundboard](https://skullface.github.io/kingdom-hearts-soundboard/)

🗝👑💗⭐️ Created for my [100 Days of JavaScript](https://github.com/skullface/100-javascript-projects) challenge via [#JavaScript30](https://javascript30.com/)’s first project, [JavaScript Drum Kit](https://github.com/wesbos/JavaScript30/tree/master/01%20-%20JavaScript%20Drum%20Kit). All audio files copyright to their respective owners, used for personal entertainment purposes only.

## Observations and learnings
#### July 29th, 2017
I don’t really know what any of this means! But I completed the exercise and customized it to my liking!

ES6 is a fun, new thing for me. Up until this point, my experience with JS is mostly implementing and editing existing jQuery plugins for simple interactivity since the early 2010s. Not really any different from copying scripts from DynamicDrive to make cursor trails and falling snow, really. I’m not used to seeing `const` instead of `var` and I don’t even really know when or why the cute arrow `=>` is used to be perfectly honest. I’m happy the instructor uses ES6 so I’m learning the most up to date stuff!

In the videos, the instructor’s text editor uses a JS-autocomplete function. I’m deciding not to install one of those at this point in time. Typing the code out in full, however verbose and with whatever likelihood of messing up a `)};` by hand, is a better practice for me to get familiar with the syntax.

I’m more bothered than I should be by the lack of [click and touch support](https://twitter.com/skullface/status/891458847067570177). I want to include this somehow… otherwise it feels kind of pointless as a project beyond a learning exercise! As I was rewriting my CSS, I instinctively included styling for small screens (mobile-first), but that little viewport styling is only good if your computer browser window is small. 😂 I know adding support for _pointer events_ involves things like `click`, `mousedown`, `touchstart`… and I *think* those ”things” are, more technically, `events` I `bind` a `function` to…?! But it’s not as simple as including them alongside `keydown` in the `window.addEventListener('keydown', playSound);` method.

I’m looking forward to getting more familiar with ES6 syntax and feeling confident in knowing exactly which bits of codes are events and bindings and methods and functions (like I do with CSS selectors and declarations and properties and values).

## @TODO
#### Support for click or touch events (as well as keyboard presses)
