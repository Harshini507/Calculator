todo_list=[]
def show_menu():
    print("\nTodo_list menu")
    print("1.view tasks")
    print("2.add task")
    print("3.Delete task")
    print("4.exit")
while True:
    show_menu()
    choice=input("Enter the number(1-4):")
    if choice=="1":
        if not todo_list:
            print("no tasks yet")
        else:
            for i,task in enumerate(todo_list,1):
                print("{}{}".format(i,task))
    elif choice=="2":
        task=input("enter the task:")
        todo_list.append(task)
        print("Task added")
    elif choice=="3":
        task_no=int(input("Enter the task no:"))
        remove=todo_list.pop(task_no-1)
        print("{}".format(remove))
    elif choice=="4":
        print("Good Bye!")
        break
    else:
        print("Invalid input please try again!")
print("Thank you")
