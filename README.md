![Cinema Challenge](Assets/logo.png?1)

## Assignment

You've been assigned to a project to create a small part of the reservation system for a cinema. In particular the seating arrangement for its visitors who made an online reservation. The input you get from the online booking system is the number of persons the reservation holds and the output should be in the form of an array with the seating numbers that should be reserved. 
Priority with this booking system is that the visitors will be seated, as much as possible, next to eachother.

In other words you need to create some sort of method which looks at a number of rows and finds the best gap for the group of visitors to be seated.
If for some reason the entire group cannot be allocated into a single 'gap', then you have to split the group up into smaller groups. And remember that nobody likes to sit alone or inbetween strangers.

Also create a (dynamic) visual presentation of the seats in the cinema an the its occupation.

## Technique

We would like you to use Kotlin / JAVA. The use of additional frameworks are allowed. However the seating arrangement should be written by yourself.
Make use of a database in order to store the seats.

## Usage

The number of seats or undefined. Your approach should be able handle 10, but also 10,000 seats, or even more. Every cinema starts of with a random number of chairs already occupied. So don't start of with an empty room. This particular functionality is just a (small) part of the entire booking system, so keep that in mind.