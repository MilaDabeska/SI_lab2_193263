# Втора лабораториска вежба по Софтверско инженерство

## Мила Дабеска, 193263

### 1. Control Flow Graph



![Untitled Diagram](https://user-images.githubusercontent.com/80597973/120086937-e5c60080-c0e3-11eb-8b6b-53f04f464771.png)

### 2. Цикломатска комплексност
Во овој граф имаме 27 јазли и 32 ребра, па според тоа, цикломатската комплексност е: (32-27)+2 = 7

### 3. Тест случаи според критериумот Every branch

branch | ( ) | (-1, 45, 45) | (25, 45, 45) | (22, -2, 2) | (22, 2, -2) | (22, 2, 2) | (24, 0, 0) | (24, 2, 2) | . | .| .
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
1 -> 2.1 | * | * | * | * | * | * | * | * |  |  | 
2.1 -> 2.2 | * | * | * | * | * | * | * | * |  |  | 
2.2 -> 2.3 | * |  |  |  |  | * | * |  |  |  | 
2.2 -> 3,4,5 |  | * | * | * | * | * | * | * |  |  | 
3,4,5 -> 6 |  | * | * | * | * | * | * | * |  |  | 
6 -> 7 |  | * | * |  |  |  |  |  |  |  | 
7 -> 8 |  | * |  |  |  |  |  |  |  |  | 
8 -> 23 |  | * |  |  |  |  |  |  |  |  | 
7 -> 9 |  |  | * |  |  |  |  |  |  |  | 
9 -> 10 |  |  | * |  |  |  |  |  |  |  | 
10 -> 23 |  |  | * |  |  |  |  |  |  |  | 
6 -> 11 |  |  |  | * | * | * | * | * |  |  | 
11 -> 12 |  |  |  | * | * | * |  |  |  |  | 
12 -> 14 |  |  |  |  | * | * |  |  |  |  | 
14 -> 15 |  |  |  |  | * | * |  |  |  |  | 
15 -> 16 |  |  |  |  |  | * |  |  |  |  | 
16 -> 2.3 |  |  |  |  |  | * |  |  |  |  | 
12 -> 13 |  |  |  | * |  |  |  |  |  |  | 
13 -> 24 |  |  |  | * |  |  |  |  |  |  | 
15 -> 17 |  |  |  |  | * |  |  |  |  |  | 
17 -> 18 |  |  |  |  | * |  |  |  |  |  | 
18 -> 24 |  |  |  |  | * |  |  |  |  |  |
11 -> 19 |  |  |  |  |  |  | * | * |  |  | 
19 -> 20 |  |  |  |  |  |  | * |  |  |  | 
20 -> 2.3 |  |  |  |  |  |  | * |  |  |  | 
2.3 -> 2.2 |  |  |  |  |  | * | * |  |  |  | 
19 -> 21 |  |  |  |  |  |  |  | * |  |  | 
21 -> 22 |  |  |  |  |  |  |  | * |  |  | 
23 -> 24 | * |  |  |  |  | * | * |  |  |  | 
