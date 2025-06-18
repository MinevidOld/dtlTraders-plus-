![dltraders transparent with cloud watermark 8bit](https://github.com/user-attachments/assets/65847b64-5579-46dc-be79-3692dbd9f446)

dtlTraders was created to easily setup admin shops for your server.
Make and manage your shops with a GUI. Seriously, no hassle with configs and commands ;)

Do you like dtlTraders? Let other people know by a review!
Join [discord](https://discord.gg/fyabsMF) to get involved in future updates or get/give help from/to other server owners. ​

For 1.8 -1.16.5 use version 6.4.1
For 1.17+ use latest version​

⋆ **__Features:__**
- Easy way to setup and manage shops using a GUI
- Make/edit your shops just by drag and drop
- 3 types of shops: 'Sell', 'Buy' and 'Trade'
- 2 types of item content: 'static' and 'trade'
- 1 powerful trader type: "trader" (/trait trader) bind the dtlTraders shops with citizens(2) NPC's
- Support of vanilla and custom NBT/DataTags
- NBT/DataTags makes custom item from 3rd party plugins possible
- Advanced users can customize there own items using the configs.
- Allows stack trades
- ANY economy plugin support (with Vault)
- Compatible with spigot/bukkit 1.8 - 1.15.x
- Change descriptions and names of your items
- Add trading limitation ono items like "limits"
- Customize your shops with "default shop" and "toggle shops"
- Adjust shop interaction with "custom input amount" and "stack shift"
- Make your rank based shops with custom "permissions"
- More navigation buttons and GUI modules with a aim to "One GUI"

__**New features on Version 6.0.0:**__

- Control the text you see on items with "custom display text"
- Toggle "Item drop" allowing items to be dropped when inventory is full on buy/sell/trade
- Toggle "Sell all items" that allows to sell the remaining items
- "Broadcast message" allows you to customize or toggle the public messages on buy/sell or trade
- Change page names included
- Improved "One GUI" with Categorized Settings, Live view of Changes and a smoother, fancier look <3
- Even better handling of shop functionalities

__**Currently supported economy plugins:**__
- any Vault supported evonomy. ([EssentialsEco](https://essentialsx.net/downloads.html), [TNE](https://www.spigotmc.org/resources/the-new-economy.7805/), [CMI (with Vault enambled)](https://www.spigotmc.org/resources/cmi-300-commands-insane-kits-portals-essentials-economy-mysql-sqlite-much-more.3742/), [PlayerPoints (with Vault enabled)](https://www.spigotmc.org/resources/playerpoints.80745/)
- [BeastTokens](https://www.spigotmc.org/resources/beasttokens-custom-currency.20806/) (Optional. Enabled in config, disabled Vault hook)

***For users that wants more features, we have a premium plugin named: dtlTradersPlus***

**Features of dtlTradersPlus:**
- Make your shop bigger by adding more pages
- Set a command to open the shops without need to interact with a NPC
- Bring the shop function to a next level, set commands on items you sell
2 types of commands on items function: 'Buy and Run' and 'Buy and Keep (run it later)'
- And you can do all of it just using a GUI
- New method for commands on items: "Run as OP"
- And it could not be easier with "mirror shop" just copy between shop types and other shops
- Get real shop experience with the "discount" function
- All the features of dtlTraders (non premium version)

__New features on the PREMIUM version 6.0.0:__
- Logging shops into text files
- Allowing command execution on tradable items
- Cloning shops to save time
- Set per "Item" permission (custom permission feature)
- Set per "Page" permission (custom permission feature)

*Unlock premium features with dtlTradersPlus. Buy your copy at: [www.Degitise.com/dtltradersplus](https://www.spigotmc.org/resources/dtltradersplus.63690/)*
Buying the premium version, helps US continue working on future updates for both versions dtlTraders and dtlTradersPlus. :coffee:


**➲ Installation:**
- Download dtlTraders(Plus).jar and place it into your plugins folder. Since the recreation version "5.0.0" you need to delete the dtltraders folder! (shops created with older versions are automatic converted!)
- Download [Citizens](https://dev.bukkit.org/projects/citizens) (Citizens2) and place that into your plugins folder as well.
- You also need [Vault](https://dev.bukkit.org/projects/vault)
- You also need an economy plugin
(currently supported: [BeastTokens](https://www.spigotmc.org/resources/beasttokens-multishop-mobcoins-and-blockcoins-drops.20806/), [OptEco](https://www.spigotmc.org/resources/opteco-1-8-1-16-3-points-system-with-mysql-and-more.76179/), [GemsEconomy ](https://www.spigotmc.org/threads/gemseconomy.129254/)and any Vault supported economy plugins)
- Start your server.
- Installation is done.

**Warning: As of 6.4.2 you'll need at least Java 11!**

Note: If you want to convert again , check the [Documentation](https://dev.bukkit.org/projects/dtltraders/pages/description-500-and-higher) and go to the section converter for more.

**↝ Simple guide:**

For each step just use the ONE GUI command /dtltraders trait and select the thing you want to accomplish.
- First you need to add trait traders to a NPC
- Then you create a shop
- Manage the shop and customize it your way by drag/drop items, set prices, set limits, set names and much more.
- After finish, right click on the NPC and choose the shop you want to hook into.
- You are done :)

Advanced guide: [Dtltraders-5.0.0 and higher](https://dev.bukkit.org/projects/dtltraders/pages/description-500-and-higher)
/dtltraders shorter aliases: /dtl and /traders
Permissions:
Before 6.0.0:
The only permission is dtltraders.admin.

Starting from 6.0.0:
These are stored and can be changed inside the permissions.yml file:

Spoiler: permissions.yml
```yml
wildcards:
    admin-wildcard: "dtltraders.admin"
    shop-wildcard: "dtltraders.shop.*"
    page-wildcard: "dtltraders.page.*"
    items-wildcard: "dtltraders.items.*"
     
commands:
    help: "dtltraders.help"
    toggle: "dtltraders.toggle"
    edit: "dtltraders.edit"
    create: "dtltraders.create"
    delete: "dtltraders.delete"
    list: "dtltraders.list"
    trait: "dtltraders.trait"
    reload: "dtltraders.reload"
    info: "dtltraders.info"
    loadconfig: "dtltraders.loadconfig"
    save: "dtltraders.save"
   
inventories:
    shop:
        create-shop: "dtltraders.inv.create-shop"
        select-shop: "dtltraders.inv.select-shop"
        edit-shop: "dtltraders.inv.edit-shop"
        edit-shop-name: "dtltraders.inv.edit-shop-name"
        edit-shop-permission: "dtltraders.inv.edit-shop-permission"
        edit-shop-command: "dtltraders.inv.edit-shop-command"
        edit-shop-default: "dtltraders.inv.edit-shop-default"
        edit-shop-status: "dtltraders.inv.edit-shop-status"
        clone-shop: "dtltraders.inv.clone-shop"
        remove-shop: "dtltraders.inv.remove-shop"
    page:
        create-page: "dtltraders.inv.create-page"
        select-page: "dtltraders.inv.select-page"
        edit-page: "dtltraders.inv.edit-page"
        edit-page-name: "dtltraders.inv.edit-page-name"
        edit-page-contents: "dtltraders.inv.edit-page-contents"
        edit-page-contents-functions: "dtltraders.inv.edit-page-contents"
        edit-page-size: "dtltraders.inv.edit-page-size"
        edit-page-permission: "dtltraders.inv.edit-page-permission"
        mirror-page: "dtltraders.inv.mirror-page"
        remove-page: "dtltraders.inv.remove-page"
    items:
        static: "dtltraders.inv.items.static"
        tradable: "dtltraders.inv.items.tradable"
        commands: "dtltraders.inv.items.static"
        trade: "dtltraders.inv.items.static"
```

**⇲ Hyperlinks:**
- [Documentation](https://dev.bukkit.org/projects/dtltraders/pages/description-500-and-higher)
- [Old documentation](https://dev.bukkit.org/projects/dtltraders/pages/description2-4-4-2-5)
- [Older versions](https://dev.bukkit.org/projects/dtltraders/files)
- [Bukkit page](https://dev.bukkit.org/projects/dtltraders)
- [Old Sourcecode](https://github.com/Dandielo/dtlTraders/) (Old version of dtlTraders (V3.4.2)) (Recreation version V5+ hasn't been published)

**▶ Video tutorial:**
This is a tutorial we made for dtlTraders 'V5.0.0' and above, we guide you there for a fresh installation and how to setup a shop ingame:
English tutorial:

https://www.youtube.com/watch?v=E7Uc4QMFL78

Spanish tutorial:
​https://www.youtube.com/watch?v=g4F3wK-AHPs

**☊ Versions:**
Did you know that dtlTraders(Plus) V5.0.0 and above supports bukkit/spigot version 1.8 - 1.15.x ?
If you need a older version than 1.8 you can download it: [here](https://dev.bukkit.org/projects/dtltraders/files)
We only give support for versions started with V5.0.0 !


**✉ Contact or Issues:**
For questions or suggestions:
- PM me
- Join Discord channel: https://discord.gg/fyabsMF
- Create an issue on [the Github Issue tracker](https://github.com/MineVid/dtlTraders-plus-/issues)

**For issues:**
Issues tracker on [Github](https://github.com/MineVid/dtlTraders-plus-/issues)

*＊ Mention:**
1. Plugin started by dandielo
2. Continued by samyratchet (Degitise)
3. TheWGBbroz recreated dtlTraders commissioned
4. Maintained by Minevid under Degitise
5. Grows on features and as favorite trade plugin thanks to the community giving there feedbacks, suggestions and involvement on updates

Be also part of the progress by joining our [discord channel](https://discord.gg/fyabsMF)
