# Monorepo


1. melos를 설치합니다.

```
dart pub global activate melos
```

2. flutter project를 생성합니다.

```
flutter create app
```


3. melos.yaml를 생성합니다.


```
name: @ouul

packages:
  - packages/**
  - apps/**

command:
  bootstrap:
    usePubspecOverrides: true

```
