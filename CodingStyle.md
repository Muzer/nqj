## Curly Braces ##
Curly Braces will be underneath the function/method/statement like this:
```
int main()
{
    return 0;
}
```

## Statements ##
Statements must have a space between it and the args:
```
if (0 == 0)
{
    bool result = true;
    return result;
}
```

It will always you curly braces, but may be on one line if it does not do much.
```
if (0 == 0) { return true; }
```

## Comments ##
One line comments must be:
```
// This is a one-line comment
```
Multi-line comments must be:
```
 /* This is a multi
    line comment. */
```

## Indents ##
It will be indented with tabs.

## Libraries ##
Always use the C++ libraries where possible.
```
#include <iostream>
#include <sstream>
#include <cmath>
#include <fstream>

using namespace std;
```

## Classes / Variables ##
Always use classes rather than structs unless really really needed.

The whole application must use classes. I.E. the whole program is a class.

Do not use global variables.

## Files ##
Always end the file with a new line.
Files must use the UNIX line endings.