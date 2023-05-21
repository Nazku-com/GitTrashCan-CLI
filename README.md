# GitTrashCan-CLI

GitTrashCan-CLI is a command-line tool for managing Git repositories. It provides an easy way to rollback deleted commits by mistake.

https://user-images.githubusercontent.com/52348220/232210763-ff3556fc-621d-46fe-abf0-51c9493f9ba5.mov


## Installation

To install `GitTrashCan-CLI`, clone the repository and run the `install.sh` or run the command under below

```shell
git clone https://github.com/Nazku-com/GitTrashCan-CLI && cd GitTrashCan-CLI && chmod 555 ./init.sh && ./init.sh
```

This will install the gitTrashCan command-line tool to your system.

after download, reopen the terminal and use the GitTrashCan-CLI!

**Note**: If you are not using the zsh shell, you will need to manually copy the gitTrashCan file to a directory in your PATH.

```shell
cat ./gitTrashCan >> PathThatYouUse
source PathThatYouUse
```

## Usage

To use GitTrashCan-CLI, navigate to the root directory of your Git repository and run the gitTrashCan command:

```shell
cd /path/to/repo
gitTrashCan
```

This will display a list of dangling commits and prompt you to move them to a trash branch. 

enter the hash to restore and it automatically make the branch to restore

![image](https://user-images.githubusercontent.com/52348220/232210599-82289ef8-7ba2-4e70-841c-1dfcbe9df248.png)

You can also specify the path to the Git repository as an argument to the gitTrashCan command:

```shell
gitTrashCan /path/to/repo
```
This will perform the same operation on the specified repository.

## GUI Version

A graphical user interface (GUI) version of GitTrashCan is currently under development and will be released soon. Stay tuned for updates!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions to GitTrashCan-CLI are welcome! If you would like to contribute, please create a pull request on the GitHub repository.

## Credits

GitTrashCan-CLI was created by [tkgka](https://github.com/tkgka)
