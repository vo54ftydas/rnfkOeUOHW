# 前言

随着新冠疫情的蔓延，对于疫情信息的及时、准确、高效管理显得尤为重要。为此，我们开发了一套基于Spring Boot的疫情信息管理系统。本系统采用Java语言，集成了多种前沿技术，旨在为用户提供一个完善、易用的疫情信息管理平台。以下是该项目的详细介绍。

## 内容介绍

本项目是一款基于Spring Boot的疫情信息管理系统，主要功能包括疫情数据采集、数据分析、数据查询、数据统计等。通过本系统，可以实现对疫情信息的全方位、多角度管理，为政府、企业、医疗机构等提供有力支持。此外，系统界面简洁、操作方便，能够满足各类用户的需求。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的一部分核心代码，展示了如何实现疫情信息的查询功能：

```java
@RestController
@RequestMapping("/api/v1/covid19")
public class Covid19Controller {

    @Autowired
    private Covid19Service covid19Service;

    @GetMapping("/query")
    public ResponseEntity<List<Covid19Info>> queryCovid19Info(@RequestParam("province") String province) {
        List<Covid19Info> covid19Infos = covid19Service.queryCovid19Info(province);
        return ResponseEntity.ok(covid19Infos);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/292008/5/22577/229415/689de8d5Fe81e8cd1/56b9806f495d30a0.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/310364/12/26299/38148/689de8bdF67db651a/da095dbb9aaf673e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/314634/1/25308/200580/689de8bdF7c48d802/124034753807896e.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/314957/14/26603/42658/689de8bdF543bc870/45d7091a15567164.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/294744/4/25423/44867/689de8beF50af858b/2ac722bfd07269d8.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327575/26/4528/45057/689de8bfFe49e5c6c/86b403fa6653a9ed.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/288291/10/23436/71465/689de8c0F7925c11c/9b46ce604c53084b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/320978/15/24419/50432/689de8c0Fbfbe2658/95d076698d57b6b8.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/310233/26/25818/40141/689de8c1F4d4eddea/c19574ff3ca4f3f7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325621/10/4434/38192/689de8c1F2817935f/ffb73cde99d6e116.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
