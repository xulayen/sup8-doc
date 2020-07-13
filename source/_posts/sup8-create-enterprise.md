---
title: 基于超8创建企业号操作流程
---

# 运营号登录

> 运营号登录地址：http://host8.yesno.com.cn/home/OprationLogin
> 帐号/密码：yxceshi/yxceshi@2020

![avatar](/images/1.jpg) 

## 创建企业帐号

*企业号管理*->*新增企业号*->*填写企业信息*

![avatar](/images/2.png) 

*填写表单：企业信息*

![avatar](/images/3.jpg) 


## 分配企业权限

*企业号管理*->*搜索企业号名称*->*点击*`管理`

![avatar](/images/4.jpg) 

*点击*`添加授权产品`

![avatar](/images/5.jpg) 

*根据企业业务勾选功能菜单*

![avatar](/images/6.jpg) 

![avatar](/images/7.jpg) 


## 创建系统管理员用户

*创建管理员用户*

![avatar](/images/8.jpg) 

![avatar](/images/9.jpg) 


## 码制配置

*企业快速配置*->*企业快速配置*->*搜索企业名称*->*快速配置*

![avatar](/images/10.jpg) 

*选择码制配置方块*

![avatar](/images/11.jpg) 

*为企业添加码制*

![avatar](/images/12.jpg) 

*选择合同内该企业码制*->*勾选码制*

![avatar](/images/13.jpg) 

*添加成功*

![avatar](/images/14.jpg) 

## 添加标签

*企业快速配置*->*企业快速配置*->*搜索企业名称*->*快速配置*->*添加标签*

![avatar](/images/15.jpg) 

*添加标签*

![avatar](/images/16.jpg) 

*填写标签信息*

![avatar](/images/17.jpg) 

*添加完成*

![avatar](/images/18.jpg) 

![avatar](/images/19.jpg) 

## 添加商品

![avatar](/images/20.jpg) 

*添加成功后，在企业号中可自行查看*

![avatar](/images/21.jpg) 

## 数码激活方式选择

![avatar](/images/22.jpg) 

*找到数码激活方式这一栏，根据企业实际情况勾选*

![avatar](/images/23.jpg) 


## 为企业设置所属商务人员

*平台管理*->*企业号管理*->*搜索企业号*->*设置所属商务人员*

![avatar](/images/27.jpg) 

![avatar](/images/28.jpg) 


# 企业号登录

*企业号账号密码，使用运营号在创建企业用户时创建*

> 运营号登录地址：http://host8.yesno.com.cn
> 帐号/密码：dmddr/dmddr@2020

![avatar](/images/24.jpg) 

*登录进入之后，左侧的菜单为运营号为此企业分配的所有菜单，右侧为首次进入之后提示帐号密码，浏览器需要保存，默认点击保存即可！*

![avatar](/images/25.jpg) 

## 企业认证

![avatar](/images/26.jpg) 

*提交认证成功*

![avatar](/images/31.jpg) 

*进入运营号，在运营号中认证企业*

![avatar](/images/32.jpg) 

![avatar](/images/33.jpg) 

![avatar](/images/34.jpg) 

## 申请数码

*数码管理*->*物码管理*->*数码列表*->*申请数码*

> 提示：如何企业号为公有企业，则无法生码，只有私有企业才能生码！！

``` sql
-- 修改 IsSharedResource 字段为1，则为私有企业
select * from testsupercarrier_masterdata.t_base_enterprise x where  x.EnterpriseNo ='100924018799';
```

![avatar](/images/29.jpg) 

![avatar](/images/30.jpg) 

![avatar](/images/35.jpg) 

*数码列表信息*

![avatar](/images/36.jpg) 


# 商务帐号登录

> 运营号登录地址：http://host8.yesno.com.cn/home/OprationLogin
> 帐号/密码：shangwuceshi/shangwuceshi@2019

![avatar](/images/37.jpg) 

## 数码审核

*数码管理*->*数码审核管理*->*查看对应数码审核列表*->*审核*

![avatar](/images/38.jpg) 

## 数码生码

*数码管理*->*数码审核管理*->*查看对应数码审核列表*->*审核*->*生码*

![avatar](/images/39.jpg) 

![avatar](/images/40.jpg) 

*生码成功*

![avatar](/images/41.jpg) 

# 标签帐号登录

> 运营号登录地址：http://host8.yesno.com.cn/Home/ServicerLogin
> 帐号/密码：super8teamlabel02/ceshi123

![avatar](/images/42.jpg) 

## 下载数码解压包

*标签帐号登录*->*数码管理*->*数码列表*->*下载数码文件*

![avatar](/images/43.jpg) 

### 查看解压包解压密钥

> 复制并保存！

``` html
MDE1MTkxODEtZWZmZC00ODU3LWE4ZTUtMTQxNjg2ZjkwMmIy
ZVQrMUVvVVI5RStUbzFlSTBGaCtBWkNBSnlZcy9ZeFFBQUFB
QUFBQUFBQW0xa205dlN3V1BTRE5JV2FFdERNVW1PcGUrNnl3
bUVNUytRUWtoZ3VMaXoxajQxYVIvZTJR
```

![avatar](/images/44.jpg) 

![avatar](/images/45.jpg) 


### 解压下载的压缩包

> 解压规则请见下图

![avatar](/images/46.png) 

``` js
举例：
企业名称为：道达尔润滑油(中国)有限公司
解压包名称为：红运7400系列10W-40产品1000000_test.zip
则解压密码为：Dderhyzgyxgs-200713.H

```

> 解压后文件内容如

![avatar](/images/51.jpg) 

### 根据密码解密出文件数码

> 工具位置：$/客户项目/W/江苏王子制纸有限公司/20200227妮飘H5积分商城一期项目/项目文档/测试/测试数据/下载解密工具

![avatar](/images/47.png) 

![avatar](/images/48.jpg) 

![avatar](/images/49.png) 

![avatar](/images/50.jpg) 

> 格式如

``` html

0372636190824088,http://testh5.sup8.yesno.com.cn/?603726361908240889D731F,037801000001,http://testh5.sup8.yesno.com.cn/?60378010000017150EF
1537235083927773,http://testh5.sup8.yesno.com.cn/?615372350839277739A7A07,037801000002,http://testh5.sup8.yesno.com.cn/?6037801000002311FE5
0374957929732682,http://testh5.sup8.yesno.com.cn/?6037495792973268232550C,037801000003,http://testh5.sup8.yesno.com.cn/?603780100000359D6EC
6441994955038380,http://testh5.sup8.yesno.com.cn/?66441994955038380B1F556,037801000004,http://testh5.sup8.yesno.com.cn/?60378010000046937EF
5507298913689898,http://testh5.sup8.yesno.com.cn/?655072989136898981ECEC5,037801000005,http://testh5.sup8.yesno.com.cn/?60378010000050ACB26
4935812662812119,http://testh5.sup8.yesno.com.cn/?64935812662812119164720,037801000006,http://testh5.sup8.yesno.com.cn/?6037801000006456703

```

# 企业帐号分配子账号

## 创建角色

![avatar](/images/52.jpg) 

![avatar](/images/53.jpg)

## 为角色分配权限

![avatar](/images/54.jpg)

![avatar](/images/55.jpg) 

## 创建指定角色用户

![avatar](/images/56.jpg) 

![avatar](/images/57.jpg) 

# 活动涉及的表

``` sql
-- 中奖表
select * from testsup8_marketing_basic.t_sup8_act_e[企业号]_a[活动号]_winrecord;
-- 参与日志表
select * from testsup8_marketing_basic.t_sup8_act_e[企业号]_a[活动号]_participation;
```
