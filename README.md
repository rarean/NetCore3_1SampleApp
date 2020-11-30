# NetCore3_1SampleApp
A .NET Core 3.1 C# Sample Application used in exploring moving The Globe In My BucketList Application (TGIMBA) to the cloud.

## Related Projects/Items

These items are also related to this project. 

Blog Post(s):
<ul>
	<li><a href="https://erichelin.wordpress.com/2020/10/05/tgimba-going-aws-native-part-1-simple-net-core-3-1-app-running-in-aws-cloud/">Part 1 - Simple .NET Core 3.1 Application in cloud</a></li>
</ul>

## How To Use
Download the zip file, open up in Visual Studio, clean, restore packages, build and run.

### Docker
1) Download or clone repo
2) From command line at root of project where Dockerfile is `docker build . -t local/NetCore3_1SampleApp`
3) From command line docker run -it -p 80:80 local/NetCore3_1SampleApp
4) Open browser to http://localhost:80
