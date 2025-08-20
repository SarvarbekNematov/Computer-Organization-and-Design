 		Computer Organization and Design


Yozuvchi va kitob haqida:
(David A. Patterson 1977-yilda Kaliforniya universiteti, Berklidagi fakultetga qo‘shilganidan beri kompyuter arxitekturasi fanidan dars beradi va u yerda Kompyuter fanlari bo‘yicha Pardee kafedrasi raisi lavozimini egallaydi. Uning ta’limdagi xizmatlari Kaliforniya universitetining “Distinguished Teaching Award” mukofoti, ACM’ning Karlstrom mukofoti hamda IEEE’ning Mulligan Education Medal va Undergraduate Teaching Award mukofotlari bilan taqdirlangan.

Patterson RISC’ga qo‘shgan hissasi uchun IEEE Technical Achievement Award va ACM Eckert-Mauchly Award mukofotlarini olgan, RAID texnologiyasiga qo‘shgan hissasi uchun esa IEEE Johnson Information Storage Award mukofotini bo‘lishgan. U shuningdek, Jon Hennessy bilan birgalikda IEEE John von Neumann Medal va C & C Prize mukofotlarini ham olgan.

Ham muallifi kabi, Patterson ham Amerika San’at va Fanlar Akademiyasi, Kompyuter Tarixi Muzeyi, ACM va IEEE a’zosi (Fellow) hisoblanadi hamda AQSh Milliy Muhandislik Akademiyasi, Milliy Fanlar Akademiyasi va “Silicon Valley Engineering Hall of Fame” a’zoligiga saylangan.

U AQSh Prezidentining Axborot Texnologiyalari Maslahat Qo‘mitasida xizmat qilgan, Berkli EECS (Electrical Engineering and Computer Sciences) bo‘limi ichidagi Kompyuter fanlari bo‘limi raisi, Kompyuter Tadqiqotlari Assotsiatsiyasi raisi va ACM prezidenti bo‘lib ishlagan. Bu faoliyati unga ACM va CRA tomonidan “Distinguished Service Award” mukofotlarini olib keldi.

Bizningcha, kompyuter fanlari va muhandisligi bo‘yicha ta’lim sohasi hozirgi rivojlanish darajasini aks ettirishi, shuningdek, hisoblash texnologiyalarini shakllantirayotgan tamoyillarni ham o‘rgatishi kerak. Shuningdek, biz kompyuter sohasining har bir yo‘nalishidagi o‘quvchilar kompyuter tizimlarining imkoniyatlari, unumdorligi, energiya sarfi va yakuniy muvaffaqiyatini belgilovchi tashkiliy paradigmalarni tushunishi zarur deb hisoblaymiz.

Zamonaviy kompyuter texnologiyalari kompyuter sohasining har bir yo‘nalishidagi mutaxassislardan ham apparat (hardware), ham dasturiy ta’minotni (software) tushunishni talab qiladi. Turli darajalarda apparat va dasturiy ta’minotning o‘zaro ta’siri hisoblashning asosiy tushunchalarini tushunish uchun asos bo‘lib xizmat qiladi. Sizning asosiy qiziqishingiz apparat yoki dasturiy ta’minot, kompyuter fanlari yoki elektr muhandisligi bo‘lishidan qat’i nazar, kompyuter tashkiloti va dizaynidagi asosiy g‘oyalar bir xil. Shuning uchun, ushbu kitobda biz apparat va dasturiy ta’minot o‘rtasidagi bog‘liqlikni ko‘rsatishga va hozirgi zamon kompyuterlarining asosini tashkil etuvchi tushunchalarga e’tibor qaratamiz.

Yaqinda yagona protsessorli (uniprocessor) tizimlardan ko‘p yadroli (multicore) mikroprotsessorlarga o‘tish bizning birinchi nashrdan beri ilgari surib kelayotgan qarashlarimiz to‘g‘riligini yana bir bor tasdiqladi. Oldin dasturchilar bu tavsiyani e’tiborsiz qoldirib, o‘z dasturlarini tezroq yoki energiya samaradorroq ishlashi uchun kompyuter arxitektorlari, kompilyator yozuvchilari va kremniy (chip) muhandislariga tayana olishardi. Ammo bu davr tugadi. Endi dasturlar tezroq ishlashi uchun ular parallel bo‘lishi kerak. Ko‘plab tadqiqotchilar dasturchilar ishlayotgan apparatning parallel tabiatini bilmasdan ham dastur tuzish imkonini yaratishga intilmoqda, biroq bu orzuni amalga oshirish uchun hali yillar kerak bo‘ladi. Bizningcha, hech bo‘lmaganda kelgusi o‘n yillikda aksariyat dasturchilar samarali parallel kompyuterlarda dasturlarni ishlatish uchun apparat/dasturiy ta’minot interfeysini tushunishga majbur bo‘lishadi.

Ushbu kitobning o‘quvchilari orasida assembly tili yoki mantiqiy dizayn bo‘yicha tajribasi deyarli yo‘q, lekin kompyuterlarning asosiy tuzilishini tushunishi kerak bo‘lganlar ham, assembly tili va/yoki mantiqiy dizayn bo‘yicha bilimga ega, biroq kompyuter yaratishni o‘rganmoqchi yoki tizim qanday ishlashini va nima sababdan shunday unumdorlikka ega ekanini bilmoqchi bo‘lganlar ham bor.

Ba’zi o‘quvchilar Computer Architecture: A Quantitative Approach (“Kompyuter arxitekturasi: miqdoriy yondashuv”) nomli kitob bilan tanish bo‘lishi mumkin, u ko‘pincha Hennessy va Patterson deb ataladi. (Aksincha, ushbu kitob esa ko‘pincha Patterson va Hennessy deb ataladi.) Biz avvalgi kitobni yozishdan maqsadimiz — kompyuter arxitekturasi tamoyillarini mustahkam muhandislik asoslari va miqdoriy narx/unumdorlik tahlili orqali tushuntirish edi. Biz tijorat tizimlariga asoslangan misollar va o‘lchovlarni birlashtirgan yondashuvdan foydalandik, bu esa realistik dizayn tajribasini yaratishga yordam berdi. Maqsadimiz shuni ko‘rsatish edi — kompyuter arxitekturasini faqat tavsifiy uslubda emas, balki miqdoriy metodologiyalar yordamida ham o‘rganish mumkin. Ushbu kitob kompyuterlarni chuqur tushunishni istagan, jiddiy kompyuter mutaxassislari uchun mo‘ljallangan edi.

Biroq, ushbu kitobning o‘quvchilarining aksariyati kompyuter arxitektori bo‘lishni rejalashtirmaydi. Shunga qaramay, kelajakdagi dasturiy tizimlarning unumdorligi va energiya samaradorligi — dasturiy ta’minot ishlab chiquvchilarning tizimda ishlayotgan asosiy apparat texnikalarini qay darajada tushunishiga bevosita bog‘liq bo‘ladi. Shu sababli, kompilyator yaratuvchilari, operatsion tizim dizaynerlari, ma’lumotlar bazasi dasturchilari va boshqa ko‘plab dasturiy ta’minot muhandislari bu kitobda berilgan tamoyillarga puxta tayangan holda ishlashlari kerak. Xuddi shunday, apparat dizaynerlari ham o‘z ishlarining dasturiy ilovalarga ta’sirini aniq tushunishlari lozim.

Shu bois, biz bu kitob Computer Architecture kitobidagi materialning oddiy bir qismi bo‘lishi mumkin emasligini bildik va materialni boshqa auditoriyaga moslash uchun tubdan qayta ishladik. Natijadan shu qadar mamnun bo‘ldikki, keyingi nashrlarda Computer Architecture kitobidan kirish materiallarining katta qismini olib tashladik. Natijada, bugungi kunda ikkala kitobning ilk nashrlariga qaraganda ancha kam o‘xshashlik mavjud.)

=============================================================> SHU YERIDAN BOSHLAB O'QISH TAFSIYA QILINADI

Biz Computer Organization and Design kitobining beshinchi nashri uchun oltita asosiy maqsadni belgiladik:

Ishlaydigan bir misol yordamida apparatni tushunishning naqadar muhimligini ko‘rsatish.

Kitob boshida tanishtiriladigan yon belgilar (margin icons) orqali barcha mavzular bo‘ylab asosiy g‘oyalarni ajratib ko‘rsatish.

Misollarni PC davridan PostPC davriga o‘tishni aks ettiradigan qilib yangilash.

Kiritish/Chiqarish (I/O) bo‘yicha materialni bitta bobga jamlash o‘rniga kitob bo‘ylab tarqatib berish.

Texnik mazmunni 2009-yildagi to‘rtinchi nashrdan beri sanoatda yuz bergan o‘zgarishlarga moslab yangilash.

Qo‘shimcha bo‘limlar va ilovalarni (appendix) CD-ga joylash o‘rniga onlayn formatga o‘tkazish — bu xarajatlarni kamaytiradi va kitobning elektron nashrini qulay qiladi.

Maqsadlarni batafsil muhokama qilishdan oldin, keling, keyingi sahifadagi jadvalga nazar solamiz. Bu jadval material bo‘yicha apparat va dasturiy ta’minot yo‘llarini ko‘rsatadi. Tajriba yoki e’tibor qaratilgan yo‘nalishidan qat’i nazar, 1-, 4-, 5- va 6-boblar ikkala yo‘lda ham mavjud.

1-bob — energiyaning ahamiyatini va qanday qilib u yagona yadrodan ko‘p yadroli mikroprotsessorlarga o‘tishga turtki bo‘layotganini muhokama qiladi hamda kompyuter arxitekturasidagi sakkizta buyuk g‘oyani tanishtiradi.

2-bob — apparatga yo‘naltirilganlar uchun qayta ko‘rib chiqish (review) materiali bo‘lishi mumkin, lekin dasturiy ta’minotga yo‘naltirilganlar uchun, ayniqsa kompilyatorlar va obyektga yo‘naltirilgan dasturlash tillari haqida ko‘proq bilishni istaganlar uchun, juda muhim bo‘lim.

3-bob — ma’lumot yo‘lini (datapath) qurishga qiziqqan o‘quvchilar yoki suzuvchi nuqtali arifmetika (floating-point arithmetic) haqida ko‘proq o‘rganishni istaganlar uchun. Ba’zi o‘quvchilar 3-bobning ayrim qismlarini o‘tkazib yuborishadi — yoki ularga ehtiyoj yo‘q bo‘lgani uchun, yoki bu qismlar takror bo‘lgani uchun. Biroq, biz ushbu bobda matritsa ko‘paytirish bo‘yicha davomli misolni kiritamiz va subword parallelizm yordamida ishlash unumdorligini to‘rt baravar oshirish mumkinligini ko‘rsatamiz, shuning uchun 3.6–3.8-bo‘limlarni o‘tkazib yubormang.

4-bob — quvurli protsessorlar (pipelined processors) haqida. 4.1, 4.5 va 4.10-bo‘limlar umumiy tushuntirishlarni beradi, 4.12-bo‘lim esa dasturiy ta’minotga yo‘naltirilgan o‘quvchilar uchun matritsa ko‘paytirishda navbatdagi unumdorlik oshishini tushuntiradi. Apparatga yo‘naltirilgan o‘quvchilar uchun esa bu bob asosiy material bo‘lib, ularning bilim darajasiga qarab, oldin C ilovasi (appendix) — mantiqiy dizayn (logic design) bo‘yicha bo‘limni o‘qish foydali bo‘lishi mumkin.

Oxirgi bob — ko‘p yadroli tizimlar, ko‘p protsessorli tizimlar va klasterlar haqida bo‘lib, asosan yangi materialdan iborat va uni hamma o‘qishi tavsiya etiladi. Bu nashrda ushbu bob sezilarli darajada qayta tashkil etildi, g‘oyalar oqimi tabiiyroq bo‘lishi uchun hamda GPU’lar, ombor-miqyosidagi kompyuterlar (warehouse-scale computers) va klasterlar uchun muhim bo‘lgan tarmoq interfeys kartalarining apparat-dasturiy interfeysi bo‘yicha yanada chuqurroq ma’lumotlarni qo‘shish uchun.

Birinchi maqsad — zamonaviy apparatni tushunishning unumdorlik va energiya samaradorligiga ta’sirini aniq misol bilan ko‘rsatish edi. Yuqorida aytib o‘tilganidek, biz 3-bobda subword parallelizm orqali matritsa ko‘paytirishni 4 baravar tezlashtirishdan boshlaymiz. 4-bobda siklni ochish (loop unrolling) orqali buyruq darajasidagi parallelizm (ILP) qiymatini namoyish etib, ishlashni yana ikki baravar oshiramiz. 5-bobda keshlarga optimallashtirish uchun blocking usulini qo‘llab, unumdorlikni yana ikki baravar oshiramiz. Nihoyat, 6-bobda 16 protsessorda mavzu-darajadagi parallelizm (thread-level parallelism) yordamida 14 baravar tezlashishni ko‘rsatamiz. Bu to‘rt optimallashtirishning barchasi bizning dastlabki matritsa ko‘paytirish misolimizga atigi 24 qator C kodi qo‘shadi.

Ikkinchi maqsad — o‘quvchilarga “o‘rmon” va “daraxt”ni farqlashga yordam berish, ya’ni kompyuter arxitekturasining sakkizta buyuk g‘oyasini kitobning boshida tanishtirish va ularning qolgan boblarda qayerlarda uchrashini ko‘rsatib borish. Biz (umid qilamizki) eslab qolish oson bo‘lgan yon belgilar (margin icons)dan foydalanamiz va matnda mos so‘zni ajratib ko‘rsatamiz. Kitobda deyarli 100 ta iqtibos mavjud. Hech bir bobda 7 tadan kam misol yo‘q va hech bir g‘oya 5 martadan kam tilga olinmagan. Parallelizm, quvurlash (pipelining) va bashorat qilish (prediction) orqali unumdorlik eng ko‘p uchraydigan g‘oyalar bo‘lib, ulardan keyin Mur qonuni keladi. Eng ko‘p misol keltirilgan bob — 4-bob (protsessorlar) bo‘lib, bu ajablanarli emas, chunki u, ehtimol, kompyuter arxitektorlari tomonidan eng ko‘p e’tibor qaratilgan mavzudir. Har bir bobda uchraydigan yagona buyuk g‘oya — parallelizm orqali unumdorlik, bu esa so‘nggi yillarda parallelizmga bo‘lgan katta e’tibor fonida juda ijobiy holatdir.

Uchinchi maqsad — ushbu nashrda kompyuter sohasida avlod almashinuvini, ya’ni PC davridan PostPC davriga o‘tishni misollar va materiallarda aks ettirish. Shunday qilib, 1-bob PC o‘rniga planshet kompyuterining ichki tuzilishini o‘rganadi, 6-bob esa bulutli hisoblash (cloud computing) infratuzilmasini tasvirlaydi. Shuningdek, biz ARM arxitekturasiga e’tibor qaratamiz — u PostPC davrida shaxsiy mobil qurilmalarda asosiy tanlov bo‘lsa, x86 esa PC davrida hukmron bo‘lgan va (hozircha) bulutli hisoblashda ustun bo‘lib qolmoqda.

Ushbu kitobga xush kelibsiz! Kompyuter tizimlari olamidagi hayajonli jarayonlarni sizga yetkazish imkoniga ega bo‘lganimizdan xursandmiz. Bu sekin rivojlanadigan, zerikarli va yangi g‘oyalar e’tiborsizlikdan unutilib ketadigan soha emas. Yo‘q! Kompyuterlar — nihoyatda faol va jonli axborot texnologiyalari sanoati mahsuli bo‘lib, uning barcha jabhalari AQSh yalpi milliy mahsulotining qariyb 10% ini tashkil etadi. AQSh iqtisodiyoti ham qisman Mur qonuni va’da qilayotgan axborot texnologiyalaridagi tezkor rivojlanishlarga bog‘liq. Bu noodatiy soha yangiliklarni hayratlanarli tezlikda qabul qiladi. So‘nggi 30 yil ichida kompyuter sanoatini tubdan o‘zgartirayotgandek tuyulgan bir qator yangi kompyuterlar paydo bo‘ldi; biroq bu “inqiloblar” tez orada to‘xtadi, chunki boshqa birov undan ham yaxshiroq kompyuter yaratdi.

Bu yangilik yaratish poygasi 1940-yillarning oxirida elektron hisoblash texnikasi paydo bo‘lganidan beri misli ko‘rilmagan taraqqiyotga olib keldi. Masalan, agar transport sanoati kompyuter sanoati bilan bir xil sur’atda rivojlanganida, bugun biz Nyu-Yorkdan Londonga atigi bir soniyada va bir tiyinga uchib bora olardik. Bir zum bo‘lsa ham shunday o‘zgarish jamiyatni qanday o‘zgartirganini tasavvur qiling — masalan, Tahitida yashab, San-Fransiskoda ishlash, yoki Moskva shahriga kechqurun Bolshoy teatrida balet tomoshasiga borish — va siz bunday o‘zgarishning qanchalik ulkan ahamiyatga ega ekanini tushunishingiz mumkin.

Kompyuterlar insoniyat tarixida uchinchi inqilobga sabab bo‘ldi — axborot inqilobi qishloq xo‘jaligi va sanoat inqiloblari qatoridan o‘rin oldi. Insoniyatning aql-zakovati va imkoniyatlari ko‘payishi, tabiiyki, bizning kundalik hayotimizga chuqur ta’sir ko‘rsatdi va yangi bilim izlash usullarini o‘zgartirdi. Endilikda ilmiy tadqiqotlarning yangi yo‘nalishi paydo bo‘ldi — hisoblash texnologiyalari bilan ishlovchi olimlar (kompyutatsion olimlar) nazariy va eksperimental olimlar qatoriga qo‘shilib, astronomiya, biologiya, kimyo, fizika va boshqa sohalarda yangi ufqlarni kashf etmoqda.

Kompyuter inqilobi davom etmoqda. Har safar hisoblash narxi va samaradorligi yana 10 barobar yaxshilanganda, kompyuterlardan foydalanish imkoniyatlari ham ko‘payadi. Ilgari iqtisodiy jihatdan imkonsiz bo‘lgan dasturlar birdan amaliy bo‘lib qoladi. Yaqin o‘tmishda quyidagi ilovalar faqat “kompyuter fantastikasi”dek tuyulardi:

Avtomobillarda kompyuterlar: 1980-yillarning boshlarida mikroprotsessorlar narxi va unumdorligi keskin yaxshilanmaguncha, avtomobillarni kompyuter orqali boshqarish juda g‘alati g‘oya edi. Bugungi kunda kompyuterlar ifloslanishni kamaytiradi, dvigatel boshqaruvi orqali yoqilg‘i tejamkorligini oshiradi, xavfsizlikni esa ko‘r joy (blind spot) ogohlantirishlari, yo‘ldan chiqish signalizatsiyasi, harakatlanuvchi obyektlarni aniqlash va avariyada xavfsizlik yostiqchalarini ishga tushirish orqali ta’minlaydi.

Uyali telefonlar: Kim o‘ylabdi deysizki, kompyuter tizimlaridagi yutuqlar butun sayyoraning yarmidan ko‘pini mobil telefonlarga ega qilib, deyarli istalgan joydan istalgan odam bilan aloqa qilish imkonini beradi?

Inson genomi loyihasi: Inson DNKsini xaritalash va tahlil qilish uchun zarur kompyuter jihozlari qiymati yuzlab million dollarga teng edi. Agar kompyuter narxlari 15–25 yil oldingidek 10–100 barobar qimmat bo‘lganida, bunday loyiha amalga oshmasdi. Bundan tashqari, narxlar hanuz pasaymoqda — tez orada siz o‘zingizning genom ma’lumotlaringizni olishingiz mumkin bo‘ladi, bu esa tibbiy xizmatni aynan sizga moslashtirish imkonini beradi.

World Wide Web: Ushbu kitobning birinchi nashri paytida mavjud bo‘lmagan internet tarmog‘i jamiyatimizni tubdan o‘zgartirdi. Ko‘p odamlar uchun internet kutubxonalar va gazetalarni almashtirdi.

Qidiruv tizimlari: Internet mazmuni hajmi va qiymati jihatidan oshib borgani sayin, tegishli ma’lumotlarni topish tobora muhimlashdi. Bugungi kunda ko‘pchilik hayotining katta qismini qidiruv tizimlariga tayangan holda o‘tkazadi, ularsiz yashash esa qiyin bo‘lar edi.

Shubhasiz, ushbu texnologiyalardagi yutuqlar jamiyatimizning deyarli barcha jabhalariga ta’sir qilmoqda. Apparat (hardware) sohasidagi taraqqiyot dasturchilarga nihoyatda foydali dasturiy ta’minot yaratish imkonini berdi, shuning uchun ham kompyuterlar hamma joyda uchraydi. Bugungi “ilmiy fantastika” ertangi “asosiy dastur” bo‘lishi mumkin — hozirdanoq kengaytirilgan haqiqat (augmented reality) ko‘zoynaklari, naqd pulsiz jamiyat va o‘z-o‘zini boshqaruvchi avtomobillar hayotimiz sari yo‘l olmoqda.

Garchi aqlli uy qurilmalaridan tortib uyali telefonlar va eng yirik superkompyuterlargacha bo‘lgan turli xil qurilmalarda umumiy apparat (hardware) texnologiyalari to‘plami (1.4 va 1.5-bo‘limlarga qarang) ishlatilsa ham, bu turli sohalardagi qo‘llanilishlar o‘ziga xos dizayn talablariga ega va asosiy apparat texnologiyalaridan turlicha foydalanadi. Umuman olganda, kompyuterlar uchta asosiy toifadagi ilovalarda qo‘llaniladi.

Shaxsiy kompyuterlar (PC) — ehtimol, eng mashhur kompyuter shaklidir va ushbu kitob o‘quvchilari ularni keng foydalanib ko‘rgan bo‘lishi mumkin. Shaxsiy kompyuterlar yagona foydalanuvchiga past narxda yuqori unumdorlikni ta’minlashga urg‘u beradi va odatda uchinchi tomon dasturiy ta’minotini ishga tushiradi. Ushbu kompyuter toifasi ko‘plab hisoblash texnologiyalarining rivojlanishiga turtki bergan bo‘lib, atigi qariyb 35 yillik tarixga ega.

Serverlar — zamonaviy ko‘rinishda, ilgari juda katta bo‘lgan kompyuterlarning o‘rnini egallagan tizimlardir va odatda ularga faqat tarmoq orqali ulaniladi. Serverlar katta ish yuklarini bajarishga yo‘naltirilgan bo‘lib, bu yuklar murakkab bitta dastur (odatda ilmiy yoki muhandislik ilovasi) yoki ko‘plab kichik vazifalardan iborat bo‘lishi mumkin (masalan, yirik veb-serverni ishga tushirishda). Bunday ilovalar odatda boshqa manbadan olingan dasturiy ta’minot (masalan, ma’lumotlar bazasi yoki simulyatsiya tizimi) asosida bo‘ladi, lekin ko‘pincha aniq bir funksiyani bajarish uchun moslashtiriladi yoki o‘zgartiriladi. Serverlar ham shaxsiy kompyuterlar kabi bir xil asosiy texnologiyalar asosida yaratiladi, biroq ular ko‘proq hisoblash quvvatiga, saqlash hajmiga va kirish-chiqish imkoniyatlariga ega bo‘ladi. Odatda, serverlarda ishonchlilikka ham ko‘proq e’tibor beriladi, chunki server ishdan chiqishi bir foydalanuvchi PC’iga qaraganda ancha katta zarar keltirishi mumkin.

Serverlar narx va imkoniyatlar bo‘yicha eng keng oraliqqa ega. Arzon server deyarli ekran yoki klaviaturasiz ish stolidagi kompyuterdan farq qilmasligi mumkin va narxi ming dollar atrofida bo‘ladi. Bunday arzon serverlar odatda fayl saqlash, kichik biznes ilovalari yoki oddiy veb-xizmatlar uchun ishlatiladi (6.10-bo‘limga qarang). Eng yuqori darajada esa superkompyuterlar turadi — hozirgi kunda ular o‘n minglab protsessorlar va ko‘plab terabayt xotiradan iborat bo‘lib, narxi o‘nlab yoki yuzlab million dollarni tashkil etadi. Superkompyuterlar, odatda, yuqori darajadagi ilmiy va muhandislik hisob-kitoblari, masalan, ob-havo prognozi, neft qidirish, oqsil tuzilishini aniqlash va boshqa yirik masalalar uchun ishlatiladi. Shunday bo‘lsa-da, superkompyuterlar eng yuqori hisoblash quvvatiga ega bo‘lsa-da, ular umumiy serverlar sonining ham, kompyuter bozori daromadining ham kichik bir qismini tashkil etadi.

O‘rnatilgan kompyuterlar (embedded computers) — kompyuterlarning eng katta toifasi bo‘lib, ilovalar va unumdorlik bo‘yicha eng keng doirani qamrab oladi. Ular tarkibiga avtomobilingizdagi mikroprotsessorlar, televizor ichidagi kompyuterlar va zamonaviy samolyot yoki yuk kemasini boshqaradigan protsessor tarmoqlari kiradi. O‘rnatilgan hisoblash tizimlari odatda bitta dastur yoki bir-biriga bog‘liq dasturlar to‘plamini ishlatishga mo‘ljallangan bo‘lib, ular apparat bilan birga integratsiyalangan holda yagona tizim sifatida yetkazib beriladi. Shu sababli, juda ko‘p o‘rnatilgan kompyuterlar mavjud bo‘lsa-da, foydalanuvchilarning aksariyati aslida ular kompyuterdan foydalanayotganini sezmaydi.

shaxsiy kompyuter (PC) — Bir kishining foydalanishi uchun moʻljallangan kompyuter boʻlib, odatda grafik displey, klaviatura va sichqonchani oʻz ichiga oladi.

server — Bir vaqtning oʻzida koʻp foydalanuvchilar uchun yirik dasturlarni ishga tushirishda foydalaniladigan kompyuter bo‘lib, odatda faqat tarmoq orqali ulanish orqali foydalaniladi.

superkompyuter — Eng yuqori unumdorlik va narxga ega bo‘lgan kompyuterlar sinfi; ular server sifatida sozlanadi va odatda o‘nlab milliondan yuzlab million dollargacha turadi.

terabayt (TB) — Dastlab 1,099,511,627,776 (2⁴⁰) baytni anglatgan, ammo aloqa va ikkilamchi xotira tizimlari ishlab chiquvchilari bu atamani 1,000,000,000,000 (10¹²) bayt ma’nosida ishlata boshlashgan. Chalkashliklarni kamaytirish uchun endi tebibayt (TiB) atamasi 2⁴⁰ baytga, terabayt (TB) esa 10¹² baytga nisbatan qo‘llaniladi.
1.1-rasmda o‘nlik va ikkilik qiymatlar hamda ularning nomlari to‘liq ko‘rsatilgan.

| Decimal term | Abbreviation | Value | Binary term | Abbreviation | Value | %Larger |
|--------------|--------------|-------|-------------|--------------|-------|---------|
| Kilobyte     |     KB       | 10³   | Kibibyte    |     KiB      |  2¹⁰  |   2%    |
| Megabyte     |     MB       | 10⁶   | Mebibyte    |     MiB      |  2²⁰  |   5%    |
| Gigabyte     |     GB       | 10⁹   | Gibibyte    |     GiB      |  2³⁰  |   7%    |
| Terabyte     |     TB       | 10¹²  | Tebibyte    |     TiB      |  2⁴⁰  |   10%   |
| Petabyte     |     PB       | 10¹⁵  | Pebibyte    |     PiB      |  2⁵⁰  |   13%   |
| Exabyte      |     EB       | 10¹⁸  | Exbibyte    |     EiB      |  2⁶⁰  |   15%   |
| Zettabyte    |     ZB       | 10²¹  | Zebibyte    |     ZiB      |  2⁷⁰  |   18%   |
| Yettabyte    |     YB       | 10²⁴  | Yobibyte    |     YiB      |  2⁸⁰  |   21%   |
1.1-RASM Baytlar bo‘yicha 2^X va 10^Y o‘lchovlaridagi chalkashlik barcha keng tarqalgan o‘lchov atamalari uchun ikkilik (binary) yozuv kiritilishi orqali bartaraf etildi. Oxirgi ustunda ikkilik atama mos keluvchi o‘nlik (decimal) atamadan qanchalik katta ekanligi ko‘rsatilgan — bu farq jadval bo‘ylab pastga qarab borar ekanmiz tobora ortib boradi. Bu old qo‘shimchalar (prefikslar) bitlar uchun ham, baytlar uchun ham ishlaydi. Masalan, gigabit (Gb) 10⁹ bit bo‘lsa, gibibit (Gib) 2³⁰ bitga teng.

o‘rnatilgan (embedded) kompyuter — Boshqa qurilma ichida joylashgan, oldindan belgilangan bitta dastur yoki dasturlar to‘plamini ishga tushirish uchun ishlatiladigan kompyuter.

O‘rnatilgan (embedded) ilovalar ko‘pincha minimal unumdorlikni talab qiluvchi, lekin xarajat yoki quvvat bo‘yicha qat’iy cheklovlarga ega bo‘lgan o‘ziga xos talablarni birlashtiradi.
Masalan, musiqa pleyerini olaylik: protsessor faqat uning cheklangan funksiyalarini bajarishga yetadigan tezlikda bo‘lishi kerak, undan ortiqcha tezlikdan ko‘ra, xarajat va quvvat sarfini kamaytirish eng muhim maqsadlardir.
Arzon bo‘lishiga qaramay, o‘rnatilgan kompyuterlar ko‘pincha nosozlikka kamroq toqat qiladi, chunki nosozlik oqibatlari yengil bezovtalikdan (masalan, yangi televizoringiz ishdan chiqishi) tortib, halokatli hodisalargacha (masalan, samolyot yoki yuk kemasidagi kompyuter ishdan chiqishi) bo‘lishi mumkin.

Iste’molchiga yo‘naltirilgan o‘rnatilgan ilovalarda, masalan, raqamli maishiy texnikalarda, ishonchlilik asosan soddalik orqali ta’minlanadi — asosiy e’tibor bitta funksiyani imkon qadar mukammal bajarishga qaratiladi.
Katta o‘rnatilgan tizimlarda esa, server sohasida qo‘llaniladigan ortiqcha nusxa (redundancy) usullaridan foydalaniladi.

Garchi bu kitob umumiy maqsadli kompyuterlarga e’tibor qaratgan bo‘lsa-da, undagi aksariyat tushunchalar o‘rnatilgan kompyuterlarga bevosita yoki ozgina o‘zgartirishlar bilan tatbiq etilishi mumkin.

PostPC davriga xush kelibsiz

Texnologiyaning uzluksiz rivojlanishi kompyuter apparatida avlodlar almashinuvi keltirib chiqaradi va bu butun axborot texnologiyalari sohasini tubdan o‘zgartiradi. Kitobning oxirgi nashridan beri biz shunday bir o‘zgarishni boshdan kechirdikki, bu o‘zgarish bundan 30 yil oldin shaxsiy kompyuterlarga o‘tish darajasida muhim bo‘ldi.

Shaxsiy kompyuterni endi shaxsiy mobil qurilma (PMD) almashtirmoqda. PMD’lar batareyada ishlaydi, Internetga simsiz ulanadi va odatda bir necha yuz dollarga tushadi. Xuddi shaxsiy kompyuterlar kabi, foydalanuvchilar ularga ishlatish uchun dasturlar (“ilovalar”) yuklab olishlari mumkin. Ammo shaxsiy kompyuterlardan farqli o‘laroq, ularda endi klaviatura va sichqoncha bo‘lmaydi; ular ko‘proq sensorli ekran yoki hattoki ovoz orqali boshqarishga tayangan bo‘ladi. Bugungi PMD — bu smartfon yoki planshet kompyuter, ammo ertangi kunda bunga elektron ko‘zoynaklar ham kirishi mumkin. 1.2-rasmda planshet va smartfonlarning o‘sish tezligi shaxsiy kompyuterlar va an’anaviy uyali telefonlarnikiga nisbatan ko‘rsatilgan.

An’anaviy server o‘rnini esa Bulutli hisoblash (Cloud Computing) egallamoqda. Bu texnologiya endi “Ombor o‘lchamidagi kompyuterlar” (Warehouse Scale Computers — WSCs) deb ataladigan ulkan ma’lumot markazlariga tayanadi. Amazon va Google kabi kompaniyalar 100 ming serverdan iborat WSC’larni quradi va keyin boshqa kompaniyalarga ularning bir qismini ijaraga beradi. Shu yo‘l bilan ular o‘zlari WSC qurmasdan, PMD’lar uchun dasturiy ta’minot xizmatlarini taqdim etishi mumkin bo‘ladi.

Darhaqiqat, Bulut orqali yetkaziladigan Xizmat sifatida dasturiy ta’minot (Software as a Service — SaaS) dasturiy ta’minot sanoatini qanday o‘zgartirayotgan bo‘lsa, PMD va WSC’lar ham apparat sanoatini shunday o‘zgartirmoqda. Bugungi dasturchilar ko‘pincha dasturlarining bir qismini PMD’da, boshqa qismini esa Bulutda ishlaydigan qilib yaratishadi.




Shaxsiy mobil qurilmalar (PMD) — internetga ulanish uchun mo‘ljallangan kichik, simsiz qurilmalar bo‘lib, ular quvvat olish uchun batareyalarga tayanadi va dasturiy ta’minot (software) odatda ilovalarni (app) yuklab olish orqali o‘rnatiladi. Oddiy misollarga smartfonlar va planshetlar kiradi.

Bulutli hisoblash (Cloud Computing) — internet orqali xizmatlar ko‘rsatadigan katta serverlar to‘plami bo‘lib, ba’zi provayderlar serverlarni o‘zgaruvchan miqdorda, xizmat sifatida ijaraga beradi.

Xizmat sifatida dasturiy ta’minot (SaaS) — dastur va ma’lumotlarni internet orqali xizmat ko‘rinishida yetkazib berish usuli bo‘lib, odatda brauzer kabi yengil dastur orqali ishlaydi. Bu dastur mahalliy qurilmada ishlaydi, lekin to‘liq o‘rnatilishi shart emas. Misollarga veb-qidiruv va ijtimoiy tarmoqlar kiradi.

Ushbu kitobdan nimalarni o‘rganishingiz mumkin

Muvaffaqiyatli dasturchilar har doim dasturlarining ishlash samaradorligi haqida qayg‘urib kelishgan, chunki foydalanuvchiga natijani tez yetkazish — muvaffaqiyatli dastur yaratishning muhim omilidir. 1960- va 1970-yillarda kompyuter unumdorligining asosiy cheklovi uning xotira hajmi edi. Shu sababli dasturchilar ko‘pincha oddiy bir tamoyilga amal qilishardi: xotira hajmini kamaytir — dastur tez ishlaydi.

Oxirgi o‘n yillikda kompyuter dizayni va xotira texnologiyalaridagi yutuqlar tufayli kichik xotira hajmi omili, ko‘pchilik ilovalarda (ichki o‘rnatilgan tizimlar bundan mustasno) unchalik ahamiyatli bo‘lmay qoldi.

Endi ishlash samaradorligiga qiziqqan dasturchilar 1960-yillardagi oddiy xotira modelining o‘rnini egallagan masalalarni tushunishlari kerak: protsessorlarning parallel tabiati va xotira tuzilmasining ierarxikligi. Bundan tashqari, 1.7-bo‘limda tushuntirganimizdek, bugungi dasturchilar o‘z dasturlari PMD-da (Personal Mobile Device) yoki Cloud’da ishlayotgan bo‘lsin, energiya samaradorligi haqida ham o‘ylashlari kerak, bu esa kod ostidagi qatlamlarni tushunishni talab qiladi.

Raqobatbardosh dastur yaratmoqchi bo‘lgan dasturchilar shuning uchun kompyuter tuzilishi bo‘yicha bilimlarini oshirishlari zarur.

Bizga ushbu inqilobiy mashinaning ichki qismini tushuntirish, sizning dasturingiz ostidagi dasturiy ta’minot va kompyuteringizning “qopqog‘i” ostidagi apparatni ochib berish imkoniyati berilgani biz uchun sharafdir. Ushbu kitobni tugatganingizda, biz siz quyidagi savollarga javob bera olasiz, deb ishonamiz:

C yoki Java kabi yuqori darajadagi tillarda yozilgan dasturlar qanday qilib apparat tiliga tarjima qilinadi va apparat bu dasturlarni qanday bajaradi? Ushbu tushunchalarni anglash — dastur samaradorligiga ta’sir qiluvchi apparat va dasturiy ta’minot jihatlarini tushunishning asosi.

Dasturiy ta’minot va apparat o‘rtasidagi interfeys nima va dasturiy ta’minot apparatga kerakli funksiyalarni bajarishni qanday buyuradi? Bu tushunchalar ko‘p turdagi dasturlar yozishda juda muhim.

Dastur samaradorligini nima belgilaydi va dasturchi uni qanday yaxshilashi mumkin? Bu dastur kodining o‘ziga, uning apparat tiliga tarjimasiga va apparatning uni samarali bajarish qobiliyatiga bog‘liq.

Aparat ishlab chiquvchilar ishlash tezligini oshirish uchun qanday texnikalardan foydalanishadi? Ushbu kitob zamonaviy kompyuter dizaynining asosiy tushunchalarini tanishtiradi. Qiziqqan o‘quvchilar uchun bu mavzu bo‘yicha batafsil material bizning ilg‘or kitobimiz — Computer Architecture: A Quantitative Approach’da mavjud.

Aparat ishlab chiquvchilar energiya samaradorligini oshirish uchun qanday usullardan foydalanishadi? Dasturchi buni yaxshilashga yoki yomonlashtirishga qanday ta’sir ko‘rsatishi mumkin?

Ketma-ket ishlov berishdan parallel ishlov berishga yaqinda o‘tilishining sabablari va oqibatlari qanday? Ushbu kitob motivatsiyani tushuntiradi, parallel ishlashni qo‘llab-quvvatlovchi hozirgi apparat mexanizmlarini bayon qiladi va yangi avlod “multicore” mikroprotsessorlarini (6-bobga qarang) tahlil qiladi.

1951-yildagi birinchi tijorat kompyuteridan boshlab kompyuter arxitektorlarining zamonaviy hisoblash tizimlariga asos bo‘lgan buyuk g‘oyalari qanday edi?

Ushbu savollarga javoblarni tushunmasdan turib, zamonaviy kompyuterda dasturingiz unumdorligini yaxshilash yoki muayyan ilova uchun bir kompyuterni boshqasidan yaxshiroq qiladigan xususiyatlarni baholash jarayoni — tushuncha va tahlilga asoslangan ilmiy jarayondan ko‘ra — sinov va xatolar orqali amalga oshiriladigan murakkab jarayonga aylanadi.

Birinchi bob kitobning qolgan qismi uchun poydevor bo‘lib xizmat qiladi. U asosiy g‘oyalar va ta’riflarni tanishtiradi, dasturiy ta’minot va apparatning asosiy qismlarini umumiy nuqtai nazarda ko‘rsatadi, unumdorlik va energiyani qanday baholashni tushuntiradi, kompyuter inqilobini harakatga keltirgan texnologiya — integral sxemalarni tanishtiradi va ko‘p yadroli protsessorlarga o‘tish sabablarini izohlaydi.

Ushbu bobda va keyingi boblarda siz ko‘plab yangi so‘zlarni, yoki ilgari eshitgan bo‘lsangiz ham ma’nosini aniq bilmaydigan so‘zlarni uchratishingiz mumkin. Xavotir olmang! Ha, zamonaviy kompyuterlarni tasvirlashda maxsus terminlar juda ko‘p ishlatiladi, ammo bu terminologiya aslida yordam beradi, chunki u biror funksiyani yoki imkoniyatni aniq ifodalash imkonini beradi. Bundan tashqari, kompyuter ishlab chiquvchilar (shu jumladan, ushbu kitob mualliflari) qisqartmalardan foydalanishni juda yaxshi ko‘rishadi. Harflar nimani anglatishini bilsangiz, ularni tushunish juda oson!

Atamalarni yodda saqlash va topishda yordam berish uchun, biz matnda birinchi marta uchragan har bir terminning ta’rifini sahifa chetiga ajratib yozdik. Terminologiya bilan qisqa vaqt ishlagach, siz ularni yaxshi o‘zlashtirasiz va BIOS, CPU, DIMM, DRAM, PCIe, SATA va boshqa ko‘plab qisqartmalarni to‘g‘ri ishlatganingizdan do‘stlaringiz ham hayratda qoladi.

Dastur ishini bajarishda foydalaniladigan dasturiy va apparat tizimlari qanday qilib unumdorlikka ta’sir qilishi haqida tushunchani mustahkamlash uchun biz kitob bo‘ylab “Dastur Unumdorligini Tushunish” nomli maxsus bo‘limdan foydalanamiz. Ushbu bo‘lim muhim fikr va tushunchalarni qisqacha umumlashtirib beradi. Birinchi bo‘lim quyida keltirilgan.

Dastur unumdorligi (tezligi) uning ishlashiga ta’sir qiluvchi bir nechta omillarga bog‘liq:
— dasturning ichida ishlatilgan algoritmlarning samaradorligi,
— dasturni yaratish va uni mashina buyruqlariga tarjima qilishda qo‘llanilgan dasturiy ta’minot tizimlari,
— va kompyuterning bu buyruqlarni bajarish samaradorligi (bunga kirish/chiqarish — I/O — amallari ham kiradi).

Quyidagi jadvalda apparat va dasturiy ta’minot unumdorlikka qanday ta’sir qilishini umumlashtirib ko‘rsatadi.

Ushbu kitobdagi g‘oyalar ta’sirini namoyish qilish uchun biz C tilida yozilgan matritsa bilan vektorni ko‘paytiruvchi dastur unumdorligini bir necha bob davomida bosqichma-bosqich oshiramiz. Har bir qadam zamonaviy mikroprotsessor qanday ishlashini chuqur tushunishga asoslanadi va natijada unumdorlik 200 barobar oshiriladi!

Ma’lumot darajasidagi parallelizm (data level parallelism) bo‘yicha, 3-bobda C tilidagi intrinsic funksiyalar orqali subword parallelism usulidan foydalanib unumdorlikni 3,8 barobar oshiramiz.

Buyruqlar darajasidagi parallelizm (instruction level parallelism) bo‘yicha, 4-bobda loop unrolling (tsiklni ochish) usulidan foydalanib, bir vaqtning o‘zida bir nechta buyruq bajarish va out-of-order execution apparatini ishga solamiz. Bu esa yana 2,3 barobar tezlik qo‘shadi.

Xotira ierarxiyasi optimizatsiyasi (memory hierarchy optimization) bo‘yicha, 5-bobda cache blocking usulidan foydalanib, katta matritsalar ustida ishlash tezligini yana 2,5 barobar oshiramiz.

Oqim darajasidagi parallelizm (thread level parallelism) bo‘yicha, 6-bobda OpenMP kutubxonasida parallel for tsikllaridan foydalanib, ko‘p yadroli protsessor imkoniyatlarini ishga solamiz va unumdorlikni yana 14 barobar oshiramiz.

“O‘zingizni Tekshirib Ko‘ring” bo‘limlari o‘quvchilarga bobda kiritilgan asosiy tushunchalarni tushunishlari va ularning oqibatlarini anglashlarini baholashga yordam berish uchun mo‘ljallangan. Ba’zi “O‘zingizni Tekshirib Ko‘ring” savollari oddiy javoblarga ega; boshqalari esa guruh bo‘lib muhokama qilish uchun mo‘ljallangan. Aniq savollarga javoblarni bob oxiridan topish mumkin. “O‘zingizni Tekshirib Ko‘ring” savollari faqat bo‘lim oxirida beriladi, bu esa agar siz materialni tushunganingizga ishonsangiz, ularni o‘tkazib yuborishni osonlashtiradi.

Har yili sotiladigan o‘rnatilgan (embedded) protsessorlar soni shaxsiy kompyuterlar (PC) va hatto PostPC protsessorlari sonidan ancha ko‘p. O‘z tajribangizga asoslanib, bu fikrni tasdiqlay olasizmi yoki inkor qilasizmi? Uyingizdagi o‘rnatilgan protsessorlar sonini sanab ko‘ring. Bu son uyingizdagi an’anaviy kompyuterlar soni bilan qanday taqqoslanadi?

Yuqorida aytib o‘tilganidek, dastur ishlash tezligi ham dasturiy ta’minotga, ham apparatga bog‘liq. Quyidagi har bir holatda unumdorlikdagi “tor joy”ni (bottleneck) aniqlash uchun to‘g‘ri joyni ayta olasizmi?

Tanlangan algoritm

=> Dasturlash tili yoki kompilyator

=> Operatsion tizim

=> Protsessor

=> I/O tizimi va qurilmalari

Kompyuter arxitekturasidagi 8 ta buyuk g‘oya

Endi biz kompyuter arxitektorlari so‘nggi 60 yil ichida yaratgan sakkizta buyuk g‘oyani tanishtiramiz. Bu g‘oyalar shu qadar kuchliki, ular birinchi ishlatilgan kompyuterdan keyin ham uzoq vaqt yashab kelmoqda, yangi arxitektorlar esa o‘zlaridan oldingilarning ishiga qoyil qolib, ularni taqlid qilishadi. Bu buyuk g‘oyalar — biz bu bobda va keyingi boblarda misollar paydo bo‘lganda eslab o‘tadigan asosiy mavzular. Ularning ta’sirini ko‘rsatish uchun, bu bo‘limda biz har bir buyuk g‘oya uchun belgi (ikonka) va ajratilgan terminlarni kiritamiz hamda kitobdagi deyarli 100 ta bo‘limda ularning qo‘llanilishiga ishora qilib boramiz.

1. Mur qonuniga moslab loyihalash
Tarjima:
Kompyuter dizaynerlari uchun yagona doimiy narsa — bu tezkor o‘zgarishlar bo‘lib, u asosan Mur qonuni bilan boshqariladi. Bu qonun integral sxema (IC) resurslari har 18–24 oyda ikki barobar ortishini aytadi. Mur qonuni 1965-yilda Gordon Moore — Intel asoschilaridan biri — tomonidan IC sig‘imining bunday o‘sishini bashorat qilish natijasida paydo bo‘lgan. Kompyuter loyihalari yillar davom etishi mumkinligi sababli, loyiha boshlanishi va tugashiga qadar chipdagi resurslar osonlik bilan ikki yoki to‘rt baravar ortishi mumkin. Skeet o‘qchisi singari, kompyuter arxitektorlar dizayn yakunlanganda texnologiya qayerda bo‘lishini oldindan hisobga olishlari kerak, boshlanish holatiga moslab emas.

Texnik izoh:
Mur qonuniga mos dizayn qilish deganda VLSI (Very Large-Scale Integration) texnologiyalardagi tranzistor sonining eksponensial o‘sishidan foydalanish tushuniladi. Bu o‘sish parallel ishlov berish bloklari (masalan, ko‘proq ALU yoki GPU yadro qo‘shish), kesh hajmini oshirish, yoki murakkabroq branch predictor kabi texnologiyalarni joriy etishga imkon beradi. Shuningdek, bu qonun foydalanish muddati davomida ishlash samaradorligini oshirishni rejalashda juda muhim — dizayn boshlanganda mavjud bo‘lmagan texnologiya loyiha yakuniga kelib real bo‘lishi mumkin.

2. Dizaynni soddalashtirish uchun abstraksiyadan foydalanish
Tarjima:
Ham kompyuter arxitektorlari, ham dasturchilar o‘zlarini samaraliroq qilish uchun usullar ixtiro qilishgan. Aks holda, Mur qonuni tufayli resurslar shunchalik tez o‘sganki, dizayn vaqti ham keskin ortib ketishi mumkin edi. Ahamiyatli samaradorlik usullaridan biri — apparat va dasturiy ta’minotda turli darajadagi tasvirlash (model) yordamida abstraksiyadan foydalanish. Bu yerda past darajadagi tafsilotlar yashiriladi va yuqori darajada sodda model taqdim etiladi.

Texnik izoh:
Abstraksiya kompyuter arxitekturasida ISA (Instruction Set Architecture) kabi qatlamlar orqali amalga oshadi. Masalan, dasturchi C tilida kod yozadi, kompilyator uni ISA buyruqlariga aylantiradi, apparat esa bu buyruqlarni mikroarxitektura darajasida bajaradi. Har bir qatlam o‘zining murakkabligini yashiradi va faqat interfeysni taqdim etadi. Bu yondashuv RISC arxitekturalarda juda samarali ishlaydi, chunki buyruqlar to‘plami soddalashtirilgan bo‘ladi va apparatning ishlashini optimallashtirish osonlashadi.

3. Ko‘p uchraydigan holatni tez ishlashini ta’minlash
Tarjima:
Ko‘p uchraydigan holatni tezlashtirish, kamdan-kam uchraydigan holatni optimallashtirishdan ko‘ra samaraliroq natija beradi. Qiziqarli tomoni shundaki, ko‘p uchraydigan holat odatda kamroq murakkab bo‘ladi va shu sababli uni yaxshilash ham osonroq. Bu oddiy, ammo foydali maslahat shuni anglatadiki, siz qaysi holat ko‘p uchrashini bilishingiz kerak. Bu esa faqat ehtiyotkorlik bilan o‘tkazilgan tajriba va o‘lchovlar yordamida aniqlanadi.

Texnik izoh:
Bu tamoyil Amdahl qonuni bilan bog‘liq: umumiy ishlashni oshirish uchun eng ko‘p ishlatiladigan qismlarni tezlashtirish eng samarali. Masalan, protsessorda branch prediction juda ko‘p uchraydigan shartli sakrash buyruqlarini tezlashtirishga yordam beradi. Yoki kesh xotira eng ko‘p murojaat qilinadigan ma’lumotlarni tezda yetkazish orqali ishlashni sezilarli oshiradi. Profiling vositalari (masalan, perf, VTune) yordamida “hot path” yoki “critical path” aniqlanadi va optimallashtiriladi.

4 Performance via Parallelism — Parallelizm orqali unumdorlik

Tarjima:
Kompyuter texnologiyalari yaratilganidan beri arxitektorlar ko‘proq unumdorlikni ishlarni parallel bajarish orqali olish mumkin bo‘lgan dizaynlarni taklif qilib kelishgan. Ushbu kitobda biz parallelizmning ko‘plab misollarini ko‘ramiz. Buni tushuntirish uchun kitob bir samolyotning bir nechta dvigateli misolida tasvirlaydi.

Texnik izoh:
Parallelizm — bu ko‘p protsessorlar yoki yadrolar bir vaqtda turli vazifalarni bajaradigan arxitektura prinsipi. Masalan:

Instruction-level parallelism (ILP) — protsessor bir nechta buyruqlarni bir vaqtning o‘zida bajaradi.

Data-level parallelism (DLP) — bitta operatsiya katta ma’lumotlar to‘plamiga parallel qo‘llanadi (SIMD).

Task-level parallelism (TLP) — har bir yadro mustaqil vazifani bajaradi (multithreading).
Parallelizm ko‘p yadroli CPU, GPU va distributed computing tizimlarining asosiy tamoyilidir.

5.	Performance via Pipelining — Pipelining orqali unumdorlik

Tarjima:
Parallelizmning bir o‘ziga xos turi kompyuter arxitekturasida shu qadar keng tarqalganki, unga alohida nom berilgan — pipelining. Masalan, eski davrda yong‘in chiqqanda odamlar chelak uzatib suv yetkazadigan “bucket brigade” usuli ishlatilgan. Har kim o‘z joyida turib, ketma-ket ishlash orqali suvni tezroq yetkazishgan. Kitobda pipeline — bir necha ketma-ket bosqichlardan iborat trubalar sifatida tasvirlanadi.

Texnik izoh:
Pipelining — bu buyruqlarni bajarish bosqichlarini ketma-ket, ammo ustma-ust bajarish texnikasi. Masalan, protsessorda:

Fetch → Decode → Execute → Memory → Write-back
bosqichlari bir vaqtning o‘zida turli buyruqlar ustida ishlaydi.
Bu konveyer liniyasi printsipiga o‘xshaydi: yangi buyruq kirganda eski buyruqlar hamon boshqa bosqichlarda ishlovda bo‘ladi.
Natijada protsessor har takt siklida bitta buyruq natijasini chiqarishi mumkin.

6.	Performance via Prediction — Bashorat orqali unumdorlik

Tarjima:
“Ruxsat so‘rashdan ko‘ra, kechirim so‘rash yaxshiroq” degan maqolga amal qilib, ba’zi hollarda natijani kutmasdan taxmin qilish va ishlash tezroq bo‘lishi mumkin. Albatta, noto‘g‘ri taxminlardan keyin tuzatish mexanizmi juda qimmatga tushmasligi va taxminning o‘zi yetarlicha aniq bo‘lishi kerak. Kitobda buni folbinning kristall shariga qiyoslaydi.

Texnik izoh:
Prediction — bu branch prediction va speculative execution kabi texnologiyalar orqali protsessorning ishlashini tezlashtirish.

Branch prediction — shartli sakrash (if/else) bo‘lsa, protsessor qaysi yo‘l tanlanishini oldindan taxmin qiladi va ishlashni davom ettiradi.

Speculative execution — taxmin qilingan yo‘nalishda buyruqlar bajariladi, agar noto‘g‘ri bo‘lsa, natija bekor qilinadi.
Zamonaviy protsessorlarda to‘g‘ri bashorat darajasi 90%+ bo‘lishi mumkin, bu esa ishlashni sezilarli oshiradi.

7.	Hierarchy of Memories — Xotira iyerarxiyasi

Tarjima:
Dasturchilar xotirani tez, katta va arzon bo‘lishini xohlashadi. Tezlik unumdorlikka ta’sir qiladi, sig‘im esa yechiladigan muammolar hajmini cheklaydi, narx esa ko‘pincha tizimning katta qismiga to‘g‘ri keladi. Arxitektorlar bu qarama-qarshi talablarni xotira iyerarxiyasi orqali hal qilishadi: eng tez, eng kichik va eng qimmat xotira tepada, eng sekin, eng katta va eng arzon xotira esa pastda joylashadi. Keshlash yordamida dasturchiga asosiy xotira tez va katta bo‘lgandek ko‘rinadi.

Texnik izoh:
Xotira iyerarxiyasi quyidagicha:

Register — eng tez, lekin eng kichik.

Cache (L1, L2, L3) — juda tez, kichik sig‘im, qimmat.

Main memory (RAM) — o‘rtacha tezlik, katta sig‘im.

Secondary storage (SSD/HDD) — sekinroq, katta sig‘im.

Tertiary storage (Tape/Cloud) — juda sekin, juda katta.
Maqsad — Locality of Reference (temporal va spatial locality) tamoyiliga asoslanib, tezroq xotiralardan maksimal foydalanish.

8.	Dependability via Redundancy — Zaxiralash orqali ishonchlilik

Tarjima:
Kompyuterlar nafaqat tezkor, balki ishonchli bo‘lishi kerak. Har qanday qurilma ishdan chiqishi mumkin, shuning uchun tizimlarni ishonchli qilish uchun zaxira komponentlar qo‘shiladi. Bu komponentlar nosozlik yuz bersa ishni davom ettiradi yoki nosozlikni aniqlashga yordam beradi. Kitob buni yuk mashinasining ikki g‘ildiragi misolida tushuntiradi.

Texnik izoh:
Redundancy nima?

Redundancy — bu fault tolerance (nosozliklarga chidamlilik) va reliability engineering (ishonchlilik muhandisligi) sohalarida ishlatiladigan asosiy tamoyillardan biri bo‘lib, tizimning ishlashini to‘xtatmaslik uchun qo‘shimcha, ortiqcha yoki parallel resurslardan foydalanishni anglatadi.
Ma’no jihatdan bu “agar bir qismi ishdan chiqsa, boshqa qismi avtomatik ishni davom ettiradi” degan strategiya.

Murakkab tizimlarda nosozliklar doimo yuz beradi — bu apparatning eskirishi, dasturiy xatolik, elektr ta’minoti uzilishi yoki inson xatosi bo‘lishi mumkin. Redundancy bu xatolar tizimni to‘liq ishdan chiqarishining oldini oladi.

Turlari
1️⃣ Hardware redundancy (apparat darajasidagi ortiqchalik)

Ma’nosi: Fizik qurilmalar yoki komponentlarning bir nechta nusxasi mavjud bo‘lib, bitta ishdan chiqsa, boshqasi avtomatik ravishda ishni davom ettiradi.

Misollar: RAID 1 (disk mirroring): Har bir yozuv ikkita yoki undan ortiq diskka nusxalanadi. Bitta disk ishdan chiqsa ham ma’lumot yo‘qolmaydi.

Dual power supply: Server yoki ma’lumot markazidagi qurilma ikki mustaqil elektr manbai bilan ta’minlanadi. Agar biri o‘chsa, ikkinchisi ishlashda davom etadi.

Cluster servers (failover cluster): Bitta server ishlamay qolsa, boshqa server xizmatni qabul qilib oladi.

Texnik afzallik: Real vaqt rejimida xizmat uzilmasdan davom etadi.

Kamchiligi: Xarajat ko‘p bo‘ladi, chunki apparat nusxalari kerak.

2️⃣ Information redundancy (ma’lumot darajasidagi ortiqchalik)

Ma’nosi: Ma’lumotlar ichiga ortiqcha kod yoki nazorat bitlari qo‘shiladi, bu xatolarni aniqlash va tuzatishga imkon beradi.

Misollar: ECC (Error-Correcting Code) memory: Xotira modullari bitta yoki bir nechta bitdagi xatoni avtomatik aniqlab va tuzatib ishlashni davom ettiradi.

Checksum: Fayllar yoki paketlarga hisoblangan nazorat qiymati (hash) qo‘shiladi; tarmoq orqali uzatilganda xato bo‘lsa aniqlanadi.

CRC (Cyclic Redundancy Check): Tarmoq protokollarida ma’lumot yaxlitligini tekshirish usuli.

Texnik afzallik: Ma’lumot buzilsa, tizim uni aniqlaydi va ba’zan avtomatik tuzatadi.

Kamchiligi: Saqlash yoki uzatishda qo‘shimcha joy va vaqt talab qiladi.

3️⃣ Software redundancy (dasturiy darajadagi ortiqchalik)

Ma’nosi: Bir xil natijani berishi kerak bo‘lgan bir nechta mustaqil algoritm yoki dastur ishlaydi va natijalar solishtiriladi.

Misollar: N-version programming: Bir nechta dasturchi jamoalari mustaqil kod yozadi; tizim natijalarni solishtirib eng to‘g‘risini tanlaydi.

Self-checking algorithms: Algoritm o‘z natijasini boshqa oddiyroq algoritm bilan tekshiradi.

Voting systems: Uchtadan ko‘p modul natija chiqaradi va “ko‘pchilik ovozi” bo‘yicha qaror qabul qilinadi.

Texnik afzallik: Dasturiy xatoliklarni aniqlash va avtomatik tuzatish imkoniyati.

Kamchiligi: Ishlash tezligi sekinlashishi va ishlab chiqish xarajatining oshishi.

Qayerda ishlatiladi?

Serverlar: Web-serverlar, ma’lumot bazalari va API-lar ishlashini uzluksiz ta’minlash.

Ma’lumot markazlari: Elektr, sovutish, tarmoq va saqlash tizimlarida zaxira komponentlar.

Aviatsiya va kosmik soha: Har qanday nosozlik odam hayotiga xavf tug‘dirishi mumkin bo‘lgani uchun uch barobar (triple) ortiqcha tizimlar qo‘llanadi.

Xavfsizlik tizimlari: Yong‘in signalizatsiyasi, monitoring va kirishni nazorat qilish tizimlarida zaxira liniyalar.



Oddiy bir dastur, masalan, matn protsessori yoki katta ma’lumotlar bazasi tizimi, millionlab kod satrlaridan iborat bo‘lishi mumkin va murakkab funksiyalarni bajaradigan ilg‘or dasturiy kutubxonalarga tayanadi. Kompyuterdagi apparat esa juda oddiy, past darajadagi buyruqlarni bajarishi mumkin, xolos. Murakkab dasturdan oddiy buyruqlargacha yetib borish uchun bir nechta dasturiy qatlamlar ishlatiladi, ular yuqori darajadagi amallarni talqin qiladi yoki tarjima qilib, oddiy kompyuter buyruqlariga aylantiradi. Bu — abstraksiyaning buyuk g‘oyasiga misoldir.

1.3-rasmda ko‘rsatilganidek, ushbu dasturiy qatlamlar asosan ierarxik tarzda joylashgan bo‘lib, eng tashqi qismida ilovalar (application) joylashadi, apparat va ilova dasturlari o‘rtasida esa turli xil tizim dasturlari (system software) ishlaydi.

Tizim dasturlarining ko‘p turlari mavjud, ammo har qanday zamonaviy kompyuter tizimining asosiy ikkita tizim dasturi bor: operatsion tizim va kompilyator.

Operatsion tizim foydalanuvchi dasturi bilan apparat o‘rtasida interfeys vazifasini bajaradi va turli xizmatlar hamda nazorat funksiyalarini taqdim etadi. Eng muhim funksiyalaridan ba’zilari:

Asosiy kirish-chiqish (I/O) amallarini boshqarish

Xotira va saqlash resurslarini taqsimlash

Kompyuterni bir vaqtning o‘zida bir nechta ilovalar tomonidan himoyalangan holda bo‘lishib ishlatishni ta’minlash

Bugungi kunda keng qo‘llaniladigan operatsion tizimlarga Linux, iOS va Windows kiradi.

Tizim dasturi (systems software) — umumiy foydali xizmatlarni taqdim etadigan dasturiy ta’minot, jumladan: operatsion tizimlar, kompilyatorlar, yuklovchilar (loaders) va assemblerlar.

Operatsion tizim (operating system) — kompyuter resurslarini unda ishlaydigan dasturlar foydasiga boshqaradigan nazorat dasturi.

Kompilyatorlar yana bir muhim vazifani bajaradi: C, C++, Java yoki Visual Basic kabi yuqori darajadagi dasturlash tilida yozilgan dastur kodini apparat (hardware) bajarishi mumkin bo‘lgan ko‘rsatmalarga tarjima qilish. Zamonaviy dasturlash tillarining murakkabligi va apparatning bajaradigan ko‘rsatmalarining soddaligini hisobga olganda, yuqori darajadagi til kodini apparat ko‘rsatmalariga aylantirish jarayoni ancha murakkab. Bu jarayonning umumiy ko‘rinishini bu yerda tushuntiramiz, keyin esa 2-bob va A-Ilovada batafsil ko‘rib chiqamiz.

Yuqori darajadagi tildan apparat tiliga

Elektron apparat bilan bevosita “gaplashish” uchun elektr signallarini yuborish kerak bo‘ladi. Kompyuter uchun tushunish eng oson bo‘lgan signallar — bu yoqilgan (on) va o‘chirilgan (off) holatlar. Shuning uchun kompyuter “alfaviti” atigi ikkita belgidan iborat. Xuddi ingliz tilida 26 ta harf bo‘lishi cheksiz so‘zlar tuzishga to‘sqinlik qilmagani kabi, kompyuter alifbosidagi ikki belgi ham kompyuter imkoniyatlarini cheklamaydi.

Bu ikki belgi 0 va 1 raqamlari bilan ifodalanadi. Kompyuter tili odatda ikkilik sanoq tizimi (binary numbers, base 2) deb ataladi. Har bir bitta belgiga ikkilik raqam yoki bit deyiladi.

Kompyuter biz bergan ko‘rsatmalar (instructions) bo‘yicha ishlaydi. Ko‘rsatmalar — bu kompyuter tushunadigan va bajaradigan bitlar to‘plami. Ularni son sifatida tasavvur qilish mumkin. Masalan, bitlar ketma-ketligi:

1000110010100000

bu ko‘rsatma ayrim kompyuterlarga ikkita sonni qo‘shishni buyuradi. 2-bobda nima uchun biz ko‘rsatmalar va ma’lumotlar uchun sonlardan foydalanishimiz tushuntiriladi. Muhimi, sonlardan ham ko‘rsatmalarni, ham ma’lumotlarni ifodalashda foydalanish — bu hisoblash texnologiyasining asosiy tamoyillaridan biridir.

Dastlabki dasturchilar kompyuter bilan faqat ikkilik raqamlar orqali muloqot qilishgan, lekin bu juda mashaqqatli bo‘lgan. Shuning uchun ular tezda inson fikriga yaqinroq yozuv tizimlarini ixtiro qilishdi. Dastlab bu yozuvlarni ikkilik kodga qo‘lda tarjima qilishgan, lekin bu ham juda zerikarli jarayon edi.

Keyin esa dasturchilar kompyuter yordamida kompyuterni dasturlash g‘oyasini ishlab chiqib, ikkilik kodga tarjima qiluvchi dasturlar yaratdilar. Birinchi bunday dastur assembler deb nomlangan. U simvolik shaklda yozilgan ko‘rsatmani apparat tushunadigan ikkilik shaklga tarjima qiladi. Masalan, dasturchi shunday yozadi:

add A,B

assembler esa uni quyidagiga aylantiradi:

1000110010100000

Bu ko‘rsatma kompyuterga A va B sonlarini qo‘sh deb buyuradi. Ushbu simvolik yozuv tili assembly tili deb ataladi va hozir ham ishlatiladi. Mashina tushunadigan ikkilik til esa mashina tili (machine language) deyiladi.

Assembly tili katta yutuq bo‘lsa-da, u hanuz olimning suyuqlik oqimini modellashtirish yoki buxgalterning hisob-kitob qilish jarayonidagi tabiiy ifodalariga juda yiroq. Assembly tilida dasturchi kompyuter bajaradigan har bir ko‘rsatma uchun bitta qator yozishi kerak bo‘ladi, bu esa uni kompyuter kabi fikrlashga majbur qiladi.

`compiler — Yuqori darajadagi dasturlash tili operatorlarini assembler tilidagi operatorlarga tarjima qiluvchi dastur.

binary digit — bit deb ham ataladi. 2-lik sanoq tizimidagi ikkita raqamdan biri (0 yoki 1) bo‘lib, ma’lumotlarning asosiy elementi hisoblanadi.

instruction — Kompyuter apparat vositalari tushunadigan va bajaradigan buyruq.

assembler — Buyruqlarning simvolik (belgili) ko‘rinishini ularning ikkilik (binary) ko‘rinishiga tarjima qiluvchi dastur.

assembly language — Mashina buyruqlarining simvolik ifodasi.

machine language — Mashina buyruqlarining ikkilik (binary) ifodasi.`
