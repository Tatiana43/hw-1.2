# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

07.11 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 30 минут.

В результате тестирования выявлены следующие дефекты:
* [Валидный номер кредитной карты American Express выдается невалидным](https://github.com/Tatiana43/hw-1.2/issues/2)
* [Валидный номер кредитной карты Diners Club - Carte Blanche выдается невалидным](https://github.com/Tatiana43/hw-1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1)

В качестве тестовых данных использовались данные валидные [номера кредитных карт](freeformatter.com):
* VISA: 4539945594523431
* Discover: 6011790907449607
* Diners Club - Carte Blanche: 30004137576803
* Visa Electron: 4026209027687135
* MasterCard: 5166525127950421
* JCB: 3538462612042165
* InstaPayment: 6388408905595660
* American Express (AMEX): 347563254151466
* Diners Club - North America: 5537879664714480
* Maestro: 5020864865574051

Тестирование производилось в следующем окружении:
* ОС Windows 10 x64
* OpenJDK 11.0.9
* IntelliJ IDEA version 2020.2.3