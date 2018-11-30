# 在西信

## 部分API

1、获取公告的API：
https://gwrblog.top:8443/Sdy/GetNotice

2、获取成绩的API：
https://gwrblog.top:8443/Sdy/GetScore?name=学生姓名&sfz=身份证号

3、获取毕业设计题目的API：
https://gwrblog.top:8443/Sdy/getGraduationProjectQuestion?pageStartNum=起始值&pageEndNum=终止值

4、学生选择毕业设计题目的API
https://gwrblog.top:8443/Sdy/ChoseQuestion?questionId=问题的ID&studentName=选择该题的学生&studentCard=身份证号&studentPhone=手机号

5、限制学生只能选择一道题的API：
https://gwrblog.top:8443/Sdy/ChoseOneQuestionServlet?name=学生姓名&sfz=身份证号

6、获取体育部公众号近期10条文章的API：
https://gwrblog.top:8443/Sdy/GetSportArticle

7、获取学校新闻的API：
https://gwrblog.top:8443/Sdy/GetNews

8、校验学生身份，且添加手机号的API:
https://gwrblog.top:8443/Sdy/CheckStudentServlet?name=学生姓名&sfz=学生身份证号