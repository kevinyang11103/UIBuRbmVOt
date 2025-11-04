# 前言

欢迎来到本药品管理系统项目！这是一个基于Java语言和MySQL数据库的实战项目，适用于计算机毕业设计。在这个项目中，我们运用了Spring Boot框架、JS、Vue和CSS3等技术。以下将为您详细介绍本项目的相关内容。

# 内容介绍

药品管理系统是一个旨在帮助医疗机构高效管理药品信息的系统。通过本系统，可以实现药品的增删改查、库存管理、过期提醒等功能。本项目实战性强，覆盖了从前端到后端、从数据库设计到界面展示的全过程，让您在完成项目的同时，掌握实用的开发技能。

# 技术介绍

- **语言：** Java
- **使用框架：** Spring Boot
- **前端技术：** JS、Vue、CSS3
- **开发工具：** IDEA/Eclipse
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

# 核心代码

以下是本项目中的一段核心代码，展示了如何使用Java和Spring Boot实现药品查询功能：

```java
@RestController
@RequestMapping("/api/drugs")
public class DrugController {

    @Autowired
    private DrugService drugService;

    @GetMapping
    public ResponseEntity<List<Drug>> getAllDrugs() {
        List<Drug> drugs = drugService.getAllDrugs();
        return ResponseEntity.ok(drugs);
    }
}
```

# 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/287661/36/24731/143452/689e0f0fFc09709cd/144a777b9f9a5d23.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/294826/24/12970/19338/689e0eedFe36e26c4/37d01836d19c04d7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323575/9/4759/99343/689e0eeeF5331f1ec/fe116bf451f2a41c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/315456/27/26157/29327/689e0eefF7f1a33f2/293227f882783cd7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323843/34/4703/34750/689e0ef1Fed316349/b56cf743c2a47951.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/292036/17/19887/30650/689e0ef1F3025b184/7235f7accb8cc4e5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/309142/13/26718/58270/689e0ef3F59b90c68/01e6c6b69c704d63.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/314923/33/26231/46813/689e0ef4Fb0b21cc0/cd9949e1f2472d3c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/314037/10/26166/44932/689e0ef5F8308d25f/d6e5fcb48ad33493.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/308439/40/26568/72005/689e0ef9Ff73115a6/ad185ab9f8716b72.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
