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

**Reflections:** "clip-path:" is powerful, but finicky; especially "clip-path: polygon()"; you pretty much need to use a visual representation of the vertices in order to use it effectively, such as a premade .svg image or a generator like Clippy. From browsing around, I saw that "Canvas API" is the preferred method for drawing shapes, but it requires JavaScript. I suppose in terms of pure CSS, "clip-path" is the best option for complex shapes. It already feels like I'm close to learning all I need to know for intermediate/advanced CSS, so I'm going to begin React next week.

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

**Today's Progress:** I tried to make a particle animation with pure CSS, but being unable to use mathematical expressions for randomisation made it a pain. SASS is my next step once I get the basics of React down, as I'm feeling the limits of pure CSS when it comes to dynamic animations and styling. I also poked my nose into a little TypeScript, and I'm interested in static typing; it seems like a lot of busywork, but being declarative with your data types, creating custom types, and catching errors before compiling sounds neat. I'm starting React tomorrow, so I'm excited to get into the meat of responsive UI and state management!

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

**Link(s) to work:** https://tinyurl.com/monopttt

---

### Day 11: 31st October, 2024

**Today's Progress:** I started a to-do app project in React, but this time with JavaScript. In quite a short time, I managed to create multiple components and their CSS module files, set up the GH-Pages configs, and render all of my components within the grid model.  

**Reflections:** I'm very glad that I tried TypeScript first, as it's given me both a greater appreciation for dynamic typing and a deeper knowledge of the underlying structure of types and props. Honestly, the sheer speed of dynamic typing is probably its greatest strength, but I miss the error-catching features of TypeScript in VSCode.

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 12: 1st November, 2024

**Today's Progress:** I didn't make much progress in terms of React today, as I was struggling with implementing a responsive grid layout. I had lots of inconsistencies between my local build and the deployed GH-Pages build, which was probably because I was using % and em instead of rem. I'll start implementing some states tomorrow.

**Reflections:** Although it ate up my day, having this issue has got me thinking more about responsive design and relative units. Without media queries, rem is by far the most consistent unit as you're scaling against the root rather than any elements.

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 13: 2nd November, 2024

**Today's Progress:** I implemented an add button to my to-do app, creating multiple list components to an array. I also went through a sizeable refactor of my styling and logic, as I was expanding my scope needlessly.

**Reflections:** After I'm done with this project, I really need to get in the habit of drafting pseudocode before anything else; I've been burned twice now, and it's clearly shown me the importance of planning. I think this is especially important with React, considering you can have a component's state be defined within itself, abstracted from other components. Also, I love "position: absolute"; grid and flex are great for containers, but not so much for a responsive "root" layout without media queries.

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 14: 3rd November, 2024

**Today's Progress:** Got the delete and update buttons working after lots of trial and error. I also tidied up my component code by using fragments, and I discovered "prop object encapsulation"; wrapping multiple props into a single prop, and then passing that down to prevent excessive prop declarations.

**Reflections:** It was a huge day regarding my understanding of props; their basic structure finally clicked with me after hours of struggling. The core issue was my lack of planning and component hierarchy management as a newcomer to React; I was essentially winging it, so I had a lot of random code on both the JSX and CSS side that made things a mess to debug. I'll make a concerted effort to draft my project's structure before committing to any big implementations, or even small prototypes. Honestly, doing everything the "wrong way" has made progress stressful yet very insightful. I feel as if everything I've learned so far is crammed tightly in the forefront of my mind after bashing my head against syntax errors for the last dozen or so hours. I'm building a rock-solid foundation; keep it up, future me!

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 15: 4th November, 2024

**Today's Progress:** I add an "edit" toggle to my "update" button, allowing it to switch between buttons depending upon the task item's editability state. I'm getting comfortable with useEffect(), and I'm slowly adding media queries to make my theme and layout more responsive.

**Reflections:** useEffect() finally clicked with me; it observes the state or value encapsulated by the dependency array, and then whenever it changes it executes the code encapsulated in the first argument. Funnily enough, it seems like I've made a "CRUD" app, but I'm running out of meaningful implementations; I might consider this project finished unless I can think of any interesting ideas to push my learning further.

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 16: 5th November, 2024

**Today's Progress:** I implemented some media queries, particularly for mobile and tablet devices, as well as adding unicode symbols for my buttons rather than just text labels.

**Reflections:** Once again, it's a matter of planning; as one of my first projects, I didn't take into consideration different devices and resolutions, let alone user preferences like dark mode. I've patched it into my code, but it's not as elegant as establishing these things at the beginning of a project. With modern device usage predominately being mobiles and portables, it's a much better idea to design layouts for portrait devices first. Lots of learning regarding responsive design overall, despite not much coding. Media queries are very powerful, and it's both fun and annoying trying to optimise the correct ranges for each style.

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 17: 6th November, 2024

**Today's Progress:** I added the "clear" and "save" buttons today.

**Reflections:** Yep, that's it; not much progress, but I'm souring a bit on this project. I've been working on this to-do app for over a week now, and I've learned a ridiculous amount, but the core, underlying structure is just too messy to try and fix; if I do, I feel like everything will unravel and break. At least using "localStorage" is surprisingly simple, which is great; I was dreading that it'd be much more difficult, considering you're writing and pulling data to and from a user's browser. 

**Link(s) to work:** https://monopavo.github.io/100-days-todo-app/

---

### Day 18: 7th November, 2024

**Today's Progress:** I decided to consider my to-do app project "finished", retiring it as a stepping stone. I redefined my goals going forward, with a focus on React, UI and UX design with the aid of Figma, and project planning.

**Reflections:** I've learned a LOT, but it's time to start fresh with a new React project as I don't think I can draw any more learning out of it. I'll try integrating APIs next, but I'll take my time planning; I've just been winging it as an unguided beginner, whereas I need to consider a project's purpose, scope, and MVP. My main reflections on this project are that...

* I need to plan more, preferably with pseudocode.
* I need to use atomic commits, so that I feel more secure to make bigger leaps in implementation.
* I need to establish  a mobile-first design, and then then expand the layout for larger resolutions; not the other way around.
* I need to establish the structure and interactivity of the DOM, and THEN embellish it with styles.
* I need to refactor and optimise my code after profiling and debugging, as pre-optimising is a major time-waster.

**Link(s) to work:** N/A

---

### Day 19: 8th November, 2024

**Today's Progress:** I got quite familiar with Figma's UI and tooling, did basic research on user behaviours to enhance my designs, and searched public API listings in an attempt to get inspiration for a project idea.

**Reflections:** Yet again, not much in the way of coding outside of daily maintenance. I'll have to look up how to do "0auth" later, but I'm going to start simple and use no-key APIs. The Gutenberg diagram and the concept of "reading gravity" is fascinating, and I'll definitely incorporate it in my designs going forward. It's obvious in hindsight, but Ui and UX are more of a science than I thought; it's the manipulative application of psychology that is used to provoke, attract, and coerce in a (hopefully) moral way. What an interesting specialisation... and one that I might pursue later on.

**Link(s) to work:** N/A

---

### Day 20: 9th November, 2024

**Today's Progress:** I drafted some logic and component hierarchy trees, as well as set up my environment by downloading Tailwind CSS and all other dependencies.

**Reflections:** Not too much progress, as I'm browsing around for free APIs that spark my interest. I tried out Tailwind CSS, and I have mixed feelings about it; I can see how fast you could develop prototypes once you've memorised a good number of the utility classes, however having all of those utilities chained as inline styles feels like a complete 180 from the concept of abstraction and code clarity.

**Link(s) to work:** N/A

---

### Day 21: 10th November, 2024

**Today's Progress:** I decided upon a solid project idea; a search engine for free video games. After adjusting my previously planned trees, I jumped into VSCode and began composing my app, establishing the basic layout and basic object data. I've also begun to make a new logo for myself in Figma to reflect my current style sensibilities.

**Reflections:** The process was far smoother than I thought; more than likely due to three days of planning behind me. I've also noticed that my speed with CLI is notably increasing, almost to the point of it being faster to reach my project's directory through GitBash than clicking on the folder itself.

**Link(s) to work:** N/A

---

### Day 22: 11th November, 2024

**Today's Progress:** Feeling a nasty cold brewing, so I'm taking a semi-day off today; mostly revision and introspection.

**Reflections:** I believe I need to break down my perfectionist tendencies; what's holding me back is the desire to have all of my code perfectly optimised, and not a pixel unaligned with my styling, which is eating into precious learning time. I need to treat these projects as the stepping stones they are, rather than projects that I can proudly place on a portfolio. 

**Link(s) to work:** N/A

---

### Day 23: 12th November, 2024

**Today's Progress:** Feeling absolutely awful today; I have a terrible headache and nasal congestion, leaving me unable to sleep. I only managed to do revision, but I did rediscover the "useContext" hook, which might bring a bit of abstraction back into my workflow.

**Reflections:** N/A

**Link(s) to work:** N/A

---

### Day 24: 13th November, 2024

**Today's Progress:** Still recovering... and I hate it. My momentum has been killed by a cold, and I'm struggling to build it back up again. Physical and mental exhaustion, but at least more revision has made defining components and state effortless to me now.

**Reflections:** TBC

**Link(s) to work:** N/A

---

### Day 25: 14th November, 2024

**Today's Progress:** My final day of pure recovery, as my symptoms are waning. I'll work on "useContext" tomorrow.

**Reflections:** TBC

**Link(s) to work:** N/A
 
---

### Day 26: 15th November, 2024

**Today's Progress:** I tried out the "useContext" hook, and also finished off the core components of my project. Only logic and styling are left.

**Reflections:** "useContext" is much more powerful and flexible than I thought; it isn't just state and values, but entire objects that can be wrapped up and passed down. It's a full-blown data structure, so it'll take me a while to master it and figure out best practices, but it seems excellent for defining, quite literally, contextual data and states that can be used in a modular, "plug-and-play" manner. 

**Link(s) to work:** N/A

---

### Day 27: 16th November, 2024

**Today's Progress:** I learned about using the "dotenv" package to keep API keys secure and private by employing environmental variables. I also touched on GitHub Actions, as GH Pages requires additional setup to accept .env files. 

**Reflections:** I struggled a lot with setting up an API fetch query, as I was getting all tangled up in the syntax. Today has definitely shown me that I need to work on my JavaScript fundamentals instead of trying to master React; I should be mastering the underlying technology and languages rather than jumping straight to libraries and frameworks. Once this project's done, I might shift to a purist project; just HTML, CSS, and JavaScript; maybe with SASS for a bit of extra learning.

**Link(s) to work:** N/A

---

### Day 28: 17th November, 2024

**Today's Progress:** I finished and deployed my app prototype to Vercel.

**Reflections:** I'll probably not use GitHub Pages again for React or Vite projects; the entire configuration and setup is an ordeal compared to how effortless Vercel is, even if I lose out on the pro of having my repository and Pages under the same service. There's a lot to learn about MIME and CORS... but I need to focus on my immediate goal; to become highly proficient in full-stack JavaScript development.

**Link(s) to work:** https://100-days-game-grinder.vercel.app/

---

### Day 29: 18th November, 2024

**Today's Progress:** I brushed up on some basic JavaScript in preparation for the School Of Code BootCamp, which is a week away.

**Reflections:** I decided to leave my prototype in an "MVP" state; once again, I need to treat my current projects as stepping stones for my learning journey. At the very least, the entire process of learning the basics of React has really bumped up my conceptual knowledge of OOP, app development, and Javascript as a whole. All that remains now is for me to become fluent... which might take a while, considering I keep forgetting common methods and syntax.

**Link(s) to work:** N/A

---

### Day 30: 19th November, 2024

**Today's Progress:** More revision to reflect upon and address any clear weaknesses I have pre-bootcamp.

**Reflections:** From what I know of JavaScript so far, my sorest spot is asynchronous programming. I conceptually understand Promises, async/await, and try/catch, but I've barely used them outside of my "Game Grinder" project. Perhaps a project involving asynchronous calls to an API would be a decent idea, but I'll have to brainstorm an interesting concept and search around for some free or rateless APIs; preferably something that isn't game-adjacent, like all of my projects on this challenge so far.

**Link(s) to work:** N/A

---

### Day 31: 20th November, 2024

**Today's Progress:** I'm still deciding on an API-based project to learn asynchronous programming. In the meantime, I'm committing myself to making HackerRank, LeetCode, and Codewars part of my daily routine.

**Reflections:** Although I've used Codewars before as part of my revision, I'm throwing myself into the frying pan with HackerRank and LeetCode. Even so, I need to refine my functional programming and problem-solving skills if I want to keep up and overtake my competitors for junior interviews; might as well start the habit of learning DSA nice and early. Historically speaking, I seem to learn much faster under pressure, so going through a trial by fire might just be what I need to make a bigger leap in my understanding of coding.

**Link(s) to work:** N/A

---

### Day 32: 21st November, 2024

**Today's Progress:** I scrapped plans for an asynchronous API project; I'm using Rapid API Learn to learn the basics instead. 

**Reflections:** I need to be wary of time management going forward as the School Of Code's bootcamp starts on Monday; there's no point in trying to rush my learning of asynchronous programming in less than a week, especially when I'll be taught best practices on the bootcamp itself.

**Link(s) to work:** N/A 

---

### Day 33: 22nd November, 2024

**Today's Progress:** I went through a variety of challenges as part of my daily routine, leading to multiple breakthroughs and expansions in my knowledge.

**Reflections:** LeetCode was very tough at my current level, but I got a huge "aha!" moment out of it; most JavaScript methods are abstracted higher-order functions that accept a callback and a value as arguments, which are then reiterated via loops. Diving into more complex topics, even at my current level, was a really good idea; even learning a smidgen about 2D Arrays/matrices has bumped up my knowledge and conceptualisation of data and its encapsulation. It feels great punching above my weight after feeling in a slump.

**Link(s) to work:** N/A

---

### Day 34: 23rd November, 2024

**Today's Progress:** I focused on utilising loops and iteration, as well as learned the basics of REST APIs. 


**Reflections:** I'm surprised how far you can get with just correctly-scoped variables and loops, even if the code gets more verbose; I suppose that's where space and time complexity comes in, but I don't feel ready for that just yet. It's also been quite fun getting into the theory and anatomy of how data interchange works; I think what was tripping me up were "Content-" entity headers, and the fact that the body can be optional depending on the HTTP method used.

**Link(s) to work:** N/A

---

### Day 35: 24th November, 2024

**Today's Progress:** I underwent basic revision to prepare myself for the School Of Code Bootcamp, which starts tomorrow.

**Reflections:** I'm trying to psyche myself up for tomorrow; Imposter Syndrome's creeping in, as I feel I don't deserve to be part of the bootcamp... but that's also my primary motivator. I've been chosen from thousands of applicants, so I can't disrespect everyone else's efforts or drag down my peers. I also feel way out of my comfort zone, but I've been throwing all my energy into learning, as well as learning how to learn, so let's hope it pays off!

**Link(s) to work:** N/A

---

### Day 36: 25th November, 2024

**Today's Progress:** SoC Week 1 D- Day 1: Intro session with the School Code.

**Reflections:** I already have a lot to think about regarding my mindset and prospects. Also, I feel that as AI advances continue to increase, being an articulate problem-solver, a team player, and understanding DSA will be the keys to staying afloat.

**Link(s) to work:** N/A

---

### Day 37: 26th November, 2024

**Today's Progress:** Soc Week 1 - Day 2: First official day of the School Of Code Bootcamp; introductions and icebreakers, as well as Ira Rainey as a guest speaker.

**Reflections:** The intro session went quite well, and everyone seemed friendly... but most importantly, I have a lot to think about regarding my mindset and prospects. My Imposter Syndrome is at an all-time high despite psyching myself up, and my self-image issues are rearing their ugly head, but I knew I wouldn't be rid of them overnight; it'll be a long road ahead, but I've got to just grin and bear it.

**Link(s) to work:** N/A

---

---
---
# IMPORTANT NOTE: #
* All posts between Day 38 and Day 42 (inclusive) are paraphrased based on the post that I made on X/Twitter, as well as my natural recollections.
* This is due to overwhelming internal stressors surrounding reconciling with my surival of domestic, physical, sexual abuse, and my social anxiety.
---
---

---

### Day 38: 27th November, 2024

**Today's Progress:** SoC Week 1 - Day 3: An introduction to neural networks, a presentation by Ira Rainey from Microsoft regarding Imposter Syndrome, and a fun exercise to hack into an LLM. 

**Reflections:** As an introvert, I'm already surprised by my progress; I no longer feel flushed or embarrassed talking to my fantastic teammates, and even my stammering has reduced. It just goes to show that adaptation and growth are accelerated with the right stressors and environment. The highlight has to be the eye-opening presentation by Ira and achieving a Growth Mindset.

**Link(s) to work:** N/A

---

### Day 39: 28th November, 2024

**Today's Progress:** SoC Week 1 - Day 4:

**Reflections:** TBC

**Link(s) to work:**

---

### Day 40: 29th November, 2024

**Today's Progress:** SoC Week 1 -Day 5:

**Reflections:** TBC

**Link(s) to work:**

---

### Day 41: 30th November, 2024

**Today's Progress:** 

**Reflections:** TBC

**Link(s) to work:**

---

### Day 42: 1st December, 2024

**Today's Progress:** TBC

**Reflections:** TBC

**Link(s) to work:**

---

---
---
#IMPORTANT NOTE: #
## Accomplished a confident self through experimenting through developing my own growth nindset. ##
---
---

---

### Day 43: 2nd December, 2024

**Today's Progress:** SoC Week 1 - Day 1: Logical Problem Solving, JavaScript Workshop.

**Reflections:** I knew going into this programme that it's about understanding the problem, but having a day focused on this concept has been eye-opening. I'm beginning to see code as an actual "language"; we're basically the interpretors or translators for a human problem. Our JavaScript workshop has really stressed this point to me, as I found myself breaking up the problem statements into separate clauses, chunking them down. Coding may not be all about math, but it sure is about knowing how to comprehend a problem. The abstraction of "interfaces" is also interestineg; I'll have to research more about it. 

**Links(s) to work:**

---

### Day 43: 2 December, 2024

**Today's Progress:** SoC Week 1 - Day 2: 

**Reflections:** TBC

**Link(s) to work:**


