---
title: "Resources For Learning"
date: 2021-03-12T13:51:10-05:00
draft: false
comments: true
---

It may be suprising to some, but Object Pascal still has a healthy community. This is split between Lazarus with FreePascal and Delphi. Either way, finding help online through Slack, Reddit, Telegram, etc. has been awesome.

I went through the Marco Cantu's book _Object Pascal Handbook_, which helped get me up to date with modern practices.

The one thing that took me a bit to remember was memory management. I have been coding in the web or other garbage collection languages for a long time. Delphi handles some memory manage, but not all. It took me a bit to wrap my head around it. The over simplified version is, if the compiler handles the creation it will handle the clearing of memory automatically. If I create something, I have to do it.

It makes sense in a way. It doesn't know when I am done with something if I create it, so it stays out the way. 

Example of what I mean about me creating something.

```
procedure TForm1.DoSomething();
var
  form: TObject;
begin
  form := MyObject.Create();

  { do what I need with the form}
  
  { release the memory }
  form := Free;
end;
```

The other thing I have been learning is Firemonkey, Delphi's crossplatform framework. Being able to use the same code for desktop and mobile is nice. This was something I enjoyed about flutter, but for mobile and web.

The design elements of what I can do on a desktop with a mouse and how the web/mobile space are different. Flutter works like a web app even on desktop. Sometimes it would be nice to open a new window, than have to use a "stack."

I am still well in the learning phase, but I have enjoyed the journey thus far.

Until next update.
