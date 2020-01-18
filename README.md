# asp.net migration code spotter cheat sheet 

very very quick and dirty highlights of some of the changes between asp.net versions from 1.1 to 3.1 for me when working with lots of different projects.

this is a placeholder draft, and can only be used by you first reading through all the actual upgrade docs (see list at the bottom). I'm using this as a quick way to spot a project that has been partially upgraded, and see quickly perhaps where the developer picked up his code from. 

For example; I may have a project that was a asp.net core 1.1, that has been upgraded 'just enough' so that it almost works, and it's got bugs, and I've been asked to help. So I need a quick chart that shows me 'visually' where code patterns I might be looking at have come from, hence why so many small screenshots. (I'm a visual person, like pictures.)

This is not meant as a step by step guide on how to migrate a project.

#### How best to use the reference?

It's a really big image, and pdf. Best is to download the drawio file, assuming you've installed the desktop version of draw.io. I have it installed on my mac (OSX) as well as windows.  

I can easily see myself splitting this into a number of (smaller A3 or A4) cheatsheets focusing on different aspects of asp.net projects, starting with `startup` and `configuration`. 

## Files

- pdf : [upgrading-asp.net-projects-from-1.1-to-3.1.pdf](upgrading-asp.net-projects-from-1.1-to-3.1.pdf)
- original drawio : [upgrading-asp.net-projects-from-1.1-to-3.1.drawio](upgrading-asp.net-projects-from-1.1-to-3.1.drawio)
- large png (6264 x 2752 pixels) : [upgrading-asp.net-projects-from-1.1-to-3.1.png](upgrading-asp.net-projects-from-1.1-to-3.1.png)

<img src='upgrading-asp.net-projects-from-1.1-to-3.1.png'/>

## official Microsoft upgrade docs (very good)

- `1.1` to `2.0` [https://docs.microsoft.com/en-us/aspnet/core/migration/1x-to-2x/?view=aspnetcore-3.1](https://docs.microsoft.com/en-us/aspnet/core/migration/1x-to-2x/?view=aspnetcore-3.1)
- `2.0` to `2.1` [https://docs.microsoft.com/en-us/aspnet/core/migration/20_21?view=aspnetcore-3.1](https://docs.microsoft.com/en-us/aspnet/core/migration/20_21?view=aspnetcore-3.1)
- `2.1` to `2.2` [https://docs.microsoft.com/en-us/aspnet/core/migration/21-to-22?view=aspnetcore-3.1&tabs=visual-studio](https://docs.microsoft.com/en-us/aspnet/core/migration/21-to-22?view=aspnetcore-3.1&tabs=visual-studio)
- `2.2` to `3.0` [https://docs.microsoft.com/en-us/aspnet/core/migration/22-to-30?view=aspnetcore-3.1&tabs=visual-studio](https://docs.microsoft.com/en-us/aspnet/core/migration/22-to-30?view=aspnetcore-3.1&tabs=visual-studio)
- `3.0` to `3.1` [https://docs.microsoft.com/en-us/aspnet/core/migration/30-to-31?view=aspnetcore-3.1&tabs=visual-studio](https://docs.microsoft.com/en-us/aspnet/core/migration/30-to-31?view=aspnetcore-3.1&tabs=visual-studio)
