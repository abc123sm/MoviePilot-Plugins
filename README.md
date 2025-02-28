# MoviePilot-Plugins 本仓库地址：
```
https://github.com/abc123sm/MoviePilot-Plugins/
```

## 安装说明

MoviePilot环境变量添加本项目地址，具体参见 https://github.com/jxxghp/MoviePilot

# 插件说明

## 防剧透媒体库刮削
基于官方插件库的**媒体库刮削**进行修改，刮削时不刮削电视剧分集的截图与简介、标题，避免剧透

原版
```
  <title>One ane Only</title>
  <plot><![CDATA[为了更加受人关注，无双提出自己想同时担任主唱。于是丽决定根据“无双的形象”创作一首歌曲。在铃玖的提议下，丽为了加深和无双的友谊，前去无双家里过夜。]]></plot>
  <outline><![CDATA[为了更加受人关注，无双提出自己想同时担任主唱。于是丽决定根据“无双的形象”创作一首歌曲。在铃玖的提议下，丽为了加深和无双的友谊，前去无双家里过夜。]]></outline>
```

修改版
```
  <title>第5集</title>
  <plot><![CDATA[]]></plot>
  <outline><![CDATA[]]></outline>
```