# Setup
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install ansible

# Execute
ansible-playbook main.yml
ansible-playbook main.yml --tags {tag}


