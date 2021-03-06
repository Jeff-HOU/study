# study-app-weather #

天气APP
## 参考链接 ##

UI 资源 [https://www.zcool.com.cn/work/ZMzAzMTcxNDg=.html](https://www.zcool.com.cn/work/ZMzAzMTcxNDg=.html)、[https://www.zcool.com.cn/work/ZMjgyOTA4NDA=.html](https://www.zcool.com.cn/work/ZMjgyOTA4NDA=.html)、[https://www.zcool.com.cn/work/ZMjAyNzkzNTY=.html](https://www.zcool.com.cn/work/ZMjAyNzkzNTY=.html)

第三方 API 文档 [https://tianqiapi.com/index/doc](https://tianqiapi.com/index/doc)

## 概述 ##
### 现状 ###
查看天气的应用，目前手机自身也能够查看天气，但是不能满足需求；比如不能查明一个星期内的天气哥哥时段，每次都是需要去百度进行查询

### 相近产品 ###
http://www.pc6.com/iphoneh/weather/

彩云天气

墨迹天气

天气君

2345天气王等等

### 痛点、不足 ###
那些APP是单独的天气应用，本应用的天气只是其中的一个功能
后期会整合其他功能。

### 初衷及目标 ###
简单直接
友好
言论自由（可以留言反馈）
希望被喜欢

## 专业术语 ##

| 术语名称 | 术语详细解释说明     |
| -------- | -------------------- |
| 游客     | 未注册未登录的访问者 |

## 角色 ##

| 角色名称 | 角色功能说明                                     |
| -------- | ------------------------------------------------ |
| 游客     | 不登录直接访问，没有登录态直接使用里面提供的功能 |
| 用户     | 已注册用户登录后使用，相对于游客会增加许多新功能 |
| 管理员   | 平台配置的管理员，维护应用的稳定健康运行         |



## 概要设计 ##

### 概要介绍 ###

基于Spring 全家桶实践（相关的技术栈引导 [https://github.com/bage2014/study](https://github.com/bage2014/study)

）实现的通用功能应用

### 功能概要 ###

| 父模块   | 子模块     | 功能项说明                             | 重要、紧急    | 进度  |
| ---------- | -------------------------------------- | ------------- | ------------- | ------------- |
| 天气预报 | 主页面      | 根据城市（默认定位），自动显示当前城市的24H天气预报 | 重要 + 紧急   | 0% |
|          | 一周天气 | 根据选择的城市，显示一周内的天气 | 重要 + 不紧急 | 100% |
|          | 15天天气   | 根据选择的城市，显示15天内的天气 | 重要 + 紧急 | 0% |
| 个人设置 | 城市列表 | 用户可以选择自己的常用城市，并进行记录 |  | 0% |
| |  | 个人尝试的增删查 |  | 0% |
| | | 模型抽取，API接口抽取和实现 | | 30% |
| | | 自动定位当前城市 | | 0% |

## 详细设计 ##
## 权限 ##

| 功能名称               | 读角色 | 写角色 | 备注                 |
| ---------------------- | ------ | ------ | -------------------- |
| 天气预报模块下所有功能 | 游客   | 无     | 所有使用者都可以使用 |

## 评估 ##

### 风险 ###

| 风险名称            | 严重性必要性 | 处理对策                   | 备注 |
| ------------------- | ------------ | -------------------------- | ---- |
| 第三方API的可靠程度 | 严重+ 必要   | 多几个备胎，前期先集成一个 |      |
| UI页面交互体验      | 严重+ 必要   | 先出功能，后改进体验       |      |

### 优势 ###

#### 天时地利 ####

- 行业

  1. 进入障碍较小，谁都能做

  2. 市场状态一般，不算刚需
  3. 供应商议价较弱，无议价
  4. 代替品威胁的大小，很多很多

- 企业

  暂无

- 时政（大势）

  暂无

#### 人和 ####
- 团队

自己是发起人，有激情有干劲

## 规划 ##

先最好基本功能，后改进页面体验

## 其他 ##

## 其他 ##

暂无








