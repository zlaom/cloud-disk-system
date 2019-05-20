## 2019/5/17
- 文件分片上传基础功能实现
## 2019/5/16
- 文件选择逻辑
- 目录面包屑导航
## 2019/5/15
- 解决MySQL连接池问题
- 前端文件列表渲染
- 前端基本界面完成
## 2019/5/11
### TODO
- antd响应式布局怎么写？
### COMPLETE
- 状态树
  clouddisk--navigation--avatar
          |           |--links
          |           |--disk used
          |--tool bar--option
          |         |--search
          |         |--file path
          |--files--folder
                 |--file
## 2019/5/10
### COMPLETE
- 重学react、flux、reduce
- react服务端渲染
- CORS使用跨域获得服务器数据
- 使用redux-thunk中间件
### TODO
- 设计store树
## 2019/5/9
### COMPLETE
- 完成文件秒传
- 完成文件断点续传
- 文件分片传输时生成temp类型文件
- 完成文件传输完成后修改文件为对应后缀名
- 设计主要功能模块
  - 1用户注册模块
  - 2文件列表显示、一定类型文件预览模块
  - 3文件查看模块
  - 4文件上传模块
  - 5文件下载模块
  - 6数据库，数据库连接模块
  - 7文件加标签
  - 管理员端功能
### BUG
- 文件取消上传时候不能删除相应文件的
### TODO
- 上传速度显示
- 数据库写入
- 开始前端代码编写 done
- 设计State

## 2019/5/5 - 2019/5/8
- 拼多多笔试准备
- 拼多多笔试
- 360面试准备
- 奇安信面试

## 2019/5/3
- 后台数据库数据获取API
- 添加session
- 用户注册
- 用户登陆
- 用户登出
- 用户验证

## 2019/5/5
### COMPLETE
- 文件分片上传demo
- 多文件分片上传
### TODO
- 文件秒传
- 文件断点续传
- 取消下载
- 暂停下载

## 2019/5/4
- 文件上传流程 选择文件=>获取文件MD5=>对比服务器文件MD5=>分片=>分片上传=>写入分布式存储系统=>写入数据库=>返回成功
- 获取上传文件信息
- 计算文件MD5值
- 文件上传进度显示
- 通过formidable简单上传文件到服务器
- GitHub创库
