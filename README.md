# Практическая работа №1

Команда "СТС": Серебрякова Софья, Турсуналиев Чингиз, Меред Сарджаев, 312 группа.

## Содержвание:

1. Постановка задачи и подход к её решению
2. Инструкцией по запуску
3. Вклад каждого участника

## Постановка задачи

## Инструкция по запуску

1. Установка [pip](https://pip.pypa.io/en/stable/installing/) если его нет:

* ### Linux или macOS

```sh
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
```

* ### Windows

Скачать [get-pip.py](https://bootstrap.pypa.io/get-pip.py) в папку на вашем компьютере. Откройте окно командной строки и перейдите в папку, содержащую `get-pip.py`. Затем запустите `python get-pip.py`.

2. Скачать пакет и установить его:

```sh
cd superrnash-package
pip install .
```

3. Использование пакета:

```sh
python
>>> import superrnash
>>> suppernash.main()
2
2
5 0
6 0
```

<p align='center'>
  <img src='https://sun9-26.userapi.com/c857028/v857028320/349f5/RLZIvT0v63w.jpg' width='600' alt='npm start'>
</p>

<p align='center'>
  <img src='https://sun9-43.userapi.com/c857028/v857028320/349fd/xeNDQbxPAq0.jpg' width='600' alt='npm start'>
</p>

```sh
 Game value is : 0.0 
 optimal strategy for 1st player :  [1.0, 0.0] 
 optimal strategy for 2nd player :  [0.0, 1.0]
>>>
```

## Вклад каждого участника

* Серебрякова Софья реализовала функцию nash_equilibrium(a), которая принимает матрицу выигрыша и возвращает значение игры и оптимальные стратегии первого и второго игроков.

* Турсуналиев Чингиз реализовал функцию visualization(p), которая иллюстрирует работу функции nash_equilibrium(a) путем решения нескольких игр и визуализации спектров оптимальных стратегий игроков в Jupyter. В частности, были приведены игры в которых:

⋅⋅* Спектр оптимальной стратегии состоит из одной точки (т.е. существует
равновесие Нэша в чистых стратегиях).

⋅⋅* Спектр оптимальной стратегии неполон (т.е. некоторые чистые
стратегии не используются).

⋅⋅* Спектр оптимальной стратегии полон.

## Philosophy

- **One Dependency:** There is only one build dependency. It uses Webpack, Babel, ESLint, and other amazing projects, but provides a cohesive curated experience on top of them.

- **No Configuration Required:** You don't need to configure anything. A reasonably good configuration of both development and production builds is handled for you so you can focus on writing code.

- **No Lock-In:** You can “eject” to a custom setup at any time. Run a single command, and all the configuration and build dependencies will be moved directly into your project, so you can pick up right where you left off.



![equation](http://latex.codecogs.com/gif.latex?Concentration%3D%5Cfrac%7BTotalTemplate%7D%7BTotalVolume%7D)  

\begin{equation} \begin{bmatrix} x & \dot{x} & \theta & \dot{\theta} & L & m & M \end{bmatrix} \end{equation}
# operation-research-rep

![](https://i.imgflip.com/3eod26.jpg)

Чтобы стать коллаборатором и загрузить свои код надо отправить свой логин от github'a [мне](https://tele.click/@FredericChopin) или в беседу кафедры

### Как загрузить код?

1. Клонировать себе этот репозитории:

```sh
git clone https://github.com/CheenaT/operation-research-rep.git
```

2. Сделать бранч в виде task2-ivanovpetrov от последнего master:

```sh
git checkout -b task2-ivanovpetrov
```

3.1. Создать директорию submissions/task2/ivanov-petrov в которой будут содержаться все файлы относящиеся к заданию:

```sh 
mkdir submissions/task2/ivanov-petrov
```

3.2. Написать код:
  
![](https://media.giphy.com/media/zOvBKUUEERdNm/giphy.gif)

4. Отправить pull request в master с именем **Задание 2. Иванов, Петров**:

```sh
git push origin task2-ivanovpetrov (task2-ivanovpetrov - название вашей ветки)
```

5. Молиться, что всё сработает ~~fucking awesome~~ как надо:

![](https://im0-tub-ru.yandex.net/i?id=5b15e87f69a304493e1440fbb557f676&n=13&exp=1)

_1. List item__  
__1.1 List item

4. Написать код и сделать коммит:

* ![](https://media.giphy.com/media/zOvBKUUEERdNm/giphy.gif)

```sh
git add .
git commit -m "First commit"
```
