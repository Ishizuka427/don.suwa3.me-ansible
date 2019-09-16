# don.suwa3.me-ansible  - どんすわ構成管理
![don suwa3 me-top](https://user-images.githubusercontent.com/45281231/64934735-c5123480-d887-11e9-9257-c0d55618db00.png)

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
