# PSA: Fixing gradle builds post 1/29/21
After around the 29th - 30th of January sponge powered, the maker of mixins used in minecraft forge clients and mods made some changes to their side that breaks building of all forge mods. Fortunitly it is only a minor change an can be fixed in seconds.

This is the error you get if you try to compile a forge mod rn
![Pic](https://media.discordapp.net/attachments/712745558673981510/806005063180353596/Error.png?width=2520&height=476)


The problem lies in your build.gradle file, The server has switched from a http protocal to a https protocal so in your build.gradle file change all of the urls that have the word SPONGE in them. DONT change any of the other urls. (There are normally 2 urls)

![Pic](https://raw.githubusercontent.com/Gopro336/PSA-how-to-fix-gradle-builds-feb-2021/master/url.png?token=APBTGEANBQV6X2YMP4X5QSDADDEFA)
![Pic](https://raw.githubusercontent.com/Gopro336/PSA-how-to-fix-gradle-builds-feb-2021/master/url2.png?token=APBTGEANBQV6X2YMP4X5QSDADDEFA)

