require_relative 'animal'
require_relative 'bird'
require_relative 'Dog'
require_relative 'Grocery'

my_animal = Animal.new 
puts my_animal.speak
puts my_animal.jump

my_bird = Bird.new 
puts my_bird.speak 

dog = Dog.new('K9') 
puts dog.dog_breed
 

dog = Dog.new('Maltese') 
puts dog.dog_breed
puts dog.purchased_at

dog_guid = Dog.new('Guid Dog')
puts dog_guid.dog_breed 
puts dog.purchased_at


grocery = Grocery.new('products')
puts grocery.grocery_products 
puts grocery.purchased_at

