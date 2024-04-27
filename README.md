# py3-ex4-48-nose-package-problem-solved-re-LPTHW
If nosetests ran, but powershell shows 0 tests are ran.
Reason: nose is no longer supported for python3.
1.installed nose2: pip install nose2;
2.rename the NAME_tests file to test_NAME: mv NAME_tests test_name;
3.rename all the function in NAME_tests.py to test_funcname()

clear all the pycache file.

run nose2 in powershell. you should see:

I RAN!
.SETUP!
.TEAR DOWN!
.
----------------------------------------------------------------------
Ran 3 tests in 0.001s

OK
