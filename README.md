 RADICA RISTOVA 213247

![Control Flow Graph](https://github.com/RistovaRadica/SILab2.java/assets/127231682/45b2a086-5503-4224-9b63-aca89d3a0a9c)

3. 11- Ги избројав регионите помегу сите графови вкупно се 10 и плус 1 за цел граф.

4.
a-b
b-c
a-c
c-d
c-e
d-e
e-f
f-g
f-o
g-h
h-o
h-i
i-j
j-o
j-k
k-m
m-o
m-n
n-o
o-p
p-r
p-s
r-s
s-v
v-w
w-z
s-q
v-q
w-q
z-q
*За да не објаснувам за сите посебно, ги напишав сите branches кои постојат, кои влегуваат во точен услов а кој не.(пример за а- го земав првиот if одма после фунцијата function, за б го земав редот под а, и сега ако се исполни условот влегува во б и оди во ц, во случај да не го исполнува, од а продолжува во ц.)
Истото е и за сите останати. 


5. if (user==null || user.getPassword()==null || user.getEmail()==null)
-одве имаме 4 случаи кога се зема:
1.ТXX- кога првиот услов е точен останатото не се проверува
2.FTX- кога првиот услов е неточен одиме на вториот за да утвдиме дека условот ке биде точен, и штом имаме барем едно Т останатото не се проверува
3.FFT- одве кога двата се неточни се проверува и третиот услов, во случајот излегува дека е точен
4.FFF-во последниот се заклуцува дека нема да се влезе во ifот, условот не е точен.


6.
-Во првата функција, testValidEmail, се користи assert функцијата за да провериме дали вредноста на email одговара на зададениот регуларен израз за валидација на е-маил адреси. Ако условот не е исполнет, се испечатува пораката "Невалиден е-маил."

-Во втората функција, testValidUsername, се користи assert функцијата за да провериме дали вредноста на username одговара на зададениот регуларен израз за валидација на кориснички имиња. Ако условот не е исполнет, се испечатува пораката "Невалидно корисничко име."

