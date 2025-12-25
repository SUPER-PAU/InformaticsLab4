<img width="896" height="293" alt="image" src="https://github.com/user-attachments/assets/63505a76-d965-4a65-a289-514da32f7cb3" /># Пример
<img width="597" height="186" alt="image" src="https://github.com/user-attachments/assets/680e1b08-bc1d-4959-9a9d-037dd86b9da4" /># Установка и настройка
1. Устанавливаю Docker Desctop.
2. Создаю пустой файл Dockerfile на компьютере, в котором пишу
<img width="1215" height="142" alt="image" src="https://github.com/user-attachments/assets/0a4a0fe7-699e-48be-811d-c3e9c7dbcb95" />

3. делаю сборку на основе файла.

<img width="1097" height="415" alt="image" src="https://github.com/user-attachments/assets/0fc6672a-68e3-48ef-8284-7d87fa46a462" />

4. Далее запускаю контейнер на основе созданного образа.
5. Ввожу команду в терминал `docker run cowsay /usr/games/cowsay "Moo"`
<img width="643" height="174" alt="image" src="https://github.com/user-attachments/assets/be65fa91-e905-4459-902a-ba7d048ec3d5" />

# Задание

1. Создаю новый Dockerfile, в котором прописал образ и установку iputils-ping и libaa-bin 
<img width="597" height="186" alt="image" src="https://github.com/user-attachments/assets/6b43a97d-6ca0-4b89-9140-38875595b02d" />

2. Затем анологично собрал образ с тегом aafire
<img width="1093" height="366" alt="image" src="https://github.com/user-attachments/assets/23236584-005b-42ef-b04b-69b0f4068d24" />
<img width="962" height="152" alt="image" src="https://github.com/user-attachments/assets/9a6bba34-20cb-4d6a-b88f-2251d7aa432b" />

3. запустил aafire
<img width="434" height="13" alt="image" src="https://github.com/user-attachments/assets/5df10321-fdbf-4fab-b27a-6572e5ddebb0" />
и в строке ввел aafire
<img width="1125" height="624" alt="image" src="https://github.com/user-attachments/assets/c4579f75-d71d-4999-b4f3-8e12b47acb11" />


4. Далее я создал 2 новых контейнера и запустил их в разных терминалах.
<img width="1860" height="656" alt="image" src="https://github.com/user-attachments/assets/59d4d7b4-e6dc-4855-8b48-aecd44d84548" />

5. Создаю сеть в 3-м окне терминала и подключил оба контейнера к ней.
<img width="896" height="293" alt="image" src="https://github.com/user-attachments/assets/2563eb7b-60cd-44f9-9f7b-530d72b7df90" />

6. В настройках сети увидел оба контейнера
<img width="868" height="306" alt="image" src="https://github.com/user-attachments/assets/635567d2-bd49-4379-a24c-4f36aa4b20d5" />

7. Проверил связь контейнеров в обе стороны
<img width="1024" height="595" alt="image" src="https://github.com/user-attachments/assets/3b76f5de-63ef-473a-aa48-2163dc53f32b" />
