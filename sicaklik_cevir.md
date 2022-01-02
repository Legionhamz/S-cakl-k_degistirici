# S-cakl-k_degistirici




print("#========== Sıcaklık Çevirici ==========#")


while True:
    yesNo = input("devam etmek istermisin? evet/hayır (e/h) : ")
    
    if yesNo == "e":
    
        print("celsius-fahrenheit(1), fahrenheit-celsius(2)")      # Burada bir seçim yapın

        selection = input("1 or 2: ")
    
        if selection == "1":
            celsius = float(input("bir derece giriniz: "))      #eğer seçim 1 ise bu formül ile girilen celsius derecesini fahrenheit'e çevirir
            x = (9*celsius + 160)/5
            print("{} fahrenheit'dir.".format(x))
    
        elif selection == "2":
            fahrenheit = float(input("bir derece giriniz: "))   #seçim 2 ise bu formül ile girilen fahrenheit derecesini celsius'a çevirir 
            y = (5*fahrenheit - 160)/9
            print("{} fahrenheit'dir.".format(y))

        else:
            print("yanlış bir giriş")
    
    elif yesNo == "h":
        print("Görüşmek üzere!!!")
        break
    
    else:
        print("Hatalı bir giriş!!!")



