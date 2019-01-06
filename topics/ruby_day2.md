Ruby: Day 2

- prev day assignments
- revision of day 1
- what anyone learnt new that wasn't taught
- comparing two hashes?

- other ways to create a Hash/Array
  - using `new` keyword

- scopes of variables
- global variables
- default params for a method
- methods as arguments?
- variable number of parameters for a method (*)
- undef method

- Range in ruby:
  - use to_a method
  - as sequences:
    - 
      digits = 0..9
      puts digits.include?(5)
      ret = digits.min
      digits.each {|n| puts n }
  - as conditions:
    case when 0..30
  - as intervals
    (1..10) === 5

- loops in ruby
  - while do...end
  - begin..end while
  - until do..end
  - for in
      for num in 1..5 { num }
  - break and next statements
  - each do..end
  
- extra Array methods:
  - sort
  - select
  - collect
    a = [1,2,3,4,5]
    b = a.collect{|x| 10*x}
  - map
  
- extra Hash methods:
  - clear, delete, each, each_key, empty?, has_value?(value), inverse, keys, merge, merge!, reject, select, sort, to_a, 

  
- blocks in ruby
  - passing a block to a method (a block that accepts params)
  - calling the block in the method using `yield`
    - def test
        yield
      end
      test { puts "Hello world"}
  - other way to call the block in the method
    - def test(&block)
        block.call
      end
      test { puts "Hello World!"}`
      
- Exceptions:
    begin  
      # -  
    rescue OneTypeOfException  
      # -  
    rescue AnotherTypeOfException  
      # -  
    else  
      # Other exceptions
    ensure
      # Always will be executed
    end

