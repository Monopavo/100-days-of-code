# 100 Days Of Code - Log

### Day 1: 21st October, 2024

**Today's Progress:** I set up a sandbox and played around with basic animations. I learned the animation shorthand, the four basic transforms (rotate, scale, translate, and skew), and some timing functions. I also had an "a-hah!" moment regarding how transform values work; they're relative to the starting position of the element, not per keyframe.

**Reflections:** CSS is more entertaining than I thought, especially when using VSCode to preview and alter my animations on the fly. Next, I'd like to try and blend these animations together.

**Link to work:** https://tinyurl.com/monocss

---

### Day 2: 22nd October, 2024

**Today's Progress:** I refactored my single page in preparation for more days, turning it into a homepage with nav links. I mainly experimented with combining and layering properties to create a more complex animation, which I'm pretty chuffed with. 

**Reflections:** I initially wrote off vanilla CSS animations as something not worth learning, as "Tailwind will take care of it"; I'm glad I shook off that mentality. I've learned a lot already, and I'm excited to learn even more. My actual design skills need some work, though! So tacky!

**Link(s) to work:** https://tinyurl.com/monoday2

---

### Day 3: 23rd October, 2024

**Today's Progress:** I made a lot of progress today. My project has been refactored once again, this time by placing my .css and .html files in folders. I thought it'd be the best course of action, as I need to learn how to modularise my code and stay organised if I want to learn React and its component structure. I struggled with linking all my stylesheets and webpages together until I discovered "../", which moves the pathing up a directory. I learned about transitions, which are simple yet pretty limited, and also the Bézier curve, which is fun to play around with. Next, I'd like to find a way of making interesting shapes, as I only know how to create basic circles, squares, and rectangles.

**Reflections:** It goes without saying that planning out the structure of a project is the most important step. Redoing the hierarchy of all my files and folders was a bit of a pain, so I can't even imagine how tedious it would be for a larger, more intricate project. Also, vanilla CSS continues to surprise me with how flexible and expansive it is without needing any libraries or frameworks.

**Link(s) to work:** https://tinyurl.com/monoday3

---

### Day 4: 24th October, 2024

**Today's Progress:** I explored the "clip-path:" property and touched up the responsiveness of my project pages a bit. Slow day, but I'm letting everything sink right in.

**Reflections:** "clip-path:" is powerful, but finicky; especially "clip-path: polygon()"; you pretty much need to use a visual representation of the vertices in order to use it effectively, such as a premade .svg image or a generator like Clippy. From browsing around, I saw that "Canvas API" is the preferred method for drawing shapes, but it requires JavaScript. I suppose in terms of pure CSS, "clip-path" is the best option for complex shapes. It already feels like I'm close to learning all I need to learn for intermediate / advanced CSS, so I'm going to begin React next week.

**Link(s) to work:** https://tinyurl.com/monoday4

---

### Day 5: 25th October, 2024

**Today's Progress:** I tried out the "perspective:" property, and created a couple of simple 3D animations alongside a more complex card-flipping animation.

**Reflections:** Today surprised me. I didn't know you could imitate 3D animations with pure CSS, even though it seems pretty obvious in hindsight; after all, how else are all these 3D libraries created? It's likely much harder to use instead of importing a 3D library, but I feel much more informed from trying out "perspective:" as it's given me a sense of how far you can manipulate space on a webpage. "scroll-behavior:" tomorrow, then I'll jump on to learning React. I might continue updating my CSS sandbox with mini "artworks" for the rest of the challenge; it'd be good to have a truly creative outlet, plus it'll consolidate my CSS animation skills.  

**Link(s) to work:** https://tinyurl.com/monoday5

---

### Day 6: 26th October, 2024

**Today's Progress:** I played around with different "scroll-" properties, and why a website can feel "snappy" or "smooth". It's a bit difficult to test out all the properties with how I've structured the divs in my project, but that in itself is a learning experience; plan out the structure of both the .html AND .css files before coding a webpage, let alone a website.  

**Reflections:** On review, I noticed that my CSS style is slowly trending towards modular utility classes; at least the transition to Tailwind won't be too difficult, I suppose. I'm itching to start React, but I'll run through all I've learned this week tomorrow instead and start fresh on Monday.

**Link(s) to work:** https://tinyurl.com/monoday6

---

### Day 7: 27th October, 2024

**Today's Progress:** I tried to make a particle animation with pure CSS, but being unable to use mathematical expressions for randomisation made it a pain. SASS is my next step once I get the basics of React down, as I'm feeling the limits of pure CSS when it comes to dynamic animations and styling. I also poked my nose into a little TypeScript, and I'm interested in static typing; it seems like a lot of busy-work, but being declarative with your data types, creating custom types, and catching errors before compiling sounds neat. I'm starting React tomorrow, so I'm excited to get into the meat of responsive UI and state management!

**Reflections:** Honestly, it's pretty exciting seeing how many different directions I can branch out from just pure HTML, CSS, and JavaScript; I was afraid I'd be overwhelmed by the sheer number of libraries, frameworks, pre and post-processors, and all the other expansions that can be tacked on to the core three, but now that I've got a better grasp of the limitations of HTML, CSS, and JavaScript I can now pick and choose what to learn. It's surprisingly liberating, even at the relative start of my learning journey.

**Link(s) to work:** https://tinyurl.com/monoday7

---

### Day 8: 28th October, 2024

**Today's Progress:** I learned how Vite works, and how to configure it for GitHub Pages. It sucked up most of my time, so all I have is a component that I rendered nine times, each with a different prop value; baby steps, I suppose.


**Reflections:** It's early days, but I adore TypeScript so far; having errors pop up instead of missing type coercion or conversion is fantastic, especially as it catches any instances before the whole project compiles. I can definitely see why people rant and rave about learning it; I'm a new convert to static types!

**Link(s) to work:** https://tinyurl.com/monopttt

---

### Day 9: 29th October, 2024

**Today's Progress:** I learned more about TypeScript interfaces, <React.StrictMode>, CSS Modules, and the general structure of a React project in terms of folders, files, and the descending "index.html => main.tsx => App.tsx => Component.tsx => componentStyle.module.css" hierarchy.  

**Reflections:** After a bit of teething problems, I think CSS Modules are great, as it's much easier to handle specificity and conflicts on a component-by-component basis rather than juggling larger stylesheets. Frankly, I jumped in at the deep end with TypeScript, but I'm slowly internalising the syntax and (oddly enough) finding it easier to grasp the concepts of React with it than with JavaScript; maybe I needed a bit of complexity to engage my brain more? Regardless, I think after this project I'm going to "downgrade" to using JavaScript for React; it's been a great learning experience with TypeScript, and certainly something to aim for as soon as possible, but my current skills aren't good enough to make it worthwhile just yet. I might upgrade my "general" coding language to TypeScript and use JavaScript for React, so it isn't a wasted effort.

**Link(s) to work:** https://tinyurl.com/monopttt

---

### Day 10: 30th October, 2024

**Today's Progress:** Finished my React-Typescript tic-tac-toe app. It's very rough around the edges, and I didn't care that much about styling; function over form for my React projects, for now.

**Reflections:** I learned a LOT about TypeScript and state management through trial and error, and the syntax has been ingrained in my bones. The structure of interfaces is elegant, and the error detection is fantastic, but TypeScript isn't suitable for me at my current skill level and the scope of my learning projects. As such, it's back to JavaScript with me. Also, I learned the hard way that it's vital to sort out all your logic and architecture before writing a single line of code, as otherwise you'll get entangled in a web of states.

**Link(s) to work:**https://tinyurl.com/monopttt

---

### Day 11: 31st October, 2024

**Today's Progress:** I started a to-do app project in React, but this time with JavaScript. In quite a short time, I managed to create multiple components and their CSS module files, set up the GH-Pages configs, and render all of my components within the grid model.  

**Reflections:** I'm very glad that I tried TypeScript first, as it's given me both a greater appreciation for dynamic typing and a deeper knowledge of the underlying structure of types and props. Honestly, the sheer speed of dynamic typing is probably its greatest strength, but I miss the error-catching features of TypeScript in VSCode.

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 12: 1st November, 2024

**Today's Progress:** TBC

**Reflections:** TBC

**Link(s) to work:**

---

### Day 13: 2nd November, 2024

**Today's Progress:** TBC

**Reflections:** TBC

**Link(s) to work:**

---

### Day 14: 3rd November, 2024

**Today's Progress:** TBC

**Reflections:** TBC

**Link(s) to work:**
