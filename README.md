# 42-tester.h

## Usage

```c
#include "tester.h"

TESTER("My tester", {
	// Optional flags:
	// EXIT_ON_FAIL = true;

	group("Group", {
		test(1 == 1);
	});
});
```
