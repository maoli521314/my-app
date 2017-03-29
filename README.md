#安装node 和npm  
######然后全局安装 Angular-CLI  npm install -g @angular/cli 
######到目录下面 cd my-app 
######启动  ng serve  
#目录结构

######e2e/*
    在e2e/下是端到端（End-to-End）测试。 它们不在src/下，是因为端到端测试实际上和应用是相互独立的，它只适用于测试你的应用而已。 这也就是为什么它会拥有自己的tsconfig.json
######node_modules/...
    Node.js创建了这个文件夹，并且把package.json中列举的所有第三方模块都放在其中。
######src/
    文件夹是项目的根文件夹之一。 其它文件是用来帮助你构建、测试、维护、文档化和发布应用的。它们放在根目录下，和src/平级。

######.angular-cli.json
    Angular-CLI的配置。 在这个文件中，你可以设置一系列默认值，还能配置当构件项目时应该排除哪些文件。
######.editorconfig
    给你的编辑器看的一个简单配置文件，它用来确保参与你项目的每个人都具有基本的编辑器配置。
    http://editorconfig.org
######.gitignore
    一个Git的配置文件，用来确保某些自动生成的文件不会被提交到源码控制系统中。
######karma.conf.js
    给Karma的单元测试配置，当运行ng test时会用到它。
    Karma：  https://karma-runner.github.io/1.0/index.html
######package.json
    npm配置文件，其中列出了项目使用到的第三方依赖包。 你还可以在这里添加自己的自定义脚本。
    自定义脚本:https://docs.npmjs.com/misc/scripts
######protractor.conf.js
    给Protractor使用的端到端测试配置文件，当运行ng e2e的时候会用到它。
    Protractor： http://www.protractortest.org/
######README.md
    项目的基础文档，预先写入了CLI命令的信息。 别忘了用项目文档改进它，以便每个查看此仓库的人都能据此构建出你的应用。
######tslint.json
    给TSLint和Codelyzer用的配置信息，当运行ng lint时会用到。 Lint功能可以帮你保持代码风格的统一。
    Codelyzer： http://codelyzer.com/
    TSLint：  https://palantir.github.io/tslint/
