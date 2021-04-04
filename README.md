(1..100).each do |int|
  if int % 15 == 0
      puts "FizzBuzz"
    else
      int % 3 == 0
        puts "Fizz"
    else
      int % 5 == 0
        puts "Buzz"
    else
      puts int
  end