# Lab-07
## Exercise 1 - Add sumbodule
In this exercise, we will add submodule to an exisiting repository.
We will also change the repository pointer to several commits in the submodule

#### Cloning a repo
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL https://github.com/noama-demo/Lab07-ex1.git and choose clone

#### Adding submodule
- On the Left Panel
    - Expand Submodules
    - Right Click 'Lab07-ex1 (master)' and choose manage
    - Click 'Add submodule'
    - In 'Path for submodule', enter: https://github.com/noama-demo/Lab07-ex1.common.git (the local path should be automatically filled)
    - Click Add

#### Review and commit of the submodule
- On the Button Bar, Click Commit button
    - Review the files to be commited and their content:
        - .gitmodules
        - Lab07-ex1.common folder
    - Add to stage using the purple arrows, if required
    - Comment (adding common submodule) and commit

#### Review the submodule
- Checkout master branch
- On the Split-View -> File Tree
    - Examine the new folder Lab07-ex1.common
    - Double click the new folder Lab07-ex1.common and see what happens
- On the Left Panel
    - Expand Submodules
    - Expand 'Lab07-ex1 (master)'
    - Double click 'Lab07-ex1.common' and see what happens
- Note: Examine the Button Bar -> Change Working directory button (the long one with the file path)

## Exercise 2 - Update submodule
In this exercise, we will update a submodule and see how it reflect in the parent repo 
Continue using the same repo as before

#### Selecting the submodule
- On the parent repo (Lab07-ex1)
    - Expand Submodules
    - Expand 'Lab07-ex1 (master)'
    - Double click 'Lab07-ex1.common', you are now moved to the submodule repo
    - Checkout master branch

#### Updating the submodule
- On the Button Bar, click the File Explorer and add another file common3.txt
- Commit your changes (locally)
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add a message
    4. Click commit

#### Updating the parent repo
- On the Left Panel
    - Expand Submodules
    - Double click 'Lab07-ex1' to get back to the parent repo
- Examine the parent repo changes
    - Examine the changes in the Commit Index 
    - Make sure you understand the SHA1 changes
- Commit your changes (locally)
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add a message
    4. Click commit
