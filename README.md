## Description
This is an example Ansible playbook that will join a Debian based linux server to an Active Directory domain.  Many thanks to [Wolfhaven](http://www.wolffhaven45.com/blog/linux/join_ubuntu_workstation_windows_domain/) for his blog on the topic.
This is clone original https://github.com/tvories/ansible-realmd with my local setting.

Что нужно сделать:
1) В файл /secrets.yml добавить логин пароль от пользователя вводящего комп в домен и зашифровать это ansible-vault encrypt. Исходный файл в корне /secrets-format.yml
2) В файл /vars.yml прописать все параметры для домена. Группа для админов обязательно должна начинаться с маленькой буквы (возможно это пофиксили?)

