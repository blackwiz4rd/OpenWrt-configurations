# OpenWrt configurations for extending public networks
These configurations can be used in OpenWrt to extend two types of network:
-WOW-FI by Fastweb
-Vodafone-WiFi

Versione in italiano
------------
Guide seguite:__
`https://wiki.openwrt.org/doc/howto/hardware.button
https://wiki.openwrt.org/doc/recipes/bridgedclient`__
Per le configurazioni riguardanti Fastweb fare riferimento a `etc/config/fastweb`__
Per le configurazioni riguardanti Vodafone-WiFi fare riferimento a `etc/config/vodafone`__
Per ragioni di sicurezza alcune informazioni sono state oscurate, quindi compilatele con i dati del vostro router oppure modificate le vostre configurazioni già esistenti.__

In `custom images/` troverete le due immagini che ho utilizzato per installare openwrt su Netgear EX2700 (sconsiglio l'acquisto per la poca memoria flash disponibile).__

In `usr/bin` troverete degli script che utilizzo per fare lo switch da un wifi all'altro in modo da poter sempre scegliere quale utilizzare in poco tempo.__

Per la gestione dei pulsanti (per Negear EX2700) fare riferimento a `hotplug.d/button` e `etc/config/system`__

Versione in italiano
------------
Guides followed:__
`https://wiki.openwrt.org/doc/howto/hardware.button
https://wiki.openwrt.org/doc/recipes/bridgedclient`__
For fastweb configurations refer to `etc/config/fastweb`__
For vodafone configurations refer to `etc/config/vodafone`__
As a security measure some information were deleted, you need to compile those info with the appropriate ones from your router.__

In `custom images/` you will find two custom images I used to install OpenWrt on my router (I don't suggest buying the Netgear EX2700 as it only has 4Mb of flash storage).__

In `usr/bin` you will find some scripts I use to toggle wifi from vodafone to fastweb in a fast way.__

To implement WPS button (only for Netgear EX2700) refer to `hotplug.d/button` and `etc/config/system`__
