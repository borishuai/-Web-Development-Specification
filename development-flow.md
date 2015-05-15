## Gitlab中task的管理
我们所有的task都必须放到Gitlab中，
1. 每个task是相对完整独立的功能，功能不能太大，也不能太细，以几个小时的工作量为宜
2. 每个task都需要有合适的标签，比如feature, bug
3. task标题需要简明扼要的描述
4. 在comment中需要对task进行详细的描述，方便自己和QA进行测试验证。首先描述要实现什么功能，然后是操作步骤，如step1, step2...。如果业务逻辑比较复杂，也可以放一些关于业务逻辑和算法的描述。

## Sprint的管理
每周1个sprint，周一开始，周五结束

## WIKI管理
WIKI主要放2种东西，
1. 需求管理，需求主要有2种形式，早期的文档，wireframe，UX的visual design等，虽然这些文档基本上比较直观的反映了大部分需求了，但是它很难对用户交互部分以及业务逻辑进行详细的描述，所以我们需要在WIKI中对需求进行补充性的描述。二者合起来应该能覆盖大部分的需求了。
2. 算法/解决方案
对于开发中遇到的相对复杂的算法，可以在WIKI中单独进行描述。对于各种常见问题的解决方案也可以放在WIKI中，便于大家分享。这样当有新成员加入时可以很快的熟悉整个项目。

## 代码目录结构
－src 项目代码目录
 - augploy 自动化部署文件
 - deploy 自动化部署依赖的配置文件
 - build 辅助脚本文件
 - docs 文档相关
 - README.md
 - VERSION
 - CHANGELOG.md
 - .gitignore

## 部署
请参考：http://git.augmentum.com.cn/borishuai/web-development/blob/master/docs/Production_Deployment_Process.ppt
