# Adding an already existing Project to Git

## using Fork Client

- Open Fork
- Open the File Menu
- Click "Init New Repository..." ![InitNewRepository](img/ForkInitNew.png)
- Now Pick your Unity Project Folder ![UnityProjectFolder](img/ForkSelectProjectFolder.png)
- Go to [https://raw.githubusercontent.com/github/gitignore/main/Unity.gitignore](https://raw.githubusercontent.com/github/gitignore/main/Unity.gitignore)
- rightclick on the text and click "Save to" (Ger: "Speichern Unter") ![SaveTo](img/GitIgnoreSaveTo.png)
- save it in your Project Folder as ".gitignore" ![.gitignore](img/GitIgnoreSaveAs.png)
- INFO: because the .gitignore file is made specifically for unity it musst be saved in the Unity Project Folder, even if it is not the root git folder.
- after the .gitignore file was added, the Library Folder should not be shown in Fork anymore. ![IgnoredLibraryFolder](img/ForkAfterGitIgnore.png)
