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
            print(f'Added {p_item} into shopping cart,your current balance is {salary}')
            break
        else:
            print(f'Sorry,only{salary} left on your credit.You can"t buy')
    else:
         print(f'Product {user_choice} does not exict Dude') 
