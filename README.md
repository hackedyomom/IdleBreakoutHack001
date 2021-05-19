# IdleBreakoutHack001
[ERROR_009]

import base64

print("Idle Breakout Save Hack by EntityConfirmed")

print("What level do you want to be on?")
level = 1,000,000()

print("What amount of money would you like to have")
money = 1,000,000,000,000()

print("How much gold do you want")
gold = 1,000,000,000()

print("How many Black Boxes?")
bb = 1,000,000()

print("How many skillpoints")
sp = 1,000,000,000()

s = f"{level},{money},{gold},2,0,0,0,0,0,0,0,1,1,0,43595.78,999999,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,{bb},0,0,0,1,{sp},1,0,0"
b = s.encode("UTF-8")
e = base64.b64encode(b)
print("Encoding....")
print("Your result is....")
print(e)
print("\nCopy whats INSIDE the quotes\n")
end = 1
while end == 1:
    print("Once copied you may exit the console")
    input()

