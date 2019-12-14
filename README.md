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




























import time
import settings
import platform
import subprocess
import view
import module
from pyzt import inputs, inputi, inputf


def logger(message):
    time_format  = "%Y-%m-%d %X %A %B %p %r"
    time_current = time.strftime(time_format)
    with open('data/log.txt','a') as f:
        f.write(f"{message}")
        f.write('\n')

class Control():
    fr = settings.FIRST_RUN
    current_user = 'Azat' #Current user in this session
    current_user_role = 'admin'

    def prepare_file(self,log='data/log.txt',users='data/users.txt',products='data/products.txt',orders='data/orders.txt'):
        path_list = [log,orders,products,users]
        for each in path_list:
            with open(each,'w') as f:
                f.write('')

    def system_check(self):
        # check python version
        print(f"Step 1: Checking Python Version : {platform.python_version()}")
        if platform.python_version()[0] == '3':
            print('PYTHON VERSION OK!')
        else:
            exit('Sorry, The program does not support your python version, please update to python3.x')
        # check required packages installed
        print(f"Step 2: Checking Python packages")
        required_pkgs = ['azt','pyzt']
        installed_pkgs = subprocess.check_output(['pip3','list']).decode("utf-8")
        for pkg in required_pkgs:
            if pkg not in installed_pkgs:
                exit("requirements not installed! Please install all of required packages.")
            print("PYTHON PACKAGE REQUIREMENTS OK!")
        print(f"Step 3: Checking data resources")
        data_resources = ['data/log.txt','data/users.txt','data/products.txt','data/orders.txt']
        for each in data_resources:
            try:
                with open(each) as f:
                    pass
            except FileNotFoundError:
                exit("Data Source NOt Found!")

    def run(self):
        print("Running the AzatAI Python Shop system self checking")
        self.system_check()
        self.prepare_file()
        if self.fr is False: # super admin already exist
            print("In the case super admin already exist")
            # TODO
        else:
            home = view.Home()
            home.superadmin()
            user_name = inputs('Please input a username for SUPERADMIN:\n')
            user_pw = inputs(f'Please input a password for SUPERADMIN {user_name}:\n')
            user = module.User()
            user.is_admin = True
            user.add(user_name,user_pw)
            settings.SUPER_ADMIN = user_name
            settings.SUPER_ADMIN_PW = user_pw
            settings.CURRENT_USER = user_name
            settings.CURRENT_USER_ROLE = "Admin"
            self.log(user_name,user_pw,'Admin')
            self.admin()

            # TODO
    def admin(self):
        view.Home().welcome()
        while True:
            admin_choice = inputi("Танданыз : 1-logout; 2-адамдарды кору; 3-кирип шыққан адамдарды көрсету; 4-басты бетке кайта оралу \n")
            if admin_choice==1:
                self.adminlogout()
            elif admin_choice==2:
                view.Home().welcome()
                print('usr,pwd,                  date created            ,admin,staff, client , manager  ')
                with open('data/users.txt','r') as f:
                    data=f.read().split('\n')
                    data.pop()
                    for i in data:
                        print(i)
                    while True:
                        t=inputs('статусын озгерту -1, logout-2, басты бет-3: ')
                        if t=='1':
                            if len(data)==1:
                                print('сіз-Админсиз озиниздикин озгерте ала алмайсыз!!!')
                                while True:
                                    r1=inputs("q- басты бет; 1-logout ; 2-артқа қайту: ")
                                    if r1=='q':
                                        self.admin()
                                    elif r1=='1':
                                        self.adminlogout()
                                    elif r1=='2':
                                        break
                            elif len(data)>1:
                                f_list = []
                                with open('data/users.txt', 'r+') as f:
                                    data = f.read().split('\n')
                                    data.pop()
                                    for i in data:
                                        a = i.split(',')
                                        f_list.append(a)
                                    print('  usr,  pwd,                      date created                   , admin ,   staff , client , manager  ')
                                    for i, i1 in enumerate(f_list):
                                        print(i, i1)
                                    while True:
                                        t1 = inputs('Статусты өзгерту ушин индексін териниз; q- басты бет; q1-logout,q2-артқа қайту :  ')
                                        if t1=='q':
                                            self.admin()
                                        elif t1=='q1':
                                            self.adminlogout()
                                        elif t1=='q2':
                                            break
                                        else:
                                            try:
                                                if int(t1)<len(f_list) and int(t1)!=0:
                                                    while True:
                                                        t2 = inputs('Client>>Manager-1, Client>>Staff-2 , Staff>>Manager-3:')
                                                        if t2 == '1':
                                                            if f_list[int(t1)][5] == 'True' and f_list[int(t1)][6]=='False' and f_list[int(t1)][3]!='True' and f_list[int(t1)][4]!='True':
                                                                f_list[int(t1)][5]='False'
                                                                f_list[int(t1)][6]='True'

                                                                print('  usr,  pwd,                      date created                   , admin ,   staff , client , manager  ')
                                                                with open('data/users.txt','w+') as d1:
                                                                    for i in f_list:
                                                                        for it in i:
                                                                            d1.write(it+',')
                                                                        d1.write('\n')
                                                                        print(i)
                                                                while True:
                                                                    r2 = inputs("1- басты бетке; q-logout ,2-артқа қайту: ")
                                                                    if r2 == '1':
                                                                        self.admin()
                                                                    elif r2 == 'q':
                                                                        self.adminlogout()
                                                                    elif r2=='2':
                                                                        break

                                                            else:
                                                                while True:
                                                                    tr = inputs('''бул тапсырма орындалмады таңдаңыз:
                                                                    1- басты бет; q-logout;3-артқа қайту ''')
                                                                    if tr == '1':
                                                                        self.admin()
                                                                    elif tr == 'q':
                                                                        self.adminlogout()
                                                                    elif tr=='3':
                                                                        break



                                                        elif t2=='2':
                                                            if f_list[int(t1)][5] == 'True' and f_list[int(t1)][4]=='False' and f_list[int(t1)][3]!='True' and f_list[int(t1)][4]!='True':
                                                                f_list[int(t1)][5]='False'
                                                                f_list[int(t1)][4]='True'
                                                                print('  usr,  pwd,                      date created                   , admin ,   staff , client , manager  ')
                                                                with open('data/users.txt','w+') as d2:
                                                                    for i in f_list:
                                                                        for it in i:
                                                                            d2.write(it+',')
                                                                        d2.write('\n')
                                                                # with open('data/users.txt', 'r') as d112:
                                                                #     data11 = d112.read().split('\n')
                                                                #     data11.pop()
                                                                #     for i in data11:
                                                                        print(i)
                                                                while True:
                                                                    r2 = inputs("1- басты бет; q-logout , 2-артқа қайту: ")
                                                                    if r2 == '1':
                                                                        self.admin()
                                                                    elif r2 == 'q':
                                                                        self.adminlogout()
                                                                    elif r2=='2':
                                                                        break
                                                            else:
                                                                while True:
                                                                    tr = inputs('''Тапсырма орындалмады,таңдаңыз:
                                                                    1- басты бет; q-logout;3-артқа қайту ''')
                                                                    if tr == '1':
                                                                        self.admin()
                                                                    elif tr == 'q':
                                                                        self.adminlogout()
                                                                    elif tr=='3':
                                                                        break

                                                        elif t2=='3':
                                                            if f_list[int(t1)][4] == 'True' and f_list[int(t1)][6]=='False' and f_list[int(t1)][3]!='True' and f_list[int(t1)][5]!='True':
                                                                f_list[int(t1)][4]='False'
                                                                f_list[int(t1)][6]='True'
                                                                print('  usr,  pwd,                      date created                   , admin ,   staff , client , manager  ')
                                                                with open('data/users.txt','w+') as d3:
                                                                    for i in f_list:
                                                                        for it in i:
                                                                            d3.write(it+',')
                                                                        d3.write('\n')
                                                                # with open('data/users.txt', 'r') as d31:
                                                                #     data13 = d31.read().split('\n')
                                                                #     data13.pop()
                                                                #     for i in data13:
                                                                        print(i)
                                                                while True:
                                                                    r2 = inputs("1- басты бет; q-logout,2-артқа қайту : ")
                                                                    if r2 == '1':
                                                                        self.admin()
                                                                    elif r2 == 'q':
                                                                        self.adminlogout()
                                                                    elif r2=='2':
                                                                        break
                                                            else:
                                                                while True:
                                                                    tr = inputs('''Орындалмады, таңдаңыз:
                                                                    1- басты бет; q-logout ; 3-артқа қайту: ''')
                                                                    if tr == '1':
                                                                        self.admin()
                                                                    elif tr == 'q':
                                                                        self.adminlogout()
                                                                    elif tr=='3':
                                                                        break
                                                                    else:
                                                                        print('Kaita engiz')
                                                        else:
                                                            while True:
                                                                tr = inputs('''орындалмады, таңдаңыз:
                                                                1- басты бет; q-logout;3-артқа қайту : ''')
                                                                if tr == '1':
                                                                    self.admin()
                                                                elif tr == 'q':
                                                                    self.adminlogout()
                                                                elif tr == '3':
                                                                    break
                                                                else:
                                                                    print('Kaita engiz')
                                                else:
                                                    print('Kaita engiz, Siz ozinizdin statusynyzdy ozgerte ala almaisyz!!!')
                                            except (ValueError):
                                                print('Kaita engiz')

                        elif t=='2':
                            self.adminlogout()
                        elif t=='3':
                            self.admin()


            elif admin_choice==3:
                with open('data/log.txt','r') as f1:
                    print(f1.read())
                    while True:
                        tanda1 = inputs('1-басты бет, q-loqout:')
                        if tanda1=='1':
                            self.admin()
                        elif tanda1=='q':
                            self.adminlogout()
            elif admin_choice==4:
                self.admin()


    def login(self):
            usr=inputs('username:')
            pwd=inputs('password:')
            f_list=[]
            with open('data/users.txt', 'r') as f:
                data = f.read().split('\n')
                data.pop()
                for i in data:
                    a = i.split(',')
                    f_list.append(a)
                for i in range(len(f_list)):
                    if  f_list[i][0]==usr and f_list[i][1]==pwd and f_list[i][3]=='True':
                        settings.CURRENT_USER_ROLE='Admin'
                        settings.CURRENT_USER=usr
                        self.log(usr,pwd,settings.CURRENT_USER_ROLE)
                        self.admin()
                    elif f_list[i][0]==usr and f_list[i][1]==pwd and f_list[i][5]=='True':
                        settings.CURRENT_USER_ROLE='Client'
                        settings.CURRENT_USER=usr
                        self.log(usr, pwd, settings.CURRENT_USER_ROLE)
                        self.client()
                    elif f_list[i][0]==usr and f_list[i][1]==pwd and f_list[i][6]=='True':
                        settings.CURRENT_USER_ROLE='Manager'
                        settings.CURRENT_USER=usr
                        self.log(usr, pwd, settings.CURRENT_USER_ROLE)
                        self.manager()
                    elif f_list[i][0]==usr and f_list[i][1]==pwd and f_list[i][4]=='True':
                        settings.CURRENT_USER_ROLE='Staff'
                        settings.CURRENT_USER=usr
                        self.log(usr, pwd, settings.CURRENT_USER_ROLE)
                        self.staff()
                else:
                    print('сіз бұл сайтқа тіркелмегенсіз')
                    self.Registration()





    def Registration(self):
            settings.CURRENT_USER_ROLE = ''
            view.Home().welcome()
            while True:
                t=inputs('Registration -1, login-2:')
                if t=='1':
                    settings.CURRENT_USER_ROLE = ''
                    usr = inputs('username:')
                    pwd = inputs('password:')
                    f_list = []
                    with open('data/users.txt', 'r') as f:
                        data = f.read().split('\n')
                        data.pop()
                        for i in data:
                            a = i.split(',')
                            f_list.append(a)
                        for i in range(len(f_list)):
                            if f_list[i][0] == usr and f_list[i][1] == pwd and f_list[i][3] == 'True':
                                print('bul account saitta tirkelgen')
                                self.Registration()
                            elif f_list[i][0] == usr and f_list[i][1] == pwd and f_list[i][5] == 'True':
                                print('bul account siteta tirkelgen')
                                self.Registration()
                            elif f_list[i][0] == usr and f_list[i][1] == pwd and f_list[i][6] == 'True':
                                print('bul account siteta tirkelgen')
                                self.Registration()
                            elif f_list[i][0] == usr and f_list[i][1] == pwd and f_list[i][4] == 'True':
                                print('bul account siteta tirkelgen')
                                self.Registration()

                        if usr!='' and pwd!='':
                                user=module.User()
                                user.is_client=True
                                user.add(usr,pwd)
                                settings.CURRENT_USER_ROLE = 'Client'
                                settings.CURRENT_USER = usr
                                self.log(usr, pwd, settings.CURRENT_USER_ROLE)
                                self.client()
                        else:
                            print('Енгізген аккаунт қате, кайта енгізіңіз!')

                elif t=='2':
                    self.login()


    def client(self):
        view.Home().welcome()
        while True:
            tanda=inputs('1-Жалғастыру, 2-loqout , 3-басты бет \n')
            if tanda=='1':
                view.Home().welcome()
                sum = 0
                shopping_list = []
                print('Бізде бар продуктылар тізімі: ')
                n3 = []
                with open('1mall.txt', 'r') as fi8:
                        data = fi8.read()
                        data_split = data.split('\n')
                        for i in data_split:
                            i3 = i.split('-')
                            n3.append(tuple(i3))
                n3.pop()
                for index, item in enumerate(n3):
                    print(index, item)
                surau = inputi('Сіздің жалақыңыз қанша?: ')
                zhalaky = surau
                while True:
                        surau1 = inputs("шоппингті жалғастыру -'ok', шоппингті тоқтату-'q', logout -1, басты бет-q1 ")
                        if surau1 == 'ok':
                            print('Продуктылар тізімі: ')
                            n2 = []
                            with open('1mall.txt', 'r') as fi8:
                                data = fi8.read()
                                data_split = data.split('\n')
                                for i in data_split:
                                    i3 = i.split('-')
                                    n2.append(tuple(i3))
                            n2.pop()
                            for index, item in enumerate(n2):
                                print(index, item)
                            surau3 = inputi("Қай продуктыны калайсыз? ")
                            if surau3 < len(n2) and surau3 >= 0:
                                p_item = list(n2[surau3])
                                p_int = int(p_item[1])
                                if p_int <= surau:
                                    shopping_list.append(tuple(p_item))
                                    sum += p_int
                                    surau -= p_int
                                    print(f'Сіз таңдаған тауар дайын, сіздің қазіргі балансыңыз {surau}')
                                    timenow = subprocess.check_output(['date']).decode()
                                    with open('zakaz.txt', 'a') as file:
                                        file.write(str(p_item[0]) + '-' + str(p_item[1]) + '-' + timenow)
                                else:
                                    print('Кешіріңіз сіздің балансыңыз жетпейді!!!')
                            else:
                                print(f"Бізде {surau3}-бұл продукт жоқ ")
                        elif surau1 == 'q':
                            if sum > 0:
                                ch = set()
                                print('1mall онлайн магазин')
                                print(''.center(30, '-'))
                                timenow = subprocess.check_output(['date']).decode()
                                print(timenow)
                                for i in shopping_list:
                                    sd = (i, shopping_list.count(i))
                                    ch.add(sd)
                                for each in ch:
                                    print(each)
                                print(''.center(30, '-'))
                                print(f"ИТОГ         ={zhalaky - surau}")
                                print('Тауар алганыз ушин ракмет!Бизбен бирге болыныз!!!')
                                while True:
                                    tr = inputs('''1- басты бет; q-logout;3-артқа қайту : ''')
                                    if tr == '1':
                                        self.client()
                                    elif tr == 'q':
                                        self.clientlogout()
                                    elif tr == '3':
                                        break

                            else:
                                self.client()

                        elif surau1 == '1':
                            self.clientlogout()
                        elif surau1=='q1':
                            self.client()
            elif tanda=='2':
                self.clientlogout()
            elif tanda=='3':
                self.client()
    def manager(self):
        view.Home().welcome()
        while True:
            tanda = inputs('1-Жалғастыру, 2-loqout , 3-басты бет \n')
            if tanda == '1':
                view.Home().welcome()
                while True:
                    tandau = inputi('1-барлық продукты тізімін көру,2-тізімнен продуктыны өшіру, 3-сатылған продуктылардың тізімін көру, 4-басты бет, 5-logout:')
                    if tandau == 1:
                        with open('1mall.txt', 'r') as f:
                            print(f.read())
                        while True:
                            engiz4 = inputs(' басты бетке оралу -q, logout -1, артқа қайту-2: ')
                            if engiz4 == 'q':
                                self.manager()
                            elif engiz4 == '1':
                                self.managerlogout()
                            elif engiz4=='2':
                                break
                    elif tandau == 2:
                            n2 = []
                            with open('1mall.txt', 'r') as fi8:
                                data = fi8.read()
                                data_split = data.split('\n')
                                for i in data_split:
                                    i3 = i.split('-')
                                    n2.append(tuple(i3))
                            n2.pop()
                            for index, item in enumerate(n2):
                                print(index, item)
                            while True:
                                engiz = inputs('Жалғастыру үшін-ok , басты бет -q, logout -1,  артқа қайту-2: ')
                                if engiz == 'ok':
                                    tandau1 = inputi('Тізімдегі қай продуктыны өшіресіз? ')
                                    if tandau1 >= 0 and tandau1 < len(n2):
                                        n2.remove(n2[tandau1])
                                        with open('1mall.txt', 'w') as d5:
                                            for i in n2:
                                                d5.write(i[0] + '-' + i[1] + '\n')
                                        break
                                    else:
                                        print('Бұндай продукты тізімде жоқ!')
                                elif engiz == 'q':
                                    self.manager()
                                elif engiz=='1':
                                    self.managerlogout()
                                elif engiz=='2':
                                    break
                    elif tandau == 3:
                        with open('zakaz.txt', 'r') as z:
                            print(z.read())
                            while True:
                                engiz4= inputs(' басты бет -q, logout -1,артқа қайту -2: ')
                                if engiz4=='q':
                                    self.manager()
                                elif engiz4 == '1':
                                    self.managerlogout()
                                elif engiz4=='2':
                                    break
                    elif tandau == 4:
                        self.manager()
                    elif tandau==5:
                        self.managerlogout()

            elif tanda=='2':
                self.managerlogout()
            elif tanda=='3':
                self.manager()


    def staff(self):
        view.Home().welcome()
        while True:
            tan=inputs('1-Жалғастыру, 2-logout, 3-басты бет')
            if tan=='1':
                view.Home().welcome()
                while True:
                    tandau = inputs('1-списокке тауар қосу, 2-бағаларын өзгерту,3-барлық тауарлaрды көру,0-басты бет, q-logout:')
                    if tandau == '1':
                        while True:
                            n = []
                            with open('1mall.txt', 'r') as fi:
                                data = fi.read()
                                data_split = data.split('\n')
                                for i in data_split:
                                    i2 = i.split('-')
                                    n.append(tuple(i2))
                            n.pop()
                            for index, item in enumerate(n):
                                print(index, item)
                            product = inputs('Қай продукты енгізгіңіз келеді? Аты:')
                            price = inputi('Тауар бағасы:')
                            n.append(tuple([product, price]))
                            with open('1mall.txt', 'w') as fil:
                                for item in n:
                                    fil.write(str(item[0]) + '-' + str(item[1]) + '\n')
                            while True:
                                surak = inputs("Тізімге жаңа тауар енгізесіз бе? ok -жалғастыру үшін, q -басты бет, q1- logout :")
                                if surak == 'q':
                                    self.staff()
                                elif surak == 'ok':
                                    break
                                elif surak=='q1':
                                    self.stafflogout()
                                else:
                                    print('Kaita engiz!')
                    elif tandau == '2':

                            n1 = []
                            with open('1mall.txt', 'r') as fi7:
                                data = fi7.read()
                                data_split = data.split('\n')
                                for i in data_split:
                                    i3 = i.split('-')
                                    n1.append(tuple(i3))
                            n1.pop()
                            for index, item in enumerate(n1):
                                print(index, item)
                            while True:
                                surak = inputs("Өзгерту үшін-1 , артқа қайту -2, басты бет-3, q-logout: :")
                                if surak == '1':
                                    prod_index = inputi('Қай продуктыны өзгерткіңіз келeді?: ')
                                    if prod_index < len(n1) and prod_index >= 0:
                                        prod_item = list(n1[prod_index])
                                        print(prod_item[0], end=' ')
                                        change_price = inputi('Продуктың жаңа бағасы:')
                                        prod_item.insert(1, change_price)
                                        prod_item.pop()
                                        n1.insert(prod_index, tuple(prod_item))
                                        n1.pop(prod_index + 1)
                                        with open('1mall.txt', 'w') as d4:
                                            for item in n1:
                                                d4.write(str(item[0]) + '-' + str(item[1]) + '\n')

                                    else:
                                        print(f" {prod_index} -Өкінішке орай сіз қателестіңіз,тауар жоқ! ")
                                elif surak == '2':
                                    break
                                elif surak=='3':
                                    self.staff()
                                elif surak=='q':
                                    self.stafflogout()

                    elif tandau == '3':
                        print('Тауар тізімі:')
                        with open('1mall.txt', 'r') as f1:
                            print(f1.read())
                            while True:
                                surau=inputs('q-logout, 1-басты бет,2-артқа қайту')
                                if surau=='q':
                                    self.stafflogout()
                                elif surau=='1':
                                    self.staff()
                                elif surau=='2':
                                    break
                    elif tandau == '0':
                        self.staff()
                    elif tandau=='q':
                        self.stafflogout()
            elif tan=='2':
                self.stafflogout()
            elif tan=='3':
                self.staff()


    def logout(self,role):
        time_format = "%Y-%m-%d %X %A %B %p %r"
        time_current = time.strftime(time_format)
        with open('data/log.txt', 'a') as f:
            f.write(f" {role} {'шықты'} {time_current}")
            f.write('\n')

    def adminlogout(self):
        f_list1 = []
        with open('data/users.txt', 'r') as f:
            data = f.read().split('\n')
            data.pop()
            for i in data:
                a = i.split(',')
                f_list1.append(a)
            for i in range(len(f_list1)):
                if f_list1[i][3] == 'True':
                    self.logout('Admin')
                    self.Registration()

    def clientlogout(self):
        f_list1 = []
        with open('data/users.txt', 'r') as f:
            data = f.read().split('\n')
            data.pop()
            for i in data:
                a = i.split(',')
                f_list1.append(a)
            for i in range(len(f_list1)):
                if f_list1[i][5] == 'True':
                    self.logout('Client')
                    self.Registration()
    def managerlogout(self):
        f_list1 = []
        with open('data/users.txt', 'r') as f:
            data = f.read().split('\n')
            data.pop()
            for i in data:
                a = i.split(',')
                f_list1.append(a)
            for i in range(len(f_list1)):
                if f_list1[i][6] == 'True':
                    self.logout('Manager')
                    self.Registration()
    def stafflogout(self):
        f_list1 = []
        with open('data/users.txt', 'r') as f:
            data = f.read().split('\n')
            data.pop()
            for i in data:
                a = i.split(',')
                f_list1.append(a)
            for i in range(len(f_list1)):
                if f_list1[i][4] == 'True':
                    self.logout('Staff')
                    self.Registration()

    def log(self,user,pwd,role):
        time_format = "%Y-%m-%d %X %A %B %p %r"
        time_current = time.strftime(time_format)
        with open('data/log.txt', 'a') as f:
            f.write(f"{user} ,{pwd} , {role} {'кірді'} {time_current}")
            f.write('\n')




















import time
import control
import settings


class User():
    """
    This is the blue print of User Instance
    """
    user_name = ''
    user_pw = ''
    date_created = ''
    is_admin = False
    is_staff = False
    is_client = False
    is_manager=False
    all_users = []

    def __init__(self):
        with open('data/users.txt','r') as f:
            user_data = f.read()
        user_list = user_data.strip('\n').split('\n')
        self.all_users = user_list

    def add(self,user_name, user_pw):
        """
        bla bal
        :param user_name:
        :param user_pw:
        :return:
        """
        time_format = "%Y-%m-%d %X %A %B %p %r"
        time_current = time.strftime(time_format)
        self.user_name = user_name
        self.user_pw = user_pw
        self.date_created = time_current
        user_string = f"{self.user_name},{self.user_pw},m {self.date_created},{self.is_admin},{self.is_staff},{self.is_client},{self.is_manager}"
        log_message = f"Created new User: {user_string}"
        control.logger(log_message)
        with open("data/users.txt",'a') as f:
            f.write(user_string)
            f.write('\n')
        self.__init__()
