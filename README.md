# PublicDependOnVersionManager

公共依赖版本管理

## base_build.gradle

    application和library模块通用的基本配置


## build_application.gradle


    用于application模块，减少大部分冗余代码

## build_library.gradle

    
    用于library模块，减少大部分冗余代码


## config.gradle


    各个库版本的管理

## 关于signingConfigs下签名文件放置问题

    
    各个项目下放一个module.keystore签名文件即可，其他已经在配置文件中配好。
    密码统一123456，Alias为debug