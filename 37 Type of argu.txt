                             MyCode.py
--------------------------------------------------------------------------------


#
# def person(name , age):
#     print(name)
#     print(age)
#
# person(age=28,name='navin')



# def person(name , age=18):
#     print(name)
#     print(age)
#
# person('navin',28)

def sum(*b):

   c = 0
   for i in b:
       c = c + i

   print(c)

sum(5,6,34,78)
