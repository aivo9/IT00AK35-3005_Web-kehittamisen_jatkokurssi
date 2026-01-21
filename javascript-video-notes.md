# Microsoft Learn | Beginner's Series to: JavaScript | Video Notes

**This material has been translated and spelling improved using artificial intelligence. The use of AI in the task and original notes can be viewed behind this link:**

[Markdown Translation Request](https://chatgpt.com/share/69710df0-88a0-8012-870e-bce717da0d35)

**Beginning the Beginner's Series [1 of 51]**

- The creators of the video series introduced themselves.
- Jean has a super annoying, ear-raping, strong French accent.

**What Is JavaScript [2 of 51]**

- JavaScript is dynamically typed and JIT-compiled.
- According to a Stack Overflow survey in 2010, JavaScript was the most used programming language in the world.

**Running JavaScript: Browser or Server [3 of 51]**

- JavaScript is used both on the client side (usually in a web browser) and on the server side.
- To run JavaScript on the server, you’re going to need Node.js.

**Building Your Toolbox [4 of 51]**

- Oh no, Jean is here. He says you should first set up your toolbox, e.g. an IDE like Visual Studio Code and extensions such as ESLint & Prettier.
- He also advises installing Node.js via NVM.

**Demo: Building Your Toolbox [5 of 51]**

- First, Jean explains how to install VS Code and Node.js.
- Jean strongly recommends setting up Node.js via NVM. And his voice is still horrible.

**Creating Your First Application [6 of 51]**

- With the `console.log()` command you can also print emojis!
- Variables are placed inside the `${}` syntax.

**Comments [7 of 51]**

- `//` comments out a single line
- `/* ... */` comments out multiple lines

**Demo: Comments [8 of 51]**

- It’s smart to use something like the string `"TODO:"` in comments, so you can easily find unfinished work later using search.
- Ctrl + / comments out an entire line (or block).

**Declaring Variables [9 of 51]**

- Three ways to declare variables: `var`, `let`, and `const`
- `var` works throughout the entire function and even before declaration, `let` only works inside a block and only on lines after it’s declared, and `const` is like `let` but cannot be reassigned.

**Demo: Declaring Variables [10 of 51]**

- In this video, Aaron shows how declaring and assigning variables works in practice.
- Aaron’s last name is Powell!

**Working with Strings [11 of 51]**

- Strings are concatenated using the `+` operator.
- At this point I noticed that JavaScript’s syntax resembles C# quite a lot.

**Demo: Working with Strings [12 of 51]**

- In this video, the lady shows in the IDE how things work in practice.
- Remember to be careful with numbers!

**Using Template Literals to Format Strings [13 of 51]**

- This teaches the syntax for using variables.
- `${variable}` can be used inside a string.

**Demo: Using Template Literals to Format Strings [14 of 51]**

- Pretty much the same as the previous video, going over how to use variables inside strings.
- `!` gives the opposite value, e.g. `!true = false`.

**Data Types in JavaScript [15 of 51]**

- A bit simpler type system than in C#.
- Variable types can be changed.

**Demo: Data Types in JavaScript [16 of 51]**

- Sometimes variable types can be hard to determine.
- To check them, you can use `typeof` and `instanceof`.

**Math in JavaScript [17 of 51]**

- This video covered mathematical operators.
- For more complex calculations, there is the `Math` object.

**Demo: Math in JavaScript [18 of 51]**

- This was a demo video showing outputs in the console.
- Very similar approach to math as in C#.

**Converting Strings to Numbers [19 of 51]**

- The video went through how to convert strings to ints and floats, and vice versa.
- JavaScript can interpret hexadecimal values as numbers!

**Demo: Converting Strings to Numbers [20 of 51]**

- The video demonstrates with console output how converting works in practice.
- If you try to convert characters (e.g. `ABC`), the output will be `NaN` = Not a Number.

**Handling Errors with try/catch/finally [21 of 51]**

- This video covers errors and how to deal with them.
- `try`, `catch`, and `finally` are used to handle these errors.

**Demo: Handling Errors with try/catch/finally [22 of 51]**

- In this video, the lady shows in practice how `try`, `catch`, and `finally` work.
- This didn’t fully click for me while tired at 11 PM—need to revisit this with fresher brains.

**Dates [23 of 51]**

- Time, i.e. `Date`, is an object and contains both date and time.
- In JavaScript, time is stored as milliseconds since January 1st, 1970.

**Demo: Dates [24 of 51]**

- Windows 95 was released on August 24th, 1995.
- JavaScript always uses UTC+0.

**Boolean Logic with if Statements [25 of 51]**

- Double equals checks for equality: `'1' == 1` | `true`
- Triple equals also checks type: `'1' === 1` | `false`

**Demo: Boolean Logic with if Statements [26 of 51]**

- In my opinion, these videos could be combined. You end up watching essentially the same thing twice: first theory with still images, then the same examples again in the IDE.
- `if`, `else`, and `else if` can also be written without curly braces as long as the whole statement is on one line.

**Boolean Logic with switch and Other Syntax [27 of 51]**

- When using booleans, strings are case-sensitive.
- De facto best practice: always use `&&` and `||`.

**Demo: Boolean Logic with switch and Other Syntax [28 of 51]**

- `switch` and `case` with `break`s are a handy alternative to `if-else`.
- `switch` only checks for equality!

**Creating Arrays [29 of 51]**

- Basic stuff about arrays.
- There was no person visible in the video.

**Demo: Creating Arrays [30 of 51]**

- A demo video in the IDE about the same basic stuff.
- Arrays can be created either empty or with a predefined length.

**Populating Arrays [31 of 51]**

- Arrays can be populated when created or filled afterward.
- An array can contain multiple different data types.

**Demo: Populating Arrays [32 of 51]**

- Arrays work in practice pretty much the same as in other programming languages.
- The last index of an array is always `Array.length - 1`.

**Array Methods [33 of 51]**

- Now we got some new things about arrays!
- `push`, `pop`, `shift`, `unshift`, and `concat` are made for working with arrays.

**Demo: Array Methods [34 of 51]**

- These demo videos genuinely annoy me, because there’s rarely anything new. They almost always repeat exactly what was already explained in the previous video.
- There’s really nothing new to say about them. This time a dark-skinned lady was speaking, but she wasn’t visible. The file being edited was named `array_methods.js`. Outside it was −7°C and partly cloudy. I had sushi for lunch. On line 8 of the file it says `console.log(arr1);`

**Loops [35 of 51]**

- And then come the loops. A 7-minute video, wow! `while`, `for`, and `for...of`.
- These work pretty much the same as in most other programming languages. At the end there was a nice visual showing which loop to use in which situation.

**Demo: Loops [36 of 51]**

- Nice username & server combo: geektrainer@geektrainer.
- I think the video lacks diversity when the example names are Justin, Burke, and Sarah. Why not Carlos, Mohammad, and Li…? Just kidding—I couldn’t care less. Same stuff again. One actually useful thing (that wasn’t in the previous video!): even though a `const` variable normally can’t be reassigned, in a `for...of` loop it can change value within the loop.

**Functions [37 of 51]**

- Functions are handy when you need to repeat the same operation in code multiple times.
- Function names may contain only letters, numbers, the dollar sign, and underscore—other characters are a no-no.

**Demo: Functions [38 of 51]**

- It’s not enough to define a function; to use it, you also have to call it (isn’t that kind of obvious?).
- JavaScript seems smart in that if you provide more parameters than a function expects, it just ignores the extras.
- I haven’t left a single angry comment, but sometimes these videos are so dull that I conclude the bald guy is the best teacher out of all of them!

**Arrow and Anonymous Functions [39 of 51]**

- `=>`, the fat arrow function, is new! And it’s handy for simple operations.
- If you need multiple lines, you still need curly braces as usual.

**Demo: Arrow and Anonymous Functions [40 of 51]**

- I see no practical benefit to using fat arrows in multi-line expressions. Isn’t the whole point to fit everything on one line?
- That guy chose the wrong cap for the demo—it’s the same color as the background, and his head disappears whenever he lifts it. (I write these silly comments and details when I can’t think of anything relevant to say, just so you know I actually watched the videos and internalized the content, even if I can’t come up with anything meaningful to comment on.)

**JavaScript Object Notation (JSON) [41 of 51]**

- JSON is an easy way to store data on a server.
- I didn’t quite understand how this works in practice on the first watch—the curly-haired lady’s teaching materials could use some polishing—but finally the demo video is actually useful!

**Demo: JavaScript Object Notation (JSON) [42 of 51]**

- Now JSON and its purpose finally clicked. It’s a way to communicate with APIs and convert JavaScript data into pure strings so it can be sent to a server.
- `stringify` “packs” the data into a string, and `parse` unpacks it back into objects (or even an array of objects).

**Objects in JavaScript [43 of 51]**

- Objects can be created by defining properties and methods right away, or by creating an empty object with a constructor and adding properties and methods afterward.
- You can access object properties using either `object.example` or `object["example"]` notation. Methods are accessed the same way—add `()` to invoke them.

**Demo: Objects in JavaScript [44 of 51]**

- Long video—fortunately only a few left. The beginning demonstrated objects nicely.
- The `this` concept is hard for me. It didn’t fully click, and it’s been a while since my C# courses. I’ll need to study this more once I’ve finished these videos and submitted the assignments.

**Promises for Long-Running Operations [45 of 51]**

- These concepts get harder toward the end. Or maybe I’m just tired. I get the idea of Promises, but not quite their practical use. The demo video will help.
- That bald guy really is the best teacher, by the way—did I already mention that?

**Demo: Promises for Long-Running Operations [46 of 51]**

- I understand the idea, but not fully the logic behind it. This is another concept that needs proper time and study.
- Basically, promises exist so we can schedule code execution while waiting for a response from elsewhere.

**Async/await for Managing Promises [47 of 51]**

- `async`/`await` clarified the idea of waiting for responses even more, but the logic still isn’t entirely clear.
- Since this is essential in almost all modern web development, it’s something I must learn properly.

**Package Management [49 of 51]**

- Damn it, Jean again! Jean explains packages and where to get them. NPM is powerful.
- `package.json` contains all the project’s packages and metadata. `npm init` creates the file, and after that you just install packages with `npm install`.

**Demo: Package Management [50 of 51]**

- Jean admitted he’s lazy. But he explains the purpose of `package.json` really well.
- Finally got a practical example for `.gitignore` too.

**Next Steps [51 of 51]**

- Woohoo, the last video!
- This series was an excellent beginner’s package. It covered all the basic programming concepts quite thoroughly, and it’s a great starting point.
