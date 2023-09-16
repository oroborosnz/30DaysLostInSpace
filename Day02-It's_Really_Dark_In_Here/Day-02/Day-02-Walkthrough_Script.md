
# Day 2 code walkthrough

## ChatGPT prompt used to modify existing script

Here are five numbered lists of paragraphs for a code walkthrough.  Please edit the language to be suitable for an audience as young as 5th or 6th grade and then convert each list into a GitHub Markdown formatted table.  Each table should have three columns labeled "Paragraph", "Script" and "Notes".  Place the list number in column 1, the text into column 2 and leave column 3 blank.

Sure, here are the edited paragraphs for a younger audience and converted into GitHub Markdown formatted tables:

## Section 1

| Paragraph | Script | Notes |
|-----------|--------|-------|
| 1 | One of the most important things that accelerates your code learning... is taking notes. | Show sketch with line 1 at the top.|
| 2 | You can make comments inside your sketch. Take this one. It's a lot like Blink, with an extra light, but... I made a few notes to help me remember what does which.  | |
| 3 | Comments come in two flavors, but let's just talk about long comments. A long comment starts with this combo. | Highlight /* on first line.|
| 4 | Slash-Asterisk tells the compiler to ignore whatever comes next, until it hits the end-comment marker: Asterisk-Slash. | Highlight ending */ sequence. |
| 5 | It's a good idea to put these start and end symbols on different lines: helps make the code easier to read. | |
| 6 | THESE asterisks aren't needed, but again, it helps with readability. | Highlight column of asterisks between start and end symbols.|
| 7 | Oh hey, see this "down pointer"?. That's a collapser. Works great for long comments, AND blocks of code. | Show how to collapse comment block by clicking after line number. |
| 8 | This tells you there is hidden text. Click to show again. Isn't that cool? | Highlight "..." at end of remaining line then re-expand.|
| 9 | Comments are for people. They don't go to the board, but they hold important 'behind the scenes' info for when you start writing the sequel. | Collapse first comment. |


## Section 2

| Paragraph | Script | Notes |
|-----------|--------|-------|
| 1 | Now, here's a coding secret - programmers don't usually write all their code from the start. Instead, we use pieces of code created by other programmers and add them to our sketches using special lines called compiler directives. These lines start with a hashtag (#) and make it easy to bring in lots of code from other files without having to copy and paste. | |
| 2 | It's important to note that the Arduino IDE automatically adds the "Arduino.h" file for us. Including this file ourselves not only makes it work with other IDEs but also reminds us of this important step, so it's a good idea to do it in all your sketches. | |
| 3 | Using included files is more than just bringing pieces together, it also automatically updates the files, making sure your sketch always uses the newest version without you having to do anything. | |
| 4 | Plus, it lets you choose specific versions based on how your folders are organized, which helps the Arduino IDE select the right board and version easily. | |
| 5 | Remember the "LED_BUILTIN" from the first Blink sketch? Its pin changes depending on the board. This smart feature comes from choosing the right "Arduino.h" file, making sure it works with all boards. | |

## Section 3

| Paragraph | Script | Notes |
|-----------|--------|-------|
| 1 | After we hide the last comment, we find the biggest comment section in this sketch. | |
| 2 | Just like the "LED_BUILTIN" feature, the Arduino IDE lets us give names to constants, which are values that don't change while the sketch is running. | |
| 3 | Using constants is very handy, as explained in this big comment section. To sum it up, it makes coding simpler and avoids mistakes. There are two main ways to declare constants: using #define directive or the "const" variable declaration. | |
| 4 | Even though many people use #define, choosing the const declaration can avoid problems and make fixing errors easier. | |
| 5 | Both methods let us use both upper and lower case letters for names, but usually, we use UPPER CASE for constants so we can tell them apart from variable names which might change during the program. | |
| 6 | In this sketch, we name a constant that controls the cabin lights on our HERO board. Since it's outside the board, we'll choose pin 12 for this, giving it the name "CABIN_LIGHTS_PIN" with a value of 12. | |
| 7 | Using the "const" keyword lets us choose the kind of data it is. "uint8_t" is a type of data that is good for small values like 12. This choice saves memory space because it only uses a small amount of memory. | |
| 8 | The next sections will explain more about constants, helping you understand this important part of programming better. | |

## Section 4

| Paragraph | Script | Notes |
|-----------|--------|-------|
| 1 | As we get ready to run our first advanced sketch, it's important to know about the first steps or "setup" that every Arduino sketch needs. The `setup()` function, like its name suggests, prepares everything we need to run our sketch successfully. | |
| 2 | Inside the `setup()` function, we find the `pinMode` function, a helpful tool that lets us decide what each pin on the Arduino does. Today, we'll use it to make the `CABIN_LIGHTS_PIN` an OUTPUT. | |
| 3 | Understanding `pinMode` is a key step to working with real objects connected to the Arduino, like lights, motors, and sensors. | |
| 4 | Next, we find the `digitalWrite` function, used here to turn the cabin lights off at the start of the sketch. | |
| 5 | This prepares us for the next part of our sketch, where the real fun begins. Before we move on, think about how these functions set the stage for the exciting actions we are about to code. | |

## Section 5

| Paragraph | Script | Notes |
|-----------|--------|-------|
| 1 | Now that we've set everything up, it's time to dive into the `loop()` function, where all the exciting actions are coded in our Arduino sketch. | |
| 2 | The `loop()` function has codes that keep running over and over, letting us continuously interact with the things connected to it. | |
| 3 | The first line inside the `loop()` function uses the `digitalWrite` function to turn the cabin lights on, showing how one function can do different things in a sketch. | |
| 4 | Then, we use the `delay` function to pause for a certain amount of time, creating a visible pause before the next code line runs, giving a little break between turning the light on and off. | |
| 5 | After the pause, we use the `digitalWrite` function again to turn the cabin lights off, showing a simple but cool example of automation. | |
| 6 | We add another pause before the loop starts again, making the cabin lights flash in a rhythmic pattern. | |
| 7 | This cycle shows the magic of automation, demonstrating how a few lines of code can control real objects, making our HERO board light up in a dancing pattern of lights. | |
| 8 | As we end today's lesson, try changing the delay values to see how it changes the rhythm of the lights, helping you learn how code changes affect the real world. | |
| 9 | We hope you try different things and make this sketch your own. Remember, learning to be a great programmer is all about experimenting and learning from what happens. | |
