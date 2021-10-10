# mini-project 3-ая задача (про бензин)

petrol = float(input("Введите объем бензина (в галлонах)"))

if petrol < 0:

    print("Ошибка") 
    
if petrol >= 0:

    liters = petrol * 3.7854
    print("Объем бензина в литрах равен", "{:.2f}". format(liters))
    
    barrel = petrol/19.5
    print("Количество баррелей нефти", "{:.2f}". format(barrel))
    
    Vco2 = petrol * 20
    print("Объем углекислого газа при сжигании этого бензина", "{:.2f}". format(Vco2))
    
    ethanol = (petrol * 115000)/75700
    print("Эквивалентный объем этанола", "{:.2f}". format(ethanol))
    
    cost = petrol * 3
    print("Стоимость $" + "{:.2f}". format(cost)) 
    
print("Интересные факты: ")
russia = 94400000
person = russia/145975300                 
novosib = (person * 1620162)/365  
print(f"Примерный расход бензина в России равняется {russia} литров в год \nПримерный расход бензина в городе Новосибирске составляет {'{:.2f}'. format(novosib)} литров в день \nВ среднем на человека в России приходится {'{:.4f}'. format(person)} литров бензина в год")
