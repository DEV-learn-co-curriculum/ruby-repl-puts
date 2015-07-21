%%%

### Ruby Repl Puts

Write a method that puts "ruby" 3 times

~~~ruby

def puts_ruby_three_times
  # code your solution here
end

# do not remove the line below
puts_ruby_three-times

~~~solution

def puts_ruby_three_times
  3.times do
    puts "ruby"
  end
end

puts_ruby_three-times

~~~validation

assert_output(response, "ruby\nruby\nruby")

~~~

%%%
