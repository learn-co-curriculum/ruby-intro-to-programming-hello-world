# Introduction to Intro to Programming

## Learning Goals

* Create a new Ruby file from scratch
* Write syntactically valid code to produce "Hello World!"
* Run a Ruby file
* Run the Learn gem
* Submit a Learn lab

## Introduction

Let's make a file that will print ["Hello World!"](http://en.wikipedia.org/wiki/%22Hello,_World!%22_program) to your terminal.

![Hello World! Art](https://d32dm0rphc51dk.cloudfront.net/b6JQ66-0nHij79irJT-Pdg/large.jpg)

Hello World is based on a 1974 Bell Laboratories internal memorandum by
Brian Kernighan called Programming in C: A Tutorial, which contains the
first known version of this program. 

## Create a new Ruby file from scratch

We will need to create a text file called `hello_world.rb` within the lab's
directory. The `.rb` file extension is a common convention for specifying
the language of the file--in this case, Ruby. To create this, in the Learn
IDE's terminal type `touch hello_world.rb` or use the "Create New" or
"New File" option in the Editor. If that worked as expected, you should now
see the file appear in the file browser. You can open this file by double
clicking on it in the file browser. You should now see an empty file open
in your text editor, ready to be edited. 

## Write syntactically valid code to produce "Hello World!"

In the file `hello_world.rb` that you created, you will need to write a single
line of code that prints the `String` "Hello World!" to your terminal. To print
in Ruby, you use the method `puts`, which is short for "out**put s**tring." Since
"Hello World!" is a string, you need to surround your text with `""`.

File: `hello_world.rb`
```ruby
puts "Hello World!"
```

Anytime you make changes to a file (like the one you've just made) you need to
save the file, so your changes are preserved. If you forget to save the file
before you run your tests, the last saved version of the file will be run--without
your changes--and this can be very confusing! In this case, if you forget to save,
what gets run might be just an empty document. That won't do anything very exciting.
Always remember to save the file every time you make changes by selecting `Save`
from the `File` menu.

## Run a Ruby file

Execute this file by typing `ruby hello_world.rb` into your terminal and pressing
`enter`/`return`. The `ruby` part of that command tells your computer to use the
Ruby interpreter when reading and executing the code in your file. The second part
of the command, `hello_world.rb` is the path to the file you want to run.

**Note:** be sure to save your file before trying to run the file, otherwise it
will not work.

You should see:

```bash
$ ruby hello_world.rb
Hello World!
```

## Run the Learn Gem

Confirm everything is working by running the `learn` command. You should see that
all tests are passing (e.g. no red error text).

**Note:** When you write code, the case (uppercase/lowercase) of characters matters,
and so your test will not pass unless you print "Hello World!" exactly.

## Submit a Learn Lab

Submit your solution by typing `learn submit` into your terminal, then click "Next
Lesson" to move forward.

## Conclusion

Your adventure in Ruby has only just begun!

## Resources

[Hello World! by Brian Kernighan, from Artsy's Algorythm Auction](https://www.artsy.net/artwork/brian-kernighan-hello-world) 
