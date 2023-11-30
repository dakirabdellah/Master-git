1. git init : command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.
2. git clone : is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location __Exemple__: `git clone https://github.com/dakirabdellah/Master-git.git`
    * Cloning to a specific folder: `git clone <repo> <directory>`
    * `git clone -branch` : The -branch argument lets you specify a specific branch to clone instead of the branch the remote HEAD is pointing to, usually the main branch. In addition you can pass a tag instead of branch for the same effect.
3. Git config : The `git config` command is a convenience function that is used to set Git configuration values on a global or local project level.
    * Usage :
        * `git config user.email "dakir@email.com"`
        * `git config user.name "dakir"`
    * git config levels and files
        * `--local`: By default, `git config` will write to a local level if no configuration option is passed.
        * `--global`: Global level configuration is user-specific, meaning it is applied to an operating system user.
            * Exemple: `git config --global user.email "dakir@email.com"`
4. Git alias : This section will focus on Git aliases. To better understand the value of Git aliases we must first discuss what an alias is. The term alias is synonymous with a shortcut.
    * Overview : `git config --global alias.co checkout`
        * Exemple : <br>`git co master` == `git chechout master`