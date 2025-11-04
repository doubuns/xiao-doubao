
# doubao
https://love.doubao.fan/

豆包去了喵星，以此来纪念豆包短暂的一生.



# 如何使用
## 所需环境
```shell
node v20.19.5
yarn v1.22.22
heic # 如果有heic格式的图片转jpg才需要
```

## 初始项目
- 将照片放到 src/assets 目录下

- 执行 `yarn install` 构建项目

- 执行 `yarn build:photo-rename` 来重命名图片名称, 便于代码匹配文件日期

- 执行 `yarn build:photo-clean-gps` 移除图片的定位信息

## 本地预览

- 执行 `yarn build:code` 来构建

- 本地启动 `yarn start`

# 感谢
- 此项目fork于[Caldis/meow](https://github.com/Caldis/meow)
