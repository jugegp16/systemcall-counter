Syscall counter
----------------
Added a new system call to Xv6, which, when passed a valid system call number (listed in the file syscall.h) as an argument, will return the number of times the referenced system call was invoked by the calling process.
