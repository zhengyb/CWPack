#CWPack - Test

The folder has two tests.
- A module test to check that the packer/unpacker behaves as expected.
- A comparative speed test between CWPack, MPack and CMP.

## The module test

The shell script `runModuleTest.sh` runs the module test. The test checks that it is compiled with compatible byte order and then checks the different calls to CWPack.

## The speed test

The speed test is run by the shell script `runPerformanceTest.sh`. The script assumes that the repositories for CWPack, MPack and CMP are side by side in the same folder.

The speed test checks the duration of a number of calls by calling them 1.000.000 times.