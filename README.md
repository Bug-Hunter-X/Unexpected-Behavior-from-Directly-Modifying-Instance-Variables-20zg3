# Ruby Bug: Unexpected Behavior from Directly Modifying Instance Variables

This repository demonstrates a potential issue in Ruby related to directly manipulating instance variables using `instance_variable_set`.  Directly accessing and modifying instance variables bypasses the encapsulation intended by methods and can lead to unexpected behavior and make your code harder to maintain and debug.

The `bug.rb` file shows an example of this issue. The `bugSolution.rb` file shows the preferred way to modify the state of the object using methods, maintaining encapsulation and reducing unexpected behavior.