# Yayın sonucu

- Calisma: 38960600609 / commit 4e69eddb0ebb3966bd6429c3f844bb1e6819ca64
- Tarih (UTC): 2026-10-16 20:13

```
1-pnpm=basarili
2-kurulum=basarili
mod=YAYIN (worker: lernkoko, d1: lernkoko-db)
3-hesap=basarili
4-d1=basarili
5-sesler=basarili
5-derleme=basarili
6-sema=basarili
6-uyelik=basarili
7-yayin=basarili
8-kontrol=basarili
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
Packages are hard linked from the content-addressable store to the virtual store.
  Content-addressable store is at: /home/runner/work/lernkoko/lernkoko/.sites-runtime/pnpm-store/v11
  Virtual store is at:             node_modules/.pnpm
Progress: resolved 640, reused 0, downloaded 55, added 4
Progress: resolved 640, reused 0, downloaded 125, added 8
Progress: resolved 640, reused 0, downloaded 233, added 16
Progress: resolved 640, reused 0, downloaded 437, added 60
Progress: resolved 640, reused 0, downloaded 639, added 164
Progress: resolved 640, reused 0, downloaded 640, added 640, done
✓ Lockfile passes supply-chain policies (842 entries in 6.3s)
.../esbuild@0.28.0/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.27.3/node_modules/esbuild postinstall$ node install.js
.../node_modules/workerd postinstall$ node install.js
.../esbuild@0.18.20/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.25.12/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.28.0/node_modules/esbuild postinstall: Done
.../node_modules/unrs-resolver postinstall$ napi-postinstall unrs-resolver 1.11.1 check
.../esbuild@0.27.3/node_modules/esbuild postinstall: Done
.../node_modules/unrs-resolver postinstall: Done
.../node_modules/workerd postinstall: Done
.../esbuild@0.18.20/node_modules/esbuild postinstall: Done
.../esbuild@0.25.12/node_modules/esbuild postinstall: Done

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

Done in 8.4s using pnpm v11.25.0
```
## 03-account.log
```
Anahtar özeti: 53 karakter, biçim: uygun, not: boşluklar temizlendi

 ⛅️ wrangler 4.92.0
───────────────────
Getting User settings...
👋 You are logged in with an User API Token, associated with the email kooraycoskun@gmail.com.
ℹ️  The API Token is read from the CLOUDFLARE_API_TOKEN environment variable.
┌──────────────────────────────────┬──────────────────────────────────┐
│ Account Name                     │ Account ID                       │
├──────────────────────────────────┼──────────────────────────────────┤
│ Kooraycoskun@gmail.com's Account │ 0a6c54cf57b27b54097f9fe4b6f59923 │
└──────────────────────────────────┴──────────────────────────────────┘
🔓 To see token permissions visit https://dash.cloudflare.com/profile/api-tokens.
```
## 04-d1.log
```
D1 veritabanı: lernkoko-db (bc8bdd18-7628-4727-9fd2-a7d6e96ac054)
```
## 05-build.log
```
$ node scripts/sounds/make-sounds.mjs && node scripts/run-framework.mjs build
LernKoko sesleri hazır: tap 0.24s, tap2 0.24s, tap3 0.24s, whoosh 0.55s, correct 0.95s, complete 1.65s, soft 0.8s, beep 0.7s, retro 0.55s, low 0.95s, cartoon 0.85s

  vinext build  (Vite 8.0.13)

[34m[1/5] analyze client references...[39m
[2Ktransforming...✓ 403 modules transformed.
rendering chunks...
[32m✓ built in 1.11s[39m
[34m[2/5] analyze server references...[39m
[2Ktransforming...✓ 209 modules transformed.
rendering chunks...
[32m✓ built in 230ms[39m
[34m[3/5] build rsc environment...[39m
[2Ktransforming...✓ 400 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 839ms[39m
[34m[4/5] build client environment...[39m
[2Ktransforming...✓ 1987 modules transformed.
rendering chunks...
computing gzip size...
[33m[33m[PLUGIN_TIMINGS] [0mYour build spent significant time in plugins. Here is a breakdown:
  - vinext:middleware-server-only (39%)
  - alias (11%)
  - vinext:css-data-url (11%)
  - rsc:virtual-client-package (10%)
  - vinext:jsx-in-js (8%)
See https://rolldown.rs/options/checks#plugintimings for more details.
[39m
[32m✓ built in 4.28s[39m
[34m[5/5] build ssr environment...[39m
[2Ktransforming...✓ 215 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 626ms[39m
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

--- dist/server/wrangler.json (özet) ---
{
 "name": "lernkoko",
 "main": "index.js",
 "compatibility_date": "2026-05-15",
 "compatibility_flags": [
  "nodejs_compat"
 ],
 "d1_databases": [
  {
   "binding": "DB",
   "database_name": "lernkoko-db",
   "database_id": "bc8bdd18-7628-4727-9fd2-a7d6e96ac054"
  }
 ],
 "vars": {
  "TEAM_DOMAIN": "https://throbbing-bread-1016.cloudflareaccess.com",
  "POLICY_AUD": "3cd3e8e441c3a316e36262af3a1bb856b8e59cfe09100720ad8804701ffde8b0"
 },
 "assets": {
  "directory": "../client"
 }
}
```
## 05-voices.log
```
Site sesleri: 15330 dosya
```
## 06-members.log
```
      "rows_written": 0,
      "total_attempts": 1
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "served_by": "v3-prod",
      "served_by_region": "ENAM",
      "served_by_colo": "ORD",
      "served_by_primary": true,
      "timings": {
        "sql_duration_ms": 0.2234
      },
      "duration": 0.2234,
      "changes": 0,
      "last_row_id": 0,
      "changed_db": false,
      "size_after": 643072,
      "rows_read": 0,
      "rows_written": 0,
      "total_attempts": 1
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "served_by": "v3-prod",
      "served_by_region": "ENAM",
      "served_by_colo": "ORD",
      "served_by_primary": true,
      "timings": {
        "sql_duration_ms": 0.0757
      },
      "duration": 0.0757,
      "changes": 0,
      "last_row_id": 0,
      "changed_db": false,
      "size_after": 643072,
      "rows_read": 0,
      "rows_written": 0,
      "total_attempts": 1
    }
  }
]
[
  {
    "results": [
      {
        "name": "auth_attempts"
      },
      {
        "name": "member_sessions"
      },
      {
        "name": "members"
      }
    ],
    "success": true,
    "meta": {
      "served_by": "v3-prod",
      "served_by_region": "ENAM",
      "served_by_colo": "ORD",
      "served_by_primary": true,
      "timings": {
        "sql_duration_ms": 0.5728
      },
      "duration": 0.5728,
      "changes": 0,
      "last_row_id": 0,
      "changed_db": false,
      "size_after": 643072,
      "rows_read": 23,
      "rows_written": 0,
      "total_attempts": 1
    }
  }
]
```
## 06-schema.log
```
Şema zaten var, dokunulmadı.
```
## 07-deploy.log
```
│ ssr/_next/static/learning-effects-B_eXbkf7.js                                                                                 │ esm  │ 121.37 KiB  │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/loader-circle-CWPjAdMc.js                                                                                    │ esm  │ 0.14 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/object-study-lLbQBoAv.js                                                                                     │ esm  │ 29.95 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/practice-modes-DQvHqBkX.js                                                                                   │ esm  │ 1.18 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/progress-ui-Ctw1HL9K.js                                                                                      │ esm  │ 202.82 KiB  │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/static.edge-CtTHY6rS.js                                                                                      │ esm  │ 0.16 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/streamed-icons-lNEdsfG1.js                                                                                   │ esm  │ 0.67 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/toon-art-CCx4FDES.js                                                                                         │ esm  │ 17.89 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/user-round-BXLAu8Dl.js                                                                                       │ esm  │ 0.18 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/vault-language-preference-CKQ7-GoJ.js                                                                        │ esm  │ 0.53 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-copy-BU_pVH6f.js                                                                                        │ esm  │ 69.18 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.ar-DjqnqPNQ.js                                                                                 │ esm  │ 29.65 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.en-VQ-T5sSU.js                                                                                 │ esm  │ 22.02 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.es-DvRKoGGg.js                                                                                 │ esm  │ 22.40 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.fa--rSvXOIx.js                                                                                 │ esm  │ 34.95 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.fr-zPA4IAI9.js                                                                                 │ esm  │ 25.18 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.it-CaajIU-e.js                                                                                 │ esm  │ 21.89 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.pl-D1HKx67g.js                                                                                 │ esm  │ 22.11 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.pt-CVcGpiwe.js                                                                                 │ esm  │ 22.91 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.ru-B38k7284.js                                                                                 │ esm  │ 33.74 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.tr-Buaa8KOX.js                                                                                 │ esm  │ 21.52 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-examples.uk-C8njc3Lo.js                                                                                 │ esm  │ 34.26 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/_next/static/verb-study-DPKYRDus.js                                                                                       │ esm  │ 113.68 KiB  │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/index.js                                                                                                                  │ esm  │ 272.69 KiB  │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ ssr/vinext-client-assets.js                                                                                                   │ esm  │ 7.46 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ vinext-client-assets.js                                                                                                       │ esm  │ 7.46 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼─────────────┤
│ Total (88 modules)                                                                                                            │      │ 1724.14 KiB │
└───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┴──────┴─────────────┘
🌀 Building list of assets...
✨ Read 15726 files from the assets directory /home/runner/work/lernkoko/lernkoko/dist/client
🌀 Starting asset upload...
🌀 Found 5 new or modified static assets to upload. Proceeding with upload...
+ /vinext-client-entry-manifest.json
+ /_next/static/chunks/verb-study-CLI9bAJg.js
+ /_next/static/chunks/layout-segment-context-D6czmUDt.js
+ /_next/static/chunks/index-DAL4KXIm.js
+ /_next/static/chunks/app-route-prefetch-policy-CE7maoqh.js
Uploaded 1 of 5 assets
Uploaded 3 of 5 assets
Uploaded 5 of 5 assets
✨ Success! Uploaded 5 files (15688 already uploaded) (1.55 sec)

Total Upload: 2417.29 KiB / gzip: 763.66 KiB
Worker Startup Time: 18 ms
Your Worker has access to the following bindings:
Binding                                                           Resource                  
env.DB (lernkoko-db)                                              D1 Database               
env.TEAM_DOMAIN ("https://throbbing-bread-1016.cloudfla...")      Environment Variable      
env.POLICY_AUD ("3cd3e8e441c3a316e36262af3a1bb856b8e59...")       Environment Variable      

Uploaded lernkoko (7.67 sec)
Deployed lernkoko triggers (0.55 sec)
  https://lernkoko.kooraycoskun.workers.dev
Current Version ID: cdf0a132-af92-4823-a79a-7066e1b8f4f3
```
## 08-check.log
```
Adres: https://lernkoko.kooraycoskun.workers.dev
/ -> HTTP 200 
/giris -> HTTP 200 
/api/study -> HTTP 401 
/ev-esyalar -> HTTP 302 https://lernkoko.kooraycoskun.workers.dev/giris?return_to=%2Fev-esyalar
```
