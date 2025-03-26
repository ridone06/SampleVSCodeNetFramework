# SampleVSCodeNetFramework

# Install VS Code Extensions
1. C# Dev Kit
2. vscode-solution-explorer 

# Install MSBuild 2017 

# Download nuget.exe
1. Download nuget.exe from https://www.nuget.org/downloads.
2. Create a new folder in root of C drive e.g c:\nuget, copy the nuget.exe to nuget folder in c drive and paste. 
4. Go to environmental settings. Go to System Variable Section => select the variable name as Path and double click on path variable => and click on new button in the last add c:\nuget => then apply => save => save.

# Preparation
1. Rename folder .vscode-example to .vscode
2. Update tasks.json on folder .vscode
3. Update DebugType to portable on file <ProjectName>.csproj
4. Update virtualDirectory to directory your project on file applicationhost.config

# Restore package
- run cli "nuget restore <ProjectName>.sln"

# nuget CLI
- nuget install hangfire
- nuget install packages.config

# Build
1. "CTRL+SHIFT+P" => choose "Tasks:Run Task" => choose "build"

# Build and running
1. "CTRL+SHIFT+P" => choose "Tasks:Run Task" => choose "build run browse"