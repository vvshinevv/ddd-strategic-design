# 키친포스

## 요구 사항

- 

## 용어 사전

| 한글명 | 영문명 | 설명 |
| --- | --- | --- |

## 모델링

```uml
Object <|-- Dummy

class Dummy {
  String data
  void methods()
  -field1
  #field2
  ~method1()
  +method2()
}

class Flight {
   flightNumber : Integer
   departureTime : Date
}

class Car

Driver - Car : drives >
Car *- Wheel : have 4 >
Car -- Person : < owns

```
