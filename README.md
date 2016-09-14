# Multi-Language
Multi-language 1.0 Datalife Engine  
მოდული Multi-language 1,0 დაგეხმარებათ საიტზე იქონიოთ რამოდენიმე ენა .

ძრავი: Datalife Engine
ვერსია: 10.X 11.X
შიგთავსი: Javascript , PHP

დაყენება: 
1: შექმენით თქვენთვის სასურველი ენის დიზაინი
2: გახსენით ფაილი .htaccess  RewriteEngine On ქვემოთ  მოათავსეთ  
-RewriteRule ^eng/$index.php?/index.php?action_skin_change=yes&skin_name=eng[L] <br>
-RewriteRule ^rus/$index.php?/index.php?action_skin_change=yes&skin_name=rus[L] <br>
-RewriteRule ^geo/$index.php?/index.php?action_skin_change=yes&skin_name=geo[L] 

rus - eng - geo - თქვენი დიზაინის სახელი 

გადადით სამართავ პანელში შექმენით დამატებითი ველები 
- titile(ძირითადი) : სახელწოდება ქართულად     (ამიშექმნათ დამატებითი ველი ქართული სათაურისთვის)
- title-eng : სახელწოდება ინგლისურად
- title-rus : სახელწოდება რუსულად
- shortstory და fullstory (ძირითადი)  : მოკლეაღწერა   და სრული აღწერა ქართულად   (არ შექმნათ ეს დამატებითი ველები გამოიყებეთ ძირითადი ველები)
- shortstory-eng : მოკელე აღწერა ინგლისურად
- shortstory-rus : მოკელე აღწერა რუსულად
- fullstory-eng : სრული-აღწერა ინგლისურად
- fullstory-rus : სრული-აღწერა რუსულად

სასურველ ადგილას მოათავსეთ:
- <a href="/eng/" > English </a>
- <a href="/rus/" > Russian </a>
- <a href="/geo/" > Georgian </a>
