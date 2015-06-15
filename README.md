# LLDB python script to catch exceptions when thrown

to use add the python script to ~/Library/lldb and add the .lldbinit into your
home directory.

Then setup your exception break point in Xcode like this:

![Breakpoint](https://github.com/nerakhon/sniff_objc_exception_throw/blob/master/docs/breakpoint.png)

Based on Rob Mayoff's script : http://qwan.org/2013/06/18/how-to-snatch-the-error-code-from-the-trap-frame-in-xcode/
