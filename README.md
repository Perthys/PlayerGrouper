# PlayerGrouper
Groups players into their respective region, this was made for target finding for "AOE" Attacks for bots

```lua
local Groups = Group:Form({
    Visualize = true;
    GroupableRange = 10;
    IgnorePlayerList = {}
})

for _, Group in pairs(Groups) do
    print(Group.PlayerCount)
    print(Group.Players)
    print(Group.Center)
    print(Group.Distance)
    print(Group.Part);
end
```

![Example](https://i.gyazo.com/45e9fa745fef53e866dea5ce4fdfaf00.mp4)
