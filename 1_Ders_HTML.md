# Web Devolopment HTML CSS JS :)


## HTML kodu necə yazırlar?
Öncəliklə file haqda bəzi şeyləri bimək lazımdır.
Yəqin ki   **.txt** uzantısı olan sadə mətn faylları ilə rastlaşmısınız.
**proqram.txt** - file iki yerə bölünür. **adı və uzantısı**
Burada nöqtədən əvvəl gördüyünüz **proqram** - **adı** , nöqtədən sonra olan **.txt** - **uzantısıdır**.

**HTML** - file qurmaq üçün də **.html** - uzantısından istifadə edəcik.
Misal: **index.html** - Adətən belə adlandırılır :)
## Visual Studio Code
**Visual Studio Code -** bir proqramlaşdırma mühitidir **(IDE - integrated development environment )**. Qısa sözlə desək proqaram qurmaq üçün bir proqramdır :)


## İlk Web saytımız!
  
Addım-addım təlimatımız sizə HTML-nin əsaslarını və ilk veb saytınızı necə qurmağı öyrədəcik. 

* İlk öncə Visual Studio Code - u komputerə yükləyirik
* Yazacağımız kodlar üçün desktop(və ya başqa bir yerdə) **Folder** qururuq
* Proqramı açdıqdan sonra **File** bölməsindən **Open Folder** - i seçib həmin Folder-i seçirik.
* Artıq bütün yazacağımız kodlar o Folder-in içərisində olacaq

### index.html file qururuq.
Açılan səhifədə **Doctype** strükturu qurmaq üçün **!** sonra **Enter** düymələrini seçirik. 

```html
<!DOCTYPE  html>
<html  lang="en">
<head>
	<title>Document</title>
</head>
<body>

</body>
</html>
```
Fikir verdinizsə bütün tag-lar açılıb və bağlanıb
**< html >** — Bu teq işarə edir ki, biz bundan sonra HTML kodunda yazacağıq.
**< head >** — Bu, səhifə üçün bütün metadataların getdiyi yerdir, **meta**, **link**,**title** bu hissədə yazılır. Head içərisində olan **title** - Web saytın adıdır.
**< body >** — Bu, səhifənin məzmununun getdiyi yerdir. Əsasən kodları burada yazacıq.

## Tag Sintaksisi
**HTML -** açılışı (**H**yper**T**ext **M**arkup **L**anguage)
Digər proqramlaşdırma dillərindən fərqli olaraq HTML **- İşarələmə dili** adlanır.
Hər hansı bir dil kimi, HTML -in də özünəməxsus kod sırası var
. . .  **Gəlin Başlayaq**
```html
<p>Hal-hazırda oxuduğunuz mətn Paraqraf adlanır</p>
```

**< p >** HTML tag - dır.  **Tag** bir şeyin harada başladığını və bitdiyini göstərir.
Onların hər biri müəyyən məna daşıyır. Bu halda **< p >** paraqrafı ifadə edir. 

Tag - lar adətən cüt-cüt olurlar
**< p >**   - Paraqrafın başlanğıcını müəyyən edir
**< /p >**  - isə Paraqrafın sonunu müəyyən edir

Açılış və bağlanma tag-ı arasındakı yeganə fərq, etiketin adından əvvəl olan **slash** **/** işarəsidir.

Gəlin bəzi taglar-ilə tanış olaq!
HTML-də **başlıqlar**  aşağıdakı elementlərlə yazılır:
* **< h1 > < /h1 >**
* **< h2 > < /h2 >**
* **< h3 > < /h3 >**
* **< h4 > < /h4 >**
* **< h5 > < /h5 >**  
* **< h6 > < /h6 >**  
Başlıqlar **< h1 > - < h6 >** aralığında dəyişir. Böyük və qalın fontda olur. **h1** ən böyüyü, **h6** isə ən kiçik başlıqdır.

```html
<!DOCTYPE  html>
<html  lang="en">
<head>
	<title>Document</title>
</head>
<body>

	<h1> Başlıq </h1>
	<h3> Başlıq </h3>
	<h6> Başlıq </h6>

	<p>Burada paraqraf yazırıq :)<p>
	
</body>
</html>
```
___
### Başlıq
##### Başlıq
###### Başlıq 
Burada paraqraf yazırıq :)
___

Gördüyünüz kimi kodları body içərsində yazırıq.

### Gəlin digər tag - lar ilə tanış olaq
* **< b >, < strong >**  - Bold - Vacib hissələri vurğulayır. Yəni yazını qalın edər
* **< i > , < em >**  - Italic - Mətni əl yazısı kimi göstərir
* **< u >, < ins >**  - UnderLine- Yazının altından xətt çəkir
* **< mark >**  - Marked Text- Yazını digərlərindən fərqli göstərər
* **< small >**  - Small Text- Yazını kiçik göstərər
* **< sub >**  -Subscript Text- yazının indeksi formasında(altında) yazar
* **< sup >**  - Superscript Text- yazının qüvvəti formasında(üstündə) yazar


```html
<!DOCTYPE  html>
<html  lang="en">
<head>
	<title>Document</title>
</head>
<body>

	<p>Hello <b>Welcome</b> <em>my</em> new website. This site will be my
	<u>new</u> home on the web.</p>  
	
</body>
</html>
```

