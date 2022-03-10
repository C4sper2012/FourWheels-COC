# FourWheels-COC

### General Conducts

- I will follow the professional standards
- I will understand the value of the work delivered.
- I will uphold a clear and transparent standard of quality
- I will not withhold any information that might harm my team
- I will selflessly share my knowledge
- I will do the best I can
- I will uphold this code for myself and others

### Git Convensions

#### Branch names
- All branch names should start Capitalized


### Programming Styles

#### Namespace definitions
- Namespace should be of the type *scoped namespace*

#### Variable naming

Pascal cases are used in the following scenarios:
- Class definitions
- Properties
- Enums
- Namespace definitions
- Struct
- Methods

Camel cases are used in the following scenarios:
- Variable definitions
- Parameter definitions

Fields are defined as starting with an underscore, followed by camelcase:
- _myFieldVariable

#### Method naming convention

- Method names should not exceed 20 characters
- Method name should contain a definition of the work its doing.
- Method names should not start with "my" e.g not "MyCalculateSum()"

#### Method data convention
- Methods should not complete multiple acitons e.g CalculateSum(int num1, int num2) should only calculate and not write the output.
- Methods should only follow async/await pattern when awaiting is available
  - Async methods should not have return type void
  - Delegates should have name delegate in naming
- Methods should not be declared static outside a static class

#### Comment conventions
- Comments SHOULD NOT contain code.
- Multiple comments should not exceed 3 lines excluding start and end comment delimiters.
- Inline comments should be specified before code its describing.
- All methods should have a brief summary describing the action its performing
- Comments should not describe builtin functions.
