# UnityGitignore

## Custom Folders
### `__NoVersionControl` 
This folder can be created inside the Unity project folder and is meant to provide a sandbox for local development without accidentally commiting its contents.

### `Assets/Plugins`
A folder used by many Asset Store plugins, which provide editor functionality, but might not be needed for the game to compile properly. If an Asset Store plugin that installs into this directory is needed for the game, you can take it out of the `.gitignore` or specify only certain subfolders instead.