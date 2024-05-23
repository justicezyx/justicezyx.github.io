# Notes

```
[16:21:34] yzhao:~ $ cat test.c
#include <stdlib.h>

[16:12:49] yzhao:~ $ clang -c test.c
test.c:1:10: fatal error: cannot open file '/usr/local/include/stdlib.h': Permission denied
#include <stdlib.h>
         ^
1 error generated.

# Use this to fix the issue
# No idea how this happens
chmod a+x /usr/local/include
```
