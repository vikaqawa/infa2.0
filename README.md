# infa
# СОЛОВЬЕВА ВИКТОРИЯ
## **lesson 23**
### **задачи**
### 1)

а, б, д, е, з

### 2) 

а)  у ≤ 1

б)  у ≤ - х

в)  х2 + у2 ≤ 1

г)  (х - 1)2 + у2 ≤ 1

д)  х ≤ 2 и у ≤ х и у ≥ 0 и х2 + у2 ≥ 4

е)  х  ≥ 0 и х ≤ π и у ≤ 0,5 и y ≤ sin х

ж)  у ≤ 2 - х2 и ( у ≥ х или у ≥ 0)

з)    у ≥ х2 - 2 и ( у ≤ х или у ≤ -х)

и)    х2 + у2 ≤ 1 и ( х ≤ 0 или у ≥ х)

к)    х2 + у2 ≤ 1 и ( у ≤ х или у ≥ -х)

л)    х ≤ 1 и у ≥ 1 - х и ( у ≥ 2х2 или х ≥ 0)

м)   у ≤ 1 и х ≥  0 и ( х2 + у2 ≤ 1 или у ≥ х - 1)

н)    х2 + у2 ≤ 1 или ( х ≥ 0 и у ≥ 0 и х ≤ 1 и у ≤

### 3) 

а)    «все окуни — рыбы»

б)    «все рыбы умеют плавать»

в)    «не все реки впадают в моря»

г)    «все моря солёные»

д)    «не все числа чётные»

е)    «все ломаные состоят из отрезков»

ж)   «не все прямоугольники — квадраты»

з)    «все кошки — млекопитающие»

### 4)
а) ∃x(x > y) 

б) ∀x(x ≤ y) 

в) ( 1) 2 ∀x x > 

г) ∀r ( (r – река)  → (r впадает в Каспийское море) ) 


д) ∃r ( (r – река)  и (r впадает в Каспийское море) ) 

е) ∀r ( (r – река) →  ∃M (M – море и r впадает в M) ) 

ж) ∀M ( (M – море) →   ∃r (r – река и r впадает в M) ) 

з) ∃r ( (r – река)  →  ∀M ((M – море) → (r впадает в M) ) ) 

и) ∃M ( (M – море)  →  ∀r ( (r – река) → (r впадает в M ) ) )

### 5)

а) ∃x ( (x – школьник) и (x ходит в театры) ) 

б) ∀x ( (x – кошка) → (x – серая) ) 

в) ∃x ( (x – собака) и (x – злая) ) 

г) ∀x∀y ( (x ≠ y) → (x отличается от y) ) 

д) ∀x ( (x – человек) → (x ошибается) ) 

е) ∀x (  x не обращает на него внимания ) 

ж) ∀x ( (x – фирма) → (x не обанкротилась) ) 

з) ∀x ( (x – лебедь) → (x – белый или чёрный) ) 

### 6)

а) ( 5) 2 ∀x x ≠ 

б) ∀x (x + y ≠ 5) 

в) ∃y (x + y ≠ 5) 

г) ∃y ∀x (x + y ≠ 5) 

д) «x не работает в вузе» 

е) ∃x («x не студент») 

ж) ∀x («x не учитель y») 

з) ∀x ∃y («x не учитель y»)
 
## **lesson 24**
### **вопросы**

### 1)

Триггер - это устройство последовательного типа с двумя устойчивыми состояниями равновесия, предназначенное для записи и хранения информации. Под действием входных сигналов триггер может переключаться из одного устойчивого состояния в другое. При этом напряжение на его выходе скачкообразно изменяется.
   
### 2)

Такая комбинация входных сигналов неприемлема по двум причинам: не выполняется условие взаимной инверсности входов и после снятия входных сигналов триггер с равной вероятностью может перейти в состояние, при котором на прямом выходе 1, или в состояние, при котором на прямом выходе 0. Противоречивая команда R=S=1 не запоминается триггерной ячейкой. В. JK-триггере при входном сигнале J=K=1 начальное состояние триггера меняется на противоположное.

### 3)

В отличие от полусумматора сумматор учитывает перенос из предыдущего разряда, поэтому имеет не два, а три входа

### 4)

Чтобы построить сумматор с помощью двух полусумматоров, можно использовать цепочку из полных сумматоров. 
Полусумматор — комбинационная логическая схема, имеющая два входа и два выхода. Он позволяет вычислять сумму A + B, где A и B — это разряды двоичного числа. Результатом будут два бита s и c, где s — это бит суммы по модулю 2, а c — бит переноса. 
Полный сумматор выполняет двоичное сложение трёх переменных: A, B и Cin (вход переноса). Полные сумматоры обычно соединяются покаскадно и используются для сложения двоичных чисел с увеличивающимся количеством разрядов. 
Таким образом, сам полный сумматор состоит из двух полусумматоров, а соединяя их в цепочку, можно получить схему сложения многоразрядных чисел. 

### 5) 

1. Сумма S: S = Ai ⊕ Bi ⊕ Cin
Это означает, что сумма S равна исключающему ИЛИ (XOR) между Ai, Bi и входом переноса Cin. Исключающее ИЛИ возвращает true (1), если только один из входных сигналов равен true (1), а остальные равны false (0).

2. Перенос C: C = (Ai ∧ Bi) ∨ (Ai ∧ Cin) ∨ (Bi ∧ Cin)
Здесь мы используем логическое И (AND) и логическое ИЛИ (OR). Перенос C равен логическому ИЛИ между тремя частями: логическое И между Ai и Bi, логическое И между Ai и входом переноса Cin, и логическое И между Bi и входом переноса Cin.

### 6) 

Многоразрядный сумматор работает следующим образом: он представляет собой комбинацию одноразрядных сумматоров, которые реализуют сложение одноразрядных чисел.

### 7) 
Перенос в многоразрядном сумматоре — это сигнал, который формируется в младшем разряде и проходит через остальные разряды. Многоразрядные сумматоры выполняют сложение многоразрядных слагаемых с учётом переноса.

### **задачи**

### 1) ![1](https://github.com/user-attachments/assets/488247c1-9264-48d3-8f26-ea345ec2ff1e)

### 2) ![2](https://github.com/user-attachments/assets/7fbcf264-452e-4f39-8dbc-ceef9e5c8324)

### 3) ![3](https://github.com/user-attachments/assets/05760486-dd4d-49a8-9d5d-0d9d40ba6432)

### 4) ![4](https://github.com/user-attachments/assets/a545e48e-604e-4f64-b2d6-706da878b750)

### 5) ![5](https://github.com/user-attachments/assets/48d118e3-9535-4af1-adc9-907b181ba8ea)

### 6)

RS‐триггер на двух элементах «И‐НЕ»

![6](https://github.com/user-attachments/assets/ab5d4aaf-d561-4525-9380-022a5af5b000)

 
### 7)

D‐триггер

![7](https://github.com/user-attachments/assets/e790609e-6036-43e0-9b80-5db0a1f52204)

