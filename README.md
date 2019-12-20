依赖
第一步，在项目根目录的build.gradle文件中加入：
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
}
第二步，在模块根目录的build.gradle文件中加入：
dependencies {
	        implementation 'com.github.foreverGoUp:AndroidMvpArch:Tag'
}