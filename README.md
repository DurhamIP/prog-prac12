#Introduction to Programming

##Practical 12: Enumerations 

## Instructions

This practical focuses on the enumerated types used in the previous lectures.

###Level 1: Days of the Week

1. Create an enumerated type _Day_ that represents the days of the week:
MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY and 
SUNDAY
2. Test your enumeration for _Day_. You should create a variable dayOfWeek (of type _Day_), set this to a day of the week, and then compare dayOfWeek with each enumeration from _Day_.
3. Using If statements output the following information on each day of the week. (You should loop through each enumeration of Day)
   - I like Mondays as we have an IP lecture
   - Tuesday's aren't that great
   - Wednesday is a half-day
   - Thursday are good as we have an IP lecture
   - Friday is almost the weekend
   - Saturday's are for sleeping in
   - On Sunday I think about the next week

###Level 2: Enumeration Constructors and Methods

1. Extend your _Day_ enumeration to take a single boolean parameter representing if this day is a weekend day. E.g. MONDAY(false) or SUNDAY(true).
2. Add a method goodDay() to your enumeration which returns true if the day is a weekend and false otherwise.
3. Test your enumeration by looping through the days and outputting "I like \<DAY>" where \<DAY> is a weekend day and "I don't like \<DAY>" when \<DAY> is not a weekend day.

###Level 3: Ordering

Create an enumeration called _Planets_ which represents the planets in our solar system. Extend the _Planets_ to include their distance from the sun. Add a method to the _Planets_ enumeration which given the following statement:

`Planets.MERCURY.closerToSun(Planets.EARTH)`

would return true and given the statement:

`Planets.NEPTUNE.closerToSun(Planets.MARS)`

would return false.

Test your code thoroughly.