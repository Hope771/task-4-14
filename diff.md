[~к Содержанию](./readme.md)

# Основные команды

## **git diff**

Команда **git diff** используется для вычисления разницы между любыми двумя Git деревьями. 

Это может быть:

- разница между вашей рабочей директорией и индексом:

```bash=
git diff
```

- разница между индексом и последним коммитом:

```bash=
git diff --staged
```

- между любыми двумя коммитами:

```bash=
git diff master branchB
```

[<назад](./status.md) [_________]        [вперед>](./difftool.md)