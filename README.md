<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot_plugin_small_world
  
_✨ NoneBot 游戏王小世界现象小助手  ✨_
  
<a href="https://pypi.python.org/pypi/nonebot-plugin-small-world">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-small-world.svg" alt="pypi">
</a>

</div>


# 安装

* pip 
```
pip install nonebot_plugin_small_world
```

* nb_cli
```
nb plugin install nonebot_plugin_small_world
```


# 使用
```
nonebot.load_plugin('nonebot_plugin_small_world')
```


# 命令
**注：使用命令时需要加命令前缀**（举例中的命令前缀为 /，请根据情况替换）

* `sw/small_world/小世界 [卡组名] [卡牌]`  （需要先保存一个卡组）

实例：`/sw 不死均 灰流丽`

* `yi/ydk_input/ydk/卡组码 [卡组名]` 然后输入你的卡组ydk

实例：`/yi 不死均` ,等待bot回复，  `[ydk]`

* `sws/small_world_search/小世界搜索 [卡牌a] [卡牌c]` （a是里侧除外的手牌，c是要检索的卡牌，会回复可以当中介的卡牌b）

实例：`/sws 增殖的G 灰流丽`
