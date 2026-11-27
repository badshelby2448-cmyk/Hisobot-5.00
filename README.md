# Yuk hisoboti: GitHub Pages'ga joylash

## 1. GitHub'ga yuklash
1. github.com'da hisobingizga kiring va **New repository** ni bosing.
2. Nomini yozing (masalan `yuk-hisoboti`), **Public** ni tanlang va yarating.
3. **uploading an existing file** (yoki Add file, Upload files) ni bosing.
4. Shu papkadagi **hamma 5 faylni** yuklang: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`. `README.md` ni yuklash shart emas.
5. **Commit changes** ni bosing.

## 2. Saytni yoqish
1. Repozitoriyda **Settings → Pages** ga kiring.
2. **Source**: Deploy from a branch. **Branch**: `main`, papka `/ (root)`. **Save** ni bosing.
3. 1–2 daqiqadan keyin tepada manzil chiqadi: `https://LOGININGIZ.github.io/yuk-hisoboti/`

## 3. Telefonda
- Manzilni **Android'dagi Chrome'da** oching.
- Chrome menyusidan **"Ekranga qo'shish"** (Install app) ni tanlang. Ilova kabi ochiladi va internet bo'lmasa ham ishlaydi.

## 4. Chek chop etish
1. Printerni yoqing, telefonda Bluetooth yoqilgan bo'lsin.
2. Blankada mijoz ustunidagi **Chek** → **Printerga chop etish**.
3. Birinchi marta ro'yxatdan printeringizni tanlang.
4. Qog'oz kengligini (58 yoki 80 mm) chek oynasida tanlang. XP-P301A uchun 80 mm (boshlang'ich holat shu).
5. XP-P301A ekranida printer **chek (receipt) rejimida** turishi kerak, yorliq (label) rejimida chek to'g'ri chiqmaydi.

Muammo bo'lsa:
- Belgilar buzilsa yoki chek uzilib qolsa, **"Sekin (ishonchli)"** ni tanlang.
- Printer ro'yxatda chiqmasa, u boshqa telefonga ulanib turgan bo'lishi mumkin, yoki oddiy Bluetooth (BLE emas) bo'lishi mumkin. Bunda **Rasm olish** orqali printer ilovasidan chop eting.
- iPhone'da Chrome va Safari Bluetooth'ni qo'llamaydi. Bluefy brauzerini sinab ko'ring yoki rasm orqali chop eting.

## 5. Ma'lumotlar
- Ma'lumot **shu telefonning brauzerida** saqlanadi. Telefonlar orasida o'tmaydi.
- Brauzer ma'lumotlarini o'chirsangiz hammasi yo'qoladi. Shuning uchun **Narxlar → Zaxirani yuklab olish** ni vaqti-vaqti bilan bosib turing.
- Claude'dagi eski versiyadan ko'chirish: o'sha yerda Narxlar → Zaxirani yuklab oling, yangi sayt'da **Zaxiradan tiklash** ni tanlang.
- Kodga o'zgartirish kiritsangiz va `sw.js` dagi `yuk-v1` ni `yuk-v2` ga almashtirsangiz, telefonlar yangilanishni darrov oladi.

## Chop etish ishlamasa
- Chek oynasida har qadam yoziladi (1/4 tanlash, 2/4 ulanish, 3/4 kanal, 4/4 chop etish). Qaysi qadamda to'xtasa, shu yerdan qarab ayting.
- Telefonda **Bluetooth** va **Joylashuv (Location)** yoqilgan bo'lishi kerak.
- Printerni telefonning Bluetooth sozlamasida oldindan ulangan bo'lsa, **Forget** qiling. Printerni o'chirib-yoqing.
- Zaxira usul: Play Market'dan **RawBT** o'rnating, printerni uning ichida tanlang, keyin chek oynasidagi **RawBT orqali chop etish** tugmasini bosing.
