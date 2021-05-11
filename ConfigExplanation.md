# Config
#### Here is what an empty config looks like. Scroll down to see what each of these does 
```js
{
    "DISCORD_ID": "",
    "CMDS": "",
    "notifs": [
      ""
    ],
    "NOTIF_CHANNEL": "",
    "TRADE_CHANNEL": "",
    "colors": {
      "inbound": "GREEN",
      "declined": "RED",
      "completed": "PINK"
    },
    "want": {},
    "dontcheckoutbound": true,
    "rapboost": 1.1,
    "reset_already_sent_interval": 3600000,
    "MAX_ITEMS": 4,
    "use_robux": true,
    "projected_ratio": 0.3,
    "robux_ratio_send": 0.001,
    "testmode": false,
    "custom_values": {},
    "accept_ratio": 1.1,
    "USER_ID": 1,
    "plugger9000_enabled": false,
    "avoid_devpois_like_the_fucking_plague": true,
    "stop_on_completed": false,
    "selfeval": 1,
    "ratio": 1.05,
    "maxratio": 1.2,
    "dontdecline": false,
    "mineval": 0,
    "keepmyrares": false,
    "manualeval": 99999999,
    "DONOTGET": {},
    "keep_images": false,
    "DONOTTRADE": {},
    "getridoffast": {},
    "fuckrares": true,
    "rewrite_to_end_if_ratelimited": false,
    "upgrading_ratio": 0.9,
    "upgrading_max_ratio": 1,
    "onlytradefor": false,
    "onlytradeforarray": {},
    "proof_based": {},
    "autoregen": false,
    "autoregeninterval": 43200000,
    "owned_proj_ratio": 0.9
  }
  ```
  #### DISCORD_ID
  ###### This is your discord dev ID. To get this, go to **SETTINGS** > **ADVANCED** > **DEVELOPER MODE** and right click on your profile. To make sure its yours, send a message with <@idhere> and it should ping you.

⠀    
  #### CMDS
  ###### This is the channel id of where other users can run commands in your server. The bot owner (the one whose discord id is in DISCORD_ID) can run commands everywhere. Only they can run sensitive commands like $mass_send
  ⠀
  #### notifs
  ###### This channel id is for roli trade ad notifications.
  ⠀
  #### NOTIF_CHANNEL
  ###### The channel id of where it will display queued trades.
  ⠀
  #### TRADE_CHANNEL
  ###### The channel id of where inbounds/declined/outbound/completed will be shown
  ⠀
  #### want
  ###### These are the itemids of items you want to be notified for when someone posts an ad about
  ⠀
   #### colors
 ###### The colors for embeds, MUST BE HEX
 ⠀⠀
 #### dontcheckoutbound
 ###### When this is set to true, it wont notify of outbounds anymore, saving on valuable http requests
 ⠀
 #### rapboost
 ###### This **ratio** is multiplied by your rep items to determine what to send them for. Rapboost takes precedence over other ratios. 
 ⠀
#### reset_already_sent_interval
###### The time in milliseconds before it'll reset the list of users its already sent to. 
⠀
#### MAX_ITEMS
###### If this number is less than the number of items in your inventory, the bot will downgrade. If it is = to or higher the bot will upgrade
⠀
#### use_robux
###### Whether it should add robux to the trades
⠀
#### projected_ratio
###### How much it should give for projecteds
⠀
#### robux_ratio_send
###### A ratio which is multiplied by your robux to change its value. If I had 1k robux, and set this to 1.2 it would value the 1k as 1.2k when trading it.
⠀
#### testmode
###### When this is set to true, the bot will only queue trades, and will not send
⠀
#### custom_values
###### This will assign a value to an item. 
```js
{
    "itemid1":true,
    "itemid2":true
}
```
 ⠀
 #### accept_ratio
 ###### This ratio determines which inbounds the bot will accept
 ⠀
 
  
