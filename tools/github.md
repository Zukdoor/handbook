# Github工作流

1. 从zukdoor中fork项目到自己的仓库里
2. 在自己的项目里进行开发和调试
3. 调试完成后，首先将zukdoor中原项目的master分支merge到自己当前开发的branch上
4. 测试无误后，再向zukdoor中项目的master分支提起Pull Request。
5. 在PR的提交说明中，用`fix #13`这样的方式说明该PR对应的Issue。如果没有对应的Issue，需要先提Issue，再发起PR。
6. 等待审核通过。
7. 如果审核人提出意见，或自动测试不通过，及时回应和修改。修改方法为：向自己提出PR的那个分支作提交，PR会相应地自动更新。