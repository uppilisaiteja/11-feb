sno=int(input('enter sno'))

sname=input('enter sname')

s1=int(input('s1 marks'))

s2=int(input('s2 marks'))

s3=int(input('s3 marks'))

s4=int(input('s4 marks'))

s5=int(input('s5 marks'))

s6=int(input('s6 marks'))

total=s1+s2+s3+s4+s5+s6

avg=total/6

if(s1<35 or s2<35 or s3<35 or s4<35 or s5<35 or s6<35):

    print('fail')

elif avg>=91:

    print('o-grade')

elif avg>=81:

    print('a-grade')

elif avg>=71: 

    print('b-grade')

elif avg>=60:

    print('c-grade')

elif avg>=50:

    print('d-grade')

else avg>=40:

    print('pass')
