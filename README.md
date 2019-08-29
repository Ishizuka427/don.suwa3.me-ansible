# don.suwa3.me-ansible  - どんすわ構成管理

## これは何か？

- https://don.suwa3.me の構成管理
- 今の所ansibleのplaybook集

## 使い方

### cronの設定

```
ansible-playbook -i hosts cron.yml
```

## 実行環境の作成

```
python3 -m venv ./NAME
source ./NAME/bin/activate
pip install ansible
```

## 依存ツール

- Python3
- Ansible
