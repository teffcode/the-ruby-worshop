# 💎 The Ruby Workshop
<img src="./assets/banner.gif" alt="banner" width="100%"/>

> * **Book:** The Ruby Workshop
> * **Authors:** Akshat Paul, Peter Philips, Dániel Szabó, Cheyne Wallace
> * **Link:** https://s3.amazonaws.com/thinkific-import-development/59347/B14197_RubyWorkshop_eBook-200128-104214.pdf

## Table of Contents

1. [Chapter 1: **Writing and Running Ruby Programs**](#chapter-1-writing-and-running-ruby-programs)
2. [Chapter 2: **Ruby Data Types and Operations**](#chapter-2-ruby-data-types-and-operations)
3. [Chapter 3: **Program Flow**](#chapter-3-program-flow)
4. [Chapter 4: **Ruby Methods**](#chapter-4-ruby-methods)
5. [Chapter 5: **Object-Oriented programming with Ruby**](#chapter-5-object-oriented-programming-with-ruby)

## Chapter 1: **Writing and Running Ruby Programs**
[👆🏼 Go to Table of Contents](#table-of-contents)

### 🍏 1. What is a common purpose of a guard clause ?

* a) Exit a method immediately if an invalid parameter was passed in.
* b) Send an email if an unusual parameter is passed in.
* c) Massage parameters into expected values.
* d) Verify that the method is allowed to be called.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > A variable can change from one type to another, and you're only ever really concerned if an object responds to a given method.
</details>

### 🍏 2. What phrase represents the idea that we don't care what type an object is – only if it responds to a given method or not ?

* a) Goose Typing
* b) Duck Typing
* c) Loose Typing
* d) Static Typing

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > "If it quacks like a duck...".
</details>

### 🍏 3. What are the elemental building blocks of all Ruby programs ?

* a) Blocks
* b) Procs
* c) Lambdas
* d) Objects

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > Everything we create or interact with in Ruby is an object.
</details>

### 🍏 4. Which best describes how Ruby code is executed ?

* a) Interpreted
* b) Compiled
* c) JVM
* d) By hand

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > Ruby is interpreted on the fly when it's executed.
</details>

### 🍏 5. What does metaprogramming mean ?

* a) Talking about code
* b) Writing code that creates code
* c) Programming literature
* d) Metaphysical code

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > Metaprogramming helps to keep your code DRY and elegant.
</details>

### 🍏 6. Ruby is primarily what sort of programming language ?

* a) Procedural
* b) Object-oriented
* c) Static
* d) Functional

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > Anything in Ruby is an object.
</details>

### 🍏 7. What is the result of the code: `4.class` ?

* a) NoMethodError
* b) Integer
* c) String
* d) Class

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > 4 is the integer class.
</details>

### 🍏 8. Which code snippet would prompt for user input using Ruby ?

* a) prompt
* b) ask
* c) request
* d) gets

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > This will prompt the user for input in the terminal.
</details>

### 🍏 9. What method strips a trailing line break from a string ? For example, called on `"4\n"` would return `"4"`.

* a) chomp
* b) sanitize
* c) stripize
* d) remove_line_break

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > `chomp` or `strip` would both work.
</details>

### 🍏 10. How do we round `"3.14"` up ?

* a) 3.14.round
* b) 3.14.ceil
* c) 3.14.floor
* d) 3.14.up

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > `ceil` rounds the number up.
</details>

### 🍏 11. How can we get a list of all the methods that instances of Float respond to ?

* a) 3.14.methods
* b) Float.methods
* c) Float.public_methods
* d) 3.methods

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > This will return an array of method names that instances of Float respond to.
</details>

### 🍏 12. After running the following code, what is the value of the `food` variable ?

```
food = 'pudding'
food.upcase
```

* a) "pudding"
* b) "PUDDING"
* c) "nil"
* d) "Pudding"

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > String#upcase yields a new instance of the string that is all capitalized but does not modify the existing string.
</details>

### 🍏 13. After running the following code, what is the value of the `food` variable ?

```
food = 'pudding'
food.capitalize!
```

* a) "pudding"
* b) "PUDDING"
* c) "nil"
* d) "Pudding"

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > String#capitalize! capitalizes the first letter in place.
</details>

### 🍏 14. What does the following code return?

```
"Chocolate pudding is delicious; chocolate is my favorite.".gsub('chocolate', 'vanilla')
```

* a) "Chocolate pudding is delicious; vanilla is my favorite."
* b) "Chocolate pudding is delicious; chocolate is my favorite."
* c) "Chocolate pudding is delicious; Chocolate is my favorite."
* d) "Chocolate pudding is delicious; Vainilla is my favorite."

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > gsub replaces "chocolate" with "vanilla".
</details>

### 🍏 15. What does the following code return ?

```
"Apples,Oranges,Melons".split(',')
```

* a) `"Apples","Oranges","Melons"`
* b) `"Apples", "Oranges", "Melons"`
* c) `["Melons", "Oranges", "Apples"]`
* d) `["Apples", "Oranges", "Melons"]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > String#split splits a string by the specified delimiter and returns an array of the parts, but it preserves the order.
</details>

### 🍏 16. What code snippet would return `"one two three"` ?

* a) `["one", "two", "three"].join("")`
* b) `["one", "two", "three"].join(" ")`
* c) `["one", "two", "three"]`
* d) `["One", "Two", "Three"]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > Array#join will join the elements of the array using the specified delimiter, which is not specified here, so the result would be "onetwothree".
</details>

### 🍏 17. If we had a variable `one` assigned `"Hello"`, and a variable `two` assigned `"world"`, which code snippet would return `"Hello world"` ?

* a) `[one, two].join`
* b) "#{one}#{two}"
* c) "one two"
* d) "#{one} #{two}"

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > This interpolates the strings with a space in between.
</details>

### 🍏 18. What does IRB stand for ?

* a) Iteractive Ruby Scheduler
* b) Interpretive Ruby Shell
* c) Interactive Ruby Shell
* d) Interactive Ruby Scheduler

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > IRB stands for Interactive Ruby Shell.
</details>

### 🍏 19. Which code snippet would print `"hello"` using Ruby ?

* a) write "hello"
* b) puts "hello"
* c) say "hello"
* d) echo "hello"

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > We can use "puts", "p", or "print".
</details>

### 🍏 20. What does the following code return – `4.lcm(3)` ?

* a) 4/3
* b) 3/4
* c) 12
* d) 6

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > Integer#lcm yields the least common multiplier of the integer it's called on and the parameter.
</details>

## Chapter 2: **Ruby Data Types and Operations**
[👆🏼 Go to Table of Contents](#table-of-contents)

### 🍎 1. What does `[4, 5, 6] – [5]` return?

* a) `[4, 5, 6]`
* b) `[4, 6]`
* c) `[5]`
* d) `[4, 5, 6, 5]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > This will return [4, 6].
</details>

### 🍎 2. If you saw a method called "internal?", what would be a possible value you'd expect it to return ?

* a) nil
* b) "internal"
* c) :internal
* d) true

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > Method names with a question mark at the end should return true or false.
</details>

### 🍎 3. What does the following code return ?

```
def woof
  "woof"
end

woof("meow")
```

* a) "woof"
* b) "meow"
* c) ArgumentError
* d) nil

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > Calling a method that does not accept parameters with a parameter will result in an ArgumentError being raised.
</details>

### 🍎 4. What is the value of the hash after the following code has been executed ?

```
hash = { a: 1, b: 2 }
hash['a'] = 2
hash[:b] = 4
```

* a) { :a => 1, :b => 4, 'a' => 2 }
* b) { :a => 1, :b => 4 }
* c) { :a => 2, :b => 4 }
* d) { :a => 1, :b => 2 }

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The keys are originally symbols, so assigning `"a"` as a string adds a new element, and assigning a new value to `:b`replaces the existing one.
</details>

### 🍎 5. What does the following code return ?

```
['Oh no', 'why', 'oh why?'].join(', ')
```

* a) `"Oh no why oh why?"`
* b) `"Ohnowhyohwhy?"`
* c) `"Oh no,why,oh why?"`
* d) `"Oh no, why, oh why?"`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > The strings will be joined by `", "`.
</details>

### 🍎 6. What is the value of `a` after the following code is executed ?

```
a = [1, 2, 3, 3, 3]
a.uniq!
```

* a) `[1, 2, 3]`
* b) `[3]`
* c) `[3, 3, 3]`
* d) `[1, 2, 3, 3, 3]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > Array#uniq! modifies the array to remove any duplicate elements in place.
</details>

### 🍎 7. What does `['rats', 'cats'].pop` return ?

* a) 'cats'
* b) 'rats'
* c) ['rats']
* d) ['rats', 'cats']

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > Array#pop will return the last element from the array that was removed.
</details>

### 🍎 8. What is the value of `a` after the following code is executed ?

```
a = [1, 2]
a.push(0)
a << 3
```

* a) `[1, 2]`
* b) `[0, 1, 2, 3]`
* c) `[0, 3, 1, 2]`
* d) `[1, 2, 0, 3]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > Both push and << add to the end of the array.
</details>

### 🍎 9. What is the value of `"b"` after executing the following code ?

```
a, *b = [1, 2, 3, 4]
```

* a) `1`
* b) `[1]`
* c) `[2, 3, 4]`
* d) `[1, 2, 3, 4]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > The splat operator at work!
</details>

### 🍎 10. What does the following code output ?

```
def woof(*other_sounds)
  puts "woof! #{other_sounds.join(', ')}"
end

woof 'meow', 'ribbit'
```

* a) woof! meow, ribbit
* b) woof!
* c) meow, ribbit
* d) ArgumentError

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The asterisk or splat argument accepts any number of parameters into an array.
</details>

### 🍎 11. What does the following code return ?

```
def add_things(a, b = 100)
  a + b
end

add_things 200
```

* a) RuntimeError
* b) 200
* c) 400
* d) 300

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > `b` defaults to 100, and we pass in 200 as the value for `a`.
</details>

### 🍎 12. What does the following code return?

```
{ ghosts: ['Casper'], cartoons: ['Barney'] }.values
```

* a) `[:ghosts, :cartoons]`
* b) `['Casper']`
* c) `['Casper', 'Barney']`
* d) `[['Casper', 'Barney']]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > Hash#values returns an array of all the values in the hash.
</details>

### 🍎 13. What is the last element of the returned array from this code ?

```
[{ name: 'George', age: 3 }, { name: 'Bill', age: 1 }, { name: 'Alfred', age: 5 }].sort_by { |hash| hash[:age] }.reverse
```

* a) { name: 'George', age: 3 }
* b) { name: 'Bill', age: 1 }
* c) { name: 'Alfred', age: 5 }
* d) [{ name: 'George', age: 3 }, { name: 'Bill', age: 1 }, { name: 'Alfred', age: 5 }]

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > Sorting will return the elements in ascending order, but then reversing will make them return in order of decreasing age.
</details>

### 🍎 14. What does the following code return ?

```
{ one: 'saucy', two: 'frantic' }['one']
```

* a) nil
* b) 'frantic'
* c) { one: 'saucy', two: 'frantic' }
* d) 'saucy'

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The keys in the hash are symbols, not strings.
</details>

### 🍎 15. What does the following code return ?

```
hash = Hash.new('butterflies')
hash[:fruits]
```

* a) nil
* b) :fruits
* c) 'butterflies'
* d) {}

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > Accessing a key that hasn't been set will return the default value specified when the hash was created.
</details>

### 🍎 16. What does the following code return ?

```
['cashews', 'almonds'].include?('Almonds')
```

* a) nil
* b) NoMethodError
* c) true
* d) false

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > Array#include? is case-sensitive.
</details>

### 🍎 17. What does the following code return?

```
[1, 2, 3].length == [6, 7, 9].size
```

* a) false
* b) true
* c) nil
* d) NoMethodError

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > length and size return the same value.
</details>

### 🍎 18. What is the value of `a` after the following code is executed ?

```
a = [1, 2, 3, 3, 3]
a.uniq
```

* a) `[1, 2, 3]`
* b) `[3]`
* c) `[3, 3, 3]`
* d) `[1, 2, 3, 3, 3]`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > Array#uniq does not modify the array, but returns a new copy of the array with the duplicate elements removed.
</details>

### 🍎 19. What does `["puppies", "kitties"][1]` return ?

* a) nil
* b) "puppies"
* c) "kitties"
* d) array index out-of-bounds exception

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > `"kitties"` is at index 1.
</details>

### 🍎 20. What does this code return ?

```
Array.new(2, "apples")
````

* a) `[2, 2]`
* b) SyntaxError
* c) `[2, 'apples']`
* d) `['apples', 'apples']`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > The first parameter is the number of elements, and the second is the default value for those elements.
</details>

## Chapter 3: **Program Flow**
[👆🏼 Go to Table of Contents](#table-of-contents)

### 🍐 1. What is a common purpose of a guard clause ?

* a) Exit a method immediately if an invalid parameter was passed in.
* b) Send an email if an unusual parameter is passed in.
* c) Massage parameters into expected values.
* d) Verify that the method is allowed to be called.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
</details>

### 🍐 2. What is the value of `x` after the following code is run ?

```
x = 0
x += 1 while x < 10
```

* a) 0
* b) 1
* c) 2
* d) 10

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > `x < 10` until `x` is `9`, at which point we add 1 more to it, so we'll return 10.
</details>

### 🍐 3. What does the following code print ?

```
{ 'dog' => 'Annie' }.each_with_index do |(a, b), c|
puts "#{a} - #{b} - #{c}"
end
```

* a) dog - Annie - 0
* b) Annie - dog - 0
* c) 0 - dog - Annie
* d) 0 - Annie - dog

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > `a` will be assigned the key from the hash, `b` the value, and `c` the index.
</details>

### 🍐 4. How many times will the following loop execute if left alone ?

```
while 1 < 2 do
  puts "dogs are great"
end
```

* a) 0
* b) 1
* c) 2
* d) Infinite

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > `1` will always be less than `2`, so this loop will execute infinitely.
</details>

### 🍐 5. What does the following code return ?

```
true && !false
```

* a) false
* b) SyntaxError
* c) true
* d) nil

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > You can read this as `true` AND NOT false
</details>

### 🍐 6. What does `yield 5` do from within a method ?

* a) Invoke the block passed to the method with a parameter of 5.
* b) Repeat the method 5 times.
* c) Return a valur of 5 from the method.
* d) Exit the application with a status code of 5.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The block will be called with a parameter of 5
</details>

### 🍐 7. What does the following code return ?

```
[1, 2, 3, 4, 5].map do |num|
  num > 3
end
```

* a) [1, 2, 3, 4, 5]
* b) [true, true, true, true, true]
* c) [false, false, false, true, true]
* d) [false, false, false, false, false]

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > We're mapping to a Boolean (whether the number is greater than three or not).
</details>

### 🍐 8. What does the following code return ?

```
['cats', 'dogs'].map(&:upcase)
```

* a) 'CATS'
* b) 'DOGS
* c) ['cats', 'dogs']
* d) ['CATS', 'DOGS']

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > `map` returns a new array with each value in uppercase for this example.
</details>

### 🍐 9. What does the following code print ?

```
{ 'dog' => 'Annie' }.each do |a, b|
  puts "#{a} - #{b}"
end
```

* a) Annie - dog
* b) dog - Annie
* c) { 'dog' => 'Annie' }
* d) #{a} - #{b}

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > The key will be assigned to `a` and the value to `b`.
</details>

### 🍐 10. What will the following code print ?

```
["apples"].each_with_index do |a, b|
  puts "#{b}: #{a}"
end
```

* a) 0: apples
* b) 1: apples
* c) apples: 0
* d) apples: 1

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The second block parameter is the index and it starts at 0.
</details>

### 🍐 11. What is the name of this shorthand of the if/else conditional ? `true ? "option 1" : "option 2"`

* a) if / else
* b) ternary operator
* c) question colon operator
* d) shorthand if / else

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > That is the name of this shorthand syntax.
</details>

### 🍐 12. What does the following code print ?

```
def identify(input)
  case input
  when String
    puts "Nice string, buddy."
  when Integer
    puts "Nice number, buddy"
  when Hash
    puts "Nice hash, buddy"
  else
    puts "What is that, buddy?"
  end
end

identify(["apples"])
```

* a) Nice string, buddy.
* b) Nice number, buddy
* c) What is that, buddy?
* d) Nothing

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > We don't have a case for an array.
</details>

### 🍐 13. What is the value of `x` after the following code is executed ?

```
x = 1
x = x + 5 if !false
x = x + 1 unless false
x = x + 10 if false
```

* a) 1
* b) 5
* c) 17
* d) 7

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > The first two postfix conditionals return in a way that we add 6 to the starting value of 1.
</details>

### 🍐 14. What does the following code print ?

```
apples = 10

if apples > 12
  puts "That's a lot of apples"
elsif apples < 8
  puts "That's not very many apples"
else
  puts "That's a great number of apples to have."
end
```

* a) That's a lot of apples
* b) That's not very many apples
* c) That's a great number of apples to have.
* d) Nothing

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > We don't match the if or elsif conditions, so we reach the else.
</details>

### 🍐 15. What is the value of `fruit` after the following code is run ?

```
fruit = 'apples' && 'bananas'
```

* a) 'apples'
* b) 'bananas'
* c) ['apples', 'bananas']
* d) true

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > The && operator is evaluated before assignment, which will return 'bananas'.
</details>

### 🍐 16. Which of the following is a "falsy" value ?

* a) ""
* b) 0
* c) []
* d) nil

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > nil is falsy.
</details>

### 🍐 17. Which of the following is similar to `!(x || y)` ?

* a) `!x || !y`
* b) `!x && !y`
* c) `x && y`
* d) `!x || y`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > Think about if `x` and `y` were both `true`. These are logically equivalent.
</details>

### 🍐 18. Which of the following is similar to `!(x && y)` ?

* a) `!x || !y`
* b) `!x && !y`
* c) `x && y`
* d) `!x || y`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > Consider if `x` was `true` and `y` was `false`. These are logically equivalent.
</details>

### 🍐 19. What does the following code return ?

```
false || true
````

* a) false
* b) SyntaxError
* c) true
* d) nil

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > If something is false OR true, then it is true.
</details>

### 🍐 20. What method is the most common way to iterate over an enumerable in data ?

* a) every
* b) each
* c) iterate
* d) per

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > This will pass each element to a block one at a time.
</details>

## Chapter 4: **Ruby Methods**
[👆🏼 Go to Table of Contents](#table-of-contents)

### 🍊 1. What does the following code return ?

```
def divide(numerator, denominator = 10)
  numerator / denominator.to_f
end

divide(1)
```

* a) ArgumentError
* b) 0.5
* c) 0.1
* d) 100

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > We're using positional arguments here, where the denominator has a default value of 10, so the passed in parameter becomes the numerator.
</details>

### 🍊 2. What does the following code return ?

```
def divide(numerator: 10, denominator: 20)
  numerator / denominator.to_f
end

divide(denominator: 100)
```

* a) ArgumentError
* b) 0.5
* c) 0.1
* d) 100

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > We're using keyword arguments here and each argument has a default value, but then we pass in 100 for the value of 'denominator'.
</details>

### 🍊 3. What does the following code return ?

```
def sum(a, b = 10)
  a + b
end

sum 20
```

* a) 10
* b) ArgumentError
* c) 30
* d) 20

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > We've provided a default value of 10 for b, so we return 20 + 10.
</details>

### 🍊 4. What is the term for an object on which a method is called ?

* a) Method object
* b) Sender
* c) Method container
* d) Receiver

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > We name the object on which a method is called as the receiver of that message.
</details>

### 🍊 5. What is wrong with the following method definition ?

```
def sum one two
  one + two
end
```

* a) It's syntactically correct, but the arguments should have parentheses around them.
* b) It's syntactically invalid and will raise a 'SyntaxError' error.
* c) We should add an explicit "return" value.
* d) We should put the method body on the same line as the signature.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > While the arguments should have parentheses around them as well, the missing comma between the argument names will cause a 'SyntaxError'.
</details>

### 🍊 6. What is wrong with the following method definition ?

```
def sum(one, two)
  return one + two
end
```

* a) It's syntactically correct but the "return" value should be removed since it is unnecessary.
* b) It's syntactically invalid – the "return" value will cause an exception.
* c) The method name should be capitalized.
* d) There should be spaces inside of the parentheses.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > This method will work just fine, but the "return" value can be safely removed (and should be).
</details>

### 🍊 7. What does the following code return ?

```
def number(input)
  return "nope" if input > 10

  input * 2
end

number(20)
```

* a) SyntaxError
* b) "nope"
* c) 20
* d) 40

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > The input is greater than 10, so we hit the return value in the guard clause.
</details>

### 🍊 8. What does the following code return ?

```
def number(input)
  return "nope" if input > 10

  input * 2
end

number(5)
```

* a) SyntaxError
* b) "nope"
* c) 10
* d) 20

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > The last line of the method is executed and returned, so we get 10.
</details>

### 🍊 9. What is wrong with the following method definition ?

```
def greetings()
  puts "hey there"
end
```

* a) It's invalid syntax and will raise a 'SyntaxError' error.
* b) It's valid syntax but bad style; the parentheses should be removed from the signature.
* c) It's valid syntax but bad style; there should be a space in the parentheses.
* d) It's valid syntax but bad style; there should be a space before the parentheses.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > The parentheses are unnecessary and do nothing to add to the clarity of this code.
</details>

### 🍊 10. What exception gets raised by the following code ?

```
def greetings
  puts "hey there"
end

greetings("hello")
```

* a) SyntaxError
* b) ArgumentError
* c) RuntimeError
* d) No exception gets raised

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > The method does not accept arguments, so passing one will cause an ArgumentError exception to be raised.
</details>

### 🍊 11. What is the correct way of calling this method using `send` ?

```
def yell(words:, punctuation:)
  puts "#{words.upcase}#{punctuation}"
end
```

* a) `send(:yell, 'oh no', '!')`
* b) `send(:yell, [{ words: 'oh no', punctuation: '!' }])`
* c) `send(:yell, 'words' => 'oh no', 'punctuation' => '!')`
* d) `send(:yell, words: 'oh no', punctuation: '!')`

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > The correct way is send(:yell, words: 'oh no', punctuation: '!').
</details>

### 🍊 12. What does the following code return ?

```
[1, 2, 3].send(:last, 2)
```

* a) ArgumentError
* b) NoMethodError
* c) [1, 2, 3]
* d) [2, 3]

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > This is functionally the same as [1,2,3].last(2).
</details>

### 🍊 13. Why is it better to check whether an object `'responds to?'` a method instead of checking its type ?

* a) Duck typing allows flexibility; we only care if an object behaves like we need it to.
* b) Ruby provides built-in type checking for us.
* c) Method decorations ensure that arguments are of a given type.
* d) We want to keep a list of acceptable types of objects.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The behavior is really all we care about.
</details>

### 🍊 14. What is the name of the `*` operator that indicates a method will take any number of arguments ?

* a) Asterisk
* b) Splat
* c) Accepting
* d) Infinity

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > It will take the arguments and "splat" them into an array.
</details>

### 🍊 15. What is the value of `var2` after the following code is executed ?

```
array = ['apples', 'bananas', 'bears', 'puppy dogs']
var1, var2 = array.last(3)
```

* a) 'apples'
* b) 'bananas'
* c) 'bears'
* d) 'puppy dogs'

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > First, we get the last 3 elements of the array ('bananas', 'bears', and 'puppy dogs'), and then `var1` is assigned 'bananas' and `var2` is assigned 'bears'.
</details>

### 🍊 16. What does the term `"message"` refer to ?

* a) A method
* b) An object
* c) A parameter
* d) A string

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: a)
  > The Ruby documentation refers to methods as messages.
</details>

### 🍊 17. What is the correct term for the first line of a method, for example, `"def method(param)"` ?

* a) Method start
* b) Method name
* c) Method parameters
* d) Method signature

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: d)
  > The method signature consists of the method's name and parameters that it will accept.
</details>

### 🍊 18. Which of the following is equivalent to `"self.apple"` ?

* a) this.apple
* b) apple
* c) @apple
* d) call(:apple)

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > The 'self.apple' is implicit.
</details>

### 🍊 19. What is true about a method's name?

* a) It should be an acronym
* b) It should be in all uppercase
* c) It should make sense for the concept it represents
* d) It should be as short as possible (for example, "m1," not "method_1")

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: c)
  > Make your code readable and both your coworkers and your future self will thank you.
</details>

### 🍊 20. What is true about a well-designed method ?

* a) It performs strict type checking on its parameters.
* b) It has a single purpose.
* c) It returns a different type of object based on complex conditions.
* d) It encapsulates a lot of logic.

<details>
  <summary>👀 Click here to see the answer</summary>

  > #### The correct answer is: b)
  > Methods should be short and simple to enable readability and reusability.
</details>

## Chapter 5: **Object-Oriented programming with Ruby**
[👆🏼 Go to Table of Contents](#table-of-contents)

To be continued...