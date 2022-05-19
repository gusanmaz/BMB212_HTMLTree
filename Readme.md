# Proje 5 (Basit HTML Agaci)

* Bu projede `HTMLTree` sinifinda bir HTML dokumanindaki veriler basitlestirilmis olarak saklanabilmektedir. 
* Bu proje icin HTML dokumanlarini sadece HTML etiketlerinden (taglerinden) olusan dokumanlar olarak varsayaniz.
* Sizden istenen HTMLTree sinifindaki GETHTML() metodunun islevini yerine getirebilmesi icin `HTMLTree.java` dosyasinda gerekli duzenlemeleri yapmanizdir.
* `GETHTML()` metodunun ustundeki yorum satirlarini okuyarak bu metodun nasil bir islev gerceklestirmesi gerektigini ogrenebilirsiniz.

## Uyarilar

* Projenizdeki HTMLNode.java dosyasi icinde herhangi bir degisiklik yapmayiniz.
* `HTMLTree.java` dosyasindaki constructor(yapici) kodlar uzerinde herhangi bir degisiklik yapmayiniz.
* `HTMLTree.java` dosyasindaki sinif degiskeni olan root degiskeninin tanimlandigi satirda herhangi bir oynama yapmayiniz.
* Yeni bir java uzantili kaynak dosyasi olusturmayiniz.
* Github'a yukleyeceginiz kodun derlendiginden emin olunuz. Derlenmeyen kodlar 0 puan alacaktir!

## Kodun derlenmesi

```javac HTMLNode.java HTMLTree.java Main.java```

## Kodun calistirilmasi

```java Main```

## Program ciktisi

Size verilen kod Main.java uzerinde degisiklik yapilmadiginda ve `GETHTML()` metodu dogru kodlandiginda asagidaki ciktiyi uretmelidir. Verilen ciktida agactaki her seviyenin etiketlerinin ilgili etiketin bir ustundeki seviyeden 3 karakter sagda basladigina dikkat ediniz. 

```html
Printing HTML output for document #1:
<html>
   <body>
      <div>
         <article>
         </article>
      </div>
      <p>
      </p>
      <h1>
      </h1>
   </body>
</html>
Printing HTML output for document #2:
<html>
   <head>
      <meta>
      </meta>
      <title>
      </title>
   </head>
   <body>
      <h1>
      </h1>
      <div>
         <div>
            <p>
               <a>
               </a>
            </p>
         </div>
      </div>
      <article>
      </article>
      <div>
         <ol>
            <li>
            </li>
            <li>
            </li>
            <li>
            </li>
            <li>
            </li>
         </ol>
      </div>
   </body>
</html>
Printing HTML output for document #3:
<html>
</html>
Printing HTML output for document #4:
```

###### `Main.java` altindaki GetHTML4Document1() fonksiyonunda uretilen HTML agaci

![Tree1](tree1.png)

###### `Main.java` altindaki GetHTML4Document2() fonksiyonunda uretilen HTML agaci

![Tree2](tree2.png)

###### `Main.java` altindaki GetHTML4Document3() fonksiyonunda uretilen HTML agaci

![Tree3](tree3.png)

###### `Main.java` altindaki GetHTML4Document4() fonksiyonunda uretilen HTML agaci

![Tree1](tree4.png)

