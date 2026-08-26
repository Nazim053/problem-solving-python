<img width="875" height="628" alt="Снимок экрана 2026-08-26 в 21 22 51" src="https://github.com/user-attachments/assets/1a316fb5-0139-4154-8e65-a5a782e570ca" />
<img width="875" height="628" alt="Снимок экрана 2026-08-26 в 21 22 51" src="https://github.com/user-attachments/assets/b5d08ff8-78fb-4a7d-82e1-f9a04f6056cc" />

Answer:

from math import *
a,b,c = float(input()), float(input()),float(input())
d = (pow(b,2)-(4*a*c))

if d == 0:
  print (-b / (2* a) )
elif d > 0:
  root1 = ((-b - sqrt(d)) / (2 * a))
  root2 = ((-b + sqrt(d)) / (2 * a))
  print(min(root1, root2), max(root1, root2), sep='\n')
else:
  print('Нет корней')
