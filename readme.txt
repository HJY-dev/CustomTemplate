dotnet new 自定义模板
微软文档：https://docs.microsoft.com/zh-cn/dotnet/core/tools/custom-templates

1.执行打包操作，生成Eidu.Core.Webapi.Template.1.0.0.nupkg，唯一id：Eidu.Core.Webapi.Template.
nuget pack D:\Companyproject\Template\Project.Template.nuspec

2.上传nuget，地址：https://www.nuget.org/packages/manage/upload
需要等几分钟

3.dotnet new -i Eidu.Core.Webapi.Template

安装模板

dotnet new -u Eidu.Core.Webapi.Template

卸载模板

dotnet new  eiducoretpl -n helloEidu

根据模板创建项目

dotnet new -u

查看已安装的模板，以及模板详细信息