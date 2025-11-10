# 前言

欢迎来到我们的研知识题库小程序项目！这是一个基于SSM+SpringBoot的微信小程序，旨在为广大研究生提供一个便捷、高效的学习平台。在这里，你可以查找各类题型、刷题、查看答案解析等。本项目完全开源，欢迎各位开发者共同参与，共同进步！

# 内容介绍

研知识题库小程序包含以下核心功能：

1. 题库分类：根据学科、题型、难度等维度进行分类，方便用户快速找到所需题目。
2. 刷题模式：支持顺序刷题、随机刷题、模拟考试等多种模式，满足不同用户需求。
3. 答案解析：每道题目都附有详细答案解析，帮助用户理解解题思路。
4. 错题本：自动收集用户错题，便于用户查漏补缺。
5. 个性化推荐：根据用户刷题记录，推荐适合的题目，提高学习效率。

# 技术介绍

本项目采用以下技术栈：

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一段核心代码示例：

```java
// 查询题库列表
@RequestMapping("/queryQuestionList")
public List<Question> queryQuestionList(@RequestBody QuestionQueryVO questionQueryVO) {
    // 参数校验
    if (questionQueryVO.getSubjectId() == null || questionQueryVO.getQuestionType() == null) {
        throw new CustomException("参数错误");
    }
    // 调用service层方法查询题库列表
    return questionService.queryQuestionList(questionQueryVO);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/325211/35/19733/77302/68c5a9d9Fc139504a/bb7c1d010b143c17.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339208/15/10384/12029/68c5a9b1Fabd9417b/a0f036590e22f65b.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/334954/31/12949/10884/68c5a9b1F5d6524b9/fa7db260ff1c8cd1.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339223/29/10452/17212/68c5a9b2F35d02016/9f0e4f83b187594b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/346592/23/3123/9943/68c5a9b2F948dc137/0b6c3868e4f6e4e2.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324592/9/19771/15521/68c5a9b2F14d67b54/5c289a6e33170e8a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326602/2/19728/12123/68c5a9b2F341d0e02/15b10c078b05b00c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339913/9/10472/54177/68c5a9b3F50ee5254/1bd4ef0c8db5a75a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/349976/9/3048/51354/68c5a9b3F9fbaffd5/ee2c6b0623912f5e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/332405/40/12851/33676/68c5a9b4F5dbb7829/074552b695dd0691.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
