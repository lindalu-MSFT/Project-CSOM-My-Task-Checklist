# Project-CSOM-My-Task-Checklist

The Project CSOM My Checklist sample uses C# and Project CSOM to demonstrate how to assignments assigned to the current user and submit status indicating that the tasks are complete.

## Scenario

As a project team member, I want an easy way to see the tasks assigned to me and can check them off when complete.

### Using App

1.	Add the Project CSOM client package [here](https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/)
2.	Update the PWA site and click connect
3.	Update the login/password to your PWA site.
4.	Run the app

### Prerequisites
To use this code sample, you need the following:

* PWA Site (Project Online, Project Server 2013 or Project Server 2016)
* Visual Studio 2013 or later 
* Project CSOM client library.  It is available as a Nuget Package from [here](https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/)
* One or more project stored in the PWA instance that use ECFs.


## How the sample affects your tenant data
This sample runs CSOM methods that reads all assignments in the PWA instance for the specified user. Tenant data will be changed if assignments are checked/unchecked and submitted.

## Additional resources

* [Client-side object model (CSOM) for Project 2013](https://aka.ms/project-csom-docs)

* [SharePoint (Project) CSOM Client library](https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/)

## Copyright

Copyright (c) 2016 Microsoft. All rights reserved.


