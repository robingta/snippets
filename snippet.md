
alias bitbucket_token="echo 'ATBBKy8GJuT3gwTJG36RbTmvae6pD15C9151'"
alias github_token="echo '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'"
alias gta_github_token="echo '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'"
alias gta_github_user="git config --global user.email 'robin@primtechs.com' && git config --global user.name 'robingta'"
alias github_user="git config --global user.email 'sk118420@gmail.com' && git config --global user.name 's1k3'"
alias edit_path="sudo nano ~/.bashrc"
alias smart_school_ssh="sudo ssh -i '/var/pem/school_project_test.pem' ubuntu@ec2-34-234-17-110.compute-1.amazonaws.com"
alias smart_school_sftp="sudo sftp -i '/var/pem/school_project_test.pem' ubuntu@ec2-34-234-17-110.compute-1.amazonaws.com"
alias nsaa_dev_ssh="sudo ssh -i '/var/pem/NSAA.pem' ubuntu@52.14.190.112"
alias nsaa_dev_sftp="sudo sftp -i '/var/pem/NSAA.pem' ubuntu@52.14.190.112"

export PATH="$PATH:$HOME/.config/composer/vendor/bin"

function switch(){
  sudo update-alternatives --config "$1";
}
