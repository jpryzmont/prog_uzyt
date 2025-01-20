# Kolokwium 2 - zestaw 13
## Zad 1.a
```
cotg(5/12)
```
## Zad 1.b
```
M = [3,-2,3; -2,3,8; 6,4,0]
inv(M)
```
## Zad 1.c
```
I = 23
w = 25
E = (I * w.^2)/2
```
## Zad 1.d
```
n=-3:50;
y = sum((n+4)/n.^2+2)
```
## Zad 2
```
x = 2:0.1:6;
y1=log(x)/log(2)
y2=sin(x)+1
G = exp(-((x-xm)/dx).^2/2)*30;
plot(x, y1, "b", "LineWidth", 2);
plot(x, y2, "g", "LineWidth", 2);
```
## Zad 3
```
rok=[2010,2015,2020]
ilosc = [4,2,3; 2,0,4; 3,1,0]
bar(rok,ilosc)
xtitle=("Ilosc wydobycia zlota, srebra i brazu w latach 2010, 2015, 2020")
h1=legend(['Zloto';'Srebro';'Bronz'])
```
