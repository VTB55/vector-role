# Домашнее задание "Тестирование roles"

1. Страница тегов на GitHub
https://github.com/VTB55/vector-role/tags

<img width="1645" height="584" alt="image" src="https://github.com/user-attachments/assets/3e13df58-401a-453d-b419-4a21af3d6757" />

2. Содержимое папки molecule/
https://github.com/VTB55/vector-role/tree/main/molecule

<img width="1372" height="342" alt="image" src="https://github.com/user-attachments/assets/fe08e50d-1bb8-4b27-a1df-66e9f51fea06" />

3. Файл tox.ini
https://github.com/VTB55/vector-role/blob/main/tox.ini

<img width="1382" height="551" alt="image" src="https://github.com/user-attachments/assets/8407f40f-0b72-40af-9df2-9df1512b6ae8" />


Ссылка на репозиторий: https://github.com/VTB55/vector-role

Вывод:
1. Созданы сценарии тестирования Molecule для vector-role:
   - molecule/default/ - сценарий с Docker драйвером
   - molecule/podman/ - облегченный сценарий с Podman драйвером
   - Добавлены assert проверки в verify.yml

2. Настроено Tox тестирование:
   - tox.ini с конфигурацией для разных версий Python и Ansible
   - .yamllint и .ansible-lint для проверки кода

3. Созданы теги:
   - v1.0.0 - реализация Molecule тестирования
   - v1.1.0 - реализация Tox тестирования

