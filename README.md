rows = int(input("Enter rows: "))
columns = int(input("Enter columns: "))

for i in range(rows):
    for j in range(columns):
        print(" _ ", end=" ")
    print() 
    for j in range(columns):
        print("/   \\", end=" ")
    print("  ") 
    
    for j in range(columns):
        print("\\_/", end=" ")
    print()