[![Build status](https://ci.appveyor.com/api/projects/status/0wh9dw80mm55v7pg?svg=true)](https://ci.appveyor.com/project/sergey-tihon/opennlp-net)

OpenNLP for .NET [![NuGet Status](http://img.shields.io/nuget/v/OpenNLP.NET.svg?style=flat)](https://www.nuget.org/packages/OpenNLP.NET/)
=====================

`OpenNLP for .NET` is a port of OpenNLP to .NET.

This project contains build scripts that recompile OpenNLP `.jar` packages to .NET assemblies using [IKVM.NET](http://www.ikvm.net/) and tests that help to be sure that recompiled packages are workable. Recompiled assemblies are available on [NuGet](https://www.nuget.org/packages/OpenNLP.NET/).

.NET samples are available [in tests](https://github.com/sergey-tihon/OpenNLP.NET/blob/master/tests/OpenNLP.NET.Tests/Tests.fs). [Manual](https://opennlp.apache.org/documentation/1.5.3/manual/opennlp.html) is available on official site.

Versioning
----------

Versioning model used for NuGet packages is aligned to versioning used by OpenNLP Team. 
For example, if you get `OpenNLP` package from [OpenNLP site](https://opennlp.apache.org/) with version `1.5.3`, then the NuGet version of this package has a version `1.5.3.x`, where `x` is the greatest that is available on NuGet. Last number is used for internal versioning of .NET assemblies.

Licensing
----------
Project is licensed under the terms of the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0.html)
