# ansible-playbooks
## Mac book（作業端末）へのansibleインストール
### brewのインストール　※必要に応じて実施
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### ansibleのインストール
```bash
brew install ansible
```

### ansible playbookの実行
```bash
ansible-playbook -i inventory.yml playbook.yml --ask-become-pass
```