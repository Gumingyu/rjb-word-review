# 高中英语单词复习

> 谷sir · 高中英语教学辅助工具


配合人教版2019版高中英语必修一教材使用的单元词汇检测工具。
> 网址：https://gumingyu.github.io/rjb-word-review/
学生学完一个单元的单词后，通过三种题型（看英文选释义、看中文选单词、语境填空）检验是否真正掌握，自动生成成绩单。

## 当前状态（必修第一册）

- ✅ Welcome Unit · Getting to know each other（18词，54题）
- ✅ Unit 1 · Teenage Life（25词，75题）
- ✅ Unit 2 · Travelling Around（25词，75题）
- ✅ Unit 3 · Sports and Fitness（25词，75题）
- ✅ Unit 4 · Natural Disasters（25词，75题）
- ✅ Unit 5 · Languages around the World（25词，75题）

**合计：143个核心词 · 429道题**

## 功能特点

- **三关检测**：每个单词要在三种题型都答对才算"掌握"
- **错题回炉**：答错的题会在5-8题后再问一次，加深记忆
- **单词收集墙**：每个单元顶部一排小格子，绿色=已掌握，红色=待巩固
- **成绩单生成**：完成后生成可截图分享的成绩单
- **本地记录**：自动保存每个单元的最佳成绩
- **键盘支持**：电脑端数字键1-4答题，H键看翻译

## 部署到GitHub Pages

### 第一次部署（10分钟）

1. 在GitHub上创建新Repo（建议名字：english-word-review 或 gusir-english）
2. 把 index.html 上传到Repo根目录
3. 进入Repo → Settings → Pages
   - Source 选择 Deploy from a branch
   - Branch 选择 main（或 master），文件夹选 / (root)
   - 点击 Save
4. 等待约1分钟，页面会显示访问链接
5. 把链接发给学生

### 更新内容

修改 index.html 上传覆盖，30秒内生效。

## 使用建议

学生侧：用手机浏览器打开链接，添加到主屏幕，首次输入姓名后自动记住。做完截图发到群里。

老师侧：关注"待巩固"单词——是学生群体性薄弱点。

## 技术说明

- 单文件HTML，无依赖（仅一个CDN库 html2canvas）
- 数据存浏览器localStorage，不上传
- 支持手机、平板、电脑各种浏览器
