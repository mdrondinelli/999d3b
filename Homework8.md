# Homework 8

1. How many elements (i.e. entries) are in the table t in the following code
snippet?

    ```lua
    local t = {1, 2, 3, 4, "a", "b", "c", "d", true, false}
    ```

1. What is the value of `t[7]` in the following code snippet?

    ```lua
    local t = {1, 2, 3, 4, "a", "b", "c", "d", true, false}
    ```

1. What is the value of `t[7]` in the following code snippet?

    ```lua
    local t = {
      [1] = false,
      [3] = true,
      [5] = false,
      [7] = true
    }
    ```

1. What is the value of `speed["brown fox"]` in the following code snippet?

    ```lua
    local speed = {
      ["brown fox"] = 89,
      ["lazy dog"] = 2
    }
    ```

1. What is the value of `melon["value"]` in the following code snippet?

    ```lua
    local melon = {
      name = "Melon",
      value = 4
      weight = 10
    }
    ```

1. What is the value of `melon.weight` in the following code snippet?

    ```lua
    local melon = {
      name = "Melon",
      value = 4
      weight = 10
    }
    ```

1. Describe what the function `someFunction` does in the following code snippet.

    ```lua
    local someFunction = function (item1, item2)
      if item1.value > item2.value then
        return item1
      else
        return item2
      end
    end
    ```
