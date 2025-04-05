import random

w = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
qwer = ''
user_number = int(input('какая длина пароля нужна:'))
for i in range(user_number):
    number = random.randrange(73)
    qwer += w[number]
print(qwer)
