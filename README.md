import random

names = ['Аня','Ваня','Юля','Дима','Саша','Глаша','Егор','Денис','Вася','Миша']
dct = {}

for i in range(10):
    name = random.choice(names)
    dct[i+1] = name

for g,i in dct.items():
    print(f'{g}: {i}')
