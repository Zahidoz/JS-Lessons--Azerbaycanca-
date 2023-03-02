# Box Model , background

Əvvəlki dərsdə div sahəsini görmək üçün ona bacground vermişdik. İndi isə background mövzusunu daha da aydınlaşdıraq.  CSS - də background növləri vardır.
* background
	* background-color  
	* background-image 
	* background-repeat 
	* background-attachment
	* background-position

\
**background color** - > Arxa fonun rəngi deməkdir. 
```css
body {  
	background-color:  lightblue;  
}
```
Bundan əlavə rəngləri adı, rgba dəyərində və ya hex dəyərində yaza bilərik.
```css
body {  
	background-color:  lightblue;  
}
.box1{
	background-color: #6badca;
}
.box2{	
	background-color: rgb(64, 18, 133);
	color: #fff;
}
.box3{	
	background-color: rgba(51, 51, 225, 0.84);
}
```
**rgb** -> (red, green, blue) rənglərin ortalamasıdır. 
**rgba** - > o da rgb kimidir, sadəcə rəngə opacity( qeyri-şəffaflıq ) vermək mümkündür.
\
**background-image** - > Arxa fona şəkil qoymaq üçündür. 
```css
body {  
	background-image:  url("car.jpg");  
}
```
Bəzən isə şəkil bütün sahəni tutmaq üçün təkrarlanır. Bunun üçün....
**background-repeat** - > Arxa fonda olan şəkli təkrarlanmaları idarə etmək üçündür. 
```css
body {  
	background-image:  url("sky.png");  
	background-repeat:  no-repeat;  
}
```
**background-position ** - > Arxa fondakı şəklinin mövqeyini təyin etmək üçün istifadə olunur.
```css
body {  
	background-image:  url("cool_bg.jpg");  
	background-repeat:  no-repeat;  
	background-position:  center  
}
```
**background-position ** - > Arxa fon şəklinin düzəldilməli olduğunu qeyd edin:

```css
body{  
	background-image:  url("tree.png");  
	background-repeat:  no-repeat;  
	background-position:  right top;  
	background-attachment:  fixed;  
}
```
## Border
Tag-lara kənar sərhəd qoymaq istəyiriksə bunun üçün border istifadə olunur.
**border-width** - kənarların qalınlığını müəyyən edir. 
Width növləri - 2px, 5px, 10px və s.
**border-style** - kənarların stilini müəyyən edir. 
Style növləri -  solid, dotted, dashed,  double və s.
**border-color** - kənarların rəngini müəyyən edir. 
Color növləri -  black, #000 , rgb(64, 18, 133) ,  red və s.
```css
.first-header{  
	border-style:  solid;  
	border-width:  5px;  
}
.second-header{  
	border-style:  dotted;  
	border-width:  2px;
	border-color: green;  
}
```
Əsasən bütün detallar 1 sətirdə yazılır . . .
**Misal :**
```css
p{  
	border:  5px solid red;  
}
```
Burada . . . 
5 px - >  kənarların qalınlığı 5px ,
solid - > kənarların düz xətt olacağı,
red - > kənarların qırmızı olduğunu göstərir.


**Outline** xüsusiyyətləri də demək olarki border ilə eynidir. Border - dən kənarda sərhəd qoymaq üçündür.

## Margin , Padding
Tag - xaricindən və ya tag daxilindən məsafə ( boşluq ) qoymaq üçün margin və ya padding istifadə olunur.
* **Margin**- tag sahəsinin xaricdən məsafə qoymaq üçün.
* **Padding**- tag sahəsinin daxildən məsafə qoymaq üçün.


## Margin
**Margin - >**  4 əsas xüsusiyyətləri var. 
* **margin-top - >**  Yuxarıdan məsafə
* **margin-bottom- >** Aşağıdan məsafə
* **margin-left- >** Soldan məsafə
* **margin-right - >** Sağdan məsafə

**Misal :**
```css
h1{
	margin-left: 10px;
	margin-top: 33px;
}
.navbar{
	margin-bottom: 6px;
}
```
Margin üçün qısayollar da var . . . 

* **margin =  10px; - >** 4 tərəfdən 10 px xarici məsafə saxlayır.
* **margin = 10px 20px; - >**  İlk yazılan yuxarı və aşağıdan 10px xarici məsafə, İkinci yazılan isə sağdan və soldan 20px xarici məsafə deməkdir.
* **margin = 10px 33px 50px 25px; - >**  Saat istiqamətində yuxarıdan 10px, sağdan 33px, aşağıdan 50px, soldan 25px xarici məsafə deməkdir.

## Padding 
**Padding- >**  4 əsas xüsusiyyətləri var. 
* **padding-top - >**  Yuxarıdan daxili məsafə
* **padding-bottom- >** Aşağıdan daxili məsafə
* **padding-left- >** Soldan daxili məsafə
* **padding-right - >** Sağdan daxili məsafə

**Misal :**
```css
h1{
	padding-right: 5px;
	padding-bottom: 33px;
}
.navbar{
	padding-top: 28px;
}
```
Margin üçün qısayollar da var . . . 

* **padding=  20px; - >** 4 tərəfdən 20 px daxili məsafə saxlayır.
* **padding= 15px 8px; - >**  İlk yazılan yuxarı və aşağıdan 15px daxili məsafə, İkinci yazılan isə sağdan və soldan 8px daxili məsafə deməkdir.
* **padding= 0 10px 10px 30px; - >**  Saat istiqamətində yuxarıdan 0, sağdan 10px, aşağıdan 10px, soldan 30px daxili məsafə deməkdir.



