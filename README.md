# xsprintf
Minimal header-only sprintf implementation, modded from ChaN's code.

Original xprintf code could be found at: http://elm-chan.org/fsw/strf/xprintf.html

# ChangeLog
1. Thread safety. The original project is not thread-safe because it uses global variables to store function and buffer pointers, our code has eliminated such usages.
2. Only xsprintf function is provided, other functions from original code was removed. 
