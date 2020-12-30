# Linear Alerts, A discord bot.

### Not reproduced/relayed alerts
All alerts you see by our bot is set by a staff member of that cookgroup manually, Linear does not set any alerts.

![Image](https://cdn.discordapp.com/attachments/793726684741632000/793727557081497640/Screen_Shot_2020-12-30_at_12.29.43_AM.png)
![Image](https://cdn.discordapp.com/attachments/793726684741632000/793730148120657970/Screen_Shot_2020-12-30_at_12.40.03_AM.png)


### Support
Open a ticket in the linear discord server: https://discord.gg/ZSyYNzBdxk

# Commands:
- *Assuming you've set the prefix to `r.`*
- *In order to work with the bot you need to have a role that varies in each server, the owner sets the permissions.*

## General
- `r.help`: Gives you a link to the docuementation and list of commands [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793726951311147028/Screen_Shot_2020-12-30_at_12.27.18_AM.png)
- `r.setalert`: This will add alert on your desired time. [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793727557081497640/Screen_Shot_2020-12-30_at_12.29.43_AM.png)
- `r.alerts`: This will list all active alerts.[IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793727759322578974/Screen_Shot_2020-12-30_at_12.30.32_AM.png)
- `r.delalert`: It will print all the alerts and you can delete any one by providing the `id` of alert that you'll see when you type `r.delalert`.
- `r.clear`: This will create all the alerts for that particular server.
- `r.time`: Will returh the current time for your server, by default it use the timezone `Greenwich` that you can change with `r.settz` (see the use below.). [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793728008698462208/Screen_Shot_2020-12-30_at_12.31.33_AM.png)
- `r.settz <time-zone>`: Will change the timzone for your server example `r.settz America/New_York`. [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793728008698462208/Screen_Shot_2020-12-30_at_12.31.33_AM.png)

### Avalible Timezones
https://en.m.wikipedia.org/wiki/List_of_tz_database_time_zones

## Admin
- `r.channelsetup`: This will ask you a few questions to setup a branded webhook in a channel, if you do not have a webhook set in the channel that te alert uses the bot will send the alert. The image MUST be sent as a url. You'll have to do this for every channel you want to use custom branding in. [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793728408051646464/Screen_Shot_2020-12-30_at_12.32.38_AM.png)
- `r.addrole @Support`: This will allow you to add a role that will be allowed to interact with the bot, you can use a role ID. [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793728626716573706/Screen_Shot_2020-12-30_at_12.34.00_AM.png)
- `r.removerole @Support`: This will allow you to remove access to the bot for the role you remove, you can use a role ID.
- `r.roles`: This will list all roles with access to the bot in your server. [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793728626716573706/Screen_Shot_2020-12-30_at_12.34.00_AM.png)
- `r.setcolor #fffff`: This will change the color of embed messeges. This example will set the color to `#fffff` [IMAGE](https://cdn.discordapp.com/attachments/793726684741632000/793728937359704064/Screen_Shot_2020-12-30_at_12.35.14_AM.png)
- `r.setprefix .`: This will change the prefix for bot commands. This exapmple will set the prefix to `.`
