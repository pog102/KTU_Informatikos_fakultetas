# My full-course
This should help for any Linux connoisseur newbie
# Table of contents
1. [First semester](#sem)
    1. [Modules](#modules)
    2. [Dirbtinio intelekto ekosistema](#dib)
    3. [Objektinio programavimo įvadas](#ob)
    4. [Matematika 1](#mat)
    5. [Informatikos studijų įvadas](#ifd)
    6. [Other](#ot)
## 1 Semester <a name="sem"></a>
### Modules <a name="modules"></a>
| Moddule  | Languages   |
|-------------- | -------------- |
| Dirbtinio intelekto ekosistemos | Python     |
| Matematika 1    | Matlab/octave     |
|  Objektinio programavimo įvadas | C#     |
| Informatikos studijų įvadas | HTML, CSS, Matlab, Wordpress     |
| Neuromokslas |     |
### Dirbtinio intelekto ekosistemos  <a name="dib"></a>
I use python, mate!
### Matematika 1 <a name="mat"></a>
I use octave for checking the answers
### Objektinio programavimo įvadas<a name="ob"></a>
In arch linux I installed dotnet-sdk:
```sh
sudo pacman -S dotnet-sdk
```
I use **neovim** as my IDE and for **LSP** use **csharp-language-server**

to create a project, do:
```sh
dotnet new console
```

to run the file, do:
```sh
dotnet run
```
Currently, there arent any neovim plugins for XML documentation. 
So, for documentation i use Vscode, you can find the plugin [here](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment) 
### Informatikos studijų įvadas<a name="ifd"></a>
For **Matlab** you can substitute for **Octave**,
you can find it in the repos:

```sh
sudo pacman -S octave
```
### Other<a name="ot"></a>
I use zathura as my PDF reader
```sh
sudo pacman -S zathura zathura-pdf-poppler
```
sgpt for interacting with chatgpt

```sh
pip install shell-gpt --user
```

use my neovim [config](https://github.com/pog102/installer/blob/main/config/nvim/init.lua) if you like 
