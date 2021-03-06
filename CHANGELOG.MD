## Change Log

### v4.5.1-aspnetcore (2018/04/02)
- [#268](https://github.com/nlog/nlog.web/pull/268) Improved ConfigureNLog for better out-of-the-box experience (@snakefoot)


### v4.5.0-aspnetcore (2018/03/27)
- [#257](https://github.com/nlog/nlog.web/pull/257) ConfigureNLog should not be used together with UseNLog (@snakefoot)
- [#256](https://github.com/nlog/nlog.web/pull/256) ASP.NET Core2 Example - Updated with NLog.LogManager.Shutdown() (@snakefoot)
- [#253](https://github.com/nlog/nlog.web/pull/253) ASP.NET Core2 Example - Updated blackhole configuration + ${aspnet-appbasepath} + ${aspnet-webrootpath} (@snakefoot)
- [#252](https://github.com/nlog/nlog.web/pull/252) Configured xunit DisableTestParallelization to make tests more stable (@snakefoot)
- [#250](https://github.com/nlog/nlog.web/pull/250) Removed System.ValueTuple as dependency for .NET Core app 1, add file version to assembly (@snakefoot)
- [#249](https://github.com/nlog/nlog.web/pull/249) Automatically register NLog.Web LayoutRenders for NetCoreApp1 (@snakefoot)
- [#245](https://github.com/nlog/nlog.web/pull/245) Use LogManager.LoadConfiguration + RC3 (@snakefoot)
- [#236](https://github.com/nlog/nlog.web/pull/236) AspNetCore 4.5 RC2 - Update changelog and version (@304NotModified)
- [#232](https://github.com/nlog/nlog.web/pull/232) Updated dependencies (@304NotModified)
- [#233](https://github.com/nlog/nlog.web/pull/233) Better hide assemblies for ${callsite} (@304NotModified)
- [#231](https://github.com/nlog/nlog.web/pull/231) Made ServiceLocator public (@304NotModified)
- [#226](https://github.com/nlog/nlog.web/pull/226) ASP.NET core: 4.5 rc1 + changelog (@304NotModified)
- [#223](https://github.com/nlog/nlog.web/pull/223) .NET 4.6.1 + ASP.NET Core 2 support (@304NotModified)
- [#224](https://github.com/nlog/nlog.web/pull/224) Fix assembly-version (@304NotModified)
- [#212](https://github.com/nlog/nlog.web/pull/212) Beta4 (@304NotModified)
- [#207](https://github.com/nlog/nlog.web/pull/207) Fix ${callsite} from configure (@304NotModified)

### v4.5.0-aspnetcore-beta02 (2017/10/13)
- [#205](https://github.com/nlog/nlog.web/pull/205) Register NLogProvider instead of NLogFactory (@304NotModified)
- [#204](https://github.com/nlog/nlog.web/pull/204) Improve ASP.NET core 2 example - add callsite (@304NotModified)
- [#202](https://github.com/nlog/nlog.web/pull/202) Fix ${callsite} in Asp.net core 2 (@304NotModified)

### v4.5.1-aspnet4 (2017/10/12)
- [#198](https://github.com/nlog/nlog.web/pull/198) Refactor code (@304NotModified)

### v4.5.0-aspnetcore-beta01 (2017/10/12)
- [#197](https://github.com/nlog/nlog.web/pull/197) versions and changelog, updated dependencies: NLog.Web 4.5.1 and NLog.Web.AspNetCore 4.5.0-beta01 (@304NotModified)
- [#195](https://github.com/nlog/nlog.web/pull/195) add ConfigureNLog on ILoggingBuilder (@304NotModified)
- [#191](https://github.com/nlog/nlog.web/pull/191) Added  NLogBuilder and  ASP.NET Core 2 example (@304NotModified)
- [#190](https://github.com/nlog/nlog.web/pull/190) Fix error reporting, fix introduced bug (@304NotModified)
- [#188](https://github.com/nlog/nlog.web/pull/188) Auto register NLog.Web.AspNetCore (ASP.NET 2 only) (@304NotModified)
- [#186](https://github.com/nlog/nlog.web/pull/186) Register HttpContextAccessor by default (@304NotModified)
- [#181](https://github.com/nlog/nlog.web/pull/181) Add UseNLog for ASP.NET Core 2 (@304NotModified)
- [#182](https://github.com/nlog/nlog.web/pull/182) Codecov tweaks (@304NotModified)
- [#180](https://github.com/nlog/nlog.web/pull/180) Fix IHttpContextAccessor warning (@304NotModified)
- [#178](https://github.com/nlog/nlog.web/pull/178) ASP.NET Core 2 support (@304NotModified)
- [#179](https://github.com/nlog/nlog.web/pull/179) rename NETSTANDARD_1plus => ASP_NET_CORE (@304NotModified)
- [#156](https://github.com/nlog/nlog.web/pull/156) Remove unneeded path in build script (@304NotModified)
- [#164](https://github.com/nlog/nlog.web/pull/164) Add IncludeScheme option to ${aspnet-request-url} (@BlaikiC)
- [#162](https://github.com/nlog/nlog.web/pull/162) Update AssemblyVersionLayoutRenderer docs for .NET core (@Valeriy1991)
- [#155](https://github.com/nlog/nlog.web/pull/155) fix xUnit warnings (@304NotModified)
- [#154](https://github.com/nlog/nlog.web/pull/154) deploy to Nuget from AppVeyor (@304NotModified)

### v4.4.1-aspnetcore (2017/06/16)
- [#152](https://github.com/nlog/nlog.web/pull/152) Run test for asp.net core on full and core framework, fix unit test build (#152) (@johnkors)
- [#150](https://github.com/nlog/nlog.web/pull/150) Update vulnerable dependency (#150) (@johnkors)


### v4.5.0-aspnet4 (2017/05/14)

#### Features

- [#66](https://github.com/nlog/nlog.web/pull/66) ${Assembly-version} working for asp.net (core) (#66) (@304NotModified)
- [#140](https://github.com/nlog/nlog.web/pull/140) Added ${aspnet-request-ip} (@304NotModified)
- [#143](https://github.com/nlog/nlog.web/pull/143) added ${aspnet-user-isAuthenticated} (@304NotModified)
- [#125](https://github.com/nlog/nlog.web/pull/125) Added ${aspnet-environment} (@grokky1)
- [#123](https://github.com/nlog/nlog.web/pull/123) Added Culture option to ${aspnet-item} and {aspnet-session} (#123) (@sbebrys)

#### Improvements

- [#141](https://github.com/nlog/nlog.web/pull/141) Improve performance with many threads 2 (@304NotModified)
- [#133](https://github.com/nlog/nlog.web/pull/133) Improve performance with many threads (@304NotModified)

#### Fixes

- [#132](https://github.com/nlog/nlog.web/pull/132) Fix invalid JSON format for ${aspnet-request-cookie} and ${aspnet-request-querystring}, added extra formatting options, consistent rendering of multiple values (@304NotModified)


### v4.4.0-aspnetcore (2017/05/14)

#### Features

- [#66](https://github.com/nlog/nlog.web/pull/66) ${Assembly-version} working for asp.net (core) (#66) (@304NotModified)
- [#140](https://github.com/nlog/nlog.web/pull/140) Added ${aspnet-request-ip} (@304NotModified)
- [#143](https://github.com/nlog/nlog.web/pull/143) added ${aspnet-user-isAuthenticated} (@304NotModified)
- [#126](https://github.com/nlog/nlog.web/pull/126) Add ${aspnet-request-contenttype} (ASP.NET Core only) (@304NotModified)
- [#125](https://github.com/nlog/nlog.web/pull/125) Added ${aspnet-environment} (@grokky1)
- [#123](https://github.com/nlog/nlog.web/pull/123) Added Culture option to ${aspnet-item} and {aspnet-session} (#123) (@sbebrys)

#### Improvements

- [#144](https://github.com/nlog/nlog.web/pull/144) Limit dependecies (#144) (@304NotModified)
- [#142](https://github.com/nlog/nlog.web/pull/142) ignore ObjectDisposedException in aspnet-user renderers (@304NotModified)
- [#141](https://github.com/nlog/nlog.web/pull/141) Improve performance with many threads 2 (@304NotModified)
- [#133](https://github.com/nlog/nlog.web/pull/133) Improve performance with many threads (@304NotModified)

#### Fixes

- [#132](https://github.com/nlog/nlog.web/pull/132) Fix invalid JSON format for ${aspnet-request-cookie} and ${aspnet-request-querystring}, added extra formatting options, consistent rendering of multiple values (@304NotModified)
- [#125](https://github.com/nlog/nlog.web/pull/125) fix ${iis-site-name} for ASP.NET Core (@grokky1)

### v4.3.2-aspnetcore (2017/02/17)
- [#112](https://github.com/nlog/nlog.web/pull/112) NLog.Web.AspNetCore 4.3.2 (@304NotModified)

### v4.4.0-aspnet4 (2017/02/17)
- [#110](https://github.com/nlog/nlog.web/pull/110) Enabled strong naming with correct version (@304NotModified)
- [#111](https://github.com/nlog/nlog.web/pull/111) Update nlog version (@304NotModified)
- [#106](https://github.com/nlog/nlog.web/pull/106) Update assemblyinfo & strong name version to 4.0.0.0 (@304NotModified)
- [#108](https://github.com/nlog/nlog.web/pull/108) Added mvc tag (@304NotModified)

### v4.3.1 (2017/02/10)
- [#98](https://github.com/nlog/nlog.web/pull/98) support for empty 'QueryStringKeys' for ${all-querystrings{aspnet-request-querystring} (@304NotModified)
- [#100](https://github.com/nlog/nlog.web/pull/100) Fixing missing name for ${aspnet-request-cookie} (@304NotModified)
- [#99](https://github.com/nlog/nlog.web/pull/99) Add ${aspnet-traceidentifier} (ASP.NET Core only) (@304NotModified)
- [#97](https://github.com/nlog/nlog.web/pull/97) Update dependencies and version number (@304NotModified)
- [#95](https://github.com/nlog/nlog.web/pull/95) Adding a link to some ASP.NET Core examples (@damienbod)
- [#91](https://github.com/nlog/nlog.web/pull/91) Update AssemblyInfo (@304NotModified)

### v4.3.0-aspnetcore (2017/01/18)
- [#89](https://github.com/nlog/nlog.web/pull/89) Update NLog.Extensions.Logging dependecy (@304NotModified)
- [#80](https://github.com/nlog/nlog.web/pull/80) Update README.md for 4.3 (@304NotModified)
- [#88](https://github.com/nlog/nlog.web/pull/88) Move ASP.NET helpers from nlog.extensions.logging, (@304NotModified)
- [#87](https://github.com/nlog/nlog.web/pull/87) Renames #2, allow aspnet-request-host in non-core ASP.NET (@304NotModified)
- [#86](https://github.com/nlog/nlog.web/pull/86) renames for consistency (@304NotModified)
- [#78](https://github.com/nlog/nlog.web/pull/78) added null checks (@304NotModified)
- [#77](https://github.com/nlog/nlog.web/pull/77) Upgrade to NLog 4.4 (@304NotModified)
- [#68](https://github.com/nlog/nlog.web/pull/68) Readme - make core vs non-core clearer (@timabell)
- [#54](https://github.com/nlog/nlog.web/pull/54) Additional aspnet renderers & unit tests for .net core (@304NotModified, @Page-Not-Found)
- [#61](https://github.com/nlog/nlog.web/pull/61) Upgrade RC2 to RTM. .Net Core. (#61) (@Page-Not-Found)
- [#59](https://github.com/nlog/nlog.web/pull/59) Upgrade to ASP.NET Core RC2 (@304NotModified)

### v4.2.1-aspnet4 (2016/05/12)
- [#57](https://github.com/nlog/nlog.web/pull/57) Package both nupkg + build scripts (#57) (@304NotModified)
- [#56](https://github.com/nlog/nlog.web/pull/56) Suppressing exception thrown when accessing HttpContext.Request (#56) (@vegar)

### 4.2.2 (2016/04/15)
- [#48](https://github.com/nlog/nlog.web/pull/48) Update LICENSE (#48) (@304NotModified)
- [#41](https://github.com/nlog/nlog.web/pull/41) DNX: Prevent stackoverflowException in ${aspnet-session} (#41) (@304NotModified)
- [#52](https://github.com/nlog/nlog.web/pull/52) Extra null check (#52) (@304NotModified)
- [#50](https://github.com/nlog/nlog.web/pull/50) Add dotnet5.4 framework (@304NotModified)
- [#37](https://github.com/nlog/nlog.web/pull/37) fix syntax of readme.md (@petemounce)

### v4.2.1 (2016/02/16)
- [#36](https://github.com/nlog/nlog.web/pull/36) Update README for aspnet5 (@304NotModified)
- [#35](https://github.com/nlog/nlog.web/pull/35) Fix aspnet5 (@304NotModified)
- [#33](https://github.com/nlog/nlog.web/pull/33) Less dependencies (@304NotModified)
- [#30](https://github.com/nlog/nlog.web/pull/30) Added ASP.NET 5 compatible package (@304NotModified)

### v4.2.0 (2016/02/07)
- [#27](https://github.com/nlog/nlog.web/pull/27) Add ability to render Headers (@petemounce)
- [#22](https://github.com/nlog/nlog.web/pull/22) Introducing ASP.NET Layout Renderer base class (@epignosisx)
- [#25](https://github.com/nlog/nlog.web/pull/25) Add info about configuration of NLog.Web in web.config to README.md (@muromek)

### v4.1.0 (2015/11/24)
- [#18](https://github.com/nlog/nlog.web/pull/18) Added Codecov (@304NotModified)
- [#17](https://github.com/nlog/nlog.web/pull/17) MsTest  => xUnit2 (@304NotModified)
- [#16](https://github.com/nlog/nlog.web/pull/16) Added Culture tests and use current culture (can be set) (@304NotModified)
- [#15](https://github.com/nlog/nlog.web/pull/15) Aspnet-item renderer (@304NotModified, @dafanasiev)

### v4.0.0 (2015/10/22)
- [#13](https://github.com/nlog/nlog.web/pull/13) Improved config for release (@304NotModified)
- [#7](https://github.com/nlog/nlog.web/pull/7) Enable Strong name signing (@304NotModified)
- [#8](https://github.com/nlog/nlog.web/pull/8) added unit tests project + tests for session (@304NotModified)

### 2.0.0 (2015/06/11)
- [#3](https://github.com/nlog/nlog.web/pull/3) Added support for logging nested properties of session items. (@Giorgi)
- [#2](https://github.com/nlog/nlog.web/pull/2) Move stuff from extended (@kichristensen)
- [#1](https://github.com/nlog/nlog.web/pull/1) Add IIS web site name layout renderer (@kichristensen)
