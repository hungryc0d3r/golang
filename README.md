------------------------------------------------------------
                           Golanguage
------------------------------------------------------------

 Go language ==>intially developed by google in 2007

 it was developed by Robert Griesemer, Rob Pike, and Ken Thompson

  Key Features:-

    $  static typing

    $  language design
 
    $  testing support
 
    $  platform independent
 
    $  package management
 
    $  powerful standard library

    $  fast compilation time

    $  Garbage collection


 -----------------------------------------------------------------
                           Variables in Go
 ------------------------------------------------------------------
 SYNTAX:-
 
         var variable type
         variable = value

        var variable type = value

        variable := value

    We can't Redeclare them but we can shadow them

    All variables must be used 

    Visibility
        lower case first letter for package scope
        upper case first letter to export
        no private scope 
    
    Naming conventions
        Pascal or camelCasing
          Capitalize acronyms(HTTP,URL)
        As short as reasonable
          longer names for longer lives

    TypeConversions
        destinationType(variable)
        use strconv package for strings


 ----------------------------------------------------------------------
                            Primitives
 ----------------------------------------------------------------------

    Boolean

    Numeric types
      integers
      floating point
      complex

    Text types

  --------------------------
           Boolean
  --------------------------
      Syntax:- 

            var variable bool = true/false
                            (it is similar syntax as variables but the type will be the datatypes)
  -> In Golang if we not initialize the value to the variable then it considers as false/0

