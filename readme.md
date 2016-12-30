> 使用Laravel开发的简单DEMO，主要实现的txt小说文件的读取和API接口

- 基本实现的功能
    1. API提供：
        - TXT中按照1000字符进行一次切割并发送
        - TXT中每次请求会增加一页页码标签
        - 获取所有的书本信息
        - 对于每本阅读的书最近阅读的书，并且记录书签
        - 用户通过邮箱，密码，昵称等注册
        - 用户通过邮箱密码登录后可以获得token
        - 通过token验证可以进行数据的获取
    2. 后台管理：
        - 新增书籍上传，自动上传到publicbook中，需要使用UTF-8编码先转换txt（防止编码错乱）
        - 删除对应的书籍信息
        - 查看用户信息，并删除相应的用户信息
    3. 接口返回示例：
    ```
    {status:0,message:"ErrorMessage",data:""}
    {status:1,message:"",data:"ReturnData"}
    ```
- 其他详细使用与示例：
……
等会说~