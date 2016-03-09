Many developers often want to monitor the performance rate of an application, a process, or an operation, and display them in a nice looking graph. Some existing implementations exist as a solution of this problem. However many of us would probably want to have a dynamic and interactive performance manager widget, something similar to the performance graph in Windows Task Manager.

One important issue is cross-platform compatibility. We want to make sure that  the library is not OS implementation dependent, i.e. dependent on MFC framework, .NET platform, etc.

This motivated me to create an implementation of performance monitoring widget, which is built based on Qt library, one of the most widely-used User Interface (UI) library that is available on market today.
This performance widget library is called qw-performance-monitoring, and at the moment it is distributed as a static library. All header files, libraries (both for 32 bit and 64 bit architectures), examples, and documentation are included in this software distribution.
If you find any issues / bugs, please submit a bug report, by going to the Issues tab in this page, and submit your issue from there. You can also submit a bug report or request for some features to be added into the qw-performance-monitoring library by sending an email to issuetracking 'at' graziacomputing 'dot' com.
Thanks, and enjoy using it !!