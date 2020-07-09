## 组件添加

1. 完成本地开发

2. 在远程仓库添加新的组件：

	- 地址：[https://bintray.com/bihe0832/android/](https://bintray.com/bihe0832/android/)
	
	- 版本库：https://github.com/bihe0832/AndroidAppFactory.git

3. 上传组件 

4. 把组件添加的依赖添加到 LibUtils （或LibUIUtils）和 LibWrapper 并构建新版本

5. 在 APPTest 同时引入 LibWrapper的源码和最新依赖，在根目录运行

		./gradlew clean 

## 组件更新

1. 完成本地开发

2. 在 LibWrapper 更新到最新版，然后，在根目录运行

		./gradlew clean 

3. 根据提示，升级依赖该组件的组件的版本

4. 依次重复 2 和 3 直到所有组件 版本不冲突且最新，更新 LibWrapper 版本