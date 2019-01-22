RubyTutorial
============

Ruby is a powerful, flexible programming language you can use in web/Internet development, to process text, to create games, and as part of the popular Ruby on Rails web framework. 

1. It is a High-level meaning reading and writing Ruby is really easy—it looks a lot like regular English!
2. Interpreted- meaning you don't need a compiler to write and run Ruby.
3. Object-oriented- meaning it allows users to manipulate data structures called objects in order to build and execute programs.
4. Easy to use- Ruby was designed by Yukihiro Matsumoto (often just called "Matz") in 1995. Matz set out to design a language that emphasized human needs over those of the computer, which is why Ruby is so easy to pick up.

# Data Types: Numbers, Strings, Booleans

In Ruby, data can come in different types. There are three data types in Ruby that we're interested in right now: numbers, booleans, and strings.
It's also important to remember that Ruby is case-sensitive (it cares about capitalization).

## Variables
num = 25

Declaring variables in Ruby is easy: you just write out a name like num, use = to assign it a value, and you're done! If you need to change a variable, no sweat: just type it again and hit = to assign it a new value.

## 'puts' and 'print'
The print command just takes whatever you give it and prints it to the screen. 
puts (for "put string") is slightly different: it adds a new (blank) line after the thing you want it to print. 

Example:
puts "What's up?"
print "Oxnard Montalvo"

No parentheses or semicolons needed!

# Everything in Ruby is an Object
Because everything in Ruby is an object, everything in Ruby has certain built-in abilities called methods. 

We can think of methods as "skills" that certain objects have. For instance, strings (words or phrases) have built-in methods that can tell you the length of the string, reverse the string, and more.

# Interpreter

1. The interpreter is the program that takes the code we write and runs it. 
2. We type code in the editor, the interpreter reads our code, and it shows the result of running our code in the console.


## The '.length' Method

Methods are summoned using a .(dot) . 

If we have a string, "I love espresso", and take the .length of it, Ruby will return the length of the string (that is, the number of characters—letters, numbers, spaces, and symbols).

"I love espresso".length = This will output 15 

## The '.reverse' Method

The .reverse method is called the same way .length is, but instead of asking Ruby to tell you how long a string is, it spits out a backwards version of the string you gave it. 

For instance,

"Eric".reverse = will result in "cirE"

Reversing input can be useful if you want to sort a list of values from highest to lowest instead of lowest to highest. 

## '.upcase' & '.downcase'

The .upcase and .downcase methods convert a string to ALL UPPER CASE or all lower case, respectively.

Call .upcase on your name to make your name ALL CAPS and use puts to print it to the screen, like this:

puts "praveen".upcase outputs "PRAVEEN"

puts "PRAVEEN".downcase outputs "praveen"

## Multi-Line Comments

=begin
I'm a comment!
I don't need any # symbols.
=end

## Ruby multiple methods

name = "PRAVEEN"

name.downcase.reverse.upcase => "NEEVARP"

"name.downcase.reverse.upcase" method will first change name to lowercase, then reverse it and finally prints its uppercase.
