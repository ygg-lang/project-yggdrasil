

```ygg
@named_token_hook.insert(",")
@named_token_hook.remove(",")
//? 当出现如下字符串时, 替换为一个 token
//? 会生成匿名符号, 不会出现在 NodeList 中
@named_token_hook("{", "}","(", ")","[", "]")

@named_token()
```