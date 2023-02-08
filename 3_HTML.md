# Cədvəl və list teqləri
Standart bildiyimiz cədvəlləri Web səhifəmizdə də qura bilərik. 
Bunun üçün xüsusi tag-lar var.
* Cədvəl qurmaq üçün **< table >** etiketi
* Cədvəldəki sətirlər üçün **< tr >** etiketi
* Cədvəldəki sütünlar üçün **< td >** etiketi
* Çərçivə qoymaq üçün border="1" yaza  bilərik.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>Link Etiketleri</title>
</head>
<body>
	<table border="1">
		<tr>
			<td>Zahid</td>
			<td>Vahabzade</td>
			<td>21</td>
		</tr>
		<tr>
			<td>Rustem</td>
			<td>Ceferli</td>
			<td>36</td>
		</tr>
	</table>
</body>
</html>
```
Cədvəldə başlıq orta hissə və sonluq yaza bilərik.
* **< thead >** - cədvələ başlıq yazmaq üçün,
* **< tbody>** - > cədvəldə orta hissələri yazmaq üçün,
* **< tfoot>** -> cədvələ sonluq yazmaq üçündür.
* **< caption >** vasitəsi ilə cədvələ başlıq yazmaq olur.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>Link Etiketleri</title>
</head>
<body>
	<table border="1">
		<caption>Istifadeciler</caption>
		<thead>
			<tr>
				<th>Ad</th>
				<th>Soyad</th>
				<th>Yaş</th>
			</tr>
		</thead>
		
		<tbody>
			<tr>
				<td>Zahid</td>
				<td>Vahabzade</td>
				<td>21</td>
			</tr>
			<tr>
				<td>Rustem</td>
				<td>Ceferli</td>
				<td>36</td>
			</tr>
		</tbody>
		
	</table>
</body>
</html>
```

### List 
**list ( siyahı )** -  ən çox istifadə olunan taglardandır. 3 cür list növü var. 2 si istifadə olunur.
* **unordered** list - > Sırasız list
* **ordered** list - > Sıralı list

Unordered list - də hər sətrin qarşısında **qara nöqtə** olur.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>List etiketi</title>
</head>
<body>
	<ul>
		<li>Todo 1</li>
		<li>Todo 2</li>
		<li>Todo 3</li>
	</ul>
</body>
</html>
```
Ordered list - də hər sətrin qarşısında **sıra ilə nömrələnmiş** olur.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>List etiketi</title>
</head>
<body>
	<ul>
		<ol>Todo 1</ol>
		<ol>Todo 2</ol>
		<oi>Todo 3</ol>
	</ul>
</body>
</html>
```
