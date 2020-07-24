MiraiPixiv
=====

支持**查看pixiv榜单**，**查看指定id插画**，**随机抽选指定关键字插画**，**随机抽选书签插画**，**随机抽选指定画师插画**功能。

## 使用方式

> 1.  配置mirai-console与mirai-api-http（参见：https://mirai-py.originpages.com/mirai/use-console.html）
> 2. `pip install -r requirements.txt`
> 3. `python bot.py`

初次使用请将`settings.template.json`拷贝为`settings.json`，并填写mirai与pixiv栏目的信息。

- 看看榜*1-20*：查看pixiv榜单的第1到第20名（可省略*1-20*）
- 来张*FGO*图：搜索关键字*FGO*，从搜索结果随机抽选插画
- 来张*森倉円*老师的作品：搜索画师*森倉円*，从该画师的插画列表里随机抽选插画
- 看看图*114514*：查看id为*114514*的插画
- 来张私家车：从书签中随机抽选插画

触发词可以在设置中更改。

## Special Thanks

[pixivpy](https://github.com/upbit/pixivpy)

[python-mirai](https://github.com/NatriumLab/python-mirai)

## LICENSE

[AGPLv3](https://github.com/ssttkkl/MiraiPixiv/blob/master/LICENSE)