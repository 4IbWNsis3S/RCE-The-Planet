# RCE-The-Planet
Can you RCE it?

Warning: Don't run these without a test subnet or local firewall blocking public or enterprise traffic to the listening port.

This is a repository of intentionally remote exploitable code with gradual levels of modem x86 compiler and chip level mitigations. All are 100% exploitable under all platforms. I don't include sandboxing or ring-zero.

easy = stack and heap overflows with no protections

medium = stack and heap overflows with full stack protections, forced ASLR. and NX

hard = uninitialized-variable and double-free with full stack protections, forced ASLR, and NX with or without obfuscation
