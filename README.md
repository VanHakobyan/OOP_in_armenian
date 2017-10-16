## Օբեկտակողմնորշված Ծրագրավորում (OOP) : Պարզ բարդի մասին, առանց ծրագրավորման :


    
   Ցանկացած մարդ, որը սկսում է ուսումնասիրել որևէ ծրագրավորման լեզու, անկասկած հանդիպում է այնպիսի գաղափարի հետ, որը կոչվում է OOP:
Object Oriented Programming - ի թեման անվերջ է: Կարելի է շատ խոսալ այս թեմայով, բերել բազում օրինակներ տարբեր լեզուներով, բայց այդ բոլոր ներկայացումներն ունեն նույն սկզբնաղբյուրը, որը առաջացել է կենցաղային խնդիրի լուծումներ փնտրելու ճանապարհին:
   Այս նյութում կարճ և հասկանալի լեզվով (ոչ ծրագրավորման) ներկայացնում եմ  OOP-ն և նրա սկզբունքները (concept , парадигма):
   OOP-ն ներկայացնում է  2 հիմնական գաղափար՝ Class և Object:
   Class-ը (դասը) աբստրակտ տվյալների տիպ է (abstract data type): Class - ի միջոցով սահմանվում են որոշակի էություններ (entities) (հատկանիշները և հնարավոր գործողությունները):Օրինակ՝ class-ը կարող է նկարագրել ուսանողին, ավտոմեքենային և այսպես շարունակ:
  Object: Սահմանելով class-ը՝ կարող ենք սահմանել նրա որևէ օրինակ-օբյեկտ (instace-object): Object-ը արդեն Class-ի կոնկրետ  ներկայացումն է:
  Ըստ Պլատոնի՝ աշխարհը բաժանվում  էր 2 մասի՝ գաղափարների և իրերի :
Class-ները կարող ենք դիտարկել որպես գաղափարներ, իսկ object-ները՝ իրեր : Օրինակ ՝ միրգը գաղափար է , իսկ խնձորը՝ կոնկրետ իր (չնայած խնձորը նույնպես կարող է դիտարկվել գաղափար):
 Ստացվում է, որ OOP-ի առաջին հիշատակումները արել է, ոչ ավել  ոչ պակաս, Պլատոնը:
 

   OOP-ի սահմանում տալը անշնորհակալ գործ է, բայց այնուամենայնիվ, փորձենք ձևակերպել :

### OOP Ձևակերպում 1:

OOP-ի հիմանական խնդիրն է պռոեկցիա ստեղծել մատերիական իրականությունից կամ սուբեկտային իրականությունից դեպի վիրտուալ իրականություն:
   1.Մատերիական իրականություն - այն ինչ մենք տեսնում ու շոշափում ենք:
   2.Սյուբեկտային իրականություն  - այն ինչ մեր գլխում ու մտքերում է :
   3.Վիրտուալ իրականություն         - այն ինչ ստեղծում ենք ԷՀՄ-ներում (էլեկտրոնային հաշվիչ մեքենաներ):




### OOP Ձևակերպում 2:

OOP-ն ծրագրավորման մեթոդոլոգիա է, որը հիմնված է այն գաղափարի վրա, որ ցանկացած օբեկտների համախումբ հանդիսանում է որևէ Class-ի Instance, իսկ Class-ները ձևավորվում են որպես ժառանգականության հիերարխիա:
  


### OOP-ի ձևակերպումից հետո փորձենք տալ նրա սկզբունքների սահմանումները: Գոյություն ունի 4 հիմնական և ևս 2 ոչ հիմնական սկզբունքներ: 



1.Encapsulation (Ինկապսուլյացիա)
2.Inheritance (Ժառանգականություն)
3.Polymorphism (Պոլիմորֆիզմ)
4.Abstraction (Աբստրակցիա)
5.Sending messages (Հաղորդագրությունների փոխանցում)
6.Reusable (Բազմակի օգտագործում)


    
   Առաջին 4-ը OOP-ի հիմնական դրույթներն են, ընդ որում, ճիշտ այն հերթականությամբ, ինչպես որ նշված է: Բանն այն է, որ այստեղ գումարելիների տեղերը փոխելուց գումարը փոխվում է: Օրինակ՝ եթե դուք պատմում եք Ձեր ընկերոջը որևէ այլ անձի մասին և սկսեք նրան բնորոշել, սկսելով նրա կոշիկի համարից, համաձայնեք, որ Ձեր ընկերոջն այնքան էլ հասկանալի չի լինի: Այնպես որ, OOP-ի դրույթները թվարկելիս պետք է սկսել և ավարտել նշված հերթականությամբ, քանզի մեկը մյուսից ինչ որ չափով կախված է:
    Անդրադառնանք հիմնականներին:


  ### 1.Encapsulation (Ինկապսուլյացիա)

#### Ձևակերպում 1:

    Class-ի տվյալների «փակ» ռեալիզացիա:

#### Ձևակերպում 2:

Class-ի վիճակի «թաքցնելու» մեխանիզմը արտաքին միջամտությունից կոչվում է ինկապսուլյացիա:

#### Ձևակերպում 3:

  Նախատեսված է, որպեսզի թաքցվի ոչ պետքական կամ անհարկի ռեալիզացիայի դետալները (implementation details) user-օգտագործողից:

Օրինակ՝  
  Դուք ուսանող եք և որևէ հարցով ուզում եք դիմել դեկանին: Դրա համար Ձեր դիմումը պետք է ներկայացնեք դեկանատ, այնուհետև համապատասխան աշխատակիցը Ձեր դիմումը ներկայացնում է դեկանին, և թե այնտեղ ինչ գործընթացներ են իրականանում (դեկանը մեդիում է կանչում կամ խորհրդակցում է իր օգնականի կամ սիրուհու հետ), դուք չեք իմանում: Ձեզ ներկայացնում են միայն Ձեր դիմումի պատասխանը: Դեկանի աշխատանքը ինկապսուլացվում է:
 
### 2.Inheritance (Ժառանգականություն)

#### Ձևակերպում 1:

Ժառանգությունը այն մեխանիզմն է, որը թույլ է տալիս նոր class-ներ (տիպեր) կառուցել արդեն  գոյություն ունեցող class-երից (տիպերից)` ընդլայնելով եւ վերամշակելով իր հնարավորությունները (capabilities):

Ձևակերպում 2:

Ըստ էության ժառանգականությունը թույլ է տալիս ընդարձակել class-ի վարքագիծը՝ ժառանգելով բազային class-ի ֆունկցիոնալը: 


Օրինակ՝
   
   Ունենք մարդ class-ը, որն իր մեջ նկարագրում է, թե մարդն ինչ տեսքի է և ինչ հիմնական գործառույթներ ունի: Կան մարդու տարբեր տեսակներ՝ ուսանող, ոստիկան, ֆուտբոլիստ և այլն : Բոլորն էլ մարդ class-ի բոլոր հատկություններով օժտված են, բայց ամեն մեկը յուրովի է: Ուսանողի հիմանական գործառույթը սովորելն է, ոստիկանինը՝  կարգ ու կանոն պահպանելը, ֆուտբոլիստինը դե երևի հասկանալի է : Այսպիսով, ուսանողը, ոստիկանը, ֆուտբոլիստը ժառանգվում են մարդ-class-ից:


3. Polymorphism (Պոլիմորֆիզմ)

Ձևակերպում 1:

Polymorphism (պոլիմորֆիզմ) հունական բառ է, որը նշանակում է բազմաթիվ ձևեր ընդունելու ունակություն: Պոլիմորֆիզմը թույլ է տալիս տարբեր ներքին կառուցվածք ունեցող օբյեկտներին ունենալ ընդհանուր արտաքին ինտերֆեյս: Պոլիմորֆիզմը հատկապես արդյունավետ է ժառանգականության իրականացման ժամանակ:

Ձևակերպում 2:

Պոլիմորֆիզմը նույն օբեկտը տարբեր միջավայրերում իրեն տարբեր կերպ դրսևորելու հատկությունն է:

Օրինակ՝
   
   Օրինակը վերցրեք հենց Ձեր վրա: Դուք ենթադրենք ուսանող եք: Դասի գնալիս դուք պետք է հագնեք համապատասխան հագուստ (դասի չեք կարող գնալ լողազգեստով) և Ձեզ պետք է դրսևորեք ըստ ԲՈՒՀ-ական կանոնադրության, իսկ ծովափ գնալիս  հենց պետք է լինել լողազգեստով, կամ եթե դուք գնում եք գործնական հանդիպման պետք է կրեք համապատասխան հագուստ և չեք կարող հագնել սպորտային հագուստ: Ին՞չ է ստացվում: Դուք նույն «օբեկտն» եք, բայց կախված միջավայրից ձեզ տարբեր կերպ եք դրսևորում: 
  

 4.Abstraction (Աբստրակցիա)

Ձևակերպում 1:

Աբստրակցիան օբեկտին տալիս է հատկություններ՝ հստակ նշելով նրա տրամաբանական սահմնաննեը:

Ձևակերպում 2:

Abstraction-ը իրական աշխարհից որոշ օբյեկտներ վերցնելու հատկությունն է՝ այն վերափոխելով ծրագրավորման տերմինալոգիայով:



Օրինակ՝
  Երբ ասում ենք ավտոմեքենա մենք կոնկրետ մեքենա չենք հասկանում այլ հասկանում ենք ընդհանուր գաղափարը: Այլ բան է երբ ասում ենք  Mitsubishi Pajero iO 1.8 4WD 1999թ. բալագույն, ապա հասկանում եմ, որ դա ընկերոջս ավտոմեքենան է, այսինքն կոնկրետ օբեկտ է ոչ թե գաղափար :  
