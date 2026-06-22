Установка Ansible:
```
sudo apt install ansible -y
```
Проверяем корректность установки и версию пакета:
```
ansible --version
```
Запуск плейбука:
```
ansible-playbook -i inventory lab-nginx.yml 
```
