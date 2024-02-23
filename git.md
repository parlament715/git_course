### HEAD - всему голова

Файл HEAD (англ. «голова», «головной») — один из служебных файлов папки .git. Он указывает на коммит, который сделан последним (то есть на самый новый).

### git log

git log --oneline

```f0e6542 (HEAD -> master, origin/master) Шпора готова по md
9e8b23e Добавление всякой фигни
```

выдаёт сокращённые хеши

git log --graph

```* commit f0e65420ad60aa4bc15f02e8cd9bc2bd2e45a160 (HEAD -> master, origin/master)
| Author: parlament700 <alexfresh700@gmail.com>
| Date: Fri Feb 23 11:17:14 2024 +0700
|
| Шпора готова по md
|
* commit 9e8b23e06ec334dac6e4b2bb20ab281091747c6d
  Author: parlament700 <alexfresh700@gmail.com>
  Date: Fri Feb 23 11:06:49 2024 +0700
```

выдаёт граф и визуальное разделение веток
