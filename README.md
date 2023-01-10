# Projects

## List Freak

Repo:
https://github.com/JeffersonAmori/ListApp

App:
https://play.google.com/store/apps/details?id=com.deviance.listfreak

Built with Xamarin.Forms (there was no GA .MAUI releases back then) with cloud backup after login with your Google Account.

## Playstation Wishlist

Repo:
https://github.com/JeffersonAmori/PlaystationWishlist

Back when there was no wishlist functionality for the PSN. This project makes use WebJobs to scrap the PS store and notify clients (using SendGrid), there is a front-end and a back-end, and the SQL Server is used to store the data. All this hosted on Azure.

## Operating system Architecture in AI for Screeps

Repo:
https://github.com/JeffersonAmori/screeps-typescript-starter-master

Game:
https://screeps.com

Screeps is a tick-based MMORPG for programmers. Think Age of Empires meets JS. There are some approaches for an enrivonment like this, and I went with the Operating System architecture. This means that the AI has a process scheduler, a GC and processes can retain state between cycles.

## Hi-Lo Game

Repo:
https://github.com/JeffersonAmori/HighLowGame

Game:
https://hi-lo-game.azurewebsites.net

My take on the multiplayer version of the Hi-Lo game. The multplayer part is achieved using SignalR and the multiple engine support is implemented using the strategy pattern.
