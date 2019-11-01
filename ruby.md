# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer: Both Ruby and Javascript are object oriented scripting languages. They both have conditional syntax that can be used to create logic. 
               They both have higher order functions like .map that can be used to iterate through data. 
               
               They are different in that Ruby is mainly for backend while javascript is used more for front end. Ruby is used more to look into databases and get information
               from it, while javascript is more for creating logic for the user to interact with. 

  Researched answer:



2. What is a hash?

  Your answer: A hash is a collection of data that is made up of key value pairs 

  Researched answer:A Hash is a collection of key-value pairs like this: "employee" = > "salary". It is similar to an Array, except that indexing
                    is done via arbitrary keys of any object type, not an integer index.



3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer: Rspec. You must connect rspec to your file with require 'rspec' and then require_relative '...'(name of the ruby file you are testing..also within same folder)
               
  Researched answer:



4. Name three possible relationships between objects?

  Your answer: has_many,  belongs_to 

  Researched answer: has_many,  belongs_to, has_many_through



5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer: instance variables have greater scope 

  Researched answer: A normal variable has scope only within the current context; an instance variable has scope throughout one instance of a class.



6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) greeter.respond_to?("say_hi").. you can use the responds_to method to check if your class has a certain method 

2) if __FILE__ == $0 . This check says “If this is the main file being used…” This allows a file to be used as a library,
                      and not to execute code in that context, but if the file is being used as an executable, then execute that code.

3) mpopulation = 12_000_000_000 .. cant use commas in numbers so underscores work if trying to make more readable 


7. Stretch: What are blocks, procs, and lambdas?

  Your answer: blocks are snippets of code that can be used later when they are either passed to a method or just used to display something. 
               procs are instances of the Proc class which are used to hold code for when it is to be used later. These procs are often held in the variables 
               lambdas

  Researched answer: Lambdas are procs that behave like methods, meaning they enforce arity and return as methods instead of in their parent scope.
