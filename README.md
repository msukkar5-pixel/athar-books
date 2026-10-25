# مكتبة أثر — Athar books

الكتب اللي تطبيق **أثر** بيعرضها في «المكتبة». الريبو ده فيه بس الكتب، ومفيهوش كود التطبيق.

- `tools/books.json`: قائمة الكتب ومصدر كل كتاب.
- `tools/books.py` و`tools/openiti.py`: بيحوّلوا كل كتاب لملف `zip`، وجواه `index.json` و`vNN.json`.
- كل ما `books.json` يتغير، GitHub Actions بيبني الكتب من جديد وبينشرها في إصدار **books**. ومن هناك التطبيق بيحمّلها.

## المصادر والتراخيص
| المصدر | الكتب | الترخيص |
|---|---|---|
| [OpenITI](https://openiti.org) (نصوص المكتبة الشاملة) | كتب التراث (التفسير، والحديث، والسيرة، والتاريخ، والأدب، والمعاجم…) | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |
| [ويكيبيديا العربية](https://ar.wikipedia.org) | مقالات تاريخ البلاد العربية | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [مؤسسة هنداوي](https://www.hindawi.org) | كتب مؤلفين توفوا من أكتر من 50 سنة (سليم حسن، وجرجي زيدان، وعبد الرحمن الرافعي) | ملكية عامة، ومنشورة مجانًا على هنداوي |

كل ملف بيفضل نسبه لمصدره، والتطبيق بيعرض المصدر جنب كل كتاب. والتطبيق مجاني ومن غير إعلانات.
لو إنت صاحب حق في نص هنا وعايزه يتشال، افتح Issue أو ابعت لـ mohammed.sokar@icloud.com.

---

Book files used by the **Athar** app's in-app library (no app code here). Texts come from OpenITI (CC BY-NC-SA 4.0), Arabic Wikipedia (CC BY-SA 4.0) and public-domain titles published by the Hindawi Foundation. Each book keeps its source attribution. Rights holders can request removal via an issue or mohammed.sokar@icloud.com.
