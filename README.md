# PawnScript-StdLib
:mouse: ¤ PawnScript standard include with return references, constants and more.

# Features
## Shorter keywords
- Now you can simply use the `std::` keyword wrappers instead of using `new.datatype,...`.
```cpp
std::uint,stduinttest=-23;
console.rawout.log(stduinttest);

std::sint,stdsinttest=738436;
console.rawout.log(stdsinttest);

std::int,stdinttest=23243;
console.rawout.log(stdinttest);

std::bool,stdbooltest=true;
console.rawout.log(stdbooltest);

std::string,stdstrtest="std::string works";
console.println.log(stdstrtest);

std::float,stdfloattest=23.243;
console.rawout.log(stdfloattest);

std::double,stddoubletest=4323.243; // Float and double are simply the same.
console.rawout.log(stddoubletest);

std::char,stdchartest='s';
console.cout.log(stdchartest);
```

## Everything in one place
- This standard library includes all the language components to avoid using the boring `using` keyword all the time.

Say good bye to:
```cpp
using data;
using console;
using pawn;
using system;
// and many more
```

And say hello to:

```cpp
#include:stdlib;
```

## Return references

- Are you bored of creating a return reference variable each time you need it, now with the **stdlib**, you can simply do this:
```cpp
console.println.log("I don't need anything here!") std::intretref; // There are also std::boolretref, strretref, charretref and doubleretref!
```

## Constants
- `std::nullstr` - Empty string.
- `std::nullchar` - Empty character.
- `std::pi` - PI.
- `std::euler` - Euler's number.
- `std::gravacc` - Gravitational acceleration.

## Call templates
- `std::writeln` - `console.println.log`
- `std::writec` - `console.cout.log`
