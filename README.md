# Prenex-to-DFA
Scala project for conversion of a string representing prenex form of a regex into a DFA. The conversion is prenex->NFA->DFA.

## Each class contains specific functions.
 - The NFA class has methods for conversing the regex written in the premex forms using words into an NFA. This class also deals with the parsing of the string input and determing if it represents a valid regex.
 - The DFA class contains methods for conversing a regex in the prenex form to a DFA. It is dependant on methods from the NFA class.
