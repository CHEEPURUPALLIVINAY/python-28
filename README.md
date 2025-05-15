ch= input("enter any character from a-z")
if ch>'A' and ch<='z':
    ch= ch.lower()
    print("converted case of input char:",ch)
else:
   ch= ch.upper()
   print("converted case of input char:",ch)
