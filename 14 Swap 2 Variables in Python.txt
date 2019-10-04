                                dec.py
--------------------------------------------------------------------------------

class TopTen:

    def __init__(self):
        self.num = 1

    def __iter__(self):
        return self

    def __next__(self):

        if self.num <= 10:
            val = self.num
            self.num += 1

            return val
        else:
            raise StopIteration


values = TopTen()

print(next(values))

for i in values:
    print(i)


--------------------------------------------------------------------------------
                                 gen.py
--------------------------------------------------------------------------------


num =47

for i in range(2,num):
    if num % i ==0:
        print("Not prime")
        break


else:
    print("prime")


