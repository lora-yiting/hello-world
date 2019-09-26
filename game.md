name = raw_input('Name of the player?: ')
gift = raw_input("You are going to a birthday party of your friend. You may want to choose something as a gift. cookies or pen?: ")

if (gift == "cookies"):
    #do cookie stuff
    print(name + " takes cookies as gift") 
    location = raw_input("Which way to choose,go through a forest or climb a hill?:  ")#forest or hill    
    if (location == "climb a hill"):
        print(name + " climb the hill with cookies and sadly got robbed and lost everything!!!")#cookies & hill
        mood = raw_input("What do you think would be the mood of friend, happy or disappointed?: ")
        if (mood == "happy"):
            print("Not a chance :) ")
        elif mood == "disappointed":
            print("SURE!")
    elif location == "go through a forest":
        print(name + " went through a forest with cookies and had no empty hand for a beautiful flower on the way!")#cookies & forest
        mood = raw_input("What do you think would be the mood of friend, happy or disappointed?: ")
        if (mood == "happy"):
            print("Your friend was happy and you had a great time!")
        elif mood == "disappointed":
            print("Of course not!")

else:
    #do pen stuff
    print(name + " takes a pen as gift") 
    location = raw_input("Which way to choose,go through a forest or climb a hill?:  ")#forest or hill
    if (location=="climb a hill"):
        #pen & hill
        print(name + ' climb the hill with a pen and after a long way,successfully brought a pen as gift :)')
        mood = raw_input("What do you think would be the mood of friend, happy or disappointed?: ")
        if (mood == "happy"):
            print("Maybe :) ")
        elif mood == "disappointed":
            print("Not true!")
    #else:
    elif location == "go through a forest":
        print(name + " went through a forest with a pen, also got chance to get a beautiful flower during the way!")#pen & forest
        mood = raw_input("What do you think would be the mood of friend, happy or disappointed?: ")
        if (mood == "happy"):
            print("Yes!Your friend was really glad :) and made you a nice pie! ")
        elif mood == "disappointed":
            print("What! Of course not!")
