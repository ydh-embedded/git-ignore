
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


## push an excisting repository from the command line

## Step 1
        git remote add origin https://github.com/ydh-embedded/svg.git
## Step 2
        git branch -M main
## Step 3
        git push -u origin main
## Tracking Information
        git branch --set-upstream-to=origin/<branch> main
## fetch
        git fetch
## remote Repo ziehen / download
        git pull