# openfl-custom
1. `git clone https://github.com/Misiur/openfl-custom.git`
2. Edit files in `assets/templates/project` to fit your needs
3. `cd openfl-custom`
4. `haxelib dev custom .`
5. Navigate to parent folder of your new project
6. `openfl create custom:project ProjectName`

## Caveats
In case there will be a haxelib project named `custom`, use a different name

## Roadmap
`openfl create custom:User/Template ProjectName` which will download a `https://github.com/User/Template.git` would be really nice, but that would require changes in lime core.
