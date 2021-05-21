# Health-Managment-System
Health Managment System Of Gym Peoples Based On Python Language.

from os import system
list10 = ["Banana", "Milk", "Egg"]
list11 = ["Apple , Milk , Egg"]
list12 = ["Chicken", "Banana , Milk"]
list13 = ["Paneer, Milk , Egg"]
list14 = ["Fruits , Milk , Egg"]
list15 = ["Banana , Milk , Egg"]
while True:
    try:
        n1 = int(input("Which Clint\n1.Rohan\n2.Sohan\n3.Parul\n"))
    except ValueError:
        print("Enter Valid Number")
        continue
    if n1 == 1:
        while True:
            try:
                n2 = int(input("Select Option\n1.Diet\n2.Exercise\n3.Previous Menu\n"))
            except ValueError:
                print("Enter Valid Number")
                continue
            if n2 == 1:
                while True:
                    list2 = ["1.Monday", "2.Tuesday", "3.Wednesday", "4.Thursday", "5.Friday", "6.Saturday", "7.Sunday",
                             "8.Previous Menu"]
                    [print(x) for x in list2]
                    try:
                        n3 = int(input("Choose Day"))
                    except ValueError:
                        print("Enter Valid Number")
                        continue
                    if n3 == 1:
                            print("Monday")
                            while True:
                                    list3 = ["1.See Diet", "2.Add Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list10)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list10.append(n5)
                                        print(list10)
                                    elif n4 == 3:
                                        print(list10)
                                        r1 = int(input("Enter"))
                                        list10.pop(int(r1 - 1))
                                        print(list10)
                                    elif n4 == 4:
                                        break
                    elif n3 == 2:
                            print("Tuesday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list11)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list11.append(n5)
                                        print(list11)
                                    elif n4 == 3:
                                        print(list11)
                                        r2 = int(input("Enter"))
                                        list11.pop(int(r2 - 1))
                                        print(list11)
                                    elif n4 == 4:
                                        break
                    elif n3 == 3:
                            print("Wednesday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list12)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list12.append(n5)
                                        print(list12)
                                    elif n4 == 3:
                                        print(list12)
                                        r3 = int(input("Enter"))
                                        list12.pop(int(r3 - 1))
                                        print(list12)
                                    elif n4 == 4:
                                        break
                    elif n3 == 4:
                            print("Thursday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list13)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list13.append(n5)
                                        print(list13)
                                    elif n4 == 3:
                                        print(list13)
                                        r4 = int(input("Enter"))
                                        list13.pop(int(r4 - 1))
                                        print(list13)
                                    elif n4 == 4:
                                        break
                    elif n3 == 5:
                            print("Friday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list14)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list14.append(n5)
                                        print(list14)
                                    elif n4 == 3:
                                        print(list14)
                                        r5 = int(input("Enter"))
                                        list14.pop(int(r5 - 1))
                                        print(list14)
                                    elif n4 == 4:
                                        break
                    elif n3 == 6:
                            print("Saturday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list15)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list15.append(n5)
                                        print(list15)
                                    elif n4 == 3:
                                        print(list15)
                                        r6 = int(input("Enter"))
                                        list15.pop(int(r6 - 1))
                                        print(list15)
                                    elif n4 == 4:
                                        break
                    elif n3 == 7:
                            print("Sunday Holiday")
                    elif n3 == 8:
                            break
                    elif n3 >= 9:
                            print("Invalid Option \nTry Again")
                            break
            elif n2 == 2:
                print("Exercise")
                while True:
                    list4 = ["1.Monday", "2.Tuesday", "3.Wednesday", "4.Thursday", "5.Friday", "6.Saturday", "7.Sunday",
                             "8.Previous Menu"]
                    [print(z)for z in list4]
                    try:
                        n6 = int(input("Choose Day"))
                    except ValueError:
                        print("Enter Valid Number")
                        continue
                    if n6 == 1:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Legs"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 2:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Abs"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 3:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Back"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(2, n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 4:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Triceps"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 5:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Biceps"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 6:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Chest"]
                                print(list6)
                            elif n7 == 2:
                                n8 = str(input("Enter"))
                                list6.append(2, n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 7:
                        print("Sunday Holiday")
                        break
                    elif n6 == 8:
                        break
                    elif n6 >= 9:
                        print("Invalid Option \nTry Again")
            elif n2 == 3:
                print("Previous Menu")
                break
            elif n2 >= 4:
                print("Invalid Option \n Try Again")
                break
    elif n1 == 2:
        while True:
            try:
                n2 = int(input("Select Option\n1.Diet\n2.Exercise\n3.Previous Menu\n"))
            except ValueError:
                print("Enter Valid Number")
                continue
            if n2 == 1:
                while True:
                    list2 = ["1.Monday", "2.Tuesday", "3.Wednesday", "4.Thursday", "5.Friday", "6.Saturday", "7.Sunday",
                             "8.Previous Menu"]
                    [print(x) for x in list2]
                    try:
                        n3 = int(input("Choose Day"))
                    except ValueError:
                        print("Enter Valid Number")
                        continue
                    if n3 == 1:
                            print("Monday")
                            while True:
                                    list3 = ["1.See Diet", "2.Add Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list10)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list10.append(n5)
                                        print(list10)
                                    elif n4 == 3:
                                        print(list10)
                                        r1 = int(input("Enter"))
                                        list10.pop(int(r1 - 1))
                                        print(list10)
                                    elif n4 == 4:
                                        break
                    elif n3 == 2:
                            print("Tuesday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list11)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list11.append(n5)
                                        print(list11)
                                    elif n4 == 3:
                                        print(list11)
                                        r2 = int(input("Enter"))
                                        list11.pop(int(r2 - 1))
                                        print(list11)
                                    elif n4 == 4:
                                        break
                    elif n3 == 3:
                            print("Wednesday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list12)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list12.append(n5)
                                        print(list12)
                                    elif n4 == 3:
                                        print(list12)
                                        r3 = int(input("Enter"))
                                        list12.pop(int(r3 - 1))
                                        print(list12)
                                    elif n4 == 4:
                                        break
                    elif n3 == 4:
                            print("Thursday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list13)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list13.append(n5)
                                        print(list13)
                                    elif n4 == 3:
                                        print(list13)
                                        r4 = int(input("Enter"))
                                        list13.pop(int(r4 - 1))
                                        print(list13)
                                    elif n4 == 4:
                                        break
                    elif n3 == 5:
                            print("Friday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list14)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list14.append(n5)
                                        print(list14)
                                    elif n4 == 3:
                                        print(list14)
                                        r5 = int(input("Enter"))
                                        list14.pop(int(r5 - 1))
                                        print(list14)
                                    elif n4 == 4:
                                        break
                    elif n3 == 6:
                            print("Saturday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list15)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list15.append(n5)
                                        print(list15)
                                    elif n4 == 3:
                                        print(list15)
                                        r6 = int(input("Enter"))
                                        list15.pop(int(r6 - 1))
                                        print(list15)
                                    elif n4 == 4:
                                        break
                    elif n3 == 7:
                            print("Sunday Holiday")
                    elif n3 == 8:
                            break
                    elif n3 >= 9:
                            print("Invalid Option \nTry Again")
                            break
            elif n2 == 2:
                print("Exercise")
                while True:
                    list4 = ["1.Monday", "2.Tuesday", "3.Wednesday", "4.Thursday", "5.Friday", "6.Saturday", "7.Sunday",
                             "8.Previous Menu"]
                    [print(z)for z in list4]
                    try:
                        n6 = int(input("Choose Day"))
                    except ValueError:
                        print("Enter Valid Number")
                        continue
                    if n6 == 1:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Legs"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 2:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Abs"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 3:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Back"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(2, n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 4:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Triceps"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 5:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Biceps"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 6:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Chest"]
                                print(list6)
                            elif n7 == 2:
                                n8 = str(input("Enter"))
                                list6.append(2, n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 7:
                        print("Sunday Holiday")
                        break
                    elif n6 == 8:
                        break
                    elif n6 >= 9:
                        print("Invalid Option \nTry Again")
            elif n2 == 3:
                print("Previous Menu")
                break
            elif n2 >= 4:
                print("Invalid Option \n Try Again")
                break
    elif n1 == 3:
        while True:
            try:
                n2 = int(input("Select Option\n1.Diet\n2.Exercise\n3.Previous Menu\n"))
            except ValueError:
                print("Enter Valid Number")
                continue
            if n2 == 1:
                while True:
                    list2 = ["1.Monday", "2.Tuesday", "3.Wednesday", "4.Thursday", "5.Friday", "6.Saturday", "7.Sunday",
                             "8.Previous Menu"]
                    [print(x) for x in list2]
                    try:
                        n3 = int(input("Choose Day"))
                    except ValueError:
                        print("Enter Valid Number")
                        continue
                    if n3 == 1:
                            print("Monday")
                            while True:
                                    list3 = ["1.See Diet", "2.Add Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list10)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list10.append(n5)
                                        print(list10)
                                    elif n4 == 3:
                                        print(list10)
                                        r1 = int(input("Enter"))
                                        list10.pop(int(r1 - 1))
                                        print(list10)
                                    elif n4 == 4:
                                        break
                    elif n3 == 2:
                            print("Tuesday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list11)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list11.append(n5)
                                        print(list11)
                                    elif n4 == 3:
                                        print(list11)
                                        r2 = int(input("Enter"))
                                        list11.pop(int(r2 - 1))
                                        print(list11)
                                    elif n4 == 4:
                                        break
                    elif n3 == 3:
                            print("Wednesday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list12)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list12.append(n5)
                                        print(list12)
                                    elif n4 == 3:
                                        print(list12)
                                        r3 = int(input("Enter"))
                                        list12.pop(int(r3 - 1))
                                        print(list12)
                                    elif n4 == 4:
                                        break
                    elif n3 == 4:
                            print("Thursday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list13)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list13.append(n5)
                                        print(list13)
                                    elif n4 == 3:
                                        print(list13)
                                        r4 = int(input("Enter"))
                                        list13.pop(int(r4 - 1))
                                        print(list13)
                                    elif n4 == 4:
                                        break
                    elif n3 == 5:
                            print("Friday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list14)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list14.append(n5)
                                        print(list14)
                                    elif n4 == 3:
                                        print(list14)
                                        r5 = int(input("Enter"))
                                        list14.pop(int(r5 - 1))
                                        print(list14)
                                    elif n4 == 4:
                                        break
                    elif n3 == 6:
                            print("Saturday")
                            while True:
                                    list3 = ["1.See Diet", "2.Edit Diet", "3.Remove Diet", "4.Previous Menu"]
                                    [print(y)for y in list3]
                                    try:
                                        n4 = int(input("Select Option"))
                                    except ValueError:
                                        print("Enter Valid Number")
                                        continue
                                    if n4 == 1:
                                        print(list15)
                                    elif n4 == 2:
                                        try:
                                            n5 = str(input("Enter"))
                                        except ValueError:
                                            print("Enter Valid Number")
                                            continue
                                        list15.append(n5)
                                        print(list15)
                                    elif n4 == 3:
                                        print(list15)
                                        r6 = int(input("Enter"))
                                        list15.pop(int(r6 - 1))
                                        print(list15)
                                    elif n4 == 4:
                                        break
                    elif n3 == 7:
                            print("Sunday Holiday")
                    elif n3 == 8:
                            break
                    elif n3 >= 9:
                            print("Invalid Option \nTry Again")
                            break
            elif n2 == 2:
                print("Exercise")
                while True:
                    list4 = ["1.Monday", "2.Tuesday", "3.Wednesday", "4.Thursday", "5.Friday", "6.Saturday", "7.Sunday",
                             "8.Previous Menu"]
                    [print(z)for z in list4]
                    try:
                        n6 = int(input("Choose Day"))
                    except ValueError:
                        print("Enter Valid Number")
                        continue
                    if n6 == 1:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Legs"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 2:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Abs"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 3:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Back"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(2, n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 4:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Triceps"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 5:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Biceps"]
                                print(list6)
                            elif n7 == 2:
                                try:
                                    n8 = str(input("Enter"))
                                except ValueError:
                                    print("Enter Valid Number")
                                    continue
                                list6.append(n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 6:
                        while True:
                            list5 = ["1.See Exercise", "2.Edit Exercise", "3.Previous Menu"]
                            [print(a)for a in list5]
                            try:
                                n7 = int(input("Select Option"))
                            except ValueError:
                                print("Enter Valid Number")
                                continue
                            if n7 == 1:
                                list6 = ["Chest"]
                                print(list6)
                            elif n7 == 2:
                                n8 = str(input("Enter"))
                                list6.append(2, n8)
                                print(list6)
                            elif n7 == 3:
                                break
                            elif n7 >= 4:
                                print("Invalid Option\n Try Again")
                                break
                    elif n6 == 7:
                        print("Sunday Holiday")
                        break
                    elif n6 == 8:
                        break
                    elif n6 >= 9:
                        print("Invalid Option \nTry Again")
            elif n2 == 3:
                print("Previous Menu")
                break
            elif n2 >= 4:
                print("Invalid Option \n Try Again")
                break
