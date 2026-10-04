# astrbot-plugin-randomtoken

AstrBot插件：随机Token生成与管理工具

## 功能介绍
- 生成指定长度和数量的随机Token
- 导出Token为JSON文件
- 查看Token列表（图片形式）
- 提供使用教程

## 安装方法
1. 下载本插件并放入AstrBot插件目录
2. 重启AstrBot
3. 在管理面板配置插件参数

## 命令说明
### 生成随机Token
```
/生成随机token 序号 安全密码 备注
```
示例：`/生成随机token 001 mypassword 我的API密钥`

### 导出Token
```
/导出token 序号 安全密码 confirm
```
示例：`/导出token 001 mypassword confirm`

> **注意**：导出后该序号的token记录将自动删除，必须添加`confirm`参数确认操作。

### 删除Token
```
/删除token 序号
```
示例：`/删除token 001`

### 查看Token列表
```
/查看token列表
```

### 查看使用教程
```
/随机生成token教程
```

## 配置说明
在插件配置页面可调整以下参数：
- token长度：默认30位
- token条数：默认10条
- 是否开启特殊符号：默认开启
- 是否开启随机大小写：默认开启

## 反馈与支持
插件反馈群：928985352
进群密码：神人desuwa

## 作者信息
- 作者：LumineStory
- 版本：1.0.0
- 仓库地址：https://github.com/oyxning/astrabot-plugin-randomtoken

## 许可证
本插件采用AGPL-v3开源许可证。详情请参见[GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html)。

> 注：作为AstrBot生态插件，本项目遵循主项目的开源协议要求，确保衍生作品的开源兼容性。
>
> ## 💡 联系作者

如有紧急问题，请联系邮箱：shy0074@tongujiyu.cn
