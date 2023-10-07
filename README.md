# MacroChainGoneWild

**Allows chaining and looping macros**

Adding `'/nextmacro'` on the last line of Macro #01 will automatically execute Macro #02

Adding `'/nextmacro down'` on the last line of Macro #01 will automatically execute Macro #11

Adding `'/nextmacro loop'` on the last line of a macro will loop that macro until another macro is run.

Allows executing any macro using `'/runmacro'`. This works from the chatbox or within a macro.

Use `/runmacro ##` to run a macro by number. `/runmacro ## [i|s]` to specify an individual or shared macro.

## Install

add ```https://raw.githubusercontent.com/allanahkk/MacroChainGoneWild/master/mcgw.json``` to custom repos
