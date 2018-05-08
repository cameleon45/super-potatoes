# Misc Commands
>Note: These commands need `Manage_Server` permission to work.

## Commands
|Commands|Usage|
|--------|-----|
|`prefixset`| Kashima will change the prefix according on what you want.|
|`afkset`| Kashima will set whether the AFK Module will be on/off in a server.|
|`invitebuster`| Kashima will set whether the Invite Buster Module will be on/off in a server.|
|`invitebusterlv`| Kashima will set the Level of the Invite Buster Module (Level 1 - 3) _(See note 1)_.|
|`welcomeset`| Kashima will set whether to turn the Welcome Module on/off in a server.|
|`modlogset`| Kashima will set whether to turn the Mod-Log Module on/off in the server.|
|`modlogch`| Kashima will set the mod-log channel depending on what you want. Has the default of #kashima-log channel.|
|`welcomech`| Kashima will set the Welcome Channel depending on what you want. Has the default of #welcome channel.|
|`welcomemsg`| Kashima will let you specify what would be the Welcome Message in the server _(See note 2)_.|


## Notes
### Note 1:
```
Invite Buster Levels

Level 1 = Delete the Invite link, with a message mentioning that user not to send Invite Links

Level 2 = Delete the Invite Link then Kick that User.

Level 3 = Delete the Invite Link then Ban that User.
```
> Kick and Bans in Invite Buster supports Mod-Log if Mod-Log is enabled on your server, Kashima will send it there.

>Kashima will Kick / Ban anyone that has Lower Role than her, so if you want to excempt the role, move it higher than Kashima.

### Note 2:
```
Welcome Message Options

{user} will be the mention of the user joined ~

{guild} will be your Discord's Server name ~

Example : Hi {user} welcome to our {guild}, This is Kashima, gives you a warm welcome~
```