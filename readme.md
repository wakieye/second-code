is_morning= True
is_afternoon= False
is_evening= False
is_late_night= False

name=input("what is your partner's name")

if is_morning:
    print("good morning Babe")
    print("i love you have a nice day " +  name)
elif is_afternoon:
    print("babe how is your afternoon")
    print("have you had lunch yet" + name)
elif is_evening:
    print("good evenig babe how is your day ")
    print("ilove you so much" + name)
elif is_late_night:
    print("goodnight Babe")
    print('have a lovely night' + name)
else:
    print(name)
