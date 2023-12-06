T=float(input("enter value of T:"))
H=float(input("enter value of H:"))
w=float(input("enter value of w:"))

W=0.5 * T**2 - 0.2 * H + 0.1 * w - 15
print(W)
if W>300:
    print("sunny")
elif 200<W<=300:
    print("cloudy")
elif 100<W<=200:
    print("rainy")
else:
    print("stormy")  
