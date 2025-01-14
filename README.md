# Ruby Type Safety Example

This repository demonstrates a potential type safety issue in Ruby using a simple example. The code showcases how a setter method can accept different data types without explicit type checking. This may lead to unexpected runtime errors or behavior in some scenarios.

## Bug

The `MyClass` uses a setter method that doesn't enforce any type checking. This allows assigning values of any type, even if it doesn't make sense in the context of the class.