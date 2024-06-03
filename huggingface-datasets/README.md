---
license: cc-by-nc-4.0
language:
- zh
pretty_name: Linux 中国文章数据集
size_categories:
- 10K<n<100K
---
---
license: cc-by-nc-4.0
---

# Linux 中国原创文章/译文数据集

这个数据集为 Linux 中国原创技术文章 + 翻译技术文章的数据集，提供了文章标题、内容等多个字段。


## Dataset Details

### Dataset Description


- **Language(s) (NLP):** 中文
- **License:** cc-by-nc-4.0


## Dataset Structure

- id：文章ID
- title: 文章标题
- author: 文章作者
- fromurl: 文章源地址（仅翻译类文章有）
- summary: 总结
- excerpt： 摘要
- pic: 头图（缩略图版）
- largepic：头图（大图版）
- titlepic：是否有头图，可以渲染用。
- islctt：是否是 LCTT 文章（翻译文章）
- selector：选题人员，值为 Github ID
- translator：翻译人员，值为 Github ID
- reviewer：校对人员，值为 Github ID
- tags：文档标签
- category：文档所属目录
- count：计数
  - viewnum: 访问量
  - commentnum： 评论量
  - favtimes： 收藏量
  - sharetimes： 分享量
  - likes： 喜欢量
- comments_data： 评论数据
  - postip：评论 IP
  - dateline：评论时间
  - message：评论内容
  - username：评论名
  - repcids：回复的评论的 ID
- related： 相关文章的 ID
- date：发布日期
- updated：最后更新日期
- permalink：永久链接（Linux.cn 上的链接）
- content：文章内容


## 图片素材下载 & Markdown 版下载

上述文章内容中的图片素材可访问下方链接获取，attachment.zip 即为对应的图片。

### GitHub

https://github.com/Linux-CN/archive/releases/tag/release

### 百度网盘

链接: https://pan.baidu.com/s/1i7DTuf_umPkkleHFtdmZJA?pwd=lccn
提取码: lccn

## Dataset Card Contact

bestony <bestony@linux.com>