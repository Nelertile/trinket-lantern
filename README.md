# Trinket Lantern

![server, only](https://img.shields.io/badge/environment-server%20only-e61a1a)
![datapack and mod](https://img.shields.io/badge/project%20type-datapack-39951d)

Requires [Radiant Gear](https://modrinth.com/mod/radiant-gear) and [Trinkets API](https://modrinth.com/mod/trinkets)

---

Trinket Lantern is a small datapack I made to make it easier to use the [Radiant Gear](https://modrinth.com/mod/radiant-gear) mod, as that mod doesn't include a trinket slot for lanterns.

---

List of currently supported lanterns:

- Lantern : _minecraft:lantern_
- Soul Lantern : _minecraft:soul_lantern_

---

## How to add modded lanterns:

1. Download source from the [Github](https://github.com/Nelertile/trinket-lantern)
2. Navigate to `data/trinkets/tags/items/legs/belt.json`
3. Add the lanterns ID to the following section:

```json
"values": [
      "minecraft:lantern","minecraft:soul_lantern" <-- add items here
    ]
```

4. Save the file and put the datapack on your world
5. Reload datapacks using `/reload`
