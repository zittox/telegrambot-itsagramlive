
# ItsaGramLiveBot
### It's a telegram bot based on the original ItsAGramLive

### The ideia is to create a bot version so that you can go live in your instagram ( OBSStudio / Wirecast / VMix alike ) WITHOUT the need of a python installation.




#
#### bot.py is a copy of ItsAGramLive.py and has been modified with pyTelegramBotAPI
#
___**WORKS:**
- login (if the account has NO two-factor authentication) 
- go live, rtmp server link and stream key
- Info
- viewers
- comments
- mute comments
- unmute comments
- chat
- pin
- unpin
- wave
- stop
- save to IGTV (sometimes it works, sometimes it doesn't - not sure why)
 
___**TO DO:**
- two-factor authentication
- chalenge mode ( SMS / Email )

-------------------------------------

### Token setup
- Install dotenv
```bash
pip install python-dotenv
```


- Create a file .env, in the root directory, paste your token given by @BotFather in TELEGRAM as follows:
####
token = 'blablbalablabalabalbaalabalbbla'


-------------------------------------

### At the moment the bot is
- ONLINE (testing)  https://t.me/ItsaGramLiveBot
  
##

Telegram desktop version in windows can copy the stream key automatically to clipborad. Yout can use it in a custom browser docks inside OBS, but ir will not copy the stream key automatically

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/67715164/173175592-3f9ba36e-4f1b-4c8c-8cfc-bdd7461adcf6.png" width="240" height="426">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/67715164/175843475-46f61b11-b5e5-46c1-aada-1b5668662794.png" width="640" height="360"> 


##
### Contributions are much appreciated

##



### License

[ GNU GPLv3 ](https://choosealicense.com/licenses/gpl-3.0/)

-------------------------------------
 ## This project was made possible by the original script from [HarryPython](https://github.com/harrypython/itsagramlive)

#
## Did you enjoy this bot? Please consider donating to help me keep this bot [ONLINE](https://www.paypal.com/donate/?business=8GTDHP8TTEMUJ&no_recurring=0&item_name=Thank+you%21+This+means+a+lot+to+me+and+to+this+project.&currency_code=BRL) 


 
## Disclaimer

Neither this bot or its creator are associated or affiliated to Instagram. This is an unofficial application and stands no liability or warranty of usage. Use at your own risk.




