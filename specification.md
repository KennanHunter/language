bracket scopes
no semicolons
static typed
correlation with wasm types: (u32, u64, i32, i64)
powerful functional patterns (mapping, accumulation, )
lazy structures (processed at compile time)?
built in testing?
explicit parameter names in calls?

```ts
const function_idea = {
    // Even strings are lazy
    "string idea"
        .map {
            return it.toUpperCase()
        }
        .filter {}
}
```

have all pairs of brackets define functions

```ts
let func: Function = {};
```

# Function definitions

## Parameter-less

```ts
{
  print(5);
}
```

## With Parameters

```ts
{<gamer: i32, epic: f32>
    print(5)
}
```

## With Parameters and return value

```ts
{<gamer: i32, epic: f32, returns f32>
    print(5)
}
```

## Immediately Invoked

Because of we moved parameters inside the brackets it is now possible to invoke the function without wrapping the definition in parenthesis

```ts
{
    print(5)
}()
```
