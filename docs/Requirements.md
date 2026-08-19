# 요구사항

## 메뉴

원하는 동작을 선택할 수 있도록 목록을 보여줘야 한다.

```bash
Enter the number or the command
[1] conversion
[2] practice
[3] config
[4] exit
> 
```

## 진법변환기

원하는 진법의 숫자를 특정 진법으로 바꾸는 기능이 있어야 한다.

```bash
Enter the radix and the number
[base] [number] [radix]>
```

## 진법 변환 문제 생성

특정 진법의 숫자를 다른 진법으로 바꾸는 문제를 답과 함께 만들어 출력하는 기능이 있어야 한다.

```bash
Practice 1/4
number: AB
base: 16
base 10?>
[correct/wrong]
```

## 진법 변환 문제 시간 측정

문제를 푸는 시간을 측정하고 출력할 수 있어야 한다.
```bash
> config
Config
time-record: off
max-bites: 1
practice-base: 2, 8, 10, 16
answer-base: 2, 8, 10, 16
> time-record: on
```