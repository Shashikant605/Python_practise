1. # Write a programme where you take the input from user and after that it gives you the greatest element from that given List.

def gret():
    x = int(input("Enter the lenght of the list: "))


    lis = []

    for i in range(0,x):
        element = int(input("Enter the element of the list:"))
        lis.append(element)
    print("list", lis)
    lis.sort()
    print("Here is sorted list" , lis)
    print("\n")
    maxx = print("The gretaest no in given lis is " , lis[-1])

gret()
