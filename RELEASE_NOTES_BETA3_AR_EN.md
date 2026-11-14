# ProTech Quotes & Contracts — v2.0.0-beta.3 (Customer RC3)

**الحالة: Beta / نسخة تجريبية تحت الاختبار، وليست إصدارًا نهائيًا معتمدًا.**

## الميزات الجديدة
- بيانات العميل: اسم العميل (إلزامي)، رقم الجوال مع تطبيع الصيغ السعودية المحلية والدولية، والعنوان الأساسي (إلزامي).
- إضافة العملاء وتعديلهم، وعرض بياناتهم في الجدول والبحث وملف العميل.
- الحفاظ على سجلات المستندات الصادرة بصيغة لقطات ثابتة (immutable snapshots).
- بناء نظيف دون 41 مكتبة Runtime مأخوذة سابقًا من Microsoft JDK، مع استبعاد Qt Virtual Keyboard ذي ترخيص GPL-only.

## الاختبارات المسجلة 2026-11-14
- Python full regression: 212/212 PASS.
- Frozen EXE synthetic QA: 14/14 PASS.
- RC3 clean install and same-version upgrade: 14/14 PASS each.
- اختبارات التثبيت والترقية والإزالة حفظت النسخة السابقة والبيانات التجريبية.
- فحوص قواعد البيانات الأصلية كانت للقراءة فقط، دون تغيير البيانات.

## المخاطر والقيود
- ملف Setup.exe والبرنامج الداخلي غير موقّعين (NotSigned). قد يظهر تحذير Windows SmartScreen أو Unknown Publisher.
- لم تُستكمل مراجعة مستقلة نهائية لالتزامات Qt LGPL وتراخيص وإشعارات المكتبات المضمنة. الإشعارات مبدئية ولا تمثل شهادة امتثال مكتملة.
- تقرير Stage 11 المحلي يحدد القرار: HOLD — NOT A SIGNED FINAL RELEASE.
- لا تدل نتائج QA على صلاحية تجارية نهائية أو خلو الإصدار من جميع العيوب.
- احفظ نسخة احتياطية من المشاريع والبيانات قبل تجربة الإصدار.

## التحقق من الملف
Setup.exe — 57,879,493 bytes.
SHA256: E8A36B4823A656FEA16C5DFF9FE57B24EED6575ED48F153C0B5A658DE4B8E722.

### English summary
Customer RC3 adds required customer name, Saudi mobile normalization, required address, create/edit/search/customer dossier and immutable issued-document snapshots. The reported Python suite (212/212), EXE QA (14/14), clean install and same-version upgrade (14/14 each) passed.

**Unsigned QA prerelease only.** No trusted code-signing certificate is present. Independent Qt LGPL and other third-party redistribution compliance review is unfinished; final release gate remains on HOLD. Do not assume SmartScreen-free installation, complete legal signoff, or production certification. Back up important data.

Copyright (c) 2026 ProTech. All Rights Reserved for original ProTech materials; third-party license rights remain intact.
