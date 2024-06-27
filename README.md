Импорт данных через Postman в Altcraft Platform
1.	Установка Postman:
•	Перейдите по ссылке: Скачать Postman.
•	Нажмите «Windows 64-bit» для скачивания программы.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/1af21d9b-4607-457b-989f-f9837fc5ba1e)
•	Запустите скачанный установочный файл и следуйте инструкциям мастера установки для завершения процесса.

2.	Запуск Postman и регистрация:
•	После установки запустите программу Postman. 
•	Создайте учётную запись или войдите в существующую.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/2fb06bcc-8bc5-4a21-9c9a-6134ea2e36af)

3.	Создание запроса для импорта данных:
•	Нажмите «New» и выберите вкладку «HTTP» во всплывающем окне.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/d87e1042-a5ca-4a82-bbfc-3cf4696ba7ed)

4.	Настройка запроса:
•	Для того, чтобы дать название вашему запросу, нажмите «Save».
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/ed744237-5be4-4682-9a8a-0f41969405fd)
•	В появившемся окне введите название вашего запроса, например, «Data import».
•	Выберите коллекцию для сохранения запроса или создайте новую, например, «Altcraft».
•	Нажмите «Save» для сохранения.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/24d8af15-9555-4d53-94ed-14dcf23f83e4)


5.	Указание URL и метода запроса:
•	Введите URL: https://polina-zakaryan.dev.altkraft.com/api/v1.1/profiles/import .
•	Убедитесь, что метод запроса установлен на «POST».
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/e1d9ace6-a9b0-40fa-a444-6d6ac3a7beef)

6.	Создание «тела» запроса:
•	Перейдите во вкладку «body» и выберите опцию «raw».
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/8568e054-014d-4a32-97d2-efd63852c77a)
•	Вставьте данный JSON-код в поле ввода:

{

"token": "9746300b70c4427e89049b7f9b0fe019",

"db_id": 83,

"matching": "email",

"email": "example@example.com",

"_bdate": "2004-06-26",

"data": {

"_fname": "John",

"_lname": "Doe"

}

}

	Обратите внимание, что в поле _bdate нужно будет указать текущую дату минус 20 лет.

7.	Отправка запроса:
•	Нажмите кнопку «Send». Внизу экрана вы увидите ответ сервера. Если данные были успешно импортированы, вы получите сообщение об успешном завершении операции.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/2a1f31bd-8553-4f50-ac32-34710a4d7bb9)

 

 
Importing Data to Altcraft Platform via Postman
1.	Installing Postman:
•	Follow the link: Download Postman.
•	Click “Windows 64-bit” to download the program.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/1af21d9b-4607-457b-989f-f9837fc5ba1e)
•	Run the downloaded installation file and follow the installation instructions to complete the process.

2.	Launching Postman and Registration:
•	After installation launch the Postman program.
•	Create an account or log in to an existing one.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/2fb06bcc-8bc5-4a21-9c9a-6134ea2e36af)

3.	Creating a request for data Import:
•	Click " New " and select the " HTTP " tab in the pop-up window.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/d87e1042-a5ca-4a82-bbfc-3cf4696ba7ed)

4.	 Setting up the request:
•	To give your request a name, click “ Save ”.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/ed744237-5be4-4682-9a8a-0f41969405fd)
•	In the pop-up enter the name of your request, for example, “Data import".
•	Select a collection to save the request to, or create a new one, for example, "Altcraft".
•	Click "Save" to save the settings.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/24d8af15-9555-4d53-94ed-14dcf23f83e4)

5.	Specifying the URL and Request Method:
•	Enter the URL: https://polina-zakaryan.dev.altkraft.com/api/v1.1/profiles/import .
•	 Ensure the request method is set to “POST”.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/e1d9ace6-a9b0-40fa-a444-6d6ac3a7beef)

6.	Creating the request body:
•	Go to the "body" tab and select the "raw" option.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/8568e054-014d-4a32-97d2-efd63852c77a)
•	Paste the following JSON code into the input field:
{

"token": "9746300b70c4427e89049b7f9b0fe019",

"db_id": 83,

"matching": "email",

"email": "example@example.com",

"_bdate": "2004-06-26",

"data": {

"_fname": "John",

"_lname": "Doe"

}

}


	Note that the _bdate field should contain the current date minus 20 years.

7.	Sending the request:
•	Click the " Send " button. At the bottom of the screen you will see the server response. If the data was successfully imported, you will receive a success message.
![image](https://github.com/ntrukhnin/ntrukhnin/assets/173993952/2a1f31bd-8553-4f50-ac32-34710a4d7bb9)

