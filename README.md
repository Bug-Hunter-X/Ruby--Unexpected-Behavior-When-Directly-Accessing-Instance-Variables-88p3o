# Ruby: Unexpected Behavior When Directly Accessing Instance Variables

This example demonstrates a common pitfall in Ruby: directly manipulating instance variables outside of the class definition using methods like `instance_variable_set` and `instance_variable_get`. While functional, this practice violates encapsulation principles and can lead to difficult-to-debug issues.

The `bug.rb` file shows the problematic code, and `bugSolution.rb` provides a solution that maintains better encapsulation and readability.

**Key takeaway:** Favor using accessor methods (getter and setter methods) to interact with instance variables, promoting better code organization, maintainability, and preventing unexpected side effects.