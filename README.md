# opencart_payment_gateway_v3.x
Расширение платежный шлюз Woopkassa для CMS OpenCart. Версия 3.*

## Требования:
Для работы модуля должно быть установлено и включено PHP расширение SOAP.

## Установка
1. Авторизоваться в Opencart под своим логином и паролем, веденные при установке.
2. Скопировать папки Admin и Catalog в архиве модуля и вставить в директорию Opencart на компьютере.
![Alt text](.README/opencart_1.png?raw=true)
3. Перейти на страницу Extensions, выбрать extension type: Payments. В списке найти Wooppay или Wooppay Mobile, в зависимости от того, какой модуль устанавливается.
![Alt text](.README/opencart_2.png?raw=true)
4. Нажать на Edit, ввести данные: логин и пароль - от кабинета мерчанта, в URL ввести ссылку WSDL из кабинета мерчанта: авторизоваться в кабинете мерчанта, перейти в раздел Online приём платежей, затем на страницу WSDL. На странице две ссылки для тестового и боевого сервера. Выбрать нужный сервер, скопировать и вставить в поле URL. Сохранить данные.
![Alt text](.README/opencart_3.png?raw=true)
5. Перейти в System->Users->User Groups->Edit Administrator, найти нужный модуль, поставить галочку и сохранить.
![Alt text](.README/opencart_4.png?raw=true)
6. Перейти в магазин, выбрать товар и произвести оплату.
