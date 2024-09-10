How to propose submodule?

Authenticate with GitHub CLI:

Bash
gh auth login


Fork and Clone the Repository:

Bash
gh repo fork <original-owner>/<repository-name>


Navigate into the Cloned Repository:

Bash
cd <repository-name>


Create a New Branch:

Bash
git checkout -b my-new-feature


Clone proposed tool inside selected category:
cd Productivity/
git clone https://github.com/oscarpobleteanahuac/EthicalSign.git

Add module:
git submodule add https://github.com/oscarpobleteanahuac/EthicalSign.git EthicalSign





Stage module:

Bash
# Make your changes using your preferred text editor or IDE
git add .  

Commit Your Changes:

Bash
git commit -m "A descriptive commit message about your changes"

Push Your Changes to Your Fork:

Bash
git push origin my-new-feature


Create a Pull Request:

Bash
gh pr create --title "My New Feature" --body "A detailed description of the changes in this pull request"


Important Notes:

Replace placeholders like <original-owner>, <repository-name>, and my-new-feature with the actual names.
You can customize the title and body of the pull request in the gh pr create command.
Make sure you have the GitHub CLI installed and authenticated before running these commands.
