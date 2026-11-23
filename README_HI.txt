Census 2027 – Enumerator (PWA)

इस पैकेज में मौजूदा 40 प्रश्न, परिवार/सदस्य Add-Edit-Delete, IndexedDB Offline Save, DOB Auto-Advance, Full Data Review, JSON Backup/Restore और Android Share वाला Census Manager शामिल है।

INSTALL के लिए इसे HTTPS वेबसाइट पर host करना जरूरी है। ZIP सीधे Android APK नहीं है। ZIP को extract करके पूरे Census_2027_Enumerator_PWA folder की सामग्री static hosting पर deploy करें।

पुराने HTML से डेटा लाना: file:// HTML और HTTPS PWA का browser storage अलग होता है। पुराने HTML में पहले Combined JSON Backup बनाएं। PWA पहली बार खोलकर रीस्टोर से JSON import करें।

Android Install: HTTPS URL Chrome में खोलें, एक बार online पूरा load होने दें, Chrome मेन्यू ⋮ > Install app / Add to Home screen चुनें। पहली बार install और CDN assets cache करने के लिए internet चाहिए। उसके बाद offline खोलकर test करें।

हर दिन Combined JSON Backup लेकर Google Drive में रखें। यह निजी offline सहायक है, सरकारी PE App नहीं है और उससे स्वतः data transfer नहीं करता।
