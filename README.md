# MonoDotSettings
MonoDotSettings is a basic Resharper theme to respect the mono project coding style.

## How to use it

Resharper supports option layering.

You would use it like this:

1. Have one DotSettings file with all your settings in it.
2. For each solution perform these steps:
    1. ReSharper -> Manage Options
    2. Right-click "Solution 'Your Solution' team-shared"
    3. Select Add Layer -> Open Settings File
    4. Choose the central DotSettings file

[source](http://stackoverflow.com/a/14896788/1248177)

## Source

* [Cecil](https://raw.githubusercontent.com/jbevain/cecil/master/Mono.Cecil.sln.DotSettings)
* [Unity](https://raw.githubusercontent.com/anchan828/monodevelop-code-template-unity/master/ReSharper/UnityC%23.DotSettings)
