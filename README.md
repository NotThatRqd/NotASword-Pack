# NotASword-Pack

This is a Minecraft resource pack for 1.20.1 that makes shields look like
swords and that when you block the shield it appears as though you are
sword-blocking from version 1.8 (pre combat update).

This resource pack was [originally](https://github.com/D3lta-2-1/NotASword) made by D3lta-2-1.

This is only a resource pack, the shield is still a shield, it just makes
the shield look like a sword. In order to make the shield look like a sword,
you must set its CustomModelData in its NBT.

| CustomModelData value | Sword type |
|-----------------------|------------|
| 2                     | Wooden     |
| 3                     | Golden     |
| 4                     | Stone      |
| 5                     | Iron       |
| 6                     | Diamond    |
| 7                     | Netherite  |

For example, to get a shield that
looks like a wooden sword, you must run this command:

```
/give @s minecraft:shield{"CustomModelData": 2}
```

![image](https://github.com/NotThatRqd/NotASword-Pack/assets/67846317/1a519920-8b32-498b-b4c2-a81668615207)
