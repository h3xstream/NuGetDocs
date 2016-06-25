#3.5 Beta2 Release Notes

[Full Changelog]()

[Issues List](https://github.com/NuGet/Home/issues?q=is%3Aissue+is%3Aclosed+milestone%3A%223.5 Beta2)

**Docs:**

* Update docs for "added update command line argument -Version" - [#3025](https://api.github.com/repos/NuGet/Home/issues/3025)

* Update with project.json in VS does not restore the package - [#2976](https://api.github.com/repos/NuGet/Home/issues/2976)

* nuget.exe and dotnet restore error experiences for Project.*.json - [#2654](https://api.github.com/repos/NuGet/Home/issues/2654)

**Bug:**

* beta-final packages, Incorrect dependency on 'NuGet.Core` - [#3016](https://api.github.com/repos/NuGet/Home/issues/3016)

* Confirm that nobody is publishing .nupkg with "bad xmlns uri" for nuspec - [#3012](https://api.github.com/repos/NuGet/Home/issues/3012)

* signed vsix of 3.5.0-beta2 last worked on 6/8 - [#2985](https://api.github.com/repos/NuGet/Home/issues/2985)

* Create a NuGet.Core 2.12 final nupkg and depend on it in V3 - [#2983](https://api.github.com/repos/NuGet/Home/issues/2983)

* CoreCLR restore needs to ignore feeds with encryption - [#2942](https://api.github.com/repos/NuGet/Home/issues/2942)

* (CLI dev branch remaining only) Tweak serviceable support in nuspec to not require a new xmlns uri for dotnet pack --serviceable - [#2938](https://api.github.com/repos/NuGet/Home/issues/2938)

* 3.5.0-beta2: Package Manager Console Get-Package fails if .NET Core project is open (which blocks EF's enable-migrations) - [#2932](https://api.github.com/repos/NuGet/Home/issues/2932)

* Upgrade NuGet in 3.5.0-beta2 and dev branches to use latest corefx builds - [#2929](https://api.github.com/repos/NuGet/Home/issues/2929)

* Regression in ManifestReader on Unix - [#2914](https://api.github.com/repos/NuGet/Home/issues/2914)

* NuGet.exe push 403 handling - Incorrectly prompting for credentials - [#2910](https://api.github.com/repos/NuGet/Home/issues/2910)

* Cannot install NuGet in Dev and release-3.5.0-beta2 branch. - [#2892](https://api.github.com/repos/NuGet/Home/issues/2892)

* NuGet update through package manager removes properties from the project.json - [#2888](https://api.github.com/repos/NuGet/Home/issues/2888)

* NuGet.PackageManagement.VisualStudio try to load "NuGet.TeamFoundationServer14", but that dll name changed to "NuGet.TeamFoundationServer" - [#2857](https://api.github.com/repos/NuGet/Home/issues/2857)

* Package manager UI doesn't show newly updated version - [#2828](https://api.github.com/repos/NuGet/Home/issues/2828)

* E2E tests fail due to ActivityCorrelationContext - [#2784](https://api.github.com/repos/NuGet/Home/issues/2784)

* update-package trying to use packageid,version instead of package.version - [#2771](https://api.github.com/repos/NuGet/Home/issues/2771)

* nuget restore project.csproj should error if the project isn't using nuget (p.config or p.json) - [#2766](https://api.github.com/repos/NuGet/Home/issues/2766)

* TFS Error "[file]not be found in your workspace, or you do not have permission to access it"  during upgrade or uninstall when solution/project is bound to TFS source control - [#2739](https://api.github.com/repos/NuGet/Home/issues/2739)

* update package doesn't get dependencies for non-target packages - [#2724](https://api.github.com/repos/NuGet/Home/issues/2724)

* There is no way to set logs verbosity level for Nuget package manager UI actions - [#2705](https://api.github.com/repos/NuGet/Home/issues/2705)

* nuget configuration is invalid - VS 2015 VSIX (v3.4.3) - [#2667](https://api.github.com/repos/NuGet/Home/issues/2667)

* pack from .csproj and .nuspec content regression from 3.3 - [#2658](https://api.github.com/repos/NuGet/Home/issues/2658)

* DefaultPushSource in NuGetDefaults.config (ProgramData\NuGet) doesn't work - [#2653](https://api.github.com/repos/NuGet/Home/issues/2653)

* nuget 3.4.3 release -  getting Value cannot be null on package build - [#2648](https://api.github.com/repos/NuGet/Home/issues/2648)

* restore is not using stored credentials from nuget.config for VSTS feeds - [#2647](https://api.github.com/repos/NuGet/Home/issues/2647)

* [dotnet restore] --configfile is relative to project dir instead of the cmd dir - [#2639](https://api.github.com/repos/NuGet/Home/issues/2639)

* Excessive allocations in version comparsion code - [#2632](https://api.github.com/repos/NuGet/Home/issues/2632)

* Multiple instances of nuget.exe trying to install the same package in parallel causes a double write - [#2628](https://api.github.com/repos/NuGet/Home/issues/2628)

* Dependency information is not cached for multi-project operations - [#2619](https://api.github.com/repos/NuGet/Home/issues/2619)

* Install and update download packages without checking the packages folder first - [#2618](https://api.github.com/repos/NuGet/Home/issues/2618)

* If package source list is empty, cannot add package source via UI (NuGet 3.4.x) - [#2617](https://api.github.com/repos/NuGet/Home/issues/2617)

* Misleading error when attempting to install package that depends on design-time facades - [#2594](https://api.github.com/repos/NuGet/Home/issues/2594)

* Installing a package from PackageManager console with setting "All" tries only first source - [#2557](https://api.github.com/repos/NuGet/Home/issues/2557)

* Latest beta not unzipping ModernHttpClient - [#2518](https://api.github.com/repos/NuGet/Home/issues/2518)

* VS2015 crash at startup with self-built NuGet 3.4.1 - [#2419](https://api.github.com/repos/NuGet/Home/issues/2419)

* Update command might be a bit more verbose if i ask it to be so... - [#2418](https://api.github.com/repos/NuGet/Home/issues/2418)

* VSIX built locally should have the same dlls and files as the CI build. - [#2401](https://api.github.com/repos/NuGet/Home/issues/2401)

* Failing to authenticate package source (3 times) is blocked forever - [#2362](https://api.github.com/repos/NuGet/Home/issues/2362)

* Package content is not restored correctly when installing a package from a nuget v3.3+ feed with the argument -NoCache when the package contains *.nupkg files - [#2354](https://api.github.com/repos/NuGet/Home/issues/2354)

* Nuget Install with All Package Sources, but package missing from 1 source, fails - [#2322](https://api.github.com/repos/NuGet/Home/issues/2322)

* [PerfWatson] UIDelay: nuget.packagemanagement.visualstudio.dll!NuGet.PackageManagement.VisualStudio.VSMSBuildNuGetProjectSystem+<>c__DisplayClass_0+<<AddReference>b__>d.MoveNext - [#2285](https://api.github.com/repos/NuGet/Home/issues/2285)

* Install blocks if a single source fails authorization - [#2034](https://api.github.com/repos/NuGet/Home/issues/2034)

* nuspec version range should override -IncludeReferencedProjects version - [#1983](https://api.github.com/repos/NuGet/Home/issues/1983)

* NuGet stealth downgrades package when batch updating its dependencies - [#1903](https://api.github.com/repos/NuGet/Home/issues/1903)

* NuGet 3.3.0 update fails with 'An additional constraint ... defined in packages.config prevents this operation.' - [#1816](https://api.github.com/repos/NuGet/Home/issues/1816)

* nuget.exe update drops the assembly strong name and Private attribute. - [#1778](https://api.github.com/repos/NuGet/Home/issues/1778)

* Relative file path for "DefaultPushSource" - [#1746](https://api.github.com/repos/NuGet/Home/issues/1746)

* Improve resolver failure messages - [#1373](https://api.github.com/repos/NuGet/Home/issues/1373)

* update-package in v3 fails with packages not in the specified source - [#1013](https://api.github.com/repos/NuGet/Home/issues/1013)

* Using relative paths for package sources is problematic to use - [#865](https://api.github.com/repos/NuGet/Home/issues/865)

* Missing dependency in NUPKG-file generated from project if indirect dependency already exists with a lower version requirement - [#759](https://api.github.com/repos/NuGet/Home/issues/759)

* Deleting a project closes corresponding UI window, but, renaming a project does not rename the UI window. Note that PMC listens to project rename and project remove events - [#670](https://api.github.com/repos/NuGet/Home/issues/670)

**DCR:**

* Move NuGet to depend on v1.0 of CoreFX/CoreCLR/etc... - [#2967](https://api.github.com/repos/NuGet/Home/issues/2967)

* Update CoreCLR/CoreFX that NuGet uses to rc3-24210-10 - [#2957](https://api.github.com/repos/NuGet/Home/issues/2957)

* Mark our nupkgs as serviceable - [#2952](https://api.github.com/repos/NuGet/Home/issues/2952)

* dotnet pack needs to be able to set serviceable in output .nuspec - [#2900](https://api.github.com/repos/NuGet/Home/issues/2900)

* Replace Microsoft.Extensions.PlatformAbstractions with System.Runtime.InteropServices.RuntimeInformation - [#2890](https://api.github.com/repos/NuGet/Home/issues/2890)

* Spec, test, and doc servicable metadata in nuspec - [#2870](https://api.github.com/repos/NuGet/Home/issues/2870)

* NuGet.exe push - timeout parameter doesn't work  - [#2785](https://api.github.com/repos/NuGet/Home/issues/2785)

* nuget.exe restore doesn't produce .props and .targets files for .nuproj projects (regression in v3.4.3.855) - [#2711](https://api.github.com/repos/NuGet/Home/issues/2711)

* Need extensibility API to compare frameworks with imports - [#2633](https://api.github.com/repos/NuGet/Home/issues/2633)

* Hide dependency options when using project.json - [#2486](https://api.github.com/repos/NuGet/Home/issues/2486)

* Update dev branch, build, and related to create 2 VSIXes for Dev14 and Dev15 - [#2386](https://api.github.com/repos/NuGet/Home/issues/2386)

* Print out NuGet.exe version header in detailed output - [#1887](https://api.github.com/repos/NuGet/Home/issues/1887)

**Feature:**

* NuGet should add support for /runtimes/{rid}/nativeassets/{txm}/ - [#2782](https://api.github.com/repos/NuGet/Home/issues/2782)

* Add framework compatibilities missing in NuGet 2.x (which are already in 3.x) - [#2720](https://api.github.com/repos/NuGet/Home/issues/2720)

