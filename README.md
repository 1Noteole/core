<div align="center">
	<h1 align="center">Onenoteole Wassurname</h1>
	<img src="https://avatars.githubusercontent.com/u/125817706" width="230" alt="Onenoteole Wassurname">
	<p align="center">🌟Поставь звезду, если нравится🌟</p>
</div>

1. `git clone https://example.com/` (`--recursive`, если всё хотите выкачать сразу)
2. ...

<details open>
    <summary><b>📁2023</b></summary><br/>

| **ID** |                                **REPO**                                | **TYPE** | **TITLE**                    | **PLATFORM** |                    **OWNER**                     |
|:------:|:----------------------------------------------------------------------:|:--------:|:---------------------------- |:------------:|:------------------------------------------------:|
| `id8`  | [repo](https://github.com/IsFilimonov/1N_2023_yandex_algos-practice-3) |    CR    | Тренировки по алгоритмам 3.0 |    Яндекс    | [Илья Филимонов](https://github.com/IsFilimonov) |

</details>


<details>
    <summary><b>📁2022 (2)</b></summary><br/>

| **ID** | **REPO** | **TYPE** | **TITLE** | **PLATFORM** |                    **OWNER**                     |
|:------:|:--------:|:--------:|:--------- |:------------:|:------------------------------------------------:|
| `id6`  | [repo](https://github.com/IsFilimonov/1N_2022_udacity_cloud-architect-using-microsoft-azure-scholarship-program) | CR | [Microsoft Azure Cloud Architect](https://www.udacity.com/course/cloud-architect-using-microsoft-azure-nanodegree--nd090) | Udacity | [Илья Филимонов](https://github.com/IsFilimonov) |
| `id7`  |   repo   |    CR    | ToDo     |   Platform   | [Илья Филимонов](https://github.com/IsFilimonov) |

</details>


<details>
    <summary><b>📁2021 (4)</b></summary><br/>

| **ID** | **REPO** | **TYPE** | **TITLE** | **PLATFORM** |                    **OWNER**                     |
|:------:|:--------:|:--------:|:--------- |:------------:|:------------------------------------------------:|
| `id2`  |   repo   |    CR    | Title     |   Platform   | [Илья Филимонов](https://github.com/IsFilimonov) |
| `id3`  |   repo   |    CR    | Title     |   Platform   | [Илья Филимонов](https://github.com/IsFilimonov) |
| `id4`  |   repo   |    CR    | Title     |   Platform   | [Илья Филимонов](https://github.com/IsFilimonov) |
| `id5`  |   repo   |    CR    | Title     |   Platform   | [Илья Филимонов](https://github.com/IsFilimonov) |

</details>

<details>
    <summary><b>📁2019 (1)</b></summary><br/>

| **ID** | **REPO** | **TYPE** | **TITLE** | **PLATFORM** |                    **OWNER**                     |
|:------:|:--------:|:--------:|:--------- |:------------:|:------------------------------------------------:|
| `id1`  |   repo   |    CR    | Title     |   Platform   | [Илья Филимонов](https://github.com/IsFilimonov) |


</details>


## Легенда

- **СR** — course
- **TT** — tutorial


## Добавление нового подмодуля

```
git submodule add <repo .git link> <year>/<id>
git submodule add https://github.com/IsFilimonov/1N_2023_yandex_algos-practice-3.git 2023/id8
```

## Удаление подмодуля

```
git submodule deinit -f <year>/<id>
rm -rf .git/modules/<year>/<id>
git rm -f <year>/<id>

git submodule deinit -f 2023/id8
rm -rf .git/modules/2023/id8
git rm -f 2023/id8
```



