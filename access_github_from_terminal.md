# Initial setup 

1. Create an account on github.com
2. Check the availability of git command on your terminal
3. Set global parameters user.name and user.email
4. Create a key pair
5. Copy the public key on your github account setup page

# For each repository,

1. Create a repository on github
2. Show a ssh url for the repository
3. Clone the repository with the ssh url
4. Set a parameter for ssh command with your private key file: git config core.sshCommand "ssh -i full_path_for_your_priv_key_file"
5. Check the url for the origin (remote): git config --local -l
6. If it's using https, change to ssh: git remote set-url origin git@github.com:your_username/repository_name.git

