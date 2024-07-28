How to calculate BMI
a=float(input('please enter your weight in kg :   '))
b=float(input('please enter your height in m  :   '))
bmi=(a)/(b**2)
print(f'this is your BMI : {bmi:.2f}' ) ٪٪ Rounding the decimal number of BMI to two decimal places
if bmi >=25:
      c=(bmi-25)*(b**2)
      print('overweight')
      print(f'you have {c:.2f} overweight')
else:

     print('normal')
