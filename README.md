# lua-formatter-configs

A set of different formatter configs for [LuaFormatter](https://github.com/Koihik/LuaFormatter).

# Common Reading

```lua
local data = {
    example1 = 1,
    example2 = 2,
    example3= 3
}

function exampleFunctionLargeName(param1, param2, param3)

    print("This is a short string with double quotes!")

    local values = {v1 = 1, v2 = 2, v3 = 3}
    print("\"This is a multiple quotes string\"")

    local largeValues = {
        value1 = "largeValue",
        value2 = "largeLargeValue",
        value3 = "evenMoreLargeValue",
    }

end

exampleFunctionLargeName("this is a really large invocation", "of a function with some",
                         "really large params")
```

This format is based in most common
