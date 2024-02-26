
## Step 1
        echo "# test" >> README.md
## Step 2
        git init
## Step 3
        git add README.md
## Step 4
        git commit -m "first commit"
## Step 5
        git branch -M main
## Step 6
        git remote add origin https://github.com/ydh-embedded/test.git
## Step 7
        git push -u origin main




## >> C: \working-directory\gitHUB > git init
        Initialized empty Git repository in C:/working-directory/gitHUB/.git/
## >> C: \working-directory\gitHUB > git add .        
        warning: adding embedded git repository: git-ignore
.

        hint: You've added another git repository inside your current repository.
        hint: Clones of the outer repository will not contain the contents of    
        hint: the embedded repository and will not know how to obtain it.        
        hint: If you meant to add a submodule, use:
        hint: 
        hint:   git submodule add <url> git-ignore
        hint: 
        hint: If you added this path by mistake, you can remove it from the      
        hint: index with:
        hint: 
        hint:   git rm --cached git-ignore
        hint: 
        hint: See "git help submodule" for more information.
## PS C:\working-directory\gitHUB>