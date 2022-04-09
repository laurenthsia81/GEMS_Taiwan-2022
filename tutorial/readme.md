
# Github Tutorial

[Github](https://github.com) is an online storage for code, kinda like google drive.  
How it works is you clone a copy of the latest version of it to your local machine, you edit and make changes to the local version on your computer, then you push your local version with the latest changes to github for others to pull and update their code.

## Setup

### Step 1

**Option 1:** Download [Github Desktop](https://desktop.github.com).  

**Option 2:** Use terminal in computer (advised).

### Step 2

**Github desktop:** Clone the repo from github to your local machine.  

**Terminal:** Copy or type the following to the terminal.

```sh
git clone https://github.com/laurenthsia81/GEMS_Taiwan-2022.git
```

## Update code from github to local machine

**Github desktop:** Press pull at the top of github desktop.  

**Terminal:** Copy or type the following to the terminal.

```sh
git pull
```

## Upload code to github from local machine

**Github desktop:** Add a summary to the summary column in the bottom-left corner of github desktop, then press commit to main in the bottom-left-most corner, then press push to origin.  

**Terminal:** Copy or type the following by order.  

```sh
git add .
```
> adds current changed files to staged changes
```sh
git commit -m 'anything'
```
> commits the changes with a message describing the changes
```sh
git push
```
> pushes the code to github
