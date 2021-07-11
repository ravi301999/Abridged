# Linking the Collab.Land Bot in Discord

1. Sign in to Discord (if not already signed in)

2. Click here add [Collab.Land](https://discord.com/oauth2/authorize?client_id=704521096837464076&scope=bot&permissions=8)

3. Select a server.

4. Add Collab.Land as an administrator.

Once Collab.Land is added to your server, it will greet you and automatically create a collabland-config channel. 

To get started type

```
!help
```
in collabland-config channel
<br></br>
Next is to setup role

```
!setup role
````
Use '!setup role' in the collabland-config channel to set up token permissions and assign them to roles created in the Discord server settings. 

Once set up, community members can enter !join in any public channel to participate in your token economy!

**Roles must first be created in Discord server settings. Make sure Collab.Land is at the top of the server role hierarchy. It needs to be above any roles it will interact with.**

### Choose a Network

Collab.Land supports several blockchain networks for token permission roles.

Click on the reaction for the corresponding network to proceed.
 1. Click on the reaction for the corresponding token type to proceed.
 2. Enter a supported token address, the minimum and maximum amount of the tokens required to access that role, and the assigned role.
 3. After typing the address and min/max tokens the @ symbol will pop up a selection of available roles to choose from. Select a role.
 4. Confirmation of configuration is displayed after inputting the token address and access requirements.

___
___


<br></br>
<br></br>


# Linking the Collab.Land Bot in Telegram
1. Create A New Telegram Group
2. Add members to your group (At least one member will need to be added to your new group to proceed)
3. Add members to your group

### Configure Your Group Settings

You'll need to make sure your group is set up to use the Collab.Land bot by editing your Group Settings. 

* Access your group settings by selecting your group icon in the upper left hand corner of the menu bar. You can also get to these settings by selecting the 3 dots and then Info.
* Select Edit.
* Allow new group members who join to see the full message history. This upgrades your group into a supergroup.
* Select Chat History For New Members.
* Select Visible.
* Select Done in the upper right corner to save.
  
### Adding the Bot to your Group
Add @collablandbot to your new group. Please enter this username exactly. 
```
@collablandbot
```
Others may try to imitate the bot.
The bot will need to be added after the group chat history has been set to visible. If not, it will automatically leave the group and ask to have the chat history setting updated.

Once the bot is added to your group, it will announce itself in chat as well as send a DM to provide admin options for your group

If you have added the bot while creating the group, you will need to DM the command 
```
/start
```
 to @collablandbot to begin setting up admin options.
* Select Add.
* Search for collablandbot in the Search bar.
* Select the button next to the bot’s name.
* Select OK.
* Select Add.
* Add @collablandbot to your group as an admin. Select Edit at the upper right corner.
* Select Administrators.
* Select Add Admin.
* Select Collab.Land bot. The bot should have all the  settings enabled except **Remain anonymous and add new member**.

### Group Admin
1. To access bot admin options, go back to your chat with @collablandbot, and either press the Start button at the bottom of the screen or type 
```
/start
```
in the message composer.


2. Select Configure Token Holders Group/Airdrop.
From a list of your groups, select the group you want to configure.

3. If your group is not displayed, select Add Collab.Land To Group first.

* Once your group is selected you can:
  * Setup / edit token permissioned chat

  * Setup / edit ERC20 airdrops

  * Save the private key for reclaiming unused airdrop tokens and ETH

### Permissioned Chat
Token Permissioned Chat allows you to create an exclusive chatroom for members who hold a certain amount of your tokens.

**Setup**

* Go back to your chat with @collablandbot, and either press the Start button at the bottom of the screen or type 
```
/start
```
 in the message composer.

* Select Group Admin.

  * From a list of your group(s), select the group you wish to configure.

* Select Token Permissioned Chat.
* Select Add Token Permission Config.

The group invitation link will also be displayed. Use this link to invite members to your group after completing the setup.

* Select the blockchain network where your token resides.
* Select the token type that will be used for your membership. Depending on which blockchain network you selected there will be different options to choose from.

* Enter the token address and the minimum number of tokens a member must hold to have access to the group.

  * Example: 0xABCDED 5


Your token permissioned chat is now set up. More token configurations can be added by following the same steps.
___
___