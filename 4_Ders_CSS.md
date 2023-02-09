# Form teqləri

form etiketlərinin məqsədi istifadəçidən bilgi almaq və s.
Demək olarki günlük həyatda tez-tez istifadə edirik. Twitter-də twit atarkən, facebook-da comment yazarkən. Hansısa saytdan qeydiyyatdan keçərkən vəya giriş edərkən və s.  
Form etiketləri **< form >** tag-ı içərisində yazılır və özünə məxsus keyword-ləri var

* **action**
* **method**

```html
<!DOCTYPE  html>
<html>
<head>
	<title>FormEtiketleri</title>
</head>
<body>
	<form action="" method="">
		<input>
	</form>
</body>
</html>
```
**< input >** - istifadəçinin məlumat daxil etməsi üçündür. Və onun özünəməxsus keyword-ləri var.
* **type** - > daxil edilən məlumatın tipini göstərir
* **placeholder** - > İnput üzərində kölgə kimi yazı göstərir.

**input type** - input tiplərinin növlərinə baxaq :

* **type='text'** - > yazdığımız yazı olduğu kimi görsənir.
* **type='password'** - > yazdığımız yazı ulduz(parol) kimi görsənir.
* **type='checkbox'** - > yazmaq olmur, yalnız seçmək olur. Çoxlu seçim olar.
* **type='radio'** - > yazmaq olmur, yalnız seçmək olur. Bir seçim olar.
* **type='file'** - > Komputerdə olan faylı yükləmək üçündür.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>FormEtiketleri</title>
</head>
<body>
	<form>
		<input type="text" placeholder="İstifadəçi adı">
		<input type="password" placeholder="parolu daxil edin">
		<input type="radio" name="gender"> Kişi
		<input type="radio" name="gender"> Qadın
		<input type="checkbox"> Parolu yadda saxla
		<input type="file"> Faylı daxil edin
	</form>
</body>
</html>
```
type-ı **radio** olan etiketdə name olduğunu görürük. Əgər bir seçim etməyini istəyiriksə name dəyərini eyni yazırıq.

### Label

label vasitəsi ilə input-da nə yazcağımızı qeyd edirik.
Bunun üçün label-da olan **for** ilə input-da olan **id** eyni olmalıdır.

```html
<!DOCTYPE  html>
<html>
<head>
	<title>FormEtiketleri</title>
</head>
<body>
	<form>
		<label  for="username">Istifadeci adi</label>
		<input  id="username"  type="text">  

		<br/>
		<br/>  

		<label  for="pass">Parol</label>
		<input  id="pass"  type="password">

		<br/>
		<br/>

		<label>Cins</label>
		<br/>
		<input  id="gender1"  type="radio"  name="gender">
		<label  for="gender1">Kişi</label>
		<br>
		<input  id="gender2"  type="radio"  name="gender">
		<label  for="gender2">Qadın</label>

		<br>
		<br>
		
		<input  id="checked"  type="checkbox">
		<label  for="checked">Şərtləri qəbul edirəm</label>

		<br>
		<br>

		<button  type="submit">Təsdiqlə</button>
	</form>
</body>
</html>
```

