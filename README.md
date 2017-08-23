# hrbuild-shell
Shell script to build ipa.

===

### 使用说明

下载后，打开终端执行脚本。

```
功能：编译xcode项目并打ipa包

使用说明：
	编译project
		hrbuild <project directory> -c <project configuration> -o <ipa output directory> [-t <target name>] -p <provisioning profile> [-n]
	编译workspace
		hrbuild  <workspace directory> -w -s <schemeName> -c <project configuration> -o <ipa output directory> [-t <target name>] -p <provisioning profile> [-n]

 参数说明：
           -c NAME				工程的configuration,默认为Release。
           -o PATH				生成的ipa文件输出的文件夹
		   -t NAME				需要编译的target的名称
		   -w					编译workspace	
		   -s NAME				对应workspace下需要编译的scheme
		   -n					编译前是否先clean工程
		   -p NAME				配置文件名称
```

