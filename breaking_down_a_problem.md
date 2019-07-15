
Describe the problem to yourself in natural language first.
"It doesn't work" does not work as a problem statement.
"It's not working" is for relationship talk.

"I'm trying to ABC. I understand A and B, but I'm missing something. Can you see what I missed?"
"I'm trying to do XYZ but the documentation doesn't make sense and I've checked other tutorials and I'm still missing something, can you help me read the docs for this?"

Describe the solution in natural language (to person).

Translate your solution's sequence of steps into a programming language. 

If you say "if" when describing how your sequence of steps will solve the problem, then you're gonna have an if statement


For problem solving, try this:
- be lazy (can you identify the lowest hanging fruit)


"If you can't solve a problem, then there is an easier problem you can solve: find it." - Polya


----

Let's say the problem is "How to do the weather map?"

1st thing to do is to ask, "How best should I *start* the weather map"

1st breaking down:
- do you start with the weather OR the map?
- Can only do one thing at a time.

While we begin with the end in mind, it's important to determine the first thing to do.

Approach it like a story with a beginning, middle, and end.

Do both:
- Imagine your software development lifecycle as a story with a beginning, middle, and end.

- Imagine your final application as a story with a beginning, a middle, and an end.



In the beginning, the page loads:
    - What should it show?
    - What can people SEE on first page load?
    - What can visitors DO 
    - Start w/ Codeup address on the map? or Do you show a button that says "get started"
    - What's the starting zoom level...
    - Do we start showing the forecast for 3 days? Or another number? 
    - Do we start showing 3 days and show a drop down to increase the number of days?

In the middle, 
    - What can they see?
    - What can visitors DO?
    - Let's say we know we want to get to a click/drag the location pin...
    - If that's a mouthdful or too much to break down..
    - Then, make a text input where we can input the address... BUT, what if that's too much
    - Well, break off a small problem? Make a text input for latitude and another for longitude.
    - Assume we'll figure out the text box thing, but solve a smaller problem now... Hard code a second lat/long and run it from the connsole or on an event listener when you click a button.

    - Optimistic LazyThinking (assume you CAN solve the hard problem, but in reality, start by blowing it off and focusing on the smallest, easiest thing you CAN do)

In the end,
    What's the final state where it's good enough?
    Great software is never finished.
    Are we done when we get the geocoder working?
