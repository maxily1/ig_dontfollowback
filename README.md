# A script to find who is not following back in Instagram
This simple code, will connect to your Instagram account using your provided login data, will scan your account for your followers and your followings, and then will search for people who are not following you back. 

## Dependencies
Firstly, Install the required library using the following command:
```sh
python -m pip install instapy
```
Secondly, Make sure you have the latest version of Firefox installed! This is IMPORTANT.

## Steps for running the script:
1. Run the script using the following command - make sure to change `<username>` and `<password>` appropriately without the "<>" symbols:
```sh
python3 main.py -u <username> -p <password>
```
2. Wait a few seconds for the program to finish, and there will be a list of all of the people who don't follow back.
3. That's it.

# Common Issues and Troubleshooting:
* Checkpoint required - This is mostly occuring due to 2FA in Instagram. In order to fix this issue, all you need is to find the Firefox window opened by Selenium, and confirm the login. Or procceed to the link which is stated in the error and do the challenge. Or, before running this script, Log in to your account in Firefox.

## NOTE: If you stalk in any errors, Please open an issue / contact me (https://github.com/maxily1)

# Contributing
You are more then invited to contribute to this project. Every contribution is appreciated.

# License
MIT - See [LICENSE](https://github.com/maxily1/ig_dontfollowback/blob/master/LICENSE) for more information regarding this license.

