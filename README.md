# hpc-bug

Run `stack test --coverage`:

```
stack test --coverage                                                                                                                       ~/work/hpc-bug
hpc-bug-0.1.0.0: unregistering (local file changes: test/Spec.hs)
hpc-bug-0.1.0.0: build (lib + exe + test)
Preprocessing library hpc-bug-0.1.0.0...
Preprocessing executable 'hpc-bug-exe' for hpc-bug-0.1.0.0...
Preprocessing test suite 'hpc-bug-test' for hpc-bug-0.1.0.0...
[1 of 1] Compiling Main             ( test/Spec.hs, .stack-work/dist/x86_64-linux-nix/Cabal-1.24.2.0/build/hpc-bug-test/hpc-bug-test-tmp/Main.o )
Linking .stack-work/dist/x86_64-linux-nix/Cabal-1.24.2.0/build/hpc-bug-test/hpc-bug-test ...
hpc-bug-0.1.0.0: copy/register
Installing library in
/home/ollie/work/hpc-bug/.stack-work/install/x86_64-linux-nix/lts-9.0/8.0.2/lib/x86_64-linux-ghc-8.0.2/hpc-bug-0.1.0.0-9GTHWF941lvI0yzRNgARgf
Installing executable(s) in
Warning: Unable to strip executable or library
/home/ollie/work/hpc-bug/.stack-work/install/x86_64-linux-nix/lts-9.0/8.0.2/bin
'libHShpc-bug-0.1.0.0-9GTHWF941lvI0yzRNgARgf' (missing the 'strip' program)
Warning: Unable to strip executable or library
'libHShpc-bug-0.1.0.0-9GTHWF941lvI0yzRNgARgf-ghc8.0.2' (missing the 'strip'
program)     
Warning: Unable to strip executable or library 'hpc-bug-exe' (missing the
'strip' program)
Registering hpc-bug-0.1.0.0...
hpc-bug-0.1.0.0: test (suite: hpc-bug-test)
             
Progress: 1/2hpc-bug-test: <stdout>: commitBuffer: invalid argument (invalid character)
             
Generating coverage report for hpc-bug's test-suite "hpc-bug-test"
Error: The coverage report for hpc-bug's test-suite "hpc-bug-test" did not consider any code. One possible cause of this is if your test-suite builds the library code (see stack issue #1008). It may also indicate a bug in stack or the hpc program. Please report this issue if you think your coverage report should have meaningful results.
Completed 2 action(s).
Only one tix file found in /home/ollie/work/hpc-bug/.stack-work/install/x86_64-linux-nix/lts-9.0/8.0.2/hpc/, so not generating a unified coverage report.

An index of the generated HTML coverage reports is available at /home/ollie/work/hpc-bug/.stack-work/install/x86_64-linux-nix/lts-9.0/8.0.2/hpc/index.html
Test suite failure for package hpc-bug-0.1.0.0
    hpc-bug-test:  exited with: ExitFailure 1
Logs printed to console
```
