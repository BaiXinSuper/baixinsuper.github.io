---


title: Boxes Api用法
date: 2022-04-10 10:30:00 +0800
categories: [Api]
tags: [Lua]
pin: false
author: 欣欣

toc: true
comments: true
typora-root-url: ../../BaiXinSuper.github.io
math: false
mermaid: true

---



---

# 用法

把这行代码写入你的lua文件头部

```lua
require("Boxes.lua")
```

使用->方法名.方法() 调用

## Boxes 方法

```lua
Ped/Int/Entity  myPed()
Veh/Int/Entity  myVeh()
V3              myPos()
float           myHeal()
float           MaxHeal(Ped who)
void            HalfGod(String name,Int Parentid)
string          getIp(Int pid)
array<int>      whoIsSpectMe()
array<int>      whoIsAimMe()
array<int>      tokenSort()
```

例子

```lua
require("Boxes.lua")
local my_ped=Boxes.myPed()
```



