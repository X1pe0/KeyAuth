# KeyAuth
### Passwordless and Usernameless based Authentication.

KeyAuth is a Passwordless/Usernameless authentication (auto generated and registered) system allowing analytics and paywalls via token based authentication. In the event of a lost token, a user can provide a username and password to signin (aka a vanity token hashed via SHA256 and encrypted via AES). With KeyAuth there is no difference between regular authentication and or token based authentication. Upon authentication, a cookie will be submitted within the users browser to remain signed in. (Shown Below.)

![](https://nabyte.com/imgs/eeb048076dde920b911adb1c3ace30318770e9e7Screenshot%20at%202021-09-28%2012-01-03.png)

### Examples of standalone apps: https://bitnix.app/tunnely/ - https://nabyte.com

Both of these examples are standalone app's allowing information to be stored without the need of a registered user. Both services can be implemented with a single authentication point/service hence KeyAuth. Open enrollment will be available to 3rd party sources with generated AES keys (for each org) and example PHP scripts for users to quickly see analytics and provide secure authentication without any user interaction. This system requires no SQL DB and or other methods of storing user data minimizing the risk of a potential breach. 

## Expanded View

![](https://nabyte.com/imgs/2e6a09ef1faa48570c52710bbcfa501f078791d0Screenshot%20at%202021-09-28%2011-31-42.png)
