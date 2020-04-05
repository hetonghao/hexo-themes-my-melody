# hexo-themes-my-melody

基于[hexo-theme-melody](https://github.com/Molunerfinn/hexo-theme-melody)主题的修改版


## 集成音乐播放器aplayer组件
### 配置
```yaml
# Aplayer播放器配置
aplayer: 
  enable: true
  js: 
    - https://cdn.bootcss.com/aplayer/1.10.1/APlayer.min.js
    - https://cdn.jsdelivr.net/npm/meting@1.2.0/dist/Meting.min.js
  css: 
    - https://cdn.bootcss.com/aplayer/1.10.1/APlayer.min.css
  id: 4950985632 # 网易云歌单编号
  server: netease # 网易云
  type: playlist # 播放器类型
  fixed: 'false' # 吸附模式
  mini: 'false' # 迷你模式
  listFolded: 'true'
  width: 300px # 播放器宽度 xxxpx or xxx%
  order: list # 列表播放模式： list, random
  preload: none #是否预加载
```
### 展现效果

* 在page页面中nav与footer都显示，在文章页面中只显示footer

#### nav
![nav](https://tva1.sinaimg.cn/large/00831rSTgy1gdipqcenjej31j10u01l3.jpg)
#### footer
![footer](https://tva1.sinaimg.cn/large/00831rSTgy1gdipt7z61oj32hu0icgy5.jpg)