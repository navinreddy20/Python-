                               MyCode.py
--------------------------------------------------------------------------------


def count(lst):

    even = 0
    odd = 0

    for i in  lst:
        if i%2==0:
            even+=1
        else:
            odd+=1

    return even,odd

lst = [20,25,14,19,16,24,28,47,26]

even , odd = count(lst)

print("Even : {} and Odd : {}".format(even,odd))
