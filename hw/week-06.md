# Week 6

The evening trainings and readings below will help you solidify work so far and/or prepare you for the next day's materials.


### Tuesday

**link to submit on Tuesday's pulse check: Angular weekend project GitHub**

1. Work through [Try Ruby](http://tryruby.org/levels/1/challenges/0), an interactive introduction to Ruby. The whole tutorial is very useful, but at least do levels 1-4.  _Note: despite what the site says, this will take longer than 15 minutes! Plan to spend at least 30  minutes on this._
 
1. Work through this [arrays, hashes, and blocks](https://github.com/sf-wdi-34/ruby-arrays-hashes) guide. Don't just read it; try the code out in PRY. 

1. Read over [Ruby methods](https://github.com/sf-wdi-34/ruby-methods) notes for tomorrow, and try the code samples in PRY. (Save these exercises for tomorrow - you can try some challenges on [codewars](https://www.codewars.com/?language=ruby) if you'd like.)

1. Take about fifteen minutes (total) skimming through the following 3 free books on Ruby. Spend a little time really reading the table of contents (if there is one) and seeing what piques your interest. 

 - http://poignant.guide/book/chapter-1.html
 - http://humblelittlerubybook.com/book/html/index.html
 - http://ruby-doc.com/docs/ProgrammingRuby/
 
 Choose at least one of these books to read more of, and spend at least 30 minutes reading it and making notes.  Skip ahead to the topics that interested you most based on what you remember from JavaScript. You can always go back to previous chapters later!

 > Another great but non-free book is Practical Object Oriented Design (POODR) by Sandi Metz.  For starting out Ruby, you could focus on chapters 1-3.

1. Use any extra time to go farther with the resources above or check out other resources. One possibility is 
[codewars' Ruby language challenges](https://www.codewars.com/?language=ruby).




### Wednesday

**link to submit on Wednesday's pulse check:** a direct link to part of one of the Ruby ebooks that you found interesting. 

1. Do this [OOP reading](https://github.com/sf-wdi-34/ruby-oop-reading), up to but not including the Inheritance section. Write down answers to each of the [reflection questions](https://github.com/sf-wdi-34/ruby-oop-reading#reflection-questions) at the bottom of the readme, and **bring your answers in with you tomorrow.**  Tips:
  * If you just read through this, you're not getting the full benefit!  Instead, create a Ruby file to follow along with the code examples and run it every step or two with `ruby your_file_name.rb`.  
  * Try things out! Would it break if I do `car[color]`?  
  * If you're not feeling cars, create an entirely different class following the same examples (plants? phones? baseball players?)!  **Following along in code is a great strategy for reading docs on unfamiliar topics!**  
  * If you want to split this longer reading up a little, good break points are before "Inheritance" and before "Modules".
  

2. Finish at least the <b>first 3 methods in each of the exercises</b> of the [ruby method drills](https://github.com/sf-wdi-34/ruby_method_drills). Optionally, you can challenge yourself to take on more of these drills tongiht.  Continue working through these drills when you have time this week. 

### Thursday

**link to submit on Thursday's pulse check:** your ruby method drills repository

1. Read through the [solution code](https://github.com/sf-wdi-34/go-fish-card-game/blob/master/solution/go_fish.rb) from this afternoon's go fish training. Also, run the code! Write down two questions and one thing you learned from the solution. 

1. Read through the [test code](https://github.com/sf-wdi-34/go-fish-card-game/tree/master/spec) from this afternoon's go fish training. Using that example,  some [documentation for the basic structure of an rspec test](https://www.relishapp.com/rspec/rspec-core/v/3-5/docs/example-groups/basic-structure-describe-it), and the structure of [expectations](http://www.relishapp.com/rspec/rspec-expectations/docs), come up with basic explanations for the following Rspec methods:  `describe`, `context`, `it`, `expect`.  This should take about 30 minutes. 

1. Choose an item you are familiar with - like a jacket, backpack, table, etc.  Pseudocode tests for a Ruby class based on that object. Write down 5 "expect" lines for the object (or 8 if you chose a backpack). This should take about 10-20 minutes. An example might be:

 ```
 describe Backpack
    it starts new backpacks with an empty list of contents
      - expect a new backpack instance to have an empty array for contents
    it has a color that doesn't change
      - expect to be able to get the color
      - expect not to be able to set the color
 ```
 


<!--

### Weekend

-->
