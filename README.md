# Android 项目包结构
以 PBF(Package By Feature) —— 按功能模块分包，使 package 内高内聚，package 间低耦合。

# 包结构详解
* App: 定义 Application 类
* Config.java 定义配置数据（常量）
* base 基础组件
* custom 自定义 view
* data 数据处理
    * DataManager.java 数据管理器，持有 local 数据，remote 数据和 cache 数据
    * local 本地数据源，比如：SP，Database，File
    * modle 定义 javaBean
    * remote 远程数据源
* feature 功能呢
    * feature0 功能 0 
    * feature1 功能 1
    * featuren 功能 n
* injection 依赖注入
* util 工具类
* widget 小组件