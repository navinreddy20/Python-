                               MyCode.py
--------------------------------------------------------------------------------

# def person(name, **data):
#     print(name)
#     print(data)
# person('navin',age=28,city='Mumbai',mob=9865432)


def person(name, **data):
    print(name)
    for i,j in data.items():
        print(i,j)
person('navin',age=28,city='Mumbai',mob=9865432)