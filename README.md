# 1note

<details open>
    <summary><b>✨2023</b></summary><br/>

| **ID** | **REPO** | **TITLE** | **PLATFORM** | **OWNER** |
|:------:|:--------:|:---------|:------------:|:---------:|
| `id8`    | [repo](https://github.com/IsFilimonov/1N_2023_yandex_algos-practice-3)     | Тренировки по алгоритмам 3.0     | Яндекс       | [Илья Филимонов](https://github.com/IsFilimonov)     |

</details>

<details open>
    <summary><b>✨2022</b></summary><br/>

| **ID** | **REPO** | **TITLE** | **PLATFORM** | **OWNER** |
|:------:|:--------:|:---------|:------------:|:---------:|
| `id6`    | repo   | Title     | Platform     | [Илья Филимонов](https://github.com/IsFilimonov)     |
| `id7`    | repo   | Title     | Platform     | [Илья Филимонов](https://github.com/IsFilimonov)     |

</details>

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



