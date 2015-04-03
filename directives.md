# 基本指令语法 #

模板指令的基本语法为:
> <指令名称(执行条件)[参数设置].表达式(.指令指令作用参数[可选])>
> @{表达式}

> 详细的指令说明,参见 [首页](index.md)

|  模板内容  |  数据内容  |  生成内容 |
|:---------------|:---------------|:--------------|
|  <div>user's name\</div>    |  userName = "Tom"     |  <div>Tom</div>   |
|  <div>...</div>              |  text = "<b>hello</b>"     |  <div>&lt;b&gt;hello&lt;/b&gt;</div>  |
|  <div>...</div>  | userName = "Tom" | <div>Welcome Tom</div>  |
|  <div>...</div>  | userId=20 | <div>120</div> |