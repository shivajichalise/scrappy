**Simple web-scraping tool**

```
scrappy  [url] [any combination of <tag> "#<id>" ".<classname>"]
```

**CMD:**

```
./scrappy http://dikshyantadhikari.com.np/  '<a>' '.btn'
```

**OUTPUT:**

```bash
tag:a
class:btn
<a href="/fonts/image_gallery.php" class="btn" target="_blank" >Gallery</a>
<a href="https://ouo.io/Tjvckv" class="btn" target="_blank" >Learn Photography</a>
```

```
./scrappy http://dikshyantadhikari.com.np/  '<a>'
```

**OUTPUT:**

```bash
tag:a
<a href="/fonts/image_gallery.php" class="btn" target="_blank" >Gallery</a>
<a href="https://ouo.io/Tjvckv" class="btn" target="_blank" >Learn Photography</a>
<a href="mailto:adhikaridikshyant@gmail.com"><strong>adhikaridikshyant@gmail.com</strong></a>
<a href="tel:+9779806597666"><strong>(+977)9806597666</strong></a>
<a href="https://www.facebook.com/d_shyant/" target="blank" class="fa fa-facebook"></a>
<a href="https://www.instagram.com/d_shyant/" target="blank" class="fa fa-instagram"></a>
<a href="https://www.snapchat.com/add/d_shyant" target="blank" class="fa fa-snapchat"></a>
<a title="Hosted on free web hosting 000webhost.com. Host your own website for FREE." target="_blank" href="https://www.000webhost.com/?utm_source=000webhostapp&utm_campaign=000_logo&utm_medium=website&utm_content=footer_img"><img src="https://cdn.000webhost.com/000webhost/logo/footer-powered-by-000webhost-white2.png" alt="www.000webhost.com"></a>
```

_Currently only works for one liner html tag like 'a' and class without special character -_
