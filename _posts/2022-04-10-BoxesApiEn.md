---


title: Boxes Api Useages EN
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

# Useage

code it at your code head

```lua
require("Boxes.lua")
```

FuntionName.Func() to use it

## Boxes Funtion

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

example

```lua
require("Boxes.lua")
local my_ped=Boxes.myPed()
```



