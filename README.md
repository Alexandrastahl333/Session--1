# Session--1
import random
class point:
    def _init_(self, x, y):
        self.x = x
        self.y = y

a = []
for i in range(5):
    a.append(point(random.randint(1, 100), random.randint(1, 100)))

for i in range(5):
    print(a[i].x, a[i].y)
