# MicroserviceBasic
This project has basic of Microservice concept

#Step to run
open the comman prompt

cd <your folderwhere you want to download code>
git clone https://github.com/AbhinavSingh1git/MicroserviceBasic.git

Now browse to folder where you have clone folder.
You will see below folder created.
MicroserviceBasic

open the folder in visual code.
once folder is created.Go To ->"Terminal->Run Build Task"

once build is completed you will get below message
Terminal will be reused by tasks, press any key to close it.

Create account on below site.
https://home.openweathermap.org
Once account is created, go to below link. 
You will see api key which is very important.
https://home.openweathermap.org/api_keys

Fire below command in Visual code terminal to store the apikey
dotnet user-secrets set ServiceSettings:ApiKey yourapikey
