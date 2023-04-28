#Online translation A translation program based on chatgpt, with api key of openai, vps server and domain name. This program can be deployed to the docker of the vps server and used by accessing through the Internet. Please write the code according to the following requirements
##1. Designed a similar to https://www.deepl.com/translator translation program interface. 
##2. integrated the API key of OpenAI into the program to implement the translation function.
##3. developed a Docker container for the program to be easily deployed on a VPS server and remotely accessed via the Internet.
##4. Implemented real-time translation functionality using OpenAI's GPT API.
##5. Created a Docker container with all necessary dependencies and configurations for easy deployment on VPS servers.
##6. Implement user authentication features to ensure secure access to the program.
##7. implement the function for users to save the translation history.
##8. Implement the function for users to select the language of the text to be translated.
##9. implementing the function of adjusting the translation quality according to the user's preference
##10. implementing the function for users to translate by uploading whole or partial documents
##11. improve the user interface by adding a progress bar to the program's user interface and displaying the current status of the translation process.


Online translation 一个基于chatgpt的翻译程序，已有openai的api key，有vps服务器，有域名。这个程序可以部署到vps服务器的docker上，通过互联网访问而使用，功能和界面参考https://www.deepl.com/translator。 请根据以下要求编写代码1. 设计了一个类似于 https://www.deepl.com/translator 的翻译程序界面。
2. 将OpenAI的API密钥集成到程序中，实现翻译功能。
3. 为程序开发了一个Docker容器，以便在VPS服务器上轻松部署并通过互联网进行远程访问。
4. 使用OpenAI的GPT API实现实时翻译功能。
5. 创建一个具有所有必要依赖项和配置的Docker容器，以便在VPS服务器上轻松部署。
6. 实现用户身份验证功能，以确保对程序的安全访问。
7. 实现用户保存翻译历史的功能。
8. 实现用户选择要翻译文本的语言的功能。
9. 实现根据用户偏好调整翻译质量的功能。
10. 实现用户通过上传整个或部分文档进行翻译的功能。
11. 通过向程序的用户界面添加进度条，改进用户界面，并显示翻译过程的当前状态。

初步方案：

设计界面：您可以使用前端框架如React或Vue.js来创建一个类似于https://www.deepl.com/translator的翻译程序界面。可以使用CSS和JavaScript进行样式设计和交互功能实现。

集成OpenAI API：您可以使用OpenAI的API接口进行翻译功能的实现。可以使用Python编写一个API客户端，将OpenAI的API密钥集成到程序中，以实现实时翻译功能。

创建Docker容器：您可以使用Docker容器技术来创建一个可部署的翻译程序。可以使用Dockerfile和Docker Compose文件来配置和管理Docker容器。可以使用NGINX或Apache作为Web服务器来托管程序。

用户身份验证：您可以使用身份验证技术如OAuth 2.0或JWT来实现用户身份验证功能，以确保对程序的安全访问。

翻译历史记录：您可以使用数据库技术如MySQL或MongoDB来存储用户的翻译历史记录。可以使用ORM技术如SQLAlchemy来简化数据库访问。

语言选择和翻译质量调整：您可以使用下拉菜单来实现用户选择要翻译文本的语言的功能，并使用滑块或单选框来调整翻译质量。

文档翻译：您可以使用Python的文本处理库如Pandas或NLTK来实现用户通过上传整个或部分文档进行翻译的功能。可以将文档转换为字符串，并将其传递给OpenAI API进行翻译。

显示翻译进度：您可以使用前端框架中的组件如进度条或加载动画来显示翻译过程的当前状态。
