import random
import string
print('hello, Welcome to Password generator!')
len = int(input('\nEnter the length of password: '))
l = string.ascii_lowercase
u = string.ascii_uppercase
n = string.digits
s = string.punctuation
a = l + u + n + s
t = random.sample(a, len)
password = "".join(t)
print(password)
