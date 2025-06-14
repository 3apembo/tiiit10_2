# Bubble Sort Demo

Этот проект демонстрирует реализацию базового алгоритма **пузырьковой сортировки** на языке C++.

## 📋 Описание

Программа сортирует массив целых чисел по возрастанию, используя простой двухуровневый цикл. В начале выводится исходный массив, затем он сортируется, и результат отображается на экране.

## 🧠 Принцип работы

- Сравниваются соседние элементы массива.
- Если левый элемент больше правого — происходит обмен.
- Каждый проход "всплывает" наибольший элемент к концу массива.

## 🔧 Как использовать

1. Скомпилируйте программу:
   ```bash
   g++ bubble_sort.cpp -o bubble_sort
   ```
2. Запустите:

  ```bash
  ./bubble_sort
  ```
3. В консоли вы увидите:
  ```bash
  Original: 64 34 34 25 61 12 22 11 90 42 99
  Output:   11 12 22 25 34 34 42 61 64 90 99
  ```

