## EthicalTools

### How to propose submodule?

Authenticate with GitHub CLI:

```
sudo snap install gh
gh auth login
```

Fork and Clone the Repository:

```
gh repo fork https://github.com/ethicalainetwork/EthicalTools.git
```

Navigate into the Cloned Repository:

```
cd EthicalTools/
```

Create a New Branch:

```
git checkout -b my-new-feature
```

Clone proposed tool inside selected category:
```
cd Productivity/
git clone https://github.com/oscarpobleteanahuac/EthicalSign.git
```
Add module:
```
git submodule add https://github.com/oscarpobleteanahuac/EthicalSign.git EthicalSign
```




Stage module:

```
# Make your changes using your preferred text editor or IDE
git add .  
```
Commit Your Changes:

```
git commit -m "A descriptive commit message about your changes"
```
Push Your Changes to Your Fork:

```
git push origin my-new-feature
```

Create a Pull Request:

```
gh pr create --title "My New Feature" --body "A detailed description of the changes in this pull request"
```

Important Notes:

Replace my-new-feature with the actual names.
You can customize the title and body of the pull request in the gh pr create command.
