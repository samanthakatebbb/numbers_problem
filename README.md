# Do the following three times:
# Ask user to input a positive integer value
# Convert the user input to an integer and save the value in a variable

# ask for a positive integer 
puts "Please give me a whole number between 1 and 10."
# wait for reply, convert string anwser to an integer, save in a variable
a = gets.chomp.to_i

# ask for a positive integer
puts "Please give me a second whole number between 1 and 10"
# wait for reply, convert string anwser to an integer, save in a variable
b = gets.chomp.to_i

# ask for a positive integer
puts "Please give me a third whole number between 1 and 10."
# wait for reply, convert string anwser to an integer, save in a variable
c = gets.chomp.to_i

puts "You have entered #{a}, #{b}, and #{c} and their sum is #{a+b+c}."

puts "Twenty added to the numbers you entered gives us #{a+20}, #{b+20}, and #{c+20}."
