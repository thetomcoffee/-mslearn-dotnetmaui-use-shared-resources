
# README

This repo is a clone of the repo that was originally published at:
[MicrosoftDocs / mslearn-dotnetmaui-use-shared-resources](https://github.com/microsoftdocs/mslearn-dotnetmaui-use-shared-resources)

I will be adding shared resources to the solutions in this repo. 

Also, this repo is part of the MS Learn module [Design consistent .NET MAUI XAML pages by using shared resources](https://learn.microsoft.com/en-us/training/modules/use-shared-resources/)


Notes:  

## Issues with Static Resources 

*  Suppose you want to implement color themes that let the user change the look of the app at runtime. The StaticResource mark-up extension does the dictionary lookup only once, so it can't update the UI dynamically. 

* You store user preferences on a web server and load them when the application starts. The StaticResource mark-up extension throws an exception if the key isn't found in the dictionary.  
(bullet points copied from [Use and update dynamic resources](https://learn.microsoft.com/en-us/training/modules/use-shared-resources/4-use-and-update-dynamic-resources))
