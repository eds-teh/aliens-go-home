0.	Заходим в папку жмякаем правой кнопкой открываем гит баш
1.	Для того что бы копировать репрозиторий с сервера clone with HTTPS и копируем ссылку
	далее пишем в консоли git clone https://github.com/eds-teh/Jerto.git
2.	CD Jetro
3*	Обучение гитхаб - https://githowto.com/ru; Перед началом работы с репрозиторием его нужно инициализировать коммандой: git init в ответ получаем Initialized empty Git repository in C:/...
4.	Прописываем:
	git config --global user.name "Your Name"
	git config --global user.email "your_email@whatever.com"
5.	Сохранение
	-	git add . (возьмет все файлы которые появились)
	-	git status (узнать статус сохраняемого)
	-	git commit -m 'Added start project' (Добавляем подпись состояния он же commit)
		-	Сокращаем в одну комманду Гит аддд и Гит коммит:
			git commit -am 'update main.js'
	Комитить нужно большими и логичными блоками хедер, футер, или секшн
	*** всё это добро пока еще хранится на компьютере ***
	-	git push origin main /master (Заливаем всё на гит)

ВСЁ РАБОТАЕТ =D

6. 	Перед тем как заливать код на гит при коммандной работе, 
	нужно файлы снова стянуть с гита : git pull origin main (/master)
НО!	Перед тем как стягивать изменения свои нужно 
	сохранить иначе они перезатруутся: git commit -am 'som message'
	git status; git commit - am 'fix conflict ( ну например)'; 
	git push origin main
	И снова покругу

53:00

ssh-keygen -t rsa -C "frontendrazrabotka@gmail.com"


	
