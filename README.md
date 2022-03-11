# Task14
Create a self signed wildcard certificate with domain *.intern.phonepe.in with expiry validity of 2 years. 
- Setup a simple server running on port 5440 that implements ping/pong requests 
- Using certificates from step 1, setup a nginx ssl proxy (domain ping.intern.phonepe.in) running on port 444.  
  Proxy should redirect request to the locally setup ping-pong server
