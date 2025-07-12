def study_bot():
        name = input("What is your name: ")
        print("Hey!", name, "it's me, your Study Buddy!")

        total_days = int(input("Which day of the week is it today? "))
        for day in range(1, total_days + 1):
            print(f"\nDay {day}:")
        if day == 1:
            print("Gurl, Lt's start studying!")
        elif day == 2:
            print("You did great today, Love you")
        elif day == 3:
            print("Consistency is key, you are doin great!!")
        elif day == 4:
            print("3 more days to go, you go champ")
        elif day == 5:
            print("You are a warrior, sending lots of love and candy")
        elif day == 6:
            print("You are not a star,you are the whole galaxy.")
        elif day == 7:
            print("Congraaaaats!!! Treat yourself with a cake, you deserve it.")
        else:
            print("You are a legend, keep going...")

        mood = input("How are you feeling today, my cupcake? ")
        if mood == "happy":
            print("Yay! keep going babes.")
        elif mood == "sad":
            print("Aww it's okay, I'm sending you chocolate and hugs..")
        else:
            print("Talk to yourself, keep swimming!!!")
    
        print(f"\n{name}, you finished {total_days} days of study, your study buddy is soooo proud of you.")
    
study_bot()

