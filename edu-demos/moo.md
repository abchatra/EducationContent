# Moo

## Try the code:

```blocks
player.onChat("moo", function () {
    for (let index = 0; index < 5; index++) {
        mobs.spawn(COW, world(-268, 64, 134))
    }
})

player.onChat("moo2", function () {
    for (let index = 0; index < 5; index++) {
        mobs.spawn(COW, randpos(
        world(-273, 64, 129),
        world(-266, 64, 137)
        ))
    }
})
```