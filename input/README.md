# INPUT

Input files are splited by:
- input urls - URLs that should be tested
- test plan configuration

Test plan configuration is an CSV format using semicollons in this format:
```
# test_name ; urls_input_file ; rampup_sec ; time_interval ; wait_interval_sec
sample-simple01 ; sample-input.txt ; 17,20 ; 10s ; 5
```
1. test_name : label of the current plan test
1. urls_input_file : Path file with URLs on the vegeta's format , inside `input/`
1. rampup_sec : total requests per second, splited by collon, of each test (the rampup)
1. time_interval : total time in seconds of each battery (ramp up test)
1. wait_interval_sec : wait interval for each rampup of test plan
