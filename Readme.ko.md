# cabled

[english](./Readme.md)
[한국어](./Readme.ko.md)

cabled는 입력과 그에 맞는 행동을 잘 분리되어 모듈화되게끔 해주고 Undo와 입력 리플레이 등을 쉽게 만들어 주는 설계 패턴입니다.

## 구조

기존의 프로그램들은 다음과 같이 간단하고 확장하기 힘든 구조로 설계되어있습니다.

```
Input -> Action (Directly)
```

cabled 패턴에 맞게 처음부터 설계를 하면 더 강력한 확장성을 가진 구조를 설계가능합니다.

```
Input as cabled.Input (Queued) -> Action dispatcher -> Action
```

이렇게 설계된 프로그램은 입력을 기억만 해둔다면 Undo나 입력 리플레이 등의 구현이 간단해지고 비동기 입력 큐 등의 구현도 마찬가지입니다.

## 구현

WIP
