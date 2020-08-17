# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given the staff at the hospital gate
  When people enter they get unique ID's 
  Then counting the IDs will tell the number.

Scenario: Compute parking slots to reserve for visiting specialists

  Given the parking area with watchman carrying the tokens equal parking slots  
  When a car comes the token allocates and reserves the place
  Then the remaining tokens will tell the number of remaining parking slots.
