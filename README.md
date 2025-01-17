# Unexpected Behavior When Assigning to Getter Method in Ruby

This repository demonstrates a subtle bug in Ruby related to how getter methods are handled when assigning values.  The issue arises when developers incorrectly assume that assigning a value to the result of a getter method directly updates the internal instance variable.

The `bug.rb` file shows the problematic code, highlighting that attempting to modify the object's state through the getter doesn't work as expected.

The `bugSolution.rb` file provides the corrected approach, using a setter method to properly update the instance variable.

This example showcases the importance of understanding Ruby's object model and using proper setter methods for modifying object state.