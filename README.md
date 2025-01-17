# Unexpected Instance Variable Modification in Ruby

This example demonstrates an uncommon, yet potentially confusing, behavior related to modifying instance variables directly using `instance_variable_set` in Ruby.  While seemingly straightforward, this approach can lead to unexpected consequences if not handled carefully, especially within the context of more complex class structures or when dealing with inheritance.

The included `bug.rb` file showcases this issue.  The `bugSolution.rb` provides a resolution strategy.

**Problem:** Directly changing instance variables can bypass potential validation or side effects that might be included in a standard getter/setter.