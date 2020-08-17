# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given the staff at the hospital gate
  When someone enters the gate the unique ID's are provided to them
  Then finally counting the IDs will tell the number.

Scenario: Compute parking slots to reserve for visiting specialists

Given the parking area with watchman carrying the tokens equal 
to the number of parking slots  
When a car comes the token allocates and reserves the place
Then the remaining tokens will tell the number of remaining parking slots.
