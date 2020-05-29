# YOLO_v2

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

> `YOLO_v2`算法实现

## 内容列表

- [YOLO_v2](#yolo_v2)
  - [内容列表](#内容列表)
  - [背景](#背景)
  - [安装](#安装)
    - [文档工具安装](#文档工具安装)
  - [用法](#用法)
    - [文档浏览](#文档浏览)
  - [主要维护人员](#主要维护人员)
  - [致谢](#致谢)
    - [引用](#引用)
  - [参与贡献方式](#参与贡献方式)
  - [许可证](#许可证)

## 背景

* [YOLO9000: Better, Faster, Stronger](https://arxiv.org/abs/1612.08242)
 
## 安装

### 文档工具安装

```
$ pip install -r requirements.txt
```

## 用法

### 文档浏览

有两种使用方式

1. 在线浏览文档：[YOLO_v2](https://yolo_v2.readthedocs.io/zh_CN/latest/)

2. 本地浏览文档，实现如下：

    ```
    $ git clone https://github.com/object-detection-algorithm/YOLO_v2.git
    $ cd YOLO_v2
    $ mkdocs serve
    ```
    启动本地服务器后即可登录浏览器`localhost:8000`

## 主要维护人员

* zhujian - *Initial work* - [zjZSTU](https://github.com/zjZSTU)

## 致谢

* [lufficc/SSD](https://github.com/lufficc/SSD)

### 引用

```
@misc{redmon2016yolo9000,
    title={YOLO9000: Better, Faster, Stronger},
    author={Joseph Redmon and Ali Farhadi},
    year={2016},
    eprint={1612.08242},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}

@misc{pascal-voc-2007,
	author = "Everingham, M. and Van~Gool, L. and Williams, C. K. I. and Winn, J. and Zisserman, A.",
	title = "The {PASCAL} {V}isual {O}bject {C}lasses {C}hallenge 2007 {(VOC2007)} {R}esults",
	howpublished = "http://www.pascal-network.org/challenges/VOC/voc2007/workshop/index.html"}

@misc{pascal-voc-2012,
	author = "Everingham, M. and Van~Gool, L. and Williams, C. K. I. and Winn, J. and Zisserman, A.",
	title = "The {PASCAL} {V}isual {O}bject {C}lasses {C}hallenge 2012 {(VOC2012)} {R}esults",
	howpublished = "http://www.pascal-network.org/challenges/VOC/voc2012/workshop/index.html"}
```

## 参与贡献方式

欢迎任何人的参与！打开[issue](https://github.com/object-detection-algorithm/YOLO_v2/issues)或提交合并请求。

注意:

* `GIT`提交，请遵守[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/)规范
* 语义版本化，请遵守[Semantic Versioning 2.0.0](https://semver.org)规范
* `README`编写，请遵守[standard-readme](https://github.com/RichardLitt/standard-readme)规范

## 许可证

[Apache License 2.0](LICENSE) © 2020 zjZSTU
