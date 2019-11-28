# Projects
def K():
 import math
 a=float(input('a='))
 b=float(input('b='))
 if(a==0):
     c1=90
     k=math.sqrt(b*b)    
 else:    
    k=math.sqrt(a*a+b*b)
    c=math.atan(b/a)
    c1=(c*180)/(math.pi)
 print("{}e**j{}".format(k,c1))
def A():
  import math
  k=float(input('k='))
  g=float(input('gradus='))
  x=g*math.pi/180
  print('{}+{}j'.format((k*math.cos(x)),(k*math.sin(x))))






from pyzt import inputi
product_list=[
    ('Iphone 11 pro max',700000),
    ('Nike',150000),
    ('AzatCoffe',750),
    ('Watch',150000),
    ('Surface',399000),]
shopping_list=[]
salary=inputi('Salary')
while True:
    for index,item in enumerate(product_list):
        print(index,item)
    user_choise=inputi('Which product do you wantto buy:')
    if user_choise<len(product_list) and user_choice>=0:
        p_item=product_list[user_choice]
        if p_item[1]<=salary:
            shopping_list.append(p_item)
            salary-=p_item[1]
            print(f'Added {p_item} into shopping cart,your current balance is {salary}')users = []
try:
    with open('users.txt', 'r') as f:
        users_data = f.read()
except FileNotFoundError:
    os.system('touch users.txt')
    with open('users.txt', 'r') as f:
        users_data = f.read()
finally:users = []
try:
    with open('users.txt', 'r') as f:
        users_data = f.read()
except FileNotFoundError:
    os.system('touch users.txt')users = []
try:
    with open('users.txt', 'r') as f:
        users_data = f.read()
except FileNotFoundError:
    os.system('touch users.txt')
    with open('users.txt', 'r') as f:
        users_data = f.read()
finally:
    print("Users data loaded!\n", end='')
    with open('users.txt','w')as f:
        f.write('')

print(users_data, end='')


def check_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    return (info in users_data_list)


users_dt_list = users_data.split('\n')

users = []
try:
    with open('users.txt', 'r') as f:
        users_data = f.read()
except FileNotFoundError:
    os.system('touch users.txt')
    with open('users.txt', 'r') as f:
        users_data = f.read()
finally:
    print("Users data loaded!\n", end='')
    with open('users.txt','w')as f:
        f.write('')

print(users_data, end='')


def check_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    return (info in users_data_list)


users_dt_list = users_data.split('\n')


print(check_user_info(users_dt_list, 'azatai3', 2019, 'superadmin'))


def add_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    users_data_list.append(info)
    return users_data_list


def check_info(user_data_list, user_name):
    for each in user_data_list:
        if user_name in each:
            return users_dt_list.index(each)
    else:
        return 100


def update_user_info(user_data_list, user_name, update_password, update_role):
    index = check_info(user_data_list, user_name)
    if index != 100:
        new_info = f"{user_name} {update_password} {update_role}"
        user_data_list[index] = new_info
    return user_data_list


print('azatai' in 'azatai 2019 superadmin')
dt_updated = update_user_info(users_dt_list, 'azatai', 'elel34', 'staff')

with open('users.txt', 'a+') as f:
    for each in dt_updated:
        f.write(each)

print(check_user_info(users_dt_list, 'azatai3', 2019, 'superadmin'))


def add_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    users_data_list.append(info)
    return users_data_list


def check_info(user_data_list, user_name):
    for each in user_data_list:
        if user_name in each:
            return users_dt_list.index(each)
    else:
        return 100


def update_user_info(user_data_list, user_name, update_password, update_role):
    index = check_info(user_data_list, user_name)
    if index != 100:
        new_info = f"{user_name} {update_password} {update_role}"
        user_data_list[index] = new_info
    return user_data_list


print('azatai' in 'azatai 2019 superadmin')
dt_updated = update_user_info(users_dt_list, 'azatai', 'elel34', 'staff')

with open('users.txt', 'a+') as f:
    for each in dt_updated:
        f.write(each)

    with open('users.txt', 'r') as f:
        users_data = f.read()
finally:
    print("Users data loaded!\n", end='')
    with open('users.txt','w')as f:
        f.write('')

print(users_data, end='')


def check_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    return (info in users_data_list)


users_dt_list = users_data.split('\n')


print(check_user_info(users_dt_list, 'azatai3', 2019, 'superadmin'))


def add_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    users_data_list.append(info)
    return users_data_list


def check_info(user_data_list, user_name):
    for each in user_data_list:
        if user_name in each:
            return users_dt_list.index(each)
    else:
        return 100


def update_user_info(user_data_list, user_name, update_password, update_role):
    index = check_info(user_data_list, user_name)
    if index != 100:
        new_info = f"{user_name} {update_password} {update_role}"
        user_data_list[index] = new_info
    return user_data_list


print('azatai' in 'azatai 2019 superadmin')
dt_updated = update_user_info(users_dt_list, 'azatai', 'elel34', 'staff')

with open('users.txt', 'a+') as f:
    for each in dt_updated:
        f.write(each)

    print("Users data loaded!\n", end='')
    with open('users.txt','w')as f:
        f.write('')

print(users_data, end='')


def check_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    return (info in users_data_list)


users_dt_list = users_data.split('\n')


print(check_user_info(users_dt_list, 'azatai3', 2019, 'superadmin'))


def add_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    users_data_list.append(info)
    return users_data_list


def check_info(user_data_list, user_name):
    for each in user_data_list:
        if user_name in each:
            return users_dt_list.index(each)
    else:
        return 100


def update_user_info(user_data_list, user_name, update_password, update_role):
    index = check_info(user_data_list, user_name)
    if index != 100:
        new_info = f"{user_name} {update_password} {update_role}"
        user_data_list[index] = new_info
    return user_data_list


print('azatai' in 'azatai 2019 superadmin')
dt_updated = update_user_info(users_dt_list, 'azatai', 'elel34', 'staff')

with open('users.txt', 'a+') as f:
    for each in dt_updated:
        f.write(each)

            break
        else:
            print(f'Sorry,only{salary} left on your credit.You can"t buy')
    else:
         print(f'Product {user_choice} does not exict Dude') 
         
         
         
         
         
         
         users = []
try:
    with open('users.txt', 'r') as f:
        users_data = f.read()
except FileNotFoundError:
    os.system('touch users.txt')
    with open('users.txt', 'r') as f:
        users_data = f.read()
finally:
    print("Users data loaded!\n", end='')
    with open('users.txt','w')as f:
        f.write('')

print(users_data, end='')


def check_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    return (info in users_data_list)


users_dt_list = users_data.split('\n')


print(check_user_info(users_dt_list, 'azatai3', 2019, 'superadmin'))


def add_user_info(users_data_list, user_name, user_password, user_role):
    info = f"{user_name} {user_password} {user_role}"
    users_data_list.append(info)
    return users_data_list


def check_info(user_data_list, user_name):
    for each in user_data_list:
        if user_name in each:
            return users_dt_list.index(each)
    else:
        return 100


def update_user_info(user_data_list, user_name, update_password, update_role):
    index = check_info(user_data_list, user_name)
    if index != 100:
        new_info = f"{user_name} {update_password} {update_role}"
        user_data_list[index] = new_info
    return user_data_list


print('azatai' in 'azatai 2019 superadmin')
dt_updated = update_user_info(users_dt_list, 'azatai', 'elel34', 'staff')

with open('users.txt', 'a+') as f:
    for each in dt_updated:
        f.write(each)

