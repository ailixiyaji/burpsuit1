## Burpsuit四种爆破模式
> ### Sniper
> 针对一个变量爆破
> ![image](https://github.com/ailixiyaji/elysia/blob/main/github240104/202104241121181.png)

> ### Battering ram
> 将多个变量使用同一字典爆破

> ### Pitch fork
> 多变量使用各自字典相对应爆破
> 若有admin/passworrd,admin字典1000字符串，password字典2000字符串，burp爆破1000次
> ![image](https://github.com/ailixiyaji/elysia/blob/main/github240104/20210424113403834.png)
> ![image](https://github.com/ailixiyaji/elysia/blob/main/github240104/20210424113703747.png)

> ### Cluster bomb
> 多变量使用各自字典随机排列爆破
> 若有admin/passworrd,admin字典1000字符串，password字典2000字符串，burp爆破1000*2000次
> ![image](https://github.com/ailixiyaji/elysia/blob/main/github240104/20210424114054345.png)

## 附加社工字典生成软件（需配置java环境）
https://github.com/ailixiyaji/elysia/blob/main/github240104/safe6pwd.jar
