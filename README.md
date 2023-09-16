#### این مخزن صرفا جهت تست‌های سایت https://vimpersian.github.io ایجاد شده است. مخزن اصلی در آدرس https://github.com/vimpersian/vimpersian.github.io واقع شده است.
# START SITE HERE

<br>
<div align="center">
<a href="http://www.coffeete.ir/wolandark">
       <img src="http://www.coffeete.ir/images/buttons/lemonchiffon.png" style="width:260px;" />
</a></div>

<div align="center"><h1> Hello Vim World!</h1></div>

<div dir="rtl">
ویم‌، یک ادیتور مودال است. به این معنی که در ویم، ما مود‌های مختلف جهت انجام کارهای مختلف داریم. مد عادی ویم، یا همان نرمال مود، حالتی است که در آن ما درون فایل حرکت می‌کنیم، متن را جستجو می‌کنیم یا ویرایش‌های جزئی انجام می‌دهیم. 
<br><br>

برای وارد کردن متن از مود وردی یا اینسرت مود استفاده می‌کنیم و برای انتخاب و ویرایش‌های بزرگ‌تر از مود ویژوآل، و برای اجرای دستورات خط فرمان ویم یا خط فرمان پوسته، از مود دستوری یا کامند مود استفاده می‌کنیم.

دانستن اینکه ویم فراتر از یک ادیتور است و درواقع یک زبان برای ویرایش متن و کد است در ابتدای کار حیاتی است. 
در ویم هر کلید کیبورد در مود نرمال به یک کنش یا اکشن اختصاص دارد. مدل ویرایش در ویم این صورت است که ما مدام در بین مودهای مختلف در حال حرکت هستیم و این سرعتی باور نکردنی در پیمایش متن و ویرایش آن به ما می‌دهد.
<br><br>

ویم دارای گرامر بخصوصی است که آن‌را می‌توان به COM خلاصه کرد.
</div>

- count (شمارش)
- operation (عملیات)
- motion (جهت) 

<div dir="rtl">
تمام دستورات ویم می‌توانند با یک عدد پیش از آن‌ها، به تعداد آن عدد انجام شوند. همچنین تمام دستورات ویم نیز می‌توانند در جهت خاصی مانند ،چپ، راست، تا آخر خط، تا آخر کلمه، تا آخر پاراگراف ، تا اولین خط خالی و ... انجام شوند.
<br><br>
در ویم یا وی‌آی، ما می‌توانیم با تنها یک کلید ، در متن حرکت کنیم. این حرکت‌ها به کلمات، گروهی از حروف ، اعداد، تک حرف ، توکن‌ها یا خط ‌ها باشند.
در منطق ویم، یک کلمه می‌تواند گروهی از حروف ، اعداد و  سمبل‌ها باشد. از طرفی دیگر یک توکن، هر آنچه که با فضای سفید، (اسپیس)  جدا شده باشد تلقی می‌شود.
<br><br>
<strong style="color:red">
این راهنما باید بعد از انجام کامل vimtutor خوانده شود.
</strong>
<br>
<small> در ترمینال عبارت <code>vimtutor</code> را وارد کنید و درس‌ها را انجام دهید.
اگر با زبان انگلیسی آن راحت نیستید، این پلی‌لیست را در یوتوب ببینید.
</small>
</div>
<br>

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/1MQuSZzjvMA?si=hfl-ZmyHKMjRm7FE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<br>
<div dir="rtl">در این پلی‌لیست تمامی درس‌های <code>vimtutor</code>
به‌علاوه‌ی درس‌هایی در باره نصب پلاگین و شخصی سازی ویم، قرار
گرفته است.<br>  اگرچه بیشتر اطلاعات داخل <code>vimtutor</code> در این سایت پوشش داده
می‌شود، فرض بر آن است که مخاطب <code>vimtutor</code> را گذرانده است. مرحله اول یادگیری
ویم، همیشه و همه‌جا <code>vimtutor</code> است.</div>
<br>
<hr>

<div dir="rtl" style="margin-right: 5px;">
<ol style="list-style-type: persian;">
<li><a href="#moving">حرکت در فایل</a></li>
<li><a href="#moving2">حرکت با حروف، کلمه یا توکن</a></li>
<li><a href="#moving3">حرکت با خطوط</a></li>
<li><a href="#moving4">حرکت  به وسیله صفحه</a></li>
<li><a href="#ins">وارد کردن متن</a></li>
<li><a href="#edt"> ویرایش متن</a></li>
<li><a href="#xyp">کات کپی و جایگذاری</a></li>
<li><a href="#vis">حالت ویژوال</a></li>
<li><a href="#srch"> جستجو در متن</a></li>
<li><a href="#wq"> ذخیره کردن و خروج از فایل</a></li>
<li><a href="#multi">  کار کردن با بیش از یک فایل</a></li>
<li><a href="#mark"> مارک‌ها و پرش‌ها</a></li>
<li><a href="#macro">ماکرو</a></li>
<li><a href="#colo"> فعال کردن تم‌ها در ویم</a></li>
<li><a href="#s">دستورات جایگزینی متن </a></li>
<li><a href="#sflags">فلگ های مرسوم برای دستورات جایگزینی</a></li>
<li><a href="#larg">آرگومان های خط فرمان</a></li>
</ol>
</div>

<hr>
<div dir="rtl"><h1 id="moving">حرکت در فایل</h1></div>
<div dir="rtl"><h2 id="moving2">حرکت با حروف، کلمه یا توکن</h2></div>

<div dir="rtl">کلید‌های اساسی حرکت در ویم این‌ها هستند:</div>

-   **`h`** -- حرکت نشانگر به چپ
-   **`j`** -- حرکت نشانگر به پایین
-   **`k`** -- حرکت نشانگر به بالا
-   **`l`** -- حرکت نشانگر به راست
<br>

<div dir="rtl">
این کلید‌ها را می‌توان با یک شمارش همراه کرد تا به توان همان عدد انجام شوند
</div>

-  **`5j`**  پنج خط به پایین می‌رود
<br>

-   **`b`** -- حرکت به اول یک کلمه
-   **`B`** -- حرکت به اول یک توکن
-   **`w`** -- حرکت به اول کلمه‌ی بعد
-   **`W`** -- حرکت به اول توکن بعد
-   **`e`** -- حرکت به آخر کلمه
-   **`E`** -- حرکت به آخر توکن

<br>

<div dir="rtl">

برای  پرش به  پرانتز بسته،  گیومه بسته  و غیره از  **`%`** استفاده کنید
</div>

**`:h matchpairs`**
<br>

<div dir="rtl"><h1 id="moving3">حرکت  با خطوط</h1></div>

-   **`0 \ zero`**  -- حرکت به اول خط فعلی
-   **`$ \ dollar sign`** -- حرکت به آخر خط فعلی
-   **`^ \ caret sign`** -- حرکت به اولین  کاراکتر موجود در خط
-   **`#G`** / **`#gg`** / **`:#`** حرکت به شماره خط مشخص، (شماره خط جایگزین هشتگ شود)

<br>
<div dir="rtl">برای استفاده از این قابلیت، شماره خطوط را فعال کنید.</div>

```
:set number
```
<br>

<div dir="rtl"><h1 id="moving4">  حرکت  به وسیله صفحه</h1></div>
دستورهای زیر برای اسکرول کردن سریع در فایل کاربرد دارند.

-   **`Ctrl + b`** -- یک صفحه کامل به عقب رفتن
-   **`Ctrl + f`** -- یک صفحه کامل به جلو رفتن
-   **`Ctrl + d`** -- نصف صفحه جلو‌ رفتن
-   **`Ctrl + u`** -- نصف صفحه عقب رفتن
-   **`Ctrl + e`** -- صفحه را بدون حرکت دادن نشانگر یک خط پایین‌تر بردن
-   **`Ctrl + y`** --  صفحه را بدون حرکت دادن نشانگر یک خط بالاتر بردن
-   **`Ctrl + o`** -- به عقب رفتن در تاریخچه‌ی پرش ها. برای حرکت بین فایل‌ها و بافرها هم کاربرد دار
-   **`Ctrl + i`** -- برعکس دستور بالا

<br>

-   **`H`** -- حرکت به بالای صفحه
-   **`M`** -- حرکت به وسط صفحه
-   **`L`** -- حرکت به پایین صفحه

<div dir="rtl"><h1 id="ins">  وارد کردن متن</h1></div>

-   **`i`** -- وارد شدن به حالت ورود متن
-   **`I`** -- وارد کردن متن در اول خط
-   **`a`** -- سوییچ کردن به حالت ورود متن بعد از نشانگر
-   **`A`** -- وارد کردن متن در آخر خط
-   **`o`** -- باز کردن یک خط جدید زیر خط فعلی
-   **`O`** -- باز کردن خط جدید بالای خط فعلی
-   **`ea`** -- وارد کردن متن در آخر کلمه
-   **`Esc`** -- خارج شدن از حالت ورود متن و برگشنن به حالت نرمال
<br>

<div dir="rtl"><h1 id="edt">  ویرایش متن</h1></div>

-   **`r`** -- جایگزین کردن یک کاراکتر و بازگشت به حالت نرمال
-   **`cc`** -- جایگزین کردن کل خط (خط را پاک می‌کند و به خالت ورود متن می‌رود)
-   **`C`** / **`c$`** -- جایگزین کردن متن از مکان نشانگر تا آخر خط
-   **`cw`** -- جایگزین کردن تا آخر کلمه
-   **`s`** -- جایگزین کردن یک کاراکتر و رفتن به حالت ورود متن
-   **`J`** -- ادغام خط فعلی و خط زیر آن با یک اسپیس فاصله
-   **`gJ`** -- ادغام خط فعلی با خط زیر آن بدون اسپیس
-   **`u`** -- undo 
-   **`Ctrl`** + **`r`** -- redo
-   **`.`** -- تکرار آخرین دستور
<br>


<div dir="rtl"><h1 id="xyp">   کات کپی و جایگذاری</h1></div>

-   **`yy`** -- کپی کردن کامل خط فعلی
-   **`#yy`** -- کپی کردن تعداد مشخصی از خطوط
-   **`dd`** -- کات کردن کل خط
-   **`#dd`** -- کات کردن تعداد مشخصی از خطوط
-   **`p`** -- جایگذاری بعد از نشانگر
-   **`P`** -- جایگذاری قبل از نشانگر


<br>

<div dir="rtl"><h1 id="vis">  حالت ویژوال</h1>

به غیر از حالت ورود متن (insert mode) و حالت نرمال (normal mode) و حالت دستوری (command mode)، حالت دیگری نیز به نام حالت ویژوال (visual mode) وجود دارد. از این مود برای انتخاب و ویرایش و انجام عملیات‌های مختلف بر روی بخش‌های بزرگ‌تری از متن استفاده می‌شود

ویژوال مود سه حالت کلی دارد.

- حالت کاراکتری
- حالت خطی
- حالت بلاک

</div>

```
character mode, line mode, and block mode
```
<br>

-   **`v`** -- انتخاب متن در حالت کاراکتری
-   **`V`** -- انتخاب متن در حالت خطی
-   **`Ctrl`**+**`v`** -- انتخاب متن در حالت بلاک

پس از فعال‌سازی یکی از حالت‌ها، با استفاده از کلید‌های جهت متن را انتخاب کنید.
<br>

-   **`o`** -- حرکت از ابتدای متن انتخاب شده به آخر آن
-   **`aw`** -- انتخاب یک کلمه
-   **`ab`** -- انتخاب یک بلاک کد که در بین پرانتز است
-   **`aB`** -- انتخاب یک بلاک کد که در بین آکولاد است {}
-   **`at`** -- انتخاب یک بلاک کد که در بین تگ است \<\>
-   **`ib`** -- انتخاب قسمت داخلی یک بلاک کد که بین پرانتز است
-   **`iB`** - انتخاب قسمت داخلی یک بلاک کد که بین آکولاد است {}
-   **`it`** -- انتخاب قسمت داخلی یک بلاک کد که بین یک تگ است \<\>

<div dir="rtl">پس از انتخاب متن مورد نظر می‌توانید عملیات‌های مختلف را به وسیله‌ی کلید‌های زیر انجام دهید.</div>

-   **`y`** -- کپی
-   **`d`** -- کات
-   **`p`** -- جایگذازی
<br>
<div dir="rtl"><h1 id="srch"> جستجو در متن</h1></div>


-   **`* \ asterisk`** -- رفتن به وقوع بعدی از کلمه‌ی زیر نشانگر
-   **`# \ pound sign`** -- رفتن به وقوع قبلی از کلمه‌ی زیر نشانگر
-   **`/pattern`** --جستجوی یک الگوی مشخص در فایل 
-   **`?pattern`** -- جستجوی یک الگوی مشخص از مکان فعلی تا اول متن
-   **`n`** -- پرش به وقوع بعدی الگوی یافت شده
-   **`N`** -- پرش به وقوع قبلی الگوی یافت شده

<br>

<div dir="rtl"><h1 id="wq"> ذخیره کردن و خروج از فایل</h1></div>

-   **`:w`** -- ذخیره کردن
-   **`:wq`** / **`:x`** / **`ZZ`** -- ذخیر کردن و خروج از ویم
-   **`:q`** -- خروج
-   **`:q!`**/ **`ZQ`** -- خروج بدون ذخیره کردن تغییرات
-   **`:w new_file_name `**-- ذخیره کردن تحت نامی جدید و ادامه دادن به ویرایش فایل اصلی
-   **`:sav`** -- ذخیره کردن تحت نامی جدید و ادامه‌ دادن به ویرایش فایل کپی شده
-   **`:w !sudo tee %`** -- ذخیره کردن فایل به‌وسیله‌ی سودو و تی، مناسب وقتی که فایلی را بدون دسترسی سودو باز کرده‌ایم [tee](https://wiki.archlinux.org/title/Tee)
<br>

<div dir="rtl"><h1 id="multi">  کار کردن با بیش از یک فایل</h1></div>

-   **`:e file_name `** -- باز کردن فایل در یک بافر جدید
-   **`:bn `** -- رقتن به بافر بعدی
-   **`:bp`** -- بازگشت به بافر قبلی
-   **`:bd `** -- بستن بافر
-   **`:b# `** -- رفتن به بافر با عدد شناسایی مشخص
-   **`:b file_name`** -- رفتن به بافر با نام مشخص
-   **`:ls`** -- لیست کردن تمام بافر باز ( شناسه‌ی عددی هر بافر کنار نام آن ظاهر خواهد شد)

<br>

-   **`:sp file_name `** -- باز کردن یک فایل در یک اسپلیت افقی
-   **`:vs file_name `** --باز کردن یک فایل در یک اسپلیت عمودی
-   **`:vert ba `** -- باز کردن همه‌ی بافر های فعلی در اسپلیت‌های عمودی
-   **`:tab ba `** -- ویرایش تمام بافر‌ها به‌وسیله تب‌
-   **`gt`** -- رفتن به تب بعدی
-   **`gT`** -- رفتن به تب قبلی



-   **`Ctrl+ws`** -- اسپلیت کردن صفحه به صورت افقی
-   **`Ctrl+wv`** -- اسپلیت کردن صفحه به صورت عمودی
-   **`Ctrl+ww`** -- سوییچ کردن بین اسپلیت ها (مشابه alt + tab)
-   **`Ctrl+wq`** -- بستن اسپلیت ها
-   **`Ctrl+wx`** -- جابجا کردن اسپلیت ‌ها با یگدیگر
-   **`Ctrl+=`** -- برابر کردن طول و عرض تمام اسپلیت‌ها

<br>

<div dir="rtl"><h1 id="mark">  مارک‌ها و پرش‌ها</h1></div>

-   **`m[a-z]`** -- مارک کردن موقعیت فعلی به‌وسیله‌ی حروف الفبا 
-   **`M[a-z]`** -- مارک کردن خط فعلی به‌وسیله‌ی خطوط الفبا 
-   **`` `a ``** - پرش به موقعیتی که با حرف آ مارک شده **`a`**
-   **`` `. ``** -- پرش به آخرین تغییر در فایل 
-   **`` `0 ``** -- پرش به آخرین موقعیت فایل قبل از بسته شدن ویم
-   **``` `` ```** -- پرش به آخرین پرش
-   **`:marks`** -- لیست کردن همه‌ی مارک ها
-   **`:jumps`** -- لیست کردن همه‌ی پرش ‌ها
-   **`:changes`** لیست کردن همه‌ی‌ تغییرات
-   **`Ctrl+o`** -- رفتن به پرش قبلی
-   **`Ctrl+i`** -- رفتن به پرش بعدی
-   **`g;`** -- رفتن به تغییر قبلی در لیست تغییرات
-   **`g,`** -- رفتن به نغییر بعدی در لیست تغییرات

<div dir="rtl"><h1 id="macro">  ماکرو</h1></div>
<div dir="rtl">برای دستور ها یا ویرایش های تکرار شونده در ویم میتوان از ماکروها استفاده کرد.
برای ضبط یک ماکرو ابتدا کلید q و سپس نام رجیستری که می‌خواهیم ماکرو در آن ضبط شود را وارد می‌کنیم، بدین ترتیب می‌توانیم چندین ماکرو بصورت همزمان داشته باشیم. در این مثال از رجیستر a استفاده شده است.
</div>

-   **`qa `** -- ضبط کردن یک ماکرو **`a`**
-   **`q `** -- توقف ضبط یک ماکرو 
-   **`@a `** -- اجرا کردن ماکرو **`a`**
-   **`@@ `** -- اجرای دوباره‌ی ماکرو 

<div dir="rtl">برای مثال اگر محتوای زیر را داشته باشیم:</div>

```
aaa
bbb
ccc
ddd
```
<div dir="rtl">و بخواهیم در آخر هر خط یک کاراکتر وارد کنیم، برای مثال  حرف x، می توانیم ماکرو زیر را ضبط کنیم.</div>

```
Ax<ESC>j

با در نظر گرفتن کلید ضبط و پایان ضبط ماکرو

qAx<ESC>jq
```
<div dir="rtl">در اینجا با استفاده از اپراتور A، به آخر خط رفته و وارد مود ورود متن یا همان اینسرت مود می شویم. حرف x را تایپ کرده و با زدن کلید اسکیپ به مود نرمال بر می گردیم و در آخر با زدن کلید j به خط پایین می رویم تا ماکرو بتواند ادامه پیدا کند.
همان‌طور که پیش‌تر گفتیم، همه‌چیز در ویم شمارش پذیر یا توان پذیر هستند. بنابراین برای اجرای یک ماکرو به توان عدد خاصی، آن عدد را قبل از فراخوانی ماکرو وارد می‌کنیم.
</div>
<br>

```
10@a 
ماکروی ضبط شده در رجیستر را به تعداد ده بار اجرا می‌کند
```


<div dir="rtl"><h1 id="colo"> فعال کردن تم‌ها در ویم</h1></div>

-   **`:colorscheme [colorscheme_name] `** -- تغییر تم رنگی
-   **`:colorscheme [space]+Ctrl+d`** -- لیست کردن تمام تم های رنگی موجود

<div dir="rtl"><h5>چند تم پیش‌فرض زیبا:</h5></div>

- retrobox
- lunaperche
- elflord
- slate

<div dir="rtl">با استفاده از دستور زیر نیز می‌توان رنگ زمینه پیش‌فرض ویم را به روشن یا تاریک تغییر داد:</div>
<br>

```
:set background=dark
:set background=light
```
<div dir="rtl">برای استفاده بهتر  از رنگ ها و همچنین فعال سازی سینتکس، از دستور زیر استفاده می کنیم:</div>
<br>

```
:syntax on
```
<div dir="rtl">بعدها شیوه ذخیره کردن این تنظیمات در ویم را خواهیم آموخت.</div>

<div dir="rtl"><h1 id="s">دستورات جایگزینی متن </h1>
یکی از قابلیت‌های قدرتمند ویم، دارا بودن یک نوع فرمان SED داخلی است. این فرمان که در ویم معمولاً substitute خوانده می‌شود، ابزار بسیار پیشرفته‌ای برای یافتن و ویرایش متن به وسیله‌ی الگو‌های رجکس است.
با استفاده از این دستور، کاربر ویم می‌تواند ویرایش‌های عظیم و پیچیده‌ای را روی فایل‌ها اعمال کند. عملیات‌های طولانی و طاقت فرسای اصلاح متنی طولانی با استفاده صحیح از این دستور به آسانی صحبت کردن با بهترین دوستتان می‌شوند.

برای مثال, یک فایل html با محتوای زیر داریم.
</div>

<div align="center">
<h1> Quote of the day</h1>
<h2> Shopenhauer</h2>

"The majority of men... are not capable of thinking, but only of believing, and... are not accessible to reason, but only to authority." <br>

(Arthur Shopenhauer)
</div>

<div dir="rtl">
فرض می‌کنیم که این بخشی از یک مقاله دانشگاهی یا پستی برای یک وبلاگ است. همچنین فرض می‌کنیم که ما نام آرتور شوپنهاور را از اول این فایل اشتباه تایپ کرده‌ایم. به‌جای Sch برای صدای ش در آلمانی از Sh در انگلیسی استفاده کرده‌ایم. حالا ساعت‌ها کار ما بخاطر این اشتباه غیرقابل ارائه است. 

برای حل این مشکل از یک دستور جایگزینی ساده استفاده می‌کنیم.
</div>

```
:%s/Shopenhauer/Schopenhauer/g
```

<div dir="rtl">اجازه بدهید دستور را خرد کنیم.</div>
<br>

- % همیشه اشاره به فایل فعلی در ویم دارد، اینجا یعنی در این فایل بگرد
- s شروع دستور جستجو و جایگزینی همیشه با این حرف است. به معنی substitute 
- /الگوی هدف/
- /الگوی مقصد/
- g انجام عملیات برای تمامی مچ‌ها

<div dir="rtl"><h5>نکته </h5></div>
<div dir="rtl"><div style="color:yellow;"><strong>در ویم نقطه . اشاره به خط زیر نشانگر دارد</strong></div></div>
<br>

<div dir="rtl">سینتکس ساده ی دستورات جایگزینی به شکل زیر است:</div>

```
:s/search/replace/flags
```

<div dir="rtl"><h2 id="sflags">فلگ های مرسوم برای دستورات جایگزینی</h2></div>

- *`c`* تایید کردن هر جایگزینی بصورت دستی 
- *`e`* ساکت کردن ارورها در صورتی که الگو پیدا نشود
- *`i`*  نادیده گیری حروف بزرگ و کوچک ignorecase
- *`I`*  حساسیت به حروف بزرگ و کوچک 
- *`g`* انجام جایگزینی در تمام مچ‌ها، در غیر این صورت جایگزینی پس از اولین مچ متوقف می‌شود
- *`n`* نمایش تعداد مچ‌ها و عدم جایگزینی

<div dir="rtl"><h1 id="larg">آرگومان های خط فرمان</h1></div>

<div dir="rtl">آرگومان های خط فرمان ویم، آپشن هایی هستند که برای تغییر عمل کرد ویم در هنگام باز کردن آن از ترمینال، می توانید مقابل نام دستور ویم قرار دهید. در جدول زیر تعداد زیادی از این آرگومان ها برای شما با توضیحات فارسی قرار داده شده است.</div>
<br>
<div dir="rtl">پر کاربردترین این آرگومان  ها از نظر نگارنده در جدول اول و باقی آن ها در جدول دوم آمده اند.</div>
<hr>

<div dir="rtl"><h4>جدول اول</h4></div>

| Option           | Description                                                                                                       |
|------------------|-------------------------------------------------------------------------------------------------------------------|
| `-o`           | باز کردن تعدادی فایل در اسپلیت های افقی
| `-O`           | باز کردن تعدادی فایل در اسپلیت های افقی عمودی|
| `-p`           | باز کردن تعدادی فایل در تب های مجزا درون ویم
| `+/{pat}`         | تعیین جایگاه نشانگر براساس اولین وقوع رجکس                                      |
| `-u {vimrc}`      | خواندن فایل پیکره بندی غیر از فایل پیش فرض 
| `--clean`         |  باز کردن ویم بدون تنظیمات شخصی - بدون ویم آرسی                                              |
| `--version`       | چاپ اطلاعات مربوط به ورژن و ویژگی ها                                                                         |


<hr>

<div dir="rtl"><h4>جدول دوم</h4></div>

| Option           | Description                                                                                                       |
|------------------|-------------------------------------------------------------------------------------------------------------------|
| `vim`            | باز کردن ویم و یک بافر خالی در حالت نرمال                                                                  |
| `vim filename`   | باز کردن ویم با یک فایل مشخص                                                          |
| `vim -`          |stdin خواندن متن از ورودی استاندارد                                                                                   |
| `-n` or `--normal` | باز کردن ویم در حالت نرمال، پیش‌فرض                                                                                 |
| `-i` or `--insert` | باز کردن ویم در مود اینسرت                                                                                  |
| `-R` or `--readonly` | باز کردن فایل در حالت غیرقابل ویرایش                         |
| `-N` or `--noplugin` | باز کردن ویم بدون لود کردن هیچ پلاگینی               |
| `+[num]`          |               تعیین جایگاه نشانگر براساس شماره خط            |
| `+{command}` or `-c {command}` | اجرای یک دستور پس از بازکردن فایل                           |
| `-S {file}`       | سورس کردن یک فایل ویم اسکریپت                  |
| `-g` or `--gui`   |  باز کردن جی ویم یا همان ویم در پنجره گرافیکی
| `-A`              | باز کردن ویم در حالت عربی، راست به چپ آینه شده، درصورتی که با گزینه مربوط کامپایل شده باشد                               |
| `-b`              | حالت ویرایش فایل‌های باینری           |
| `-C`              |vi حالت هماهنگی با ادیتور  
| `-d`              | diff باز کردن ویم در حالت دیف , برای مقایسه فایل‌ها                 |
| `-E`              | باز کردن ویم در مود ارتقا یافته ی اکس
| `-F`              | باز کردن ویم با تنظیمات فارسی، این گزینه دیگر وجود ندارد
| `-h`              | نمایش پیام کمکی
| `-m`              | غیر فعال کردن امکان ایجاد تغییر 
| `-N`              |vi  خاموش کردن تطابق با 
| `-R`              |read only حالت                                                                                     |
| `-r`              | لیست کردن فایل های سواپ ویم جهت ریکاوری 
| `-x`              | فعال سازی رمزگذاری فایل                                                                          |
| `-y`              | باز کردن ویم در حالت ایزی-ویم / در این حالت ویم نت پد ویندوز را شبیه سازی می کند
| `-Z`              | باز کردن ویم در حالت محدود، جلوگیری از اجرای دستورات پوسته و غیره
| `--`              | اعلام پایان آرگومان های ویم، پس از این تمام آرگومان ها به عنوان نام فایل خوانده می شوند


<br>
<br>
<hr>
<div align="center" dir="rtl" style="color:orange;">
آخرین آپدیت:

۲۵ شهریور ۱۴۰۱

Sha Sha 25 07:07:01 +0330 1402

</div>
<hr>
<footer>
       <div dir="rtl">
              <p> مطالب این سایت بصورت مداوم به‌روز‌رسانی می‌شوند.  برای دنبال کردن مطالب این سایت را بوکمارک کنید.</p>
              <p>جهت کمک به این پروژه و اضافه کردن مطالب و نکات خود در باره ویم، فایل <a href="https://github.com/wolandark/vim-cheatsheet-farsi/blob/master/RAHNAMA.md">راهنمای</a>
 داخل مخزن را ببینید.</p>
              <p>جهت حمایت مالی از پروژه، در صورتی که در ایران هستید، روی دکمه‌ی <a href="https://www.coffeete.ir/wolandark">برام قهوه بخر</a>
 کلیک کنید.</p>
              <p>جهت ارتباط با نگارنده از طریق تلگرام یا ایمیل اقدام کنید.</p>
              <p>این سایت از یک اسکریپت web analytics کاملا اوپن سورس، ضمن احترام به حریم خصوصی کاربر استفاده می‌کند.</p>
       </div>
</footer>

### Contact me
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/wolandarkside)
[![Protonmail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:contact-woland@proton.me)

<br>
<br>
<hr>

<script async src="https://www.googletagmanager.com/gtag/js?id=G-HW0E88QFZ8"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-HW0E88QFZ8');
</script>

