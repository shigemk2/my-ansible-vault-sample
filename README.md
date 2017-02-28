# my-ansible-vault-sample

```sh
# 暗号化
ansible-vault encrypt private.yml
# 復号化
ansible-vault decrypt private.yml
# パスワード変更
ansible-vault rekey private.yml
# 実行
ansible-playbook -i hosts site.yml --ask-vault-pass
```
