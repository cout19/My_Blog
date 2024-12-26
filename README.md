This is a blog site. Created by KK.

Dowload zip or clone repository. 
And then you have to dowload some libraries.

cd AdminBlog

dotnet add package Microsoft.ENitityFrameWorkCore
dotnet add package Microsoft.ENitityFrameWorkCore.SqlServer
dotnet add package Microsoft.ENitityFrameWorkCore.Design
dotnet ef migrations add first 
dotnet ef database update

dotnet add package Microsoft.Asp.netCore.Session

cd MyBlog
dotnet add package Microsoft.ENitityFrameWorkCore
dotnet add package Microsoft.ENitityFrameWorkCore.SqlServer
dotnet add package Microsoft.ENitityFrameWorkCore.Design
dotnet ef migrations add first 
dotnet ef database update
dotnet add package Microsoft.Asp.netCore.Session


And you have to connect your sql server. And check your path for blogs images or docs.

have a good day!!!! 
