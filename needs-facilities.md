# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given the camera installed at the game to count the head counts
  When the visitors come in the hospital
  Then their head counts are noted which will tell the trends.

Scenario: Alert when seating capacity is full

  Given the seating hall with equal tokens
  When people comes they get a token
  Then the tokens left will tell the hall in full or empty.
