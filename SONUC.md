# Kurulum sonucu

- Calisma: 38960297584 / commit 4e69eddb0ebb3966bd6429c3f844bb1e6819ca64
- Tarih (UTC): 2026-10-16 20:12

```
1-pnpm=basarili
2-kurulum=basarili
3-derleme=basarili
4-typescript=basarili
5-testler=basarili
5-sesler=basarili
6-veritabani=basarili
7-site=basarili
```
## 01-pnpm.log
```
v24.21.0
Preparing pnpm@11.25.0 for immediate activation...
11.25.0
```
## 02-install.log
```
? Verifying lockfile against supply-chain policies (842 entries)...
Lockfile is up to date, resolution step is skipped
Progress: resolved 1, reused 0, downloaded 0, added 0
Packages: +640
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Progress: resolved 640, reused 0, downloaded 4, added 0
Progress: resolved 640, reused 0, downloaded 55, added 0
Packages are hard linked from the content-addressable store to the virtual store.
  Content-addressable store is at: /home/runner/work/lernkoko/lernkoko/.sites-runtime/pnpm-store/v11
  Virtual store is at:             node_modules/.pnpm
Progress: resolved 640, reused 0, downloaded 108, added 4
Progress: resolved 640, reused 0, downloaded 151, added 8
Progress: resolved 640, reused 0, downloaded 231, added 15
Progress: resolved 640, reused 0, downloaded 464, added 32
Progress: resolved 640, reused 0, downloaded 639, added 108
✓ Lockfile passes supply-chain policies (842 entries in 8.4s)
Progress: resolved 640, reused 0, downloaded 640, added 540
Progress: resolved 640, reused 0, downloaded 640, added 640, done
.../node_modules/workerd postinstall$ node install.js
.../esbuild@0.27.3/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.18.20/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.25.12/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.28.0/node_modules/esbuild postinstall$ node install.js
.../node_modules/workerd postinstall: Done
.../node_modules/unrs-resolver postinstall$ napi-postinstall unrs-resolver 1.11.1 check
.../node_modules/unrs-resolver postinstall: Done
.../esbuild@0.27.3/node_modules/esbuild postinstall: Done
.../esbuild@0.18.20/node_modules/esbuild postinstall: Done
.../esbuild@0.25.12/node_modules/esbuild postinstall: Done
.../esbuild@0.28.0/node_modules/esbuild postinstall: Done

dependencies:
+ @base-ui/react 1.7.0
+ @hookform/resolvers 5.7.1
+ @shadcn/react 0.3.0
+ class-variance-authority 0.7.1
+ clsx 2.1.1
+ cmdk 1.1.1
+ date-fns 4.4.0
+ drizzle-orm 0.45.2
+ embla-carousel-react 8.6.0
+ input-otp 1.4.2
+ lucide-react 1.31.0
+ next 16.3.4
+ next-themes 0.4.6
+ radix-ui 1.6.7
+ react 19.2.6
+ react-day-picker 10.0.1
+ react-dom 19.2.6
+ react-hook-form 7.85.0
+ react-resizable-panels 4.12.2
+ recharts 3.8.0
+ sonner 2.0.8
+ tailwind-merge 3.6.0
+ vaul 1.1.2
+ zod 3.25.76

devDependencies:
+ @cloudflare/vite-plugin 1.37.1
+ @cloudflare/workers-types 4.20260515.1
+ @tailwindcss/postcss 4.2.1
+ @types/node 22.19.19
+ @types/react 19.2.14
+ @types/react-dom 19.2.3
+ @vitejs/plugin-react 6.0.2
+ @vitejs/plugin-rsc 0.5.26
+ drizzle-kit 0.31.10
+ eslint 9.39.4
+ eslint-config-next 16.3.4
+ json-rpc-2.0 1.7.1
+ raw-body 3.0.2
+ react-server-dom-webpack 19.2.6
+ tailwindcss 4.2.1
+ tw-animate-css 1.4.0
+ typescript 5.9.3
+ vinext 1.0.0-beta.5
+ vite 8.0.13
+ wrangler 4.92.0

Done in 11.2s using pnpm v11.25.0
```
## 03-build.log
```
$ node scripts/sounds/make-sounds.mjs && node scripts/run-framework.mjs build
LernKoko sesleri hazır: tap 0.24s, tap2 0.24s, tap3 0.24s, whoosh 0.55s, correct 0.95s, complete 1.65s, soft 0.8s, beep 0.7s, retro 0.55s, low 0.95s, cartoon 0.85s

  vinext build  (Vite 8.0.13)

[34m[1/5] analyze client references...[39m
[2Ktransforming...✓ 403 modules transformed.
rendering chunks...
[32m✓ built in 1.16s[39m
[34m[2/5] analyze server references...[39m
[2Ktransforming...✓ 209 modules transformed.
rendering chunks...
[32m✓ built in 306ms[39m
[34m[3/5] build rsc environment...[39m
[2Ktransforming...✓ 400 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 870ms[39m
[34m[4/5] build client environment...[39m
[2Ktransforming...✓ 1987 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 1.50s[39m
[34m[5/5] build ssr environment...[39m
[2Ktransforming...✓ 215 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 602ms[39m
[0m
  Route (app)
  ┌ ƒ /                  
  ├ ƒ /a1-2/ev-ve-yasam  
  ├ λ /api/auth          
  ├ λ /api/study         
  ├ ƒ /ev-esyalar        
  ├ ƒ /fiiller           
  ├ ƒ /giris             
  ├ ƒ /gizlilik          
  ├ ƒ /hesabim           
  ├ ƒ /kullanim-kosullari
  └ ƒ /uye-ol            

  λ API  ƒ Dynamic

  Build complete. Run `vinext start` to start the production server.

```
## 04-typescript.log
```
```
## 05-tests.log
```
✔ kapı: geçiş dönemi — Access ile giren tanınır, üyelik oturumu önceliklidir (131.322885ms)
✔ API: üye olma kuralları, oturum çerezi ve aynı e-postayla ikinci hesap (175.557097ms)
✔ API: giriş, yanlış şifre, deneme sınırı ve çıkış (340.521471ms)
✔ API: geçiş dönemi — Access ile giren kişi üye olunca eski kayıtları hesabında kalır (85.425353ms)
✔ API: ad ve şifre değiştirme, verilerimi indir, hesabı silme (197.306554ms)
✔ API: veritabanı yoksa açık bir hata verir (26.348148ms)
✔ sayfalar ve yayın: tablolar her yayında güvenle kurulur, giriş kapısı yerelde de çalışır (0.421953ms)
✔ every Nesne Kasası object has a picture: the classic pictures and the new tool pictures (8.571663ms)
✔ every picture is drawn from a shader model kept in the repository (1.500365ms)
✔ the 107 vault objects are sorted into eight categories by meaning (3.688316ms)
✔ every category has picture, writing and listening rounds with four distinct choices (6.492988ms)
✔ an unfinished round keeps working with the answer choices it was started with (137.367882ms)
✔ every object has one listening question with four unambiguous picture choices in each course (7.13107ms)
✔ listening lengths, category scope, server pools and mistake review match (31.248024ms)
✔ all three study modes and listening instructions have copy in every helper language (0.577684ms)
✔ Nesne Kasası rounds are shuffled anew and skip solved questions in every mode (9.663911ms)
✔ a sub-topic round also leaves out what is already solved (0.490935ms)
✔ the review button covers open mistakes and starred questions (3.390497ms)
✔ stars on Nesne Kasası questions are saved for the signed-in learner (131.821968ms)
✔ the Nesne Kasası page shows the star, the combined review button and the unsolved counter (0.816025ms)
✔ Nesne Kasası has no separate voice panel; voice and speed live in the top settings button on every page (0.55472ms)
✔ every vault object belongs to exactly one translated subtopic within its existing parent (1.364254ms)
✔ subtopic rounds, lengths and mistake reviews remain scoped in German and English for every mode (90.743681ms)
✔ the textbook tools page adds 15 new objects in their own Nesne Kasası category (1.345497ms)
✔ every new tool has its own 512 px picture, meanings in all languages and a sub-topic (2.467203ms)
✔ the tools can be practised in Gör ve Seç, Yazarak Pekiştir and Dinle ve Bul, with plural puzzles (4.455714ms)
✔ the pictures are drawn from shader models kept in the repository (0.56887ms)
✔ topic percentage counts exercises whose latest answer was correct (2.101142ms)
✔ progress pools match the exercises that the Ev ve Yaşam and Nesne Kasası pages offer (5.511449ms)
✔ XP, levels, day streak and daily goal (0.676008ms)
✔ progress copy is complete in every vault language (12.664341ms)
✔ the study API returns answer totals and local practice days only when asked (116.222116ms)
✔ home, Ev ve Yaşam and Nesne Kasası show the progress interface (0.580507ms)
✔ letter banks contain exactly the required copies, stable token IDs and complete German articles (21.722238ms)
✔ repeated letters use one remaining choice and removing a placed token restores its count (0.422464ms)
✔ the screenshot answer has letters out of order while the correctly spelled Toilette is accepted (0.288557ms)
✔ whole-article, plural and compound challenges use correct complete answers and mix with spelling (1.971962ms)
✔ letter-bank and article instructions are available in every helper language (1.805446ms)
✔ visible practice choices match server selection, including empty and active review pools (207.77894ms)
✔ every ready topic has questions and supported mode pools are nonempty (18.473009ms)
✔ start, wrong explanation, correct answer, finish, history and saved progress work end to end (181.115485ms)
✔ out-of-order answers, invalid options and answers from another account are rejected (40.140546ms)
✔ question IDs, canonical answers, supported variants, audio and images stay valid (7.348161ms)
✔ retry identifiers change with practice configuration instead of resuming a different test (0.207557ms)
✔ category rounds stay inside the chosen topic and automatically cover available activity types (74.065713ms)
✔ saved vocabulary and all listening or reading texts have meanings in each helper language (12.239319ms)
✔ feedback is specific to the question rather than an unrelated topic rule (1.369533ms)
✔ A1.1 and A1.2 contain only their twenty catalogue headings (6.346783ms)
✔ written gap answers, incorrect answers, saved mode and continuation persist through the study API (20.571187ms)
✔ object picture tests retain four choices and writing includes both names and article gaps (4.11726ms)
✔ Fiiller keeps the 38 verbs of the page with Präsens, Perfekt and a meaning in every language (2.423619ms)
✔ every verb has choice, writing and listening exercises with new IDs only (4.924242ms)
✔ grading checks hat or ist, the umlaut and the separable prefix (0.232753ms)
✔ rounds follow the chosen group and mode, solved questions wait and the same verb never comes twice in a row (11.718605ms)
✔ every text of the page exists in all twelve languages (2.851952ms)
✔ a Fiiller round starts, saves answers and stars, resumes and finishes through the study API (176.18208ms)
✔ Yanlışlarım: the workshop mistakes make their own round, and a right answer takes a question off the list (51.377059ms)
✔ the page is linked from home, only the correct answer is spoken, and verb audio is in the voice list (168.499439ms)
✔ sentences, form pieces and rules explain every verb (6.45361ms)
✔ the writing puzzles use sentences, the prefix choice and the | mark of separable verbs (0.432239ms)
✔ Fiil Atölyesi: two parts in book order, each verb in turn: card, meaning test, spelling, past form (8.083237ms)
✔ after an answer every person gets an example sentence: Präsens after meanings, Perfekt after Perfekt (10.863643ms)
✔ the cards say regular, irregular or modal; irregular names and forms get their own colour (1.214693ms)
✔ a part opens its verb list with what is done; a verb opens its own card (0.254376ms)
✔ letter puzzles: a wrong letter goes back and counts, hints help, a full word is checked by itself (3.832659ms)
✔ site voice manifest: normalised lookup, default voice and safe parsing (2.168562ms)
✔ an old device-voice choice moves once to the natural site voice; later choices are kept (0.310819ms)
✔ a natural clip plays when available and the device voice is the fallback (2.640319ms)
✔ when the chosen voice has no clip yet, another natural voice plays it before the device voice (0.644392ms)
✔ late clip events after stop or a newer request are ignored (0.499467ms)
✔ every effect has a rendered sound, a fallback recipe and readable labels (392.783407ms)
✔ the voice list covers each greeting, the speech pages and the deploy step (115.370333ms)
ℹ tests 166
ℹ suites 0
ℹ pass 166
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 3352.270829
```
## 05-voices.log
```
Doğal sesi eksik metin: 0
```
## 06-db.log
```
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  }
]
Yerel veritabanı: migration/database/members.sql

 ⛅️ wrangler 4.92.0 (update available 4.151.1)
──────────────────────────────────────────────
Resource location: local 

Use --remote if you want to access the remote instance.

🌀 Executing on local database DB (00000000-0000-4000-8000-000000000000) from .wrangler/state/v3/d1:
🌀 To execute on your remote database, add a --remote flag to your wrangler command.
🚣 4 commands executed successfully.
[
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "duration": 0
    }
  }
]
```
## 07-dev-server.log
```
$ node scripts/sounds/make-sounds.mjs && node scripts/run-framework.mjs dev
LernKoko sesleri hazır: tap 0.24s, tap2 0.24s, tap3 0.24s, whoosh 0.55s, correct 0.95s, complete 1.65s, soft 0.8s, beep 0.7s, retro 0.55s, low 0.95s, cartoon 0.85s

  vinext dev  (Vite 8.0.13)

Sites local sign-in: seedy@sites.test
  [32m➜[39m  [1mLocal[22m:   [36mhttp://127.0.0.1:[1m5173[22m/[39m
[2m8:11:14 PM[22m [33m[1m[vite][22m[39m [33m[2m(rsc)[22m[39m [33mwarning: client component dependency is inconsistently optimized. It's recommended to add the dependency to 'optimizeDeps.exclude'.[39m
  Plugin: [35mrsc:use-client[39m
  File: [36m/home/runner/work/lernkoko/lernkoko/node_modules/.pnpm/lucide-react@1.31.0_react@19.2.6/node_modules/lucide-react/dist/esm/Icon.mjs?v=5cc0e215[39m
 GET / 200 in 1.0s (compile: 1792181469.4s, render: 899ms)
 GET / 200 in 50ms (compile: 1792181469.3s, render: 34ms)
 GET /ev-esyalar 302 in 8ms
 GET /giris?return_to=%2Fev-esyalar 200 in 66ms (compile: 1792181469.4s, render: 42ms)
 GET /fiiller 302 in 8ms
 GET /giris?return_to=%2Ffiiller 200 in 30ms (compile: 1792181469.3s, render: 21ms)
 GET /a1-2/ev-ve-yasam 302 in 6ms
 GET /giris?return_to=%2Fa1-2%2Fev-ve-yasam 200 in 27ms (compile: 1792181469.3s, render: 19ms)
 GET /hesabim 302 in 6ms
 GET /giris?return_to=%2Fhesabim 200 in 24ms (compile: 1792181469.3s, render: 16ms)
 GET /giris 200 in 37ms (compile: 1792181469.4s, render: 17ms)
 GET /uye-ol 200 in 34ms (compile: 1792181469.3s, render: 16ms)
 GET /gizlilik 200 in 54ms (compile: 1792181469.4s, render: 19ms)
 GET /kullanim-kosullari 200 in 37ms (compile: 1792181469.4s, render: 17ms)
 GET /api/study 401 in 540ms
 GET /api/study 401 in 7ms
 GET /uye-ol?return_to=%2Ffiiller 200 in 30ms (compile: 1792181469.3s, render: 20ms)
 POST /api/auth 400 in 60ms
 POST /api/auth 201 in 32ms
 GET /fiiller 200 in 739ms (compile: 1792181469.5s, render: 574ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 92ms
 GET /api/study 200 in 14ms
 GET /hesabim 200 in 96ms (compile: 1792181469.4s, render: 61ms)
 POST /api/auth 200 in 18ms
 GET / 200 in 42ms (compile: 1792181469.3s, render: 31ms)
 GET /api/study 401 in 7ms
 GET /giris?return_to=%2Fhesabim 200 in 26ms (compile: 1792181469.3s, render: 19ms)
 POST /api/auth 401 in 28ms
 POST /api/auth 200 in 28ms
 GET /hesabim 200 in 31ms (compile: 1792181469.3s, render: 21ms)
 POST /api/auth 200 in 31ms
 GET / 200 in 42ms (compile: 1792181469.3s, render: 32ms)
 POST /api/auth 401 in 729ms
 GET /ev-esyalar 200 in 173ms (compile: 1792181469.4s, render: 137ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 930ms
 GET /ev-esyalar 200 in 26ms (compile: 1792181469.3s, render: 17ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 1.2s
 GET /a1-2/ev-ve-yasam 200 in 176ms (compile: 1792181469.4s, render: 127ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 26ms
 GET / 200 in 70ms (compile: 1792181469.3s, render: 60ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 73ms
 GET /api/study 200 in 13ms
 POST /api/study 201 in 18ms
 POST /api/study 200 in 14ms
 GET /api/study 200 in 10ms
 GET /fiiller 200 in 25ms (compile: 1792181469.3s, render: 17ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 57ms
 GET / 200 in 33ms (compile: 1792181469.3s, render: 22ms)
 GET /fiiller 302 in 6ms
 GET /giris?return_to=%2Ffiiller 200 in 24ms (compile: 1792181469.3s, render: 16ms)
 GET /fiiller 200 in 26ms (compile: 1792181469.3s, render: 18ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 192ms
 POST /api/study?learn=de 201 in 75ms
 POST /api/study?learn=de 200 in 19ms
 POST /api/study?learn=de 200 in 16ms
 POST /api/study?learn=de 200 in 21ms
 GET /fiiller 200 in 28ms (compile: 1792181469.3s, render: 19ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 46ms
 GET /fiiller 200 in 27ms (compile: 1792181469.3s, render: 18ms)
 GET /api/study?stats=1&tz=0&learn=de 200 in 46ms
[2m8:12:45 PM[22m [36m[1m[vite][22m[39m [34m[2m(rsc)[22m[39m [32mhmr update [39m[2m/app/globals.css[22m
[2m8:12:45 PM[22m [36m[1m[vite][22m[39m [90m[2m(client)[22m[39m [32mhmr update [39m[2m/app/globals.css?direct[22m
```
## 08-smoke.log
```
curl: (7) Failed to connect to localhost port 5173 after 0 ms: Couldn't connect to server
curl: (7) Failed to connect to localhost port 5173 after 0 ms: Couldn't connect to server
curl: (7) Failed to connect to localhost port 5173 after 0 ms: Couldn't connect to server
Site 4. denemede acildi
GECTI  Sayfa / — HTTP 200, baslik "LernKoko · Almanca ve İngilizce Eğitimi", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Giriş yap Üye ol ÜCRETSİZ ALMANCA VE İNGİLİZCE Almancayı resimlerle, sesle ve küçük adımlarla öğren. LernKoko'da kelimeleri resimli kartlarla tanır,
GECTI  Girissiz ana sayfada tanitim ve uye ol dugmesi var
GECTI  Girissiz /ev-esyalar giris sayfasina yonleniyor — http://localhost:5173/giris?return_to=%2Fev-esyalar
GECTI  Girissiz /fiiller giris sayfasina yonleniyor — http://localhost:5173/giris?return_to=%2Ffiiller
GECTI  Girissiz /a1-2/ev-ve-yasam giris sayfasina yonleniyor — http://localhost:5173/giris?return_to=%2Fa1-2%2Fev-ve-yasam
GECTI  Girissiz /hesabim giris sayfasina yonleniyor — http://localhost:5173/giris?return_to=%2Fhesabim
GECTI  Sayfa /giris — HTTP 200, baslik "Giriş yap · LernKoko", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Giriş yap Üye ol Giriş yap Kaldığın yerden devam etmek için giriş yap. E-posta Şifre Giriş yap Hesabın yok mu? Ücretsiz üye ol Şifremi unuttum © 202
GECTI  Sayfa /uye-ol — HTTP 200, baslik "Üye ol · LernKoko", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Giriş yap Üye ol Ücretsiz üye ol Bütün dersler üyelere açık. İlerlemen hesabına kaydedilir. Adın E-posta Şifre En az 8 karakter. Başka sitelerde kul
GECTI  Sayfa /gizlilik — HTTP 200, baslik "Gizlilik ve kişisel veriler · LernKoko", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Giriş yap Üye ol Gizlilik ve kişisel veriler Son güncelleme: 16 Ekim 2026 LernKoko, Almanca ve İngilizce öğrenmek için ücretsiz bir sitedir. Bu meti
GECTI  Sayfa /kullanim-kosullari — HTTP 200, baslik "Kullanım koşulları · LernKoko", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Giriş yap Üye ol Kullanım koşulları Son güncelleme: 16 Ekim 2026 LernKoko'ya üye olarak bu koşulları kabul etmiş olursun. Kişisel bilgilerinin nasıl
GECTI  Girissiz kayit istegi reddediliyor (401 beklenir) — HTTP 401
GECTI  Sahte kimlik basligi ise yaramiyor (401 beklenir) — HTTP 401
GECTI  Uyelik: kosullar onaylanmadan hesap acilmiyor — Üye olmak için kullanım koşullarını ve gizlilik metnini kabul etmelisin.
GECTI  Uyelik: uye olunca istenen sayfaya donuluyor (/fiiller) — http://localhost:5173/fiiller
GECTI  Uyelik: oturum cerezi HttpOnly ve SameSite=Lax — httpOnly true, sameSite Lax
GECTI  Uyelik: uye kendi kayitlarini okuyabiliyor — HTTP 200
GECTI  Uyelik: Hesabim sayfasi ad ve e-postayi gosteriyor — Deneme Öğrenci · deneme-1792181515437@example.test
GECTI  Uyelik: cikis yapinca tanitim sayfasi ve kayitlar kapali — tanitim 1, kayitlar HTTP 401
GECTI  Uyelik: yanlis sifreyle giris olmuyor — E-posta ya da şifre yanlış.
GECTI  Uyelik: dogru sifreyle giris yapinca istenen sayfaya donuluyor — http://localhost:5173/hesabim
GECTI  Uyelik: hesap silinince kayitlar gidiyor ve giris artik olmuyor — silindikten sonra giris HTTP 401
GECTI  Uyelik sayfalarinda betik hatasi yok
GECTI  Yerel giris taklidi — son adres http://localhost:5173/ev-esyalar
GECTI  Sayfa /ev-esyalar — HTTP 200, baslik "Nesne Kasası · LernKoko", hata 2 (console: Failed to load resource: the server responded with a status of 404 (Not Found) | console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Site dili Türkçe Deutsch English العربية Українська Français Español Русский فارسی Polski Italiano Português Ana sayfa Nesne Kasası Nesne Kasası Tüm
GECTI  Sayfa /a1-2/ev-ve-yasam — HTTP 200, baslik "Ev ve Yaşam · LernKoko", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: Ana sayfa Site dili Türkçe Deutsch English العربية Українська Français A1.2 › Ev ve Yaşam A1.2 · 11 · WOHNEN Ev ve Yaşam A–D A–D · Karma tekrar 206 alıştırma %0
GECTI  Sayfa / — HTTP 200, baslik "LernKoko · Almanca ve İngilizce Eğitimi", hata 1 (console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Site dili Türkçe Deutsch English العربية Українська Français Üniteler ve konular Nesne Kasası Fiiller İlerlemen Seviye 1 0 0 XP · Sonraki seviyeye 1
GECTI  Giris yapinca ana sayfada dersler var (tanitim yok)
GECTI  Giristen sonra kayitlar okunuyor — HTTP 200
GECTI  Test oturumu basliyor (veritabanina yazma) — HTTP 201, soru obj-dictation-pfeil
GECTI  Cevap kaydediliyor ve dogru cevap donuyor — HTTP 200, dogru mu: 0
GECTI  Kayit geri okunuyor (gecmis) — cevaplanan 1/1
GECTI  Sayfa /fiiller — HTTP 200, baslik "Fiil Atölyesi · LernKoko", hata 2 (console: Failed to load resource: the server responded with a status of 404 (Not Found) | console: Failed to load resource: the server responded with a status of 404 (Not Found)), metin: İçeriğe geç Site dili Türkçe Deutsch English العربية Українська Français Español Русский فارسی Polski Italiano Português Ana sayfa Fiil Atölyesi Fiil Atölyesi K
GECTI  Fiil Atolyesi sayfasinda yol paneli ve iki bolum var — yol 1, bolum 2
GECTI  Telefonda tanitim sayfasi yana tasmiyor — fazla genislik 0px
BILGI  Telefon: ogrenme karti (resim, anlam, cekim) tek ekrana sigiyor — ust 103, alt 648, ekran 664
BILGI  Telefon: yeni fiilin karti acilinca fiil kendiliginden okunuyor — http://localhost:5173/sfx/tap2.wav | tts:abfahren
BILGI  Telefon: test sorusu tek ekrana sigiyor — ust 218, alt 536, ekran 664
UYARI  Telefon: test sonucu ve ornek cumleler tek ekrana sigiyor — ust 104, alt 704, ekran 664
BILGI  Telefon: yazim tek ekrana sigiyor — ust 156, alt 535, ekran 664
BILGI  Telefon: yazim dolunca dugmeye basmadan kontrol ediliyor — ab|fahren · 5 kutu
BILGI  Telefon: yazimdan sonra gecmis hali sorusu (hat/ist yok) — Bu fiilin geçmiş hali (Partizip II) hangisi? · abgefahrt, abfahren, geabfahren, abgefahren
BILGI  Telefon: gecmis hali testinden sonra gecmis hali yazimi — Bu fiilin geçmiş halini (Partizip II) yaz. · adim: Geçmiş yazım
BILGI  Telefon: bolum listesinde fiiller gorunuyor — 19 fiil
BILGI  Telefon: fiil kartinda ornek cumlelerin anlami var — 9 anlam satiri
BILGI  Telefon: Yanlislarim bolumu var ve calisiliyor — 0 yanlis · yanlis yok
```
