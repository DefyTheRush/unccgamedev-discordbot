# unccgamedev-discordbot
Discord Bot made to manage UNCC Game Developer's Discord @UNCCGameDevelopers

## Getting Started

1. Fork repository

2. Create a app bot token key at [Discord Developers](https://discordapp.com/developers/applications/me)

./token.json
```json
{
  "value" : "yourtokenvaluehere"
}
```
3. Invite Bot to test on your own server or ask @UNCCGameDevelopers to send you an invite to their bot test server.

4. Run the following in terminal

```bash
$ node index.js
```

4. For any feature changes, create an issue https://github.com/darkmastermindz/unccgamedev-discordbot/issues and a feature branch and submit that feature branching using a PR and link it to the issue. Keep this one feature / fix per PR. 
See guidelines for the "perfect pull request" here: [The Anatomy of a Perfect Pull Request](https://medium.com/@hugooodias/the-anatomy-of-a-perfect-pull-request-567382bb6067)

## Commands
- addrole.js - Add Role to user requires `MANAGE_ROLES` permission.                                                                                                                                                                                         
- ban.js - Perm-Ban requires `BAN_MEMBERS`                                                                                                                                                                                                
- botinfo.js - Gets Bot info                                                                                                                                                                                            
- clear.js - Cleans up a channel. Poofs number of messages Requires `BAN_MEMBERS`                                                                                                                                                                                                
- coins.js                                                                                                                                                                                             
- daily.js                                                                                                                                                                                             
- hello.js                                                                                                                                                                                             
- help.js                                                                                                                                                                                          
- kick.js                                                                                                                                                                                        
- level.js                                                                                                                                                                                          
- prefix.js                                                                                                                                                                                            
- removerole.js                                                                                                                                                                                       
- report.js                                                                                                                                                                                           
- say.js                                                                                                                                                                                              
- serverinfo.js                                                                                                                                                                                       
- stats.js                                                                                                                                                                                        
- tempmute.js

## Utils
- color.js
- errors.js
- exceptions.js
- eventsController.js
