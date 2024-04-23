# WORKFLOW GIT
In this scenario Camilo and Steve are working together.Steve has completed the data cleaning and now Camilo will perform the statistical analysis. Here’s a straightforward, step-by-step guide with their roles clearly defined. :star2:

### Step 1: **Clone the Repository** :inbox_tray:
**Camilo:** Start by cloning the repository that Steve has been working on:
```bash
git clone https://github.com/steve-repo/data-project.git
cd data-project
```
(Replace `steve-repo` and `data-project` with the actual GitHub username and repository name.)

### Step 2: **Create Your Own Branch** :twisted_rightwards_arrows:
**Camilo:** Create a new branch for your statistics work:
```bash
git checkout -b camilo-stats
```
This makes a new branch just for the statistics analysis, keeping it separate from the main data cleaning work Steve did.

### Step 3: **Update Your Branch** :arrows_counterclockwise:
**Camilo:** Make sure your branch is updated with everything from the main branch:
```bash
git pull origin main
```
This ensures you have all the latest cleaned data that Steve prepared.

### Step 4: **Do Your Statistical Analysis** :male-technologist:
**Camilo:** Perform the statistical analysis on the cleaned data.

### Step 5: **Stage Your Changes** :performing_arts:
**Camilo:** Once you’re done, stage your changes:
```bash
git add .
```
This command stages all changed files. You can specify particular files if needed.

### Step 6: **Commit Your Changes** :floppy_disk:
**Camilo:** Commit your work with a clear message describing what you did:
```bash
git commit -m "Completed statistical analysis on cleaned data"
```

### Step 7: **Push Your Branch** :earth_africa:
**Camilo:** Push your branch up to GitHub:
```bash
git push origin camilo-stats
```

### Step 8: **Create a Pull Request on GitHub** :handshake:
**Camilo:** Go to the GitHub website, find your branch `camilo-stats`, and click "New pull request." Provide details of your analysis for Steve to review.

### Step 9: **Review and Merge the Pull Request** :link:
**Steve:** Review Camilo's pull request to ensure the statistical analysis aligns with the project goals and the data cleaning standards previously set.
- If everything looks good, **Steve** merges the pull request into the `main` branch on the GitHub website.

### Step 10: **Sync Your Local Repository** :arrows_counterclockwise:
**Both Camilo and Steve:** After the merge, both of you should update your local `main` branches:
```bash
git checkout main
git pull origin main
```
This keeps everyone's local copies up to date with the central repository.

### Step 11: **Clean Up Your Branches** :broom:
**Camilo:** After your changes are merged and everything is finalized, you can clean up by deleting your branch:
```bash
git branch -d camilo-stats
git push origin --delete camilo-stats
```

These steps should guide Camilo and Steve through a smooth collaborative workflow using Git and GitHub, keeping their roles and tasks clear throughout the project. If you need more details or further assistance with any specific part, feel free to ask! :blush:
