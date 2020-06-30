## 使用方式

### 添加依赖

在根目录添加发布插件的相关依赖

    buildscript {  
        repositories {  
            jcenter()  
        }  
    }   

    allprojects {  
        repositories {  
            jcenter()  
        }  
    }
    
### import

直接在项目依赖中添加对应库的依赖：

	dependencies {
	    api 'com.bihe0832.android:lib-wrapper:1.0.3'
	}


所有的组件都可以单独使用，同时为了方便开发，直接添加了下面三个组件，方便快速使用

![LibWrapper](https://img.shields.io/badge/AndroidAppFactory-LibWrapper-brightgreen)[ ![Download](https://api.bintray.com/packages/bihe0832/android/lib-wrapper/images/download.svg) ](https://bintray.com/bihe0832/android/lib-wrapper/_latestVersion)

- 简介：

    所有基础库的合集，包含了权限声明等，建议平时开发直接使用LibWrapper的最新版
    
- 使用：

		implementation 'com.bihe0832.android:lib-wrapper:1.0.3'
    
![LibUIUtils](https://img.shields.io/badge/AndroidAppFactory-LibUIUtils-brightgreen)[ ![Download](https://api.bintray.com/packages/bihe0832/android/lib-uiutils/images/download.svg) ](https://bintray.com/bihe0832/android/lib-uiutils/_latestVersion)

- 简介：

    所有UI相关的基础库的合集
    
- 使用：

		implementation 'com.bihe0832.android:lib-uiutils:1.3.10'

![LibUtils](https://img.shields.io/badge/AndroidAppFactory-LibUtils-brightgreen)[ ![Download](https://api.bintray.com/packages/bihe0832/android/lib-utils/images/download.svg) ](https://bintray.com/bihe0832/android/lib-utils/_latestVersion)

- 简介：

    所有非UI相关的基础库的合集，使用时如果用到特殊库，需要添加对应的权限声明
    
- 使用：

		implementation 'com.bihe0832.android:lib-utils:1.6.0'

### 调用

所有的组件都可以单独使用，具体的调用方式不在这里说明