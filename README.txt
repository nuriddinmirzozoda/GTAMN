GTA DUSHANBE 3D — ЧИХЕЛ БАРНОМА КАРДАН

ВАРИАНТИ 1 — PWA (содатарин, барои компютер ва телефон)
1. Ҳамаи файлҳои ин ҷузвдонро (index.html, sw.js, manifest.webmanifest, icon-*.png) ба GitHub репозиторӣ боргирӣ кунед.
2. Settings > Pages > Branch: main > Save. Баъди 1-2 дақиқа линк пайдо мешавад: https://НОМ.github.io/РЕПОЗИТОРИ/
3. Линкро дар Edge ё Chrome кушоед. Дар тарафи рости сатри адрес тугмаи "Насб кардан" (Install app) пайдо мешавад.
4. Баъди насб бозӣ ҳамчун барнома бо нишона дар Start/Desktop кушода мешавад ва пас аз як маротиба кушодан бе интернет ҳам кор мекунад.
   Мултиплейер ва линки ?room=РАМЗ ҳам аз ҳамин суроға кор мекунад.

ВАРИАНТИ 2 — .EXE БАРОИ WINDOWS (Electron)
1. Node.js-ро аз nodejs.org насб кунед.
2. Ҷузвдони "electron"-ро кушоед, дар сатри адрес cmd нависед ва Enter занед:
      npm install
      npm start          (санҷиш)
      npm run build      (файли .exe дар ҷузвдони dist пайдо мешавад)
3. Ин .exe-ро ба дӯстон диҳед. Қайд: китобхонаи three.js аз интернет бор мешавад. Барои кори комилан офлайн:
   - https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js
   - https://cdn.jsdelivr.net/npm/three@0.128.0/examples/js/controls/PointerLockControls.js
   ин ду файлро боргирӣ карда, дар index.html (дар ҷузвдони electron) дар теги <script src="..."> бо номи файлҳои маҳаллӣ иваз кунед.

ВАРИАНТИ 3 — ANDROID (APK)
Линки GitHub Pages-ро дар сайти pwabuilder.com ворид кунед ва "Package for Stores > Android" -ро интихоб кунед. APK-ро мегиред.
Идоракунии сенсорӣ (ҷойстик + тугмаҳо) аллакай дар бозӣ ҳаст.

IPHONE / IPAD: линки GitHub Pages-ро дар Safari кушоед > тугмаи Share > "Add to Home Screen". Бозӣ дар экрани пурра ва бе сатри адрес кушода мешавад.
ANDROID: дар Chrome линкро кушоед > ⋮ > "Install app" ё "Add to Home screen" (ё APK аз pwabuilder.com).
Телефонро уфуқӣ гардонед. Агар суст кор кунад, дигар барномаҳоро пӯшед.
