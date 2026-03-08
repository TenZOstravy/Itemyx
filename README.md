Itemyx

Itemyx is a powerful and completely free Minecraft plugin that allows server owners to create custom items, furniture, and resource pack models easily.

Unlike many other plugins, Itemyx does not lock features behind paywalls or demo limitations. The goal of the project is to provide a complete custom item and furniture system that is accessible to everyone.

Itemyx includes a built-in item editor, furniture system, resource pack tools, and optional compatibility with popular protection plugins.


---

Main Features

Custom Item System

Itemyx allows server owners to create fully customizable items.

You can edit:

item names

lore

enchantments

damage values

item flags

unbreakable status


Items can be managed through a modern GUI editor and stored safely inside a database.


---

Furniture System

Itemyx includes a complete furniture system based on modern Minecraft display entities.

Furniture features include:

placing custom item models as furniture

ownership system

player furniture limits

rotation system

preview before placement

block collision (solid furniture)

protection from placing multiple furniture in the same block


Furniture settings are stored globally per item ID, meaning once furniture is enabled for an item, all instances of that item will behave as furniture.


---

Ownership System

Each placed furniture object remembers the player who placed it.

This allows:

players to remove their own furniture

players to rotate their own furniture

server administrators to manage all furniture

safe multiplayer usage without griefing



---

Player Limits

Itemyx includes a configurable furniture limit system.

Server owners can define different limits for permission groups such as:

default players

VIP players

MVP players


This allows servers to reward players with higher furniture limits.


---

Protection Plugin Support

Itemyx integrates with common server protection plugins.

Supported plugins include:

WorldGuard

Residence

Multiverse-Core


These integrations are optional. If the plugin is not installed, Itemyx will continue working normally.

When protection plugins are installed, Itemyx respects region and world rules to prevent furniture placement in restricted areas.


---

Resource Pack Workflow

Itemyx includes built-in tools to simplify the creation of custom item models.

The plugin can help with:

generating resource pack structure

adding base models

adding custom item models

verifying pack files

creating zip files

generating SHA1 hashes

sending packs automatically to players


This makes it much easier to maintain custom item models for servers.


---

GUI Item Editor

Itemyx includes an intuitive GUI editor for managing items.

Using the GUI you can:

create new items

edit item metadata

rename items

manage item models

quickly give items to players


The editor is designed to be simple and efficient for server administrators.


---

Preview System

Before placing furniture, players can see a preview of where the furniture will appear.

This helps prevent mistakes and improves the building experience.

The preview system can be toggled on or off by players.


---

Debug and Maintenance Tools

Itemyx includes useful commands for server administrators.

These tools allow you to:

inspect furniture entities

remove orphan entities

debug placement problems

manage furniture globally


These commands help maintain a stable server environment.


---

Commands

Player Commands

/itremove
Remove your looked-at furniture

/itemyx rotate <angle>
Rotate your furniture

/itemyx myfurniture
Shows how much furniture you placed and your limit


---

Admin Commands

/itemyx
Open the Itemyx GUI

/itemyx reload
Reload plugin configuration

/itemyx give <player> <id>
Give a custom item

/itemyx info <id>
Show information about an item

/itemyx renameid <old> <new>
Rename an item ID

/itemyx export
Export items to file

/itemyx import
Import items from file


---

Furniture Commands

/itemyx furniture enable <id>
Enable furniture for an item

/itemyx furniture disable <id>
Disable furniture for an item

/itemyx furniture block
Toggle solid collision

/itemyx furniture allowplace
Toggle building inside furniture block

/itemyx furniture list
List furniture-enabled items

/itemyx furniture listplaced
List placed furniture

/itemyx furniture cleanup
Remove orphan entities

/itemyx furniture debug
Debug furniture entity


---

Resource Pack Commands

/itemyx pack init
Create pack structure

/itemyx pack zip
Create resource pack zip

/itemyx pack hash
Generate SHA1 hash

/itemyx pack send
Send resource pack to player

/itemyx pack verify
Check pack structure


---

Permissions

itemyx.admin
Full access to all commands

itemyx.player.place
Allow furniture placement

itemyx.player.remove
Allow removing own furniture

itemyx.player.rotate
Allow rotating own furniture

itemyx.player.myfurniture
Allow using /itemyx myfurniture

itemyx.limit.default
Default furniture limit

itemyx.limit.vip
VIP furniture limit

itemyx.limit.mvp
MVP furniture limit


---

Compatibility

Itemyx is designed for modern Minecraft servers.

Recommended server software:

Paper


Tested Minecraft versions:

1.21+


Optional integrations:

WorldGuard

Residence

Multiverse-Core


If these plugins are not installed, Itemyx will continue working normally.


---

Support

If you encounter any issues, bugs, or compatibility problems, please report them.

You can also request new features or improvements.

Support is available on the project Discord server.

Discord: https://discord.com/invite/NAx8HHFN2g


---

Contributing

Contributions are welcome.

If you would like to improve the plugin, fix bugs, or add new features, feel free to submit pull requests or open issues on GitHub.


---

Supporting the Project

Itemyx is completely free and developed in spare time.

If you enjoy the plugin and want to support development, you can buy me a coffee.

Your support helps keep the project active and allows new features to be developed.

Buy Me a Coffee: https://buymeacoffee.com/dreammister2


---

Future Plans

Planned improvements for Itemyx include:

furniture animations

sitting system

advanced model importing

addon furniture packs

improved editor tools

additional server integrations
