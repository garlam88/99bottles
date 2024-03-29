# 99 Bottles

## Task

Change instances of "6 bottles" to "1 six-pack" without violating the
Open/Closed Principle.

## Installing Ruby

### Windows

There's an installer, it's easy.
http://rubyinstaller.org/

### Mac

Newer macs ship with a usable version of Ruby.

Try `ruby -v` in a terminal window, and if it's 1.9.x or 2.x you're fine.

http://www.railstutorial.org/book/beginning#sec-install_ruby
http://tutorials.jumpstartlab.com/topics/environment/environment.html
http://docs.railsbridge.org/installfest/macintosh

### Linux

Ubuntu: http://docs.railsbridge.org/installfest/linux
https://www.ruby-lang.org/en/installation/

## Running the Tests

To run the tests, you will need the minitest gem. Open a terminal window,
and run the following command in the exercise directory:

    bundle install

You can run the tests from the exercise directory. Execute the
following command:

    ruby test/bottles_test.rb
