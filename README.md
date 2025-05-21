# SuperMemoAssistant.Interop.dll


Updated to be compatible with JetBrains Rider IDE


Simply hit Build will generate SuperMemoAssistant.Interop.dll



Changed:

- Removed dependent SuperMemoAssistant.mshtml 7.0.3300.1, replaced by Unofficial.Microsoft.mshtml 7.0.3300 
- Lock to version 2.0.5.10 of SuperMemoAssistant.Interop.dll by switching git to commit 10/25/2020
- Update SuperMemoAssistant.Interop.csproj to use modern SDK-style, 
instead of the older non-SDK-style MSBuild format.
SDK-style WPF projects automatically include all .xaml files,
  even if they are not explicitly listed in the .csproj.
  i.e. Implicit *.xaml, *.cs, etc. include
