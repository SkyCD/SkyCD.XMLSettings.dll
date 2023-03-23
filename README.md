[![Latest Release](https://img.shields.io/github/v/release/SkyCD/SkyCD.XMLSettings.dll)](https://github.com/orgs/SkyCD/packages/nuget/package/SkyCD.XMLSettings.dll)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/SkyCD/SkyCD.XMLSettings.dll/blob/main/LICENSE)


# SkyCD.XMLSettings.dll

SkyCD.XMLSettings.dll is a library that allows you to read and write settings in XML format. It provides the following class:

#### XMLSettings

The XMLSettings class provides the following methods:

- `Sub New(ByVal FileName As String)`: Initializes a new instance of the XMLSettings class with the specified file name.
- `Public Sub WriteSetting(ByVal Category As String, ByVal Name As String, ByVal Value As String)`: Writes the specified setting to the file.
- `Public Sub Save()`: Saves the current settings to the file.

## License

This project is licensed under the terms of the MIT license. You can find the full license text in the [LICENSE](LICENSE) file.
