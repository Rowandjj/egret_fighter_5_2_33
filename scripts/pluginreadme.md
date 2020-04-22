
params 参数
{ projectName: 'Fighter_upgrade_2.5_logo',
  projectRoot:
   '/Users/nero/Documents/EgretProjects/Fighter_upgrade_2.5_logo/',
  debug: true,
  command: 'publish',
  target: 'tbgame',
  version: '200415154540',
  projectConfig:
   { entryClassName: '"Main"',
     orientation: '"auto"',
     frameRate: '60',
     scaleMode: '"showAll"',
     contentWidth: '480',
     contentHeight: '800',
     showPaintRect: 'false',
     showFPS: 'false',
     fpsStyles: '"x:0,y:0,size:30,textColor:0x00c200,bgAlpha:0.9"',
     showLog: 'true',
     logFilter: '""',
     textureScaleFactor: '1',
     maxTouches: '2' } }

+ 我们要做的事情
1. 创建淘宝小程序项目，done
2. 引入 http://gitlab.alibaba-inc.com/Cicada/egret-appx-component 项目
3. 引入资源  mini.project.json 
4. 要不要把 js 代码移动到 pages/${target}/ 下 
5. pages/${target}/js各个文件插入内容egre
3.x 
```js 
{
  
  "include": [
    "**/*.json",
    "**/*.exml",
    "**/*.js"
  ]
}
```