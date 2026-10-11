x= int(input("Enter a SHAKHA no."))
if x== 1:
  print("1.kunal\n2.saksham")
  A= input("Enter a name: ")
  if A== "kunal":
    print("kunal Randi 300")
  if A== "saksham":
    print("saksham 300")

elif x== 2:
    print("1.shreyash\n2.Abhi")
    A= input("Enter a name: ")
    if A=="Shreyash":
        print("Shreyash 300")
    if A== "Abhi":
        print("Abhi 300")
elif x== 3:
    print("1.Buch Adi\n2.Yash\n3.Adi")
    A= input("Enter a name: ")
    if A== "Buch Adi":
        print("Buch Adi 300")
    if A== "ash":
        print("Yash 300")
    if A== "Adi":
        print("Adi 300")
elif x== 4:
    print("1.Rohit\n2.Mayu\n3.sk")
    A= input("Enter a name: ")
    if A== "Rohit":
        print("Rohit 300")
    if A== "Mayu":
        print("Mayu 300")
    if A== "sk":
        print("sK")

def calculate_bill(price, quantity):
  return price * quantity

price = 300
quantity = int(input("Enter a no. of shots: "))

niks = calculate_bill(price, quantity)

print("Total price is: ", niks)
if niks >=1800:
  print("Congratulation! Coupon Applied, you will credit 300 in your wallet.")
else:
   print("Coupon not Available")
