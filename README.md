# Js Advice - Thinking JavaScript as Ninja

<!-- Replace this badge with your own-->
[![Build status](https://ci.appveyor.com/api/projects/status/hv6uyc059rqbc6fj?svg=true)](https://ci.appveyor.com/project/madskristensen/extensibilitytools)

<!-- Update the VS Gallery link after you upload the VSIX-->
Download this extension from the [VS Gallery](https://visualstudiogallery.msdn.microsoft.com/[GuidFromGallery])
or get the [CI build](http://vsixgallery.com/extension/8e5bc658-1ed9-4839-939b-204b758063a6/).

---------------------------------------

![Context Menu](art/logo/coruja-175x175.png) ![Context Menu](art/logo/js-advice-350.png)


Js Advice is a JavaScript code analyzer. Checking possible errors or bad practices will advise possible changes, in JavaScript code. By Light bulb (Visual Studio 2015) and intuitive menu.

See the [changelog](CHANGELOG.md) for changes and roadmap.

## Features

- Using the Light Bulb Visual Studio 2015.
- Code fixed to Equals Operators
- Code fixed to Unequal Operators
- Code fixed to include Semicolon in end the command

### Light Bulb Visual Studio 2015:
Using the Light Bulb Visual Studio 2015:

![Context Menu](art/features/LightBulb.png)

### Equals Operators:
In code that equality comparison is with two equal (==), then will be shown an improvement (press 'ctrl + .' or click in light bulb), to use three equal (===). Indicating how it will look the result.  

![Context Menu](art/features/EqualOperators1.png)

Pressing enter or clicking on the suggestion, will apply.

![Context Menu](art/features/EqualOperators2.png)

### Unequal Operators
When writing an unequal code '! =', It will be suggested to use '! ==' (press 'ctrl + .' or click in light bulb).

![Context Menu](art/features/UnequalOperators.png)

Suggestion apply:

![Context Menu](art/features/UnequalOperators2.png)

### Include Semicolon in end the command
When writing code that has no semicolon (;) at the end of the command will be suggested place.

![Context Menu](art/features/IncludeSemicolon.png)

Suggestion apply:

![Context Menu](art/features/IncludeSemicolon2.png)

## Contribute
Check out the [contribution guidelines](CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)