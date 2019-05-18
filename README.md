# Asp.Net-MVC-and-latest-Bootstrap-Starter-Template
Whenever we create a new Asp.Net web project with the latest .Net Framework (4.7.2 at the time of writing this), the project is created with Bootstrap 3 which is annoying because once you update to the latest Bootstrap the pages do not work properly. I thought it's good to share a starter template solution with the startup views upgraded to work with latest Bootstrap.

The project was cleaned and also the packages folder removed to reduce the repo size. 
Once downloaded right click on the project and select 'Manage NuGet Packages'.
This will bring up the NuGet Packages window where on the top it will show a message with a 'Restore' button. Click on Restore to restore the packages. Once done press F5 to verify it worked.

If you get the following message close the browser window and clean the solution and build it again and press F5.

Could not find file 'C:\.......\MVCWithLatestBootstrapTemplate\bin\roslyn\csc.exe'.

Hope you all find this useful.
