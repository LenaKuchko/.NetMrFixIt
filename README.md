### Mr Fix-It

####  _August 18th, 2017_

#### By _**Olena Kuchko**_
#### A repair technician job service.


## Specifications
 |Behavior| Input (User Action/Selection)| Output (Program Action)|
 |---|---|---|
 | User is able to create account | Username, password, confirm password | App creates account and sends user to Login page|
 | User is able to view all jobs | No input required | App sends user to page where he/she can view all jobs  |
 | User/worker is able to claim the job | Click on claim job | App asks about confirmation and add job to worker |
 | User/worker is able to view all his jobs | Click on worker dashboadr | App displays all worker's jobs |
 | User/worker is able to mark job as completed | Click on Change status | App changes job status to complete  |
 | User/worker is able to mark job as current job | Click on Mark as current job | App changes job status to current  |



## Setup/Installation Requirements

#### _**Replicating/Editing this Project**_

* Clone this repository https://github.com/LenaKuchko/.NetMrFixIt.git.
* Using PowerShell navigate to the folder, where you clone project.
* Open project with Microsoft Visual Studio 2015.
* Using terminal, navigate to this folder C:\PATH_WHERE_YOU_CLONE_PROJECT\.NetMrFixIt\src\.NetMrFixIt>    
* Then run this command: dotnet ef database update
* Press Ctrl+F5 to run application

## Technologies Used

 ASP.NET Core, C#, _HTML, SCSS, AJAX

### License

 MIT

 Copyright (c) 2017 ** Olena Kuchko **
