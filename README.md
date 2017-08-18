# MathJaxConfiguration
MathJax公式自动编号

使用方法：

1. 下载文件替换原有的mathjax.swig文件

2. 在next的配置文件中搜索MathJax，更改如下：

```
# MathJax Support
mathjax:
  enable: true
  per_page: true
  cdn: //cdn.bootcss.com/mathjax/2.7.1/latest.js?config=TeX-AMS-MML_HTMLorMML
```
