fasttest在macaca、appium、selenium的基础上做了一层关键字的封装与解析，通过yaml编写自动化用例，支持关键字联想输入、步骤单步debug，即使无代码基础的同学也已可以很快上手自动化测试；

![](https://img.shields.io/badge/python-3.7-green) 

## 运行示例
测试用例
```
    - click('标签页')
    - click('新建标签页')
    - input('URL', 'https://github.com/Jodeee')
    - sleep(3)
    - click('fasttest')
    - sleep(5)
```

结果报告

![image](https://cdn.nlark.com/yuque/0/2020/png/499819/1592730563272-b1519a95-e718-4166-8129-baa829408405.png?x-oss-process=image%2Fwatermark%2Ctype_d3F5LW1pY3JvaGVp%2Csize_20%2Ctext_am9kZWVl%2Ccolor_FFFFFF%2Cshadow_50%2Ct_80%2Cg_se%2Cx_10%2Cy_10)


## 框架介绍

[框架介绍](https://www.yuque.com/jodeee/kb/ywq037)

## 问题收集

[issues](https://github.com/Jodeee/fasttest/issues)
