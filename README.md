# cookiecutter-rimworld-mod-development-vscode-sdk
is a modified version of the original [cookiecutter-rimworld-mod-development](https://github.com/n-fisher/cookiecutter-rimworld-mod-development) template that works out the box with vscode and c# dev kit extension 

### Requires 
- [cookiecutter](https://github.com/audreyr/cookiecutter) (or `pip install cookiecutter`)

##### Usage (You can develop from any directory)
1. `cookiecutter gh:UsernameRando/cookiecutter-rimworld-mod-development-vscode-sdk`
2. Follow the prompts
3. Open mod development directory
4. use `dotnet build --configuration Release` to build the `(ModName).dll` into `Common\Assemblies` and will automatically copy `(ModName)\Common\` to `RimWorld\Mods\(ModName)\.` As well as copy `(ModName)\About` to `RimWorld\Mods\(ModName)\About`


