# Payment

A simple demonstration of state machine interaction to be executed in Verifier.
In Model explorer, open the state machines for the 3 classes in CardPayment.
Tile the editors so that all 3 are visible (See Tiling Editors in Help).
Switch to the xtUML Debugging perspective.
Create a debug configuration, selecting the PaymentMachine component.
- In TestFunctions package, execute 'Initialize' function; note instances appear in CardPayment.
- In CardPayment package expand the 3 classes and put each new instance in Spotlight.
  ( select one, then, holding Ctrl, select the other two; right click and choose 'put in Spotlight' )
- In TestFunctions, execute 'Next' repeatedly and watch how the state machines behave.
When the transaction completes, the Customer instance is deleted.
To repeat, execute 'Next' to create another customer; put the instance in Spotlight before proceeeding.
