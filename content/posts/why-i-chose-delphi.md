---
title: "Why I Chose Delphi"
date: 2021-03-01T14:07:50-05:00
draft: false
---

What do I mean by choosing Delphi. Basically, as my main IDE and Object Pascal flavor of choice for most of my development I will use Delphi.  

I have been a contract coder since 2003 with VB6. I learned Delphi in high school, but that was in 1998. So I am basiacally starting all over again. I remember a few things, but not enough to start using it now. 

Over the last 19-ish years of coding professionally, I have learned and used multiple tools and languages. I started a native desktop developer, but I as burned a few times on payment, so I switched to web applications so I could shut sites down until payment was recieved. 

In the web world, I have used PHP, ASP.NET, ASP MVC, Go, and nearly JS framework there is. I was constantly chasing harmony with what I was using with one client to ensure I could use it across all my clients. Most clients didn't care what their product as made in as long as it:
- was within spec
- was within budget
- was delivered on time

I have seen the market shift multiple times in the direction it was moving and I've tried to keep up. However, maintinng a large amount of applications in this manner is very time consuming. Most frameworks have breaking changes every 6 months as they try new things or just organize their code better. 

What started me on this path was I made a program in a JS framework, delivered it, and all was great. Then 2 years later, they wanted to add a new feature. This shouldn't have been a huge problem, except the framework changed how they wanted to get API data. It took me about 4 hours just to get the app to a working condition again before I could even start the new feature. 

This was starting to happen more and more often and I have grown tired (yes, like and old man yelling at the kids to get off his lawn.)

Either way, this started my reflection on what it was I really needed. My apps are all just front-ends to databases. I also wanted to ensure backwards compatibility and as little up keep as possible for the end-user. This started my back down the road to desktop apps. I looked over multiple paths and really settled on three: .NET, Java, and Delphi. I ruled out most others for different reasons, but I looked at Python, Go, Qt, and Rust just to name a few.

I eventually ruled out Java as I new my clients hardly ever updated their JDK so to keep them on the version I was coding in was going to be rough. I looked at .NET next. I like .NET. Blazor WASM is going to be amazing and I will most likely continue to use it for the web apps I do make. The problem I have /[p;.] .NET though is Microsoft's focus. If I am making a new desktop app, do I use WinForms, WPF, UWP, Xamarin, or the new Maui? They keep changing directions and love doing it.

Delphi checked all the boxes for me for desktop development. It is a modern language, but with the compatibility that I am looking for in a language. VCL has been around since the beginning for Windows and for crossplatform apps I need for mobile I can use Firemonkey. Firemonkey, while not as mature as VCL, is still quite stable and mature enough to use.

These are the reasons for my switch. It is a personal choice and I will still use other languages as need. I will still use Go for my API backend even for use in Delphi. 

I set this blog up as a way to share my journey in Delphi. Maybe even encourage others that are in the same place as me to consider looking at their options and see if Delphi or another flavor of Object Pascal would be right for them.


**tl;dr:** As a contract coder that maintains several programs, I have grown tired of the breaking changes every 6 momths for most frameworks. For this reason I am switching something that will allow to get an amazing product to my clients faster and cheaper; as well as let me have some sanity when maintaining apps with new features.
