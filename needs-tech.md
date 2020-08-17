# Visit-counter technical needs

Scenario: Recover across restarts of the server that runs the visit-counter

  Given a system engineer
  When the server falls down
  Then the engineer takes care to bring it back in the normal state.

Scenario: Reconcile counts if the sensor is offline for a while

  Given the staff at the time of server failure
  When someone enters the staff keep a count on that
  Then adds that count once the server gets back to its normal state.
