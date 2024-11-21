# Intro

Hey,

You are looking to reward your player day after day? Well just get the plugin here and you'll be all fine.


In the case where the player still be here more than a day, I just create a command to display the UI

# Command 
* /daily

# Config

```json
{
  "Item": [
    {
      "ItemName": "hat.wolf",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "fogmachine",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "strobelight",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "kayak",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "minihelicopter.repair",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "scraptransportheli.repair",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "workcart",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.grenadelauncher.buckshot",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.grenadelauncher.he",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.grenadelauncher.smoke",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "arrow.hv",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "arrow.wooden",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "arrow.bone",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "arrow.fire",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.handmade.shell",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.nailgun.nails",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.pistol",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.pistol.fire",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.pistol.hv",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rifle",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rifle.explosive",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rifle.incendiary",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rifle.hv",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rocket.basic",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rocket.fire",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rocket.hv",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.rocket.smoke",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.shotgun",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.shotgun.fire",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "ammo.shotgun.slug",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "door.double.hinged.metal",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "door.double.hinged.toptier",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "door.double.hinged.wood",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "door.hinged.metal",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "door.hinged.toptier",
      "MinQuantity": 1,
      "MaxQuantity": 100
    },
    {
      "ItemName": "door.hinged.wood",
      "MinQuantity": 1,
      "MaxQuantity": 100
    }
  ],
  "CUI": {
    "AnchorMin": "0 0",
    "AnchorMax": "1 1",
    "BackgroundImage": "https://images4.alphacoders.com/819/819162.jpg",
    "BackgroundColor": "0 0 0 0"
  }
}
```

I didn't push the full file as it was really long code like there are 491 items actually ah ah

# Lang file :

```json
{
  "Error": "To much error while generating ItemData, please check your config.",
  "WrongItem": "Item {0} doesn't exist.",
  "Dropped": "You don't have enough space in your inventory, just dropped to your feets.",
  "Inventory": "Just added the reward to your inventory.",
  "CantPick": "You already choose a reward for today",
  "NewDay": "It's a new day, grab your reward."
}
```
