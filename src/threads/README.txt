The following changes were made to add the alarm-mega test to the system:

Alarm-wait.c - Added a test-alarm-mega function to create 5 threads, each of which sleeps a different, fixed
   duration, 70 times

tests.h - Added a test-alarm-mega extern definition with a test_func type

Make.tests - Added alarm-mega to the list of files to be built

tests.c - Added alarm-mega and test-alarm-mega to the test struct table

Rubric.alarm - Added entry for alarm-mega

alarm-mega.ck - Created new perl script for new test. Based off of alarm multiple, but alarm-mega.ck has 70 tests.
