# 01-04-02-GardenPlots
**Kert parcellák. Készítsen OOP programot a osztályhierarchia elkészítésével.**    
A Kertépítő KFT olyan kerteket is épít, amelyiknek egy része zöldségtermesztésre alkalmas konyhakert, a másik része virágos kert lesz. Ilyen esetben ezek a kertek téglalap alakú parcellákból állnak.    
Készítsen OOP programot a következő osztályhierarchia elkészítésével.    
Készítsen kert parcella osztályt (GardenParcel) amelynek két olvasható tulajdonsága a parcella két oldalának hossza méterben megadva. Szintén olvasható kiszámított tulajdonsága a parcella területe.    
Készítse el a kert osztály (Garden) amely tárolja a kert tulajdonosának a nevét. Egy kert két parcellából áll: virágos kert és zöldségtermesztésre alkalmas konyhakert. Számított tulajdonsága a kert területe.    
Készítse el az osztályok UML diagramját!   
Tesztelésre használja a következő kódot:    
```
GardenParcel flowerGarden=GardenParcel(10,15);
Consolw.WriteLine(flowerGarden);
GardenParcel kitchenGarden=GardenParcel(10,6);
Consolw.WriteLine(kitchenGarden);
Garden marysGarden=(„Mária”, flowerGarden,kitchenGarden);
Consolw.WriteLine(marysGarden);
````
Kimenetek:   
A kiírások előtt a számított eredményeket két tizedes jegyre kerekítse.    
1.    
Consolw.WriteLine(floerGarden); kód esetén   
A 10x15-ös parcella területe xx.xx négyzetméter.    
2.    
Consolw.WriteLine(marysGarden); kód esetén    
A kert két parcellából áll:    
A 10x15 méretekkel adott parcella területe xx.xx négyzetméter.    
A 10x6 méretekkel adott parcella területe xx.xx négyzetméter.    
Mária kertjének összterülete xx.xx négyzetméter.    

[A téglalap területképlete.](http://www.amatematika.hu/a_teglalap_es_a_negyzet)
