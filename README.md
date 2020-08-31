# salesforce-jwt-bearer
A simple implementation of a OAuth 2.0 JWT Bearer Token Flow for Salesforce
This code is based on Justin Johnson (booleangate) tutorial available at https://gist.github.com/booleangate/30d345ecf0617db0ea19c54c7a44d06f

## Requirements

### Install PyJWT Module
$ pip install PyJWT

Documentation: https://pyjwt.readthedocs.io/en/latest/

Note: Some conflicts could happen if you have the JWT module installed. You can use the following commands to uninstall JWT and grant that the PyJWT is installed correctly

$ pip uninstall JWT
$ pip uninstall PyJWT
$ pip install PyJWT

### Install Requests Module
$ pip install requests

Documentation: https://pypi.org/project/requests/

### Install OpenSSL
Working....

## Instructions

### Generate SSL Certificate using OpenSSL
Working....

### Creating the Connected App
Working....

### Running the code
Working....

#### For Community Users
The domain should be replaced by the same URL address shown on "All Communities" page on Salesforce Setup.
For example: https://"Community My Domain".force.com/"Community Subdomain"

Platform users should use https://login.salesforce.com for Production/Developer or https://test.salesforce.com for sandboxes. My Domain could be used to replace "login" and "test" names. 