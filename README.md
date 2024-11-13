# Кросплатформене програмування MKR1

Ходацький Володимир
ІПЗ-32
Варіант 24

## Команди для запуску проекту

Для запуску Build/Run/Test для певних лабораторних введіть наступні команди з корня репозиторію:

Щоб запустити білд мкр:
```bash
dotnet build Build.proj -t:Build -p:Solution=MKR1
```

Щоб запустити код лабораторної:
```bash
dotnet build Build.proj -t:Run -p:Solution=MKR1
```

Щоб запустити тести лабораторної:
```bash
dotnet build Build.proj -t:Test -p:Solution=Tests
```
