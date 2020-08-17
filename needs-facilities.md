# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given the camera installed at the game to count the head counts
  When the visitors come
  Then number of head counts which will tell the trends.

Scenario: Alert when seating capacity is full

Given the seating hall with equal tokens
When someone enters gets the token
Then the tokens left will tell the hall in full or empty.
