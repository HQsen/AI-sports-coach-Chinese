# 体育 AI 教练
注：通过测试发现，中文版的性能要差于英文版，如果你英文不错，请移步[英文版](https://github.com/HQsen/AI_Coach_Sports)。

如果您喜欢这个项目，请给它一个星星。如果您有兴趣并希望使它更有用或扩展其功能，请随时打开一个 issue 或 pull request。
## 介绍
- 这是一个基于 **chatgpt** 的 **AI 教练**，可以根据您团队中不同技能的不同球员自定义有效的进攻战术。（目前仅支持篮球进攻战术。未来可能会增加足球、足球等防守战术。）期待早日使用 gpt-4！
- 如果您想让您的团队赢得更多比赛，但对战术不是很了解，可以试试这个工具。
- 以下是一些示例：
![picture 1](https://github.com/HQsen/AI_Coach_Sports/blob/main/image/1.png)
![picture 2](https://github.com/HQsen/AI_Coach_Sports/blob/main/image/2.png)


##  ## 安装
 1. 克隆该仓库
 ```$ git clone https://github.com/HQsen/AI-sports-coach-Chinese.git```
 2. 进入项目目录
 ```$ cd AI-sports-coach-Chinese```
 3. 安装依赖：
 您可以使用 pip 或 conda

pip :
 ```$ python -m pip install -r requirements.txt```
 
 conda :
 ```$ conda create -n aicoach_venv python=3.9```		
 ```$ conda activate aicoach_venv```
 ```$ python -m pip install -r requirements.txt```

4.  打开 `.env` 文件并添加您自己的 [API key](https://beta.openai.com/account/api-keys)
 
 5. 运行：
    ```$ flask run```
    您现在应该可以访问应用程序了： [http://localhost:5000](http://localhost:5000/)!


## ## 生成你自己的战术
![picture 1](https://github.com/HQsen/AI_Coach_Sports/blob/main/image/1.png)
![picture 2](https://github.com/HQsen/AI_Coach_Sports/blob/main/image/3.png)
如上所示，您可以按照以下格式分别输入您的球员特点：

**控球后卫（1号位）： "您的球员特点" 
得分后卫（2号位）： "您的球员特点" 
小前锋（3号位）： "您的球员特点" 
大前锋（4号位）： "您的球员特点" 
中锋（5号位）： "您的球员特点"**


如果一些球员没有独特的优势，您可以写上 **"无特定技能''**

:smile:如果您不喜欢这个页面的外观，请责备 chatgpt（他生成的，不是我）

## 未来
我将对这个项目进行更多改进，例如：
 - 使用 fine_tuning 或 embedding 来增加战术数据量
 - 对手分析
 - .....
 
随着更加强大的大型语言模型和视觉模型的发展，我相信AI一定会给体育带来巨大的变革。如果您对人工智能和体育领域（如AIGC或视频分析等）感兴趣，可以通过邮箱[2532953033@qq.com](mailto:2532953033@qq.com)联系我，也许我们可以互相启发，共同构建更有效的体育AI工具！
