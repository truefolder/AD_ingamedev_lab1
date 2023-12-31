# Анализ данных в разработке игр
Отчет по лабораторной работе #1 выполнил(а):
- Бабаев Тимур Ахмадалиевич
- РИ-220912
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | - |
| Задание 2 | * | - |
| Задание 3 | * | - |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
-

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр. Написать программу "Hello world" на Python и в Unity.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:
- Установил Anaconda Navigator по туториалу, представленному в описании к лабораторной работе.
- Запустил Jupyter Notebook, создал отдельную директорию для проектов.
- Создал новый файл HelloWorld.ipynb, в котором буду писать программу "Hello world"
- Открыл файл HelloWorld.ipynb и выполнил задачу

```py

print('Hello world!')

```
![image](https://github.com/truefolder/AD_ingamedev_lab1/assets/89926388/f130de24-3b05-495f-acc1-1b1a3b84fe49)


## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 
- Установил Unity Hub по туториалу, представленному в описании к лабораторной работе, установил предложенную версию редактора.
- Создал новый 3D проект в Unity Hub
  ![image](https://github.com/truefolder/AD_ingamedev_lab1/assets/89926388/346655dc-8c71-455d-a679-aa1c92a722b7)
- Загрузил проект, добавил в проект скрипт HelloWorld.cs
Вариантов реализации программы "Hello world" конкретно на Unity огромное множество. Можно выводить сообщение посредством Debug.Log() в консоль разработчика, можно создать какой-нибудь игровой объект (по типу UI-Text) и выводить сообщение в него. Я выведу сообщение через Debug.Log()
- В функции Start() вызываю метод Debug.Log("Hello world!"), чтобы при запуске сцены в консоль выводилось сообщение
- Повесил скрипт HelloWorld.cs на Main Camera
  ![image](https://github.com/truefolder/AD_ingamedev_lab1/assets/89926388/ee52f017-0a53-4efd-8584-aa66433d8ebe)
Теперь при каждом запуске игры в консоль разработчика будет выводиться сообщение "Hello world!"
```csharp

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HelloWorld : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        Debug.Log("Hello world!");
    }
}

```

## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Результатом выполнения этого задания является отчет, который вы сейчас проверяете :-)
- https://github.com/truefolder/AD_ingamedev_lab1/blob/main/README.md

## Выводы

Я установил удобную среду разработки на Python и игровой движок Unity. Разобрался в их интерфейсе и узнал, как написать на них простейшую программу "Hello world".

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
