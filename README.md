# Login System Add-On

Welcome to the login system add-on! This addon provides a simple way to manage user accounts in your minecraft server. This requires the players to register a account to play on your serer in short you can get who already played on your world.

#

# Getting Started!

## Installation:

1. Download the add-on.
2. Upload the add-on onto your minecraft.
3. Activate behavior pack on your world settings.
4. Enable `Beta APIS` in your experimental world settings.
5. Enjoy.

#

# Usage

## Permission:

1. Add a tag to the players you want to get access to use the command of this add-on with the following tags:

- Owner001
- Admin002
- Staff003

## Commands:

`DEFAULT:`

1. `-logData getAccount #`

- Allows you to get the specific player account information.

2. `-logData removeAccount #`

- Allows you to unregister the player onto your server.

3. `-logData avoidUser #`

- This command is designed to exempt specific players flagged by administrators, allowing them to enter the server without the need to log in to their accounts. However, it's important to note that this command is exclusively available for newly registered players on the server.

4. `-logData unAvoidUser #`

- You can only select players that are in the exempted list, this will unexempt a player that are flagged as to be letting in without logging in to their accounts.

5. `-logData continue`

- This command is connected with the `removeAccount` command, this can be only use within before 15 seconds or else the automatic deletion cancellation will be triggered.

6. `-logData cancel`

- Same as `-logData continue` allows you to cancel the player account deletion when on process.

## Note

- Email and password must be 5 characters longer or else system will not let you create a account!

## Reports

If you encounter any bugs, please feel free to reach out to me on Discord. Additionally, if you have any suggestions for improving this addon or want to contribute to its moderation, don't hesitate to send me a direct message!

**Discord**: `Drmz#1263`
