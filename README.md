# Solution1

Solution1 is a Visual Studio 2010 playground of unused C# and VB.NET starter templates; the solution file does not reference them. Four sibling project folders sit next to an empty Format 11.00 `Solution1.sln` that has no Project entries (only Global/HideSolutionNode). ConsoleApplication1 prints Hello World from `First.MyFirstClass`; ConsoleApplication2 is a stock empty VB.NET module; WindowsApplication1 is an empty VB.NET WinForms Form1; WindowsFormsApplication1 is a stock C# WinForms form plus Program.cs.

**Source last updated:** 2011-05-02 · **Language:** C# / VB.NET · **Target:** .NET Framework 4.0 Client Profile (Visual Studio 2010) · **Output:** unused console and WinForms starter templates

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ConsoleApplication1` | C# | Console Exe | Starter Main: namespace `First`, class `MyFirstClass`, writes Hello World |
| `ConsoleApplication2` | VB.NET | Console Exe | Stock empty `Module1` with empty `Sub Main` |
| `WindowsApplication1` | VB.NET | WinForms WinExe | Empty `Form1` class (~36 bytes) |
| `WindowsFormsApplication1` | C# | WinForms WinExe | Stock empty Form1 plus `Program.cs` entry point |

## How to open

`Solution1.sln` is Visual Studio 2010 Format 11.00 with no Project entries, so opening the solution does not load any of the four projects. Open each project file directly in Visual Studio 2010 (or later with .NET Framework 4.0 targeting): `ConsoleApplication1/ConsoleApplication1.csproj`, `ConsoleApplication2/ConsoleApplication2.vbproj`, `WindowsApplication1/WindowsApplication1.vbproj`, `WindowsFormsApplication1/WindowsFormsApplication1.csproj`.

## Requirements

- Visual Studio 2010, .NET Framework 4.0

## Attribution and provenance

Working copy from my Historical Dev folder `Solution1`. Assembly company and copyright on all four projects are Visual Studio template defaults: Microsoft / Copyright © Microsoft 2011. ProductVersion 8.0.30703 (C# projects); ToolsVersion 4.0.

## License

MIT. Copyright (c) 2026 VaderConsulting, for Dave Robinson's code. See `LICENSE`.
