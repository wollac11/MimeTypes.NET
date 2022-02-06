﻿![icon](Artwork/MimeTypes-icon-100.png)

# MimeTypes.NET [![CircleCI](https://circleci.com/gh/markwhitaker/MimeTypes.NET.svg?style=shield)](https://circleci.com/gh/markwhitaker/MimeTypes.NET) [![NuGet Version and Downloads count](https://buildstats.info/nuget/Mainwave.MimeTypes)](https://www.nuget.org/packages/Mainwave.MimeTypes/)

A structured collection of MIME type constants to use in your .NET projects.

Replace this sort of thing...

```
httpContext.Response.ContentType = "application/json";
```

with this...

```
httpContext.Response.ContentType = MimeTypes.Application.Json;
```

Pull requests welcome!

---
![icon](https://raw.githubusercontent.com/markwhitaker/MimeTypes.Java/master/artwork/MimeTypes-icon-32.png) **Java developer?** Check out the Java version of this library, [MimeTypes.Java](https://github.com/markwhitaker/MimeTypes.Java).

![icon](https://raw.githubusercontent.com/markwhitaker/MimeTypes.kt/master/artwork/MimeTypes-icon-32.png) **Kotlin developer?** Check out the Kotlin version of this library, [MimeTypes.kt](https://github.com/markwhitaker/MimeTypes.kt).
