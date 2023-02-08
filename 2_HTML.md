# Link  və şəkil teqləri 

HTML-də bağlantıları necə əlavə etmək olar
Bildiyiniz kimi, internet çoxlu keçidlərdən ibarətdir.

Linklərə keçid etmək üçün **< a >** tag-ından istifadə olunur və linki **href** içərisində yazırıq.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>Link Etiketleri</title>
</head>
<body>
	<a href="http://www.google.com">Google</a>
</body>
</html>
```
**target** - > vasitəsi ilə linkin öz səhifəmizdə yoxsa əlavə səhifədə açılmasını seçirik.Yuxarıdakı kodda target yazmasaq belə **target default olaraq _self - dir ( target = " _self " )**. Yəni link öz səhifəmizdə açılır.
Əgər biz linkin əlavə səhifədə açılmasını istəyiriksə **target = "_blank"** yazırıq.
```html
	<a href="https://www.youtube.com" target="_blank">Youtube</a>
```

Web səhifəmizə şəkil qoymaq üçün **< img >** tag-ından istifadə olunur. Və şəklin adını **src** daxilində yazırıq. Bunun üçün komputerdə olan bir şəkli seçib onu VS Code - da folder-imizə (index.html faylı olan hissəyə) əlavə edirik.
**Misal :** şəklimizin adı **dog.jpg** dir.
```html
<!DOCTYPE  html>
<html>
<head>
	<title>Link Etiketleri</title>
</head>
<body>
	<img src="dog.jpg">
</body>
</html>
```
Kursoru(mausu) şəklin üzərində gətirəndə yazı çıxmağını istəyiriksə **title** istifadə edə bilərik.
```html
	<img src="cat.jpg" title="Mestan">
```
Əgər birdən şəklin adını düzgün yazmasaq və ya yanlış şəkil yükləsək və ya internet zəif olduğundan şəkil açılmasa , şəkildə nə olduğunu yazı formasında bildirmək üçün **alt** istifadə edə bilərik.
```html
	<img src="cat.jpg" alt="Burada pişik şəkli var">
```



 
