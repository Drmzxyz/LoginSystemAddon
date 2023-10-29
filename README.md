# Login System Add-On

Welcome to the login system add-on! This addon provides a simple way to manage user accounts in your minecraft server. This requires the players to register a account to play on your serer in short you can get who already played on your world.

#

## Getting Started!

# Installation:

1. Download the add-on.
2. Upload the add-on onto your minecraft.
3. Activate both resources and behavior pack on your world settings.
4. Enable `Beta APIS` in your experimental world settings.

#

## Usage

# Permission:

1. Add a tag to the players you want to get access to use the command of this add-on with the following tags:

- Owner001
- Admin002
- Staff003

# Commands:

`DEFAULT:`

1. `-logdata getAccounts`

- Allows you to get every players that is registered on the server.

2. `-logdata removeAccount #`

- Allows you to unregister the player onto your server.

3. `-logdata avoid #`

- This command is designed to exempt specific players flagged by administrators, allowing them to enter the server without the need to log in to their accounts. However, it's important to note that this command is exclusively available for newly registered players on the server.

4. `-logdata unavoid #`

- You can only select players that are in the exempted list, this will unexempt a player that are flagged as to be letting in without logging in to their accounts.

5. `-logdata continue`

- This command is connected with the `removeAccount` command, this will confirm within 10 seconds if the player account will get unregistered to its server.

6. `-logdata cancel`

- Same as `-logdata continue` allows you to cancel unregistration of the players account you want to be removed.
