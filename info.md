from string import ascii_lowercase

a = ' '.join(ascii_lowercase).split()
alphabet = {}
for x in range(1, len(a)+1):
    alphabet.setdefault(a[x-1], x)
print(alphabet)