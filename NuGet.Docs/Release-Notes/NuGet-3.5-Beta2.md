#3.5 Beta2 Release Notes

[Full Changelog]()

[Issues List](https://github.com/NuGet/Home/issues?q=is%3Aissue+is%3Aclosed+milestone%3A%223.5 Beta2)

**Bugs:**

* Updated error message to lack of support for password decrpytion in .NET Core for authenticated feeds  - [#2942](https://github.com/NuGet/Home/issues/2942)

* Package Manager Console Get-Package fails if .NET Core project is open - [#2932](https://github.com/NuGet/Home/issues/2932)

* Fix incorrect handling of 403 in NuGet push command [#2910](https://github.com/NuGet/Home/issues/2910)

* Fix issues in uninstalling packages in a solution bound to TFS source control when disableSourceControlIntegration is set to true - [#2739](https://github.com/NuGet/Home/issues/2739)

* Fix package update to take into account non-target packages - [#2724](https://github.com/NuGet/Home/issues/2724)

* Use MSBuild verbosity level to set logger level for Nuget package manager UI actions - [#2705](https://github.com/NuGet/Home/issues/2705)

* Fix NuGet configuration is invalid error in WebSite projects - VS 2015 VSIX (v3.4.3) - [#2667](https://github.com/NuGet/Home/issues/2667)

* Fix pack issues from csproj when content files are included - [#2658](https://github.com/NuGet/Home/issues/2658)

* DefaultPushSource in NuGetDefaults.config (ProgramData\NuGet) doesn't work - [#2653](https://github.com/NuGet/Home/issues/2653)

* Fix issue in Nuget 3.4.3 release - Value cannot be null on package creation - [#2648](https://github.com/NuGet/Home/issues/2648)

* Restore uses stored credentials from nuget.config for VSTS feeds - [#2647](https://github.com/NuGet/Home/issues/2647)

* Performance - Fix excessive allocations in version comparsion code - [#2632](https://github.com/NuGet/Home/issues/2632)

* Fix issues when multiple instances of nuget.exe tries to install the same package in parallel - [#2628](https://github.com/NuGet/Home/issues/2628)

* Performance - Cache dependency information for multi-project operations - [#2619](https://github.com/NuGet/Home/issues/2619)

* If package source list is empty, cannot add package source via UI (NuGet 3.4.x) - [#2617](https://github.com/NuGet/Home/issues/2617)

* Misleading error when attempting to install package that depends on design-time facades - [#2594](https://github.com/NuGet/Home/issues/2594)

* Installing a package from PackageManager console with setting "All" tries only first source - [#2557](https://github.com/NuGet/Home/issues/2557)

* Latest beta not unzipping ModernHttpClient - [#2518](https://github.com/NuGet/Home/issues/2518)

* VS2015 crash at startup with self-built NuGet 3.4.1 - [#2419](https://github.com/NuGet/Home/issues/2419)

* Update command might be a bit more verbose if i ask it to be so... - [#2418](https://github.com/NuGet/Home/issues/2418)

* VSIX built locally should have the same dlls and files as the CI build. - [#2401](https://github.com/NuGet/Home/issues/2401)

* Failing to authenticate package source (3 times) is blocked forever - [#2362](https://github.com/NuGet/Home/issues/2362)

* Package content is not restored correctly when installing a package from a nuget v3.3+ feed with the argument -NoCache when the package contains *.nupkg files - [#2354](https://github.com/NuGet/Home/issues/2354)

* Nuget Install with All Package Sources, but package missing from 1 source, fails - [#2322](https://github.com/NuGet/Home/issues/2322)

* [PerfWatson] UIDelay: nuget.packagemanagement.visualstudio.dll!NuGet.PackageManagement.VisualStudio.VSMSBuildNuGetProjectSystem+<>c__DisplayClass_0+<<AddReference>b__>d.MoveNext - [#2285](https://github.com/NuGet/Home/issues/2285)

* Install blocks if a single source fails authorization - [#2034](https://github.com/NuGet/Home/issues/2034)

* nuspec version range should override -IncludeReferencedProjects version - [#1983](https://github.com/NuGet/Home/issues/1983)

* NuGet stealth downgrades package when batch updating its dependencies - [#1903](https://github.com/NuGet/Home/issues/1903)

* NuGet 3.3.0 update fails with 'An additional constraint ... defined in packages.config prevents this operation.' - [#1816](https://github.com/NuGet/Home/issues/1816)

* nuget.exe update drops the assembly strong name and Private attribute. - [#1778](https://github.com/NuGet/Home/issues/1778)

* Relative file path for "DefaultPushSource" - [#1746](https://github.com/NuGet/Home/issues/1746)

* Improve resolver failure messages - [#1373](https://github.com/NuGet/Home/issues/1373)

* update-package in v3 fails with packages not in the specified source - [#1013](https://github.com/NuGet/Home/issues/1013)

* Using relative paths for package sources is problematic to use - [#865](https://github.com/NuGet/Home/issues/865)

* Missing dependency in NUPKG-file generated from project if indirect dependency already exists with a lower version requirement - [#759](https://github.com/NuGet/Home/issues/759)

* Deleting a project closes corresponding UI window, but, renaming a project does not rename the UI window. Note that PMC listens to project rename and project remove events - [#670](https://github.com/NuGet/Home/issues/670)

**DCR:**

* Move NuGet to depend on v1.0 of CoreFX/CoreCLR/etc... - [#2967](https://github.com/NuGet/Home/issues/2967)

* Update CoreCLR/CoreFX that NuGet uses to rc3-24210-10 - [#2957](https://github.com/NuGet/Home/issues/2957)

* Mark our nupkgs as serviceable - [#2952](https://github.com/NuGet/Home/issues/2952)

* dotnet pack needs to be able to set serviceable in output .nuspec - [#2900](https://github.com/NuGet/Home/issues/2900)

* Replace Microsoft.Extensions.PlatformAbstractions with System.Runtime.InteropServices.RuntimeInformation - [#2890](https://github.com/NuGet/Home/issues/2890)

* Spec, test, and doc servicable metadata in nuspec - [#2870](https://github.com/NuGet/Home/issues/2870)

* NuGet.exe push - timeout parameter doesn't work  - [#2785](https://github.com/NuGet/Home/issues/2785)

* nuget.exe restore doesn't produce .props and .targets files for .nuproj projects (regression in v3.4.3.855) - [#2711](https://github.com/NuGet/Home/issues/2711)

* Need extensibility API to compare frameworks with imports - [#2633](https://github.com/NuGet/Home/issues/2633)

* Hide dependency options when using project.json - [#2486](https://github.com/NuGet/Home/issues/2486)

* Update dev branch, build, and related to create 2 VSIXes for Dev14 and Dev15 - [#2386](https://github.com/NuGet/Home/issues/2386)

* Print out NuGet.exe version header in detailed output - [#1887](https://github.com/NuGet/Home/issues/1887)

**Feature:**

* NuGet should add support for /runtimes/{rid}/nativeassets/{txm}/ - [#2782](https://github.com/NuGet/Home/issues/2782)

* Add framework compatibilities missing in NuGet 2.x (which are already in 3.x) - [#2720](https://github.com/NuGet/Home/issues/2720)

