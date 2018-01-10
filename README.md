# sipp-scenarios

We are using SIPp application to test NGN elements

for testing an element we need to create two inject file for SIPp UAC and UAS subscriber information.
also we need to write two script for UAS to register and start listening for incoming calls and UAC to register and generating
calls to UAS.


Note:
During the tests, specially FreeSwitch, I have found some problems with SIPp which can't  handle the 407 proxy authorization request from FreeSwitch properly. Use my scenario files to solve the issues.



