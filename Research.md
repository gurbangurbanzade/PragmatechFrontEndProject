 ## Sual 77
   **const Calc = (a) => a + 5 -** bu bir funksiyadır hansı ki, hər bir dəyişənini 5 vahid artırır.<br>
   **const arr = [] -** yeni bir boş arrey təyin edir.<br>
   **for (let i = 0; i < 100; i++) -** burada 0-dan 100-ə qədər olan ədədlər dövrü yaradılır.<br>
   **arr.push(i) -** burada yuxarıda yaradılan ədədlər bir-bir arr adlı arreyin içinə yazdırılır.<br>
   **const finalArr = arr.filter((x) => x % 2 == 0).map(Calc) -** burada arr.filter -  metodu arr adlı arreyin elemntin cüt elementlərini seçir. map(calc) - isə həmin seçilmiş cüt ədədlərin üzərinə 5 gəlib finalArr adlı arreyin içinə yazdırır.<br>
   **console.log(finalArr) -** bu isə bizə finalArr adlı arreyi göstərir.<br>
   **Nəticə:** 5-dən 103-ə qədər iki-iki artan ədədlər arreyi.<br>
        
        
        
        
        
 **-Sual 76:**<br>
 **-Sual 75:**<br>
 **-Sual 74:**<br>
 **-Sual 73:**<br>
 **-Sual 72:**<br>
 **-Sual 71:**<br>
 **-Sual 70:**<br>
  # Sual 59
  # Sual 58
 # Sual 57
# Sual 54
 **-Document Object Model-də Node və Element arasındakı fərqlər nələrdir? -** DOM Element-bildiyimiz HTML teqləridir. a, body, li və s. DOM Node isə bura şərhlər iki teqin qovşağı və s. aiddir.<br>
   **-nextSibling və nextElementSibling metodları nə işə yarayır və fərqləri nələrdir?**<br>
          *nextsiblig hər hans bir elementin onla eyni yerdə olan növbəti node-a müraciət edir.nextElementSibling isə növbəti elementə müraciət edir*<br><br>
   **-HTML Events və Javascript Events arasındakı fərqlər nələrdir?**<br>
          *HTML events html faylında hansı teqdə əməliyyat edəciksə onun daxilində yazırıq. Məsələn: onclick. JS-də isə bunu bir başa fayl daxilində id, class çağırmaqla edə bilirik.*<br><br>
 
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////<br>
 **- Sual 01:JavaScript nədir və necə işləyir?**<br>
         *JavaScript veb üçün skript dilidir. JavaScript kodu birbaşa veb brauzerdə işləyir. JavaScript veb tətbiqetmələr və ya veb səhifələr yaratmaq üçün HTML və CSS ilə işləyir. JavaScript veb səhifələrin dinamik elementlərini idarə edir. Veb brauzerlərdə və son zamanlarda veb serverlərdə də işləyir. JavaScript yazmazdan əvvəl başlıq altında necə işlədiyini bilmək vacibdir. Öyrənmək üçün iki vacib hissə var: Veb brauzerinin necə işləməsi və Sənəd Nişanı Modeli (DOM). Veb brauzeri bir veb səhifəni yükləyir, HTML-i təhlil edir və məzmundan Sənəd Obyekt Modeli (DOM) kimi tanınan şey yaradır. DOM veb səhifənin canlı görünüşünü JavaScript kodunuza təqdim edir. Daha sonra brauzer şəkillər və CSS sənədləri kimi HTML ilə əlaqəli hər şeyi götürəcəkdir. CSS məlumatı CSS təhlilçisindən gəlir. HTML və CSS əvvəlcə veb səhifəni yaratmaq üçün DOM tərəfindən birləşdirilir. Sonra brauzerlərin JavaScript mühərriki JavaScript sənədlərini və satır kodlarını yükləyir, ancaq kodu dərhal işləmir. HTML və CSS-nin yüklənməsini bitirməsini gözləyir. Bunu etdikdən sonra JavaScript kodun yazıldığı qaydada yerinə yetirilir. Bu, DOM-un JavaScript kodu ilə yenilənməsi və brauzer tərəfindən göstərilməsi ilə nəticələnir. Buradakı sifariş vacibdir. JavaScript HTML və CSS-nin bitməsini gözləməsəydi, DOM elementlərini dəyişdirə bilməzdi. *<br>
 **-DOM Traversing nədir? Nümunələr ilə izah edin.**<br>
          *HTML elementləri üzərində bir-başa gəzinmək üçündür. Birbaşa müraciət etməkdir. Qeyd etdiyim linkdən yazdığım nümunələrə baxa bilərsiniz. Hansısa ul elementin içindəki li elementinə çatmaq və ya a elementinə çatmaq üçün nümunələr göstərilib.  https://github.com/gurbangurbanzade/Udemy-Task/blob/main/JavaScript-Task/JS%20DOM/Traversing.js*<br>
 **-DOM Element və DOM Node arasındakı fərq nədir?**<br>
          *DOM Element-bildiyimiz HTML teqləridir. a, body, li və s. DOM Node isə bura şərhlər iki teqin qovşağı və s. aiddir. *<br>
 **-HTML daxilində var olan hər hansı elementi silmək üçün nə etmək lazımdır?**<br>
          *Məsələn: list.remove() dedikdə list klasına və id-ə sahib olan element silinəcək*<br>
 **-HTML daxilində olan bir elementi kopyalayaraq başqa bir elementin daxilinə yerləşdirmək üçün nə etmək lazımdır?**<br>
          *Bunu replace metodu vasitəsi ilə edirik. Nümunə olaraq bununla bağlı yazdığım koda yerləşdirdiyim link vasitəsi ilə baxa bilərsiniz. https://github.com/gurbangurbanzade/Udemy-Task/blob/main/JavaScript-Task/JS%20DOM/RemovingChanging.js*<br>
          <br><br><br>
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////<br>
>Imperative and Declarative Approach in programming

   **-Proqramlaşdırma dillərinin dizayn olunması deyiləndə ağlınıza nə gəlir? Yəni bir proqramlaşdırma dili necə dizayn edilə bilər?**<br>
         *Kodların yazılış forması. Bir çox əməliyyatlar yerinə yetirəcək funksiyaların proqram daxilində düzülüşü*<br>
   **-Öz həyatınızda imperativ və deklarativ yanaşmaya aid nümunələr tapın**<br>
          *Kod yazmağıöyrənmə-imperativ. Kafedə yemək sifariş etmək-deklorativ.*<br>
   **-Deklarativ yanaşma və funksiyalar arasında əlaqəni necə qura bilərsiniz?**<br>
          *Funksiyanın içində hansı əməliyyatların getdiyi maraqlı deyil. Əsas odur funksiya işləsin və bizə lazım olan nəticəni versin.*<br>
   **-imperative və deklarative yanaşmaya aid kod nümunələri yazın özünüz üçün .Düzgün olub olmadığını yoldaşlarınızla analiz edin**<br>
          <br><br><br>
          
>Function in Javascript

   **-Function necə formada təyin olunur?**<br>
         * 3 formada təyin olunur*<br>
   **-Fərqli formada function təyin etmə sizcə hansı hallarda lazım ola bilər?**<br>
          *Yazacağımız proqramın formasına, nəticəsinə və s. görə dəyişir*<br>
   **-function scope və global scope arasında fərqlər nədir?**<br>
          *funksiyanın daxilində təyin olunan dəyişən qlobalda dəyişə bilməz. Ancaq qlobalda təyin olunan dəyişən funksiyanın daxilində dəyişə bilər.*<br>
   **-function ramdə necə yer tutur?**<br>
          *Function dəyişənləri stack yaddaşda yer tutur. Funksiya çsğırılan zaman nəticə göstərilir və sonra yaddaşdan silinir.*<br><br><br>
          
 >Növbəti dərsin mövzuları üçün araşdırma sualları

   **-Javascript kodlarının arxa planda işləmə prinsipi necədir?**<br>
         **<br>
   **-Allocate memory-use memory- release memory ifadələri nə deməkdir?**<br>
          **<br>
   **-Static allocation vs dynamic allocation**<br>
          **<br>
   **-garbage collection nədir?**<br>
          **<br><br><br>
          
hoisting nədir?
scope və hoisting ifadələri arasında fərq nədir?





////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////<br>
>Understanding Syntax and Code Structure in JavaScript

    **Dəyişən təyin edərkən ya da dəyər mənimsədərkən boşluqlardan istifadə etsək bu mənə error olaraq qayıdar mı? let a=5; let a= 5; bu iki formada yazılışlardan hansısa error verəcək mi?**<br>
        *Xeyr qayıtmayacaq.Heç birində error verməyəcək*<br>
    **Bütün proqramlaşdırma dillərində olduğu kimi Js-də xüsusi simvollardan istifadə edir. () və {} mötərizələri V8Engine tərəfindən necə analiz olunur? Bu mötərizələr tərcümə prosesində necə başa düşülür?**<br>
        *() - hər hansı çərt içində yazılır, hər hansı funksiyanı bildirir. {} - proqram başa düşürki bu mötərizənin içində hər hansı bir əməliyyat gedəcək. If, for, do, while, class, switch və s. şərti ödəndikdə bu mötərizələrin içində olan əməliyyat yerinə yetirilir*<br>
    **let StudentName; let studentName; let studentname yazılışları arasında Javascript üçün hər hansı fərq varmı? Qısacası Javascript Case Sensitive dildir?**<br>
        *Bunlar ayrı-ayrı dəyişənlərdir. Bəli.*<br>
    **Javascriptdə kod yazarkən indentation hansı hallarda istifadə olunur və mən kod yazarkən indentation istifadə etməyə məcburammı?**<br>
         *Kodların oxunaqlı və səliqəli görünməsi üçün istifadə olunur. Xeyr məcbur deyil.*<br><br><br>

>Primitive and Reference data types?

   **-let x=5; kodlarının v8engine tərəfindən tərcümə edilərək maşın dilinə çevrilmə prosesini necə təsəvüür edirsiniz?**<br>
         *v8 stack yaddaşda bir xanaya 5 dəyərini mənimsədir və bir xanayada x dəyişənini.*<br>
   **-primitive və reference data tipləri deyə iki kategoriyaya ayrılma səbəbi nə ola bilər?**<br>
         *Məlumatların ölçüləri, onların sayının çoxluğu, proqram daxilində dəyərlərin dəyişməsi, əlavə olunması və silinməsi kimi hallar.*<br>
   **-bu iki tip arasında fərqli xüsusiyyətlər nədir?**<br>
         *Primitiv sabit ölçüsü var, Referans dinamik xarakter daşıyır və ölçüsü dəyişə bilər. Referans tiplər məlumatı dəyişəndə saxlamır. Dəyişən stack yaddaşda yerləşir dəyər isə heap yaddaşda. Referans tiplərdə eyni dəyərə malik dəyişənlər olduqda dəyər dəyişdikdə digər dəyişənində dəyəri dəyişir.*<br>
   **-bu data tiplərin yaddaşdakı yeri ilə əlaqədar senarilərinizi yazın. Yəni kod v8 enginə-nə ötürüldüyü zaman o kodun başına nə iş gəlir?<br>
         *Primitiv tiplər stack yaddaşda saxlanılır. Referans tipdə isə dəyişən stack dəyər heap yaddaşda saxlanır.*<br>
   **-data tiplərin bu formada iki kategoriyaya ayrılması sadəcə javascript dilinə xas xüsusiyyətdir yoxsa digər dillərdə də eyni yanaşma mövcuddur mu?**<br>
         *Hər dilin özənə məxsus data tipləri var*<br>
   **-Bu mövzunu öyrənmək proqramçı olaraq sizə nə qata bilər? Yəni bu mövzunu qavramağınız sizə nə fayda verəcək?**<br>
         *Bir proqramçı olaraq arxa tərəfdə nələrin baş verdiyini bilmək borcdur. Və proqramın sürətli və ya zəif işləməsini təmin edə bilərik.*<br><br><br>

>NaN, null, undefined in Javascript

   **-Bu tiplər başqa hansı dillərdə mövcuddur?**<br>
         *Ancaq javascriptdə mövcuddur*<br>
   **-NaN null və undefined bunlardan hansı data tipdir və növləri nədir? Primitive yoxsa reference tip olub olmadığı haqqında nə deyə bilərsiz?**<br>
         *Undifined və null primitiv data tipdir.*<br>
   **-Type Casting metodlarından istifadə edərək bu dəyərləri çevirəndə hansı nəticələr əldə edildiyini analiz edin və bunun səbəblərini araşdırın**<br>
         *Araşdırıldı*<br><br><br>
         
>Expressions and operators

   **-expression deyiləndə nə başa düşməyim lazımdır?**<br>
         *Hansısa yazılı ifadədir və heç bir əməliyyat yerinə yetirmir*<br>
   **-operator və expression arasında fərqlər nələrdir?**<br>
         *operatorlar isə hansısa əməliyyatı icra edir. Yazılış qaydaları fərqlidir.*<br><br><br>
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
> Hello World məqaləsinin effektiv oxunması üçün suallar
<br>
    1)Javascript kodları necə formada yazıla bilər?
<br>
        -HTML faylında script teqlərinin daxilində və ya ayrıca js faylında.
<br>
    2)Javascript kodlarının script tagları daxilində yazmaqla ayrı fayl formatında yazıb import etmek arasında nə fərq var?
<br>
        -Ayrı fayl daxilində yazılanda brauzer onu 1 dəfə yükləyir və keş yaddaşında saxlayır. Həmin scriptə istinad edən səhifələr onu yükləmək əvəzinə brauzein keş yaddaşından götürəcək. Nəticədə yüklənmə olmayacaq və səhifə daha sürətli olacaq. HTML daxilində isə ən sadə scriptlər olur. Zənnimcə HTML faylında olduqda hər dəfə brauzer yenidən bu faylları yükləyir.
<br>
    3)Madem mənim brauzerimdə V8-Engine yüklüdür niyə html kodu daxilində yazılan javascript kodları işləmir.<br>
        - Zənnimcə html kodu daxilində yazıldıqda V8 bu kodları adi html kodları kimi başa düşür və tərcümə etmir. Bu səbəbdən biz o kodları script teqinin daxilində yazırıq ki V8 bunun js kodlar olduğunu anlasın və onu tərcümə etsin. 
<br>
<br>

> Code Structure məqaləsinin effektiv oxunması üçün suallar 
<br>
    1)";" hansı hallarda istifadə edilir?
<br>
        - Əgər yeni sətirə keçəciksə bu zaman ";" istifadə etməliyik. Əslində istifadə etməsək də olar. Bu zaman js  ";" istifadə olunmayan sətir ilə növbəti sətiri eyni sətir kimi oxuyur və bəzi hallarda proqram bunu xəta kimi görür.   
<br>
    2)Javascript-də comment yazmaq üçün neçə üsul var.
<br>
        - Tək sətiri comment olaraq yazmaq istəyiriksə // istifadə edirik. /*…*/ çoxlu sətiri comment olaraq istifadə etmək istəyiriksə bu işarədən istifadə edirik
<br>
<br>

>Variables məqaləsinin effektiv oxunması üçün suallar
<br>
    1)let,var,const ifadələri arasında fərqlər nədir?
<br>
        -Const sabit dəyişəndir və ona mənimsədilən dəyərlər dəyişmir.Let-ə isə ancaq blok daxilində nə isə mənimsədilib çağırıla bilər. Gündəlik kod yazılımında let-dən istifadə olunur əksər hallarda. Var blok tanımır və onunla tanıdılan dəyişənlərə istənilən yerdə istənilən dəyəri mənimsətmək olar.

<br>
    2)dəyişən təyin edərkən adlandırma qaydaları nələrdir?
<br>
        -Dəyişən təyin edərkən ilk simvol rəqəm ola bilməz. JS-in öz sintaksis sözlərindən ola bilməz. Ancaq hərf, rəqəm, $ və _ işarələrindən ola bilər.
<br>
let x=5;x=7 yazıldığı zaman nəticə 7 olur.Belə olan halda 5 dəyərinin aqibəti nə olur? Yaddaşda yer tutur mu 5 dəyəri yoxsa başqa proses mi gedir?
<br>
        -5 yaddaşdan silinir artıq x 7 kimi tanınır.
<br>
<br>

>Data Types məqaləsinin effektiv oxunması üçün suallar
<br>
5 dəyəri yaddasa yazılarkən 2-li say sisteminə çevrilir və ona görə yaddaşda tutduğu yer hesablanır.Bəs 5.34 dəyərinin yaddaşda tutduğu yeri necə hesablamaq olar?
<br>
        -Yuvarlaqlaşdırıldıqdan sonra 2-lik say sisteminə çevrilir.
<br>
undefined, NaN və null dəyərlərinin yaddaşda nə qədər yer tutduğunu araşdırın
<br>
        -yaddaşda yer tutmur
<br>
let a; bu formada dəyişən təyin etmişəm.
<br>
Bu dəyişən yaddaşda stack-da mı yoxsa heap-də mi yerləşir
<br>
        - a dəyişəni stack-da ona mənimsədilən dəyər heap-də yerləşir.
<br>
Bu dəyişən yaddaşda yer tuturmu? Tutursa nə qədər yer tutur?
<br>
        -Yer tutmur
<br>
<br>

>Type Conversion məqaləsinin effektiv oxunması üçün suallar
<br>
    1)Ümumiyyətlə sizə görə bir məlumat növünü başqa məlumat növünə çevirmək nəyə lazımdır?
<br>
        - Bəzən rəqəmləri simvol kimi və ya əksinə istifadə etmək lazım olur bu zaman bu əməliyyatlardan istifadə edirik. Eyni zamanda məlumatın olub olmadığını 0 və 1 olduğunu təyin etmək üçün.
<br>
    2)Type Conversion necə formada həyata keçirilir?
<br>
        -3 formada
<br>        
    3)Type Conversion metodlarının siyahısını çıxarın
<br>
        -To Number, To String, To Boolean
<br>
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
[a. interpreter və compiler dillər arasındakı fərqləri haqqında araşdırma edərək öz anladığınız formada yazın
-interpereter dillərdə kodlar sətir sətir oxunur. hansısa sətirdə səhv olduqda proqram həmin sətiri göstərir ancaq proqramı yenə tərcümə edir. Compiler dillərdə isə bütövlükdə oxunur. Hansısa sətirdə səhv olduqda proqram işləmir və dil tərcümə olunmur. Yalnız səhv aradan qaldırıldıqdan sonra tərcümə olunur.]

[b. dəyişən və məlumat növləri arasındakı fərq nədir? Bunlar nə üçün istifadə olunur? Məlumat növü və dəyişən tamam fərqli anlayışdır. Biri hara mənsub olduğunu, təyin olunduğunu bildirir. Məlumat növü isə həmin mənsub edilən dəyişkənin hansı növdə string, boolean, null, undifined və s. olduğunu bildirir. Dəyişənə hər hansı bir məlumat təyin etdikdə onun növü olur. Məsələn rəqəm təyin ediriksə number, yazı təyin ediriksə string və s. kimi.]

[c. hər dilin özünə məxsus məlumat növləri mövcuddur. Bu məlumat növlərin dillərə görə fərqlənməsinin səbəbləri sizcə nədir?
-Düşünürəm ki istifadə olunma yerlərinə və yaranma texnologiyasına görə. Yəqin hər yeni nəsil dil yarandıqca təkmilləşdirmə olduğundan artıq əvvəlkindən fərqlənir. Bu həm də bir marketinq ola bilər. Necə ki, Apple-da İOS, digər smartfonların çoxunda adroid əməliyyat sistemidir.]

[d.javascriptdə dəyişən təyin edilmək üçün əsas üç açar söz var . let,var,const. Bu açar sözlərin vəzifələri arasındakı fərqlər nələrdir?
- Var global scopedir. Bu onun mənfi cəhətidir.
- let block scopedir. Müxtəlif scopelərdə müxtəlif dəyişənlər təyin oluna bilər. Ancaq varda belə deyil. Let dəyişənləri yenilənə bilir amma yenidən təyin edilə bilmir.
- const sabit dəyişəndir. Ona mənsub etdiyimiz element və ya sözü sonradan dəyişmək olmur.]

[e. Proqramçı olaraq bir proqram yazarkən işi görmə addımlarımız necə olmalıdır?
- yazacağım proqram haqqında və ya ona yaxın proqramlar haqqında araşdırma etmək
- alqoritm sxemini qurmaq
- harada və necə istifadə olunacağını müəyyən etmək
- sonra hansı dildə yazacağıma qərar vermək
- Proqramı yazmağa başlamaq
]
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Sual01: Javascript proqramlaşdırma dili hansı sahələrdə istifadə olunur?

Hazırki dövr internet əsri olduğundan əlbəttə ki, veb proqramlaşdırma daha çox önə çıxır. Vebdə də demək olar ki, hər istiqamətdə istifadə olunan dil sözsüz ki, JavaScript-dir. Buna görə də JavaScript-in top 1-də olması gözlənilən idi. JavaScript hazırda sürətlə inkişaf edən proqramlaşdırma dillərindən biridir. Google, Microsoft, Facebook, Netflix, Mozilla və s. kimi nəhəng texnologiya şirkətləri tərəfindən dəstəklənir və inkişaf etdirilir. Həmçinin, öyrənilməsi rahat olduğundan yeni başlayanlara da tövsiyyə olunur. Dünyada JavaScript-in backend-də istifadəsi geniş yayılsa da, ölkəmizdə hələ ki, frontend proqramlaşdırma üçün istifadə olunur. “Stack Overflow”-dakı tərtibatçıların illik sorğusuna əsasən, proqramçıların 70%-dən çoxu “JavaScript”-i istifadə edir. Onu istənilən tərtibat sahəsində tətbiq etmək olar. O, internetin aparıcı frontend-dillərindən biridir. “JavaScript” həmçinin obyekt-səmtləşdirilmədən tutmuş funksionala qədər bir neçə proqramlaşdırma üslublarını dəstəkləyir. Onda, həmçinin çoxlu sayda kitabxana var. “JavaScript” o qədər populyardır ki, oyun tərtibatı və virtual reallıq kimi sahələr üçün ən yaxşı həll olmadığı halda belə, onun bu sahələr üçün freymvörkləri mövcuddur. JavaScript bu gün demək olar ki, bütün inkişaf etmiş vebsaytlarda istifadə olunan və veb-saytların dinamikasına töhfə verən proqramlaşdırma dilidir. Veb saytlara istifadəçilərlə əlaqə saxlamağa imkan verir. JavaScript həm istifadəçi, həm də server tərəfində işləyə bilər. https://earnado.com/tr/javascript-nedir-nasil-kullanilir-neler-yapilir/


Sual02: Aşağıdakı proqramlaşdırma terminlərinin qısa acıqlamasını yazın

.compilers: Hər hansı bir dildə yazılmış kodu kompüterin başa düşəcəyi bir dilə çevirən proqramdır.

interpreters: Hər hansı bir dildə yazılmış kodu sətirlər üzrə kompüterin başa düşəcəyi bir dilə çevirən proqramdır.

translators: Yeksək səviyyəli bir kodu başqa dildə yüksək səviyyəli bir koda çevirən proqram. 

assemblers: assambler dilində yazılmış kodu maşın dilinə tərcümə edir.

programming paradigms: Programın və ya kodun yazılma tərzidir.

debugging: Komputer kodunda səhv tapmaqvə düzəltmək üçün olan bir proses

boolean: Dəyişən tipidir. Yalnız 2 qiymət alır. Doğu yalnış

char: Dəyişən tipidir. Yaddaşda 2 byte(16 bit) yer tutur. Özündə yalnız 1 simvol saxlayır.

null: Əgər hansısa dəyişənin dəyəri təyin edilməyəcəksə onu null olaraq təyin edə bilərik.Və həmin dəyər riyazi hesablamada iştirak etdikdə null üstü örtülü olaraq number –ə           çevrilərək dəyər alacaq.

command-line interface: Bu, istifadəçilərə müəyyən tapşırıqları yerinə yetirmək üçün kompüterlərə mətn əmrləri daxil etməyə imkan verən proqramdır.

low-level language: Aşağı səviyyə dilləri isə daha çox kompüterin dili olan maşın (binary) dilinə yaxın olan dillərdir. Maşın insanla müqayisədə aşağı səviyyəli dilləri asanlıqla başa düşür.

high-level language: Kompüter proqramları yazan proqramçılar adətən yuxarı səviyyəli dillərdən istifadə edirlər. Belə dillər strukturuna və sintaksisinə görə insan dilinə yaxın olur.

markup language:  Səhifənin ümumi görünüşünü və içindəki məlumatı formatlamağa kömək edən asan başa düşülən açar sözlər, adlar və ya etiketlərdən ibarət kompüter dili.

Sual03: Veb səhifəsinin işləmə prinsipini anlayabilmək üçün aşağıdakı mövhumları araşdıraraq yazın

İnternet ve intranet arasındakı fərqlər nədir? - Çoxumuz İnternet və İntranet şərtləri arasında qarışıq qalırıq. Aralarında çox bərabərsizlik olsa da, fərqlərdən biri də İnternetin hamı üçün açıq olması və hər kəs tərəfindən əldə edilə bilməsi, İntranet isə bir təşkilat özəl olaraq sahib olduğu üçün doğrulanmış giriş tələb edir.

Server-side və client-side ifadələrinin mənası nədir? BackEnd və FrontEnd. Serverdə işləyən proqramlara verilən ümumi ad. Brauzerdə Vebdə işləyən proqramlara verilən ümumi ad.

Server nədir və necə işləyir? Server, şəbəkə üzərindən edilən sorğuları qəbul edən və onlara cavab verən proqram və ya aparat qurğusudur.

Domain nədir və necə işləyir? Domain və ya domain adı istifadəçilərin sayta müraciət etdikləri zaman daxil edəcəkləri resursun ünvanına deyilir. Domain veb saytların internetdəki adı və adresidir. Bu adres olmadan internet istifadəçiləri veb saytlara girə bilməzlər. Domen İP adresi adlanan kompüterlərin birbirini tanıması üçün istifadə olunan nömrələmə sisteminin bəsitləşidirilmiş və kəlimələr ilə ifadə edilən formasıdır. Veb saytları ziyarət etmək istəyənlərin ip adresləri bilmələri çətin olacağı üçün domen alaraq sayt daha asan yadda qalan bir hala gətirilir.
HTTP nədir və nəyə lazımdır
URL və URI ifadələri arasındakı fərqləri izah edin.
