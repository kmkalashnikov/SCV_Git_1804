# Репозиторий для **pull request**
* В своём аккаунте на GitHub создать копию репозитория **"AndreyBulgakov19
/SCV_Git_1804"** с помощью кнопки **"Fork"**.
---
* Клонировать копию репозитория на локальный компьютер.
---
* Создать новую ветку.
---
* Добавить файл с инструкцией в новую ветку.
---
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
---
* Зафиксировать изменения (коммиты).
---
* Отправить изменения на GitHub.
---
* На сайте GitHub выполнить **Pull request**.
---
![dart vader saluts you](vader.jpg)

# **_GIT + .MD MANUAL_**

## GIT

First of all you need to introduse your self to git, and put in your email

    git config --global username
    git config --global useremail

Then, to make sure that everything is ok, you must enter the command  **_git version_**. If git shows his version, then everything is ok.


**_git init_** to make a repository, or **_git clone adress_** to get existing

**_git add folder.name/file.name_** to track the file. Its need to be done for each file, and before command **_git commit_**. 

**_git commit_** command to commit. If you want to add comment, then type **_git commit -m "comment"_**. Without command **_git add folder.name/file.name_** before, git will commit all uncommited files. If the is only one file, or you want to commit all files, you can enter command **_git commit -a -m "comment"_**. **_-m_** is used to add comment, _**-a**_ means "add". Before you commit, do not forget to save your text!!!

**_git status_** shows untracked files, branch, modifed files, and other information. Add **_-s_** to get short version

**_git log_**  to see all commits that has been done. Add **_--oneline_** to see commits as a list.Name of commits are shown as hash code.

**_git commit --amend -m "comment'_** gives you oportunity to edit your last comment in the last commit

**_git checkout branch.name\hash.code_** is the comand to switch on needed brunch or commit. Main brunch named "master". Olso you can use command **_git switch_** to return on master brunch

**_git diff_** command, shows differens beetwen last commit and what you have now

**_git rm --cached file.name/folder.name_** to stop tracking file/folder

**_git reflog_** shows you a log of what was done

After eny command you can add **_-h_** (means "help") and terminal will show you full list of what you can do with this command

## .MD

*italics font*

_italics font_

**bold font**

__bold font__

**_combine * and _ to get both italics and bold font_**

* list
* list
1. list
2. list

# title

## subtitle

~~strikethrough text~~

    use empty line and prees "tab" on the next line to get selection like this


# **_Second home work_**

## **_GIT_**

**_git branch_** to see on what branch you are now

**_git branch branch.name_** to create a new brunch. Use **_git checkout_** to switch beetwen branches

**_git swith -_** to retun on master branch (or **_git checkout master_**)

**_git merge branch.name_** inserts information from branch.name to branch, on which you are now. Lets supose that you made new branch wich named "new" (i did it) and in this branch you edited some line (line 71). Now, this line, looks different in master and new branch. When you will merge new branch to master, there will be a conflict, which git will offer you to solve. Git will give you opportunity to accept curent changes? to accept incoming changes, to accept both changes, and compare changes.

**_git branch -d branch name_** to delete branch

**_git rm file.name_** to delete file

**_git log --graph_** shows log with branches


## **_.MD_**

To insert a picture in your .md file print ![text which would be shown, if something wrong with picture](adress of picture). I did it in the begining

Usually pictures are not to be commited, and for this occasion you can create file **_.gitignore_** and add exstentions which are not to be included. This file you must add and commit as always

# **_GitHub_**

GitHub (GH) is used to save your projects in internet. First of all you need to create an account in GH, make a repisitory in it by using hints, and then, using hints you can add you existing local repositiry on GH.

**_git remote add origin url.adress_** shows git url adress(the path), where it will soon save our repositiry, which is local at the moment. 

**_git branch -M main_** to rename master branch as main (i do not know why we need to do this, but i promise i will learn more info about it)

**_git push -u main_** to push you local repository to GH

Last 3 commands will allow you to create copy of your  local repository in GH.

**_git remote -v_** is command to check url adress of GH repository (to make sure that you are doing everything right)


At this stage i broke eberything including all the commits, that has been done :( but it is not the reason to give up, everything happens

**_git push_** to push commited files to GH

Usually users are creating file README to give anither people an understanding about this file

**_git pull_** to update local repository from GH. Yhis command will also work ass merge 

**_git clone url.adress_** clones repository from url.adress to local repository

**_cd folder.name_** to change folder

You can offer you changes to another user by doing next:

1. fork repository in GH, in which you are interersted in
2. clone it to your local repository
3. create new branch
4. add text to the new branch
5. commit it
6. push file to GH (becouse the is no new branch in GH yet)
7. do pull request