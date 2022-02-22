# jd_AutoComment
# 本分支为stable分支，功能基本可用，但更新可能不及时，请自行选择
## 鸣谢
感谢[qiu-lzsnmb](https://github.com/qiu-lzsnmb)大佬的脚本和[Zhang Jiale](https://github.com/2274900)大佬的评论爬虫

源库链接：[自动评价](https://github.com/qiu-lzsnmb/jd_lzsnmb)
[评论爬虫](https://github.com/2274900/JD_comment_spider)

### 本脚本只是对以上两位的结合以及魔改，用于解决评论文不对题的问题。经测试，本脚本能初步解决这一问题。

## 思路

由爬虫先行对商品的既有评价进行爬取，在此基础上进行自己的评价

## 使用方法

在终端中执行：

```bash
git clone https://github.com/Dimlitter/jd_AutoComment.git
cd jd_AutoComment
pip install -r requirements.txt
```

获取电脑版ck后填入配置文件 `config.yml` 

需要填入如下内容：

```yml
user:
  cookie: '<Cookie>'
```

最后运行 `auto_comment_plus.py` ：

```bash
python3 auto_comment_plus.py
```

**注意:** 请根据设备环境换用不同的解释器路径，如 `python`、`py`。

**另外**：此分支版本不支持命令行参数，开发者请选择 `main分支`

> 此脚本需要的依赖较多，需自行安装

## 声明

本项目为Python学习交流的开源非营利项目，仅作为程序员之间相互学习交流之用。

严禁用于商业用途，禁止使用本项目进行任何盈利活动。

使用者请遵从相关政策。对一切非法使用所产生的后果，我们概不负责。

本项目对您如有困扰请联系我们删除。

## 证书

![AUR](https://img.shields.io/badge/license-MIT%20License%202.0-green.svg)
