# Отчёт о тестировании <IntelliJ IDEA>

## Краткое описание

<05.10.2020> - <05.10.2020> было проведено <Функциональное тестирование, тестирование установки, системное, интеграционное > приложения <IntelliJ IDEA>.

На тестирование затрачено: <12>
В результате тестирования выявлены следующие дефекты:
* [<Дефект>](https://github.com/Stepan164i/Javaqa-DZ-1.2/issues/1)

## Описание процесса тестирования

1. Установка IntelliJ IDEA согласно [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
Ожидаемый результат:
Выполнена установка согласно [Руководства по установки
](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

2. Проверка работы IntelliJ IDEA
**Ожидаемый результат:**
Программа работает. 
![Программа работатет](https://user-images.githubusercontent.com/69162015/95088988-4acf7f00-072c-11eb-9ec0-2feae3717676.png)

3. Проверка работы программы с кодом из [Домашнего задания 1.1.2](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
**Ожидаемый результат:**
Код работает.
![Result is OK](https://user-images.githubusercontent.com/69162015/95092480-5f157b00-0730-11eb-9135-bd37897587e7.png)

В процессе тестирования использовались следующие артефакты*:
* [<Руководство по установке IntelliJ IDEA>](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* <Отчет о тестировании>

В качестве тестовых данных использовались данные <[freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)>:
* <Валидные данные>
MasterCard :
5234712827271328
5435941238577588
2720992630255761
**Ожидаемый результат :**
MasterCard :
5234712827271328 - Result is OK
5435941238577588 - Result is OK
2720992630255761 - Result is OK

**Фактический результат :**
MasterCard :
5234712827271328 - Result is OK
5435941238577588 - Result is OK
2720992630255761 - Result is OK

* <Невалидные данные>
MasterCard: 
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные>
ВИЗА :
4492890237396131
4532680913058259
4024007173215006275
**Ожидаемый результат :**
ВИЗА :
4492890237396131- Result is OK
4532680913058259- Result is OK
4024007173215006275 - Result is OK
* <Невалидные данные>
ВИЗА : 
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные>
**American Express (AMEX) :**
375330857169195
343989822427571
346738533285365

**Ожидаемый результат :**
375330857169195- Result is OK
343989822427571- Result is OK
346738533285365- Result is OK

* <Невалидные данные>
**American Express (AMEX) :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные>
Откройте для себя :
6011414041915213
6011762925527227
6011015138975798275
**Ожидаемый результат :**
6011414041915213- Result is OK
6011762925527227- Result is OK
6011015138975798275- Result is OK
* <Невалидные данные>
Откройте для себя :
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные>
**JCB :**
3544251200040505
3532414905056135
3532597416792273514
**Ожидаемый результат :**
3544251200040505- Result is OK
3532414905056135- Result is OK
3532597416792273514- Result is OK
* <Невалидные данные>
**JCB :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные>
**Diners Club - Северная Америка :**
5456247715489055
5494604964783642
5566874731274984
**Ожидаемый результат :**
5456247715489055
5494604964783642
5566874731274984
* <Невалидные данные>
**Diners Club - Северная Америка :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные
**Diners Club - Карт-бланш :**
30106354459637
30148801167033
30419480472592
**Ожидаемый результат :**
30106354459637- Result is OK
30148801167033- Result is OK
30419480472592- Result is OK

* <Невалидные данные>
**Diners Club - Карт-бланш :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные
**Diners Club - международный :**
36544962372335
36328939835966
36396398459537
**Ожидаемый результат :**
36544962372335- Result is OK
36328939835966- Result is OK
36396398459537- Result is OK
* <Невалидные данные>
**Diners Club - международный :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные
**Маэстро :**
5020709196636766
5018945324064372
6761289026026182
**Ожидаемый результат :**
5020709196636766- Result is OK
5018945324064372- Result is OK
6761289026026182- Result is OK

* <Невалидные данные>
**Маэстро :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные
**Visa Electron :**
4508879984837852
4913591453974871
4175009021807500
**Ожидаемый результат :**
4508879984837852- Result is OK
4913591453974871- Result is OK
4175009021807500- Result is OK
* <Невалидные данные>
**Visa Electron :**
**Ожидаемый результат:**
  - Result is FAIL

* <Валидные данные
**InstaPayment :**
6394092842015727
6377965506528294
6380020541324393
**Ожидаемый результат :**
6394092842015727- Result is OK
6377965506528294- Result is OK
6380020541324393- Result is OK

* <Невалидные данные>
**InstaPayment :**
**Ожидаемый результат:**
  - Result is FAIL


Тестирование производилось в следующем окружении:
* <64-Bit>
* < Java version "11.0.8" 2020-07-14>
* <[Git(https://github.com/Stepan164i/Javaqa-DZ-1.2.git)>