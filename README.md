# Lab-07
## Exercise 1 - Add sumbodule
### Overview
In this exercise, we will add submodule to an exisiting repository.
We will also change the repository pointer to several commits in the submodule

#### <u> Cloning a repo </u>
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL C:\GitServer\labs\Lab07-ex1 and choose clone
- Right click inside/on the folder and select 'GitExt open repository'

#### <u> Adding submodule</u>
- On the Left Panel
    - Expand Submodules
    - Right Click <i>Lab07-ex1 (master)</i> and choose <i>Manage</i>
    - Click <i>Add submodule</i>
    - In <i>Path for submodule</i>, enter: <i>C:\GitServer\labs\Lab07-ex1.common</i> (the local path should be automatically filled)
    - Click <i>Add</i>
    - Close the <i>Submodules</i> window

#### <u> Review and commit the submodule</u>
- On the <i>Button Bar</i>, Click <i>Commit</i> button
    - Review the files to be commited and their content:
        - .gitmodules
        - Lab07-ex1.common folder
    - Add to stage using the purple arrows, if required
    - Comment (adding common submodule) and commit

#### <u> Review the submodule</u>
- Checkout master branch
- On the Split-View -> File Tree
    - Examine the new folder Lab07-ex1.common
    - Double click the new folder Lab07-ex1.common and see what happens
- On the Left Panel
    - Expand Submodules
    - Expand 'Lab07-ex1 (master)'
    - Double click 'Lab07-ex1.common' and see what happens
- <b>Note</b>: Examine the Button Bar -> Change Working directory button (the long one with the file path)

## Exercise 2 - Update submodule</u>
In this exercise, we will update a submodule and see how it reflect in the parent repo  
Continue using the same repo as before

#### <u> Selecting the submodule</u>
- On the parent repo (Lab07-ex1)
    - Expand Submodules
    - Expand 'Lab07-ex1 (master)'
    - Double click 'Lab07-ex1.common', you are now moved to the submodule repo
    - Checkout master branch

#### <u> Updating the submodule</u>
- On the Button Bar, click the File Explorer and add another file <i>common3.txt</i>
- Commit your changes (locally)
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add a message
    4. Click commit

#### <u> Updating the parent repo</u>
- On the Left Panel
    - Expand Submodules
    - Double click 'Lab07-ex1' to get back to the parent repo
- Examine the parent repo changes
    - Examine the changes in the Commit Index 
    - Make sure you understand the SHA1 changes
- Commit your changes (locally)
    1. On the Button Bar, Press the Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add a message
    4. Click commit
