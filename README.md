# About-Overwriting

## In the example below, the purr and getFeatures methods have been overridden by the GrumpyCat type.

##Some rules for overwriting are:

   ## the overridden method has the same return type and signature as the original method
   ## we can have a different return type than the original method as long as it is a type that inherits the original method's return type
   ## the access specifier of the overridden method cannot be more restrictive than that of the original method
   ## cannot throw more exceptions or more general exceptions, but can throw fewer or more particular or unchecked (runtime) exceptions
   ## static and final type methods cannot be overridden
   ## constructors cannot be overridden
