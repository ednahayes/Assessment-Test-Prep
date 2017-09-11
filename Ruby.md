# Ruby Questions

## Which of the expressions listed below will result in "false"?
```ruby
true    ? "true" : "false"
false   ? "true" : "false"
nil     ? "true" : "false"
1       ? "true" : "false"
0       ? "true" : "false"
"false" ? "true" : "false"
""      ? "true" : "false"
[]      ? "true" : "false"
```

answer: false ? "true" : "false"

## I want to write some code that takes an array of numbers, multiplies each item in the array by 3, and returns a new array with the new values. know I should use #map, #each, or #select, but I’m not sure which one is best -- teach me.
```ruby
array_of_numbers = [1, 2, 3]
array_of_numbers.map { |n| n * 3 }   => [3, 6, 9] #map returns a new array with the block code given. BEST CHOICE if not only!!!

array_of_numbers.each { |n| n * 3 } => [1, 2, 3] #each returns the original object

array_of_numbers.select { |n| n * 3 } => [1, 2, 3] #select returns the original object, and is used to select specific numbers not going thru the loop and selecting each number and multiplying.
```
I tried different approach on select but still didn't get the new array 

```ruby
array_of_numbers.select { |n| n == 1 || 2 || 3 * 3 }  => [1, 2, 3]
```

## What are the common controller actions?
Create

Read

Update

Delete


## Which of the following is not a benefit of Object-Oriented Programming?

a) Reduces side effects of functions
b) Enables code reuse
c) Encapsulates functionality
d) Allows the developer to make certain methods/variables inaccessible to other classes

## Consider the following two methods:
```ruby
def times_two(arg1);
  puts arg1 * 2;
end

def sum(arg1, arg2);
  puts arg1 + arg2;
end
```
What will be the result of each of the following lines of code:
```ruby
times_two 5
times_two(5)
times_two (5)
sum 1, 2
sum(1, 2)
sum (1, 2)
```

## What is missing? M_____/View/Controller

## What is the most beneficial aspect of TDD?

## Write a function that accepts an array of numbers and a second number. Beginning at index 0, total up the sum of the values of the array until you've met or surpassed the second argument. Return the number of elements required to fulfill the goal. If the goal can't be reached, return 0.

## Make a copy of http://jsbin.com/beyape/1/edit complete the task described in the comments and attach the link
