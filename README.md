# my-eve-ng-postman
Basic Postman API calls for EVE NG Pro 4

Edit environment.json file to match your lab setup.
1. Server IP value
2. username value
3. password value
4. lab path value

Import both files into your postman setup and you should be able to power on and power off devices in your lab prior to logging into GUI.

At the moment you need to run the "login" call before running any other API call. My plan is to learn enough that each API call will test for authentication and call the 'login' API call if login fails.

Any feedback is welcome as I'm new to Github, postman and Python.
mjpgannon@aol.com
