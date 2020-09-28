---
layout: post
title:      "**Loop-de-Loops**"
date:       2020-09-28 00:59:17 +0000
permalink:  loop-de-loops
---


*Loops...endless loops*, don't get stuck in one that's for sure! Make sure to **ALWAYS** end your loops and your terminal will thank you. 

**What is a loop?** Well let me think about this for a moment, so I guess the easiest way for me to describe a loop is by saying that they are a structure in Ruby that allows you to easily repeat a section of code a number of times, putting everything into one loop makes changing a small feature about each line you repeat very easy **AND** it abides to the "**D**on't **R**epeat **Y**ourself" priniciple of programming!

**Things to remember:**

Loop statements usually have *four* components: initialization (*usually of a loop control variable*), continuation test on whether to do another iteration, an update step, and a loop body.

Ruby comes with several statements and methods for looping, such as 'loop', 'each', 'for', 'while', 'until', 'times', 'step' and many others. 

*****IMPORTANT*****
ALL LOOPS NEED TO END!!! MAKE SURE TO END NOT ONLY THE METHOD BUT ALSO THE LOOP ITSELF...*OTHERWISE PREPARE FOR A VERY FRAZZLED TERMINAL*!!

An important componate of loops are block's. A block is a bunch of code that you pass into a method. To execute that code, stored blocks have a 'call' instance method that you can use to call on them. The 'call' method invokes the block's code.

Ok I'm sure you're looking at what that says like "HUH?" but I assure you it won't be hard to understand once you start working with loops, but to help you understand a little bit better I'll show you an example. 

 EXAMPLE:
        
				method_name(*a block must always follow a call method*) do(*start of the block*)
				      puts "We made a block!"(*block body*)
				end(*end of block*)
				
TA-DA!!! See that isn't so hard to understand!


So let's see, we talked about block's, loops...hmm I think we are missing something...Oh! Perhaps you would like to see an example of using loops in code? Sure!

EXAMPLE:

          *Using 'loop' command*
					
					loop do
					   puts "loop-de-loop"
					end
					
					*Using 'times' command*
					
					3.times do |i|
					   puts "#{i}"
					end
					
					
					
There! Now you have an idea of how to use loops when coding in Ruby! So now go forth my little looper and repeat whatever you want to your hearts content but be sure to **END YOUR LOOPS!!!!**

Thanks for reading!☺️
