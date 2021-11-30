<h1 align="center">
Quantumult-X-MyRules
</h1>

<h4 align="center">这里是リンホア的QuantumultX自建规则仓库，请随意取用。</h4>

## Features

- 包含了自己制作的图标（Quantumult X策略组Icon尺寸：108x108）
- 为Princess Connect! Re:Dive、Minecraft创建了专属分流策略
- 为Princess Connect! Re:Dive、Minecraft基岩版策略组创建了Icon

## Introduce

- 分流规则在[Script](https://github.com/SakuraRinhoa/Quantumult-X-MyRules/tree/main/Script)文件夹下
- 策略组Icon在[Icon](https://github.com/SakuraRinhoa/Quantumult-X-MyRules/tree/main/Icon)文件夹下
**- 引用分流规则示例：**
需要在配置文件的[filter_remote]项添加如下代码：

`https://raw.githubusercontent.com/SakuraRinhoa/Quantumult-X-MyRules/main/Script/Minecraft%20C%2B%2B.list, tag=Minecraft, force-policy=🎮 Minecraft,enabled=true`
    
同时需要在[policy]下添加如下代码,即可为示例的Minecraft分流规则手动选择节点，同时显示本项目提供的策略组Icon：

`static=🎮 Minecraft, proxy, img-url=https://raw.githubusercontent.com/SakuraRinhoa/Quantumult-X-MyRules/main/Icon/Minecraft.png`

以上代码实现的效果如下图：

![This is an image](https://raw.githubusercontent.com/SakuraRinhoa/Quantumult-X-MyRules/main/README_Files/Quantumult%20X%20%E7%AD%96%E7%95%A5%E7%BB%84%E7%A4%BA%E4%BE%8B-1.jpg)

详细的编写配置文件教程，请参考其他网站

## To-Do

- [ ] ？
- [ ] ~~早睡早起~~

## Other

<h4>有其他想法欢迎联系。</h4>
