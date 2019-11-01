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
