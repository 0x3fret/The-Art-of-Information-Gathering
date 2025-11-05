# Information Gathering in Penetration Testing / جمع المعلومات في اختبارات الاختراق

*A concise guide to passive and active reconnaissance — دليل موجز للاستطلاع السلبي والفعّال*

---

## English Summary (Full Book Summary)

**What is Information Gathering?**
Information gathering (reconnaissance) is the first and one of the most critical phases in penetration testing. It consists of collecting data about a target organization, system, network, or application. The goal is to build an accurate intelligence picture that guides later testing — the more reliable and comprehensive the recon, the higher the chance of discovering meaningful security issues.

**Types of Reconnaissance**

* **Passive Reconnaissance:** Collecting information without directly interacting with the target. Sources include public websites, WHOIS records, DNS data, social media, job postings, public code repositories, and third-party services. Passive recon minimizes detection risk and helps form hypotheses.
* **Active Reconnaissance:** Direct interaction with the target to gather detailed technical information (open ports, services, versions, banners, application responses). Active recon yields precise data but increases the chance of detection and potential operational impact — so it must be authorized and carefully planned.

**Objectives of Information Gathering**

1. **Define target scope:** Accurately identify in-scope assets and out-of-scope items to remain within legal and engagement boundaries.
2. **Reveal information-level weaknesses:** Find exposed data, misconfigurations, or public footprints that could enable further exploitation (without performing attacks).
3. **Prepare a prioritized testing plan:** Rank targets by risk and likely impact to focus later active testing on the most valuable or vulnerable areas.
4. **Reduce surprises during testing:** Anticipate obstacles (WAFs, IDS, rate limits, maintenance windows) to avoid disrupting services or triggering defenses unexpectedly.

**Recommended Mental Workflow / Phases**

1. Define scope and rules of engagement.
2. Collect high-level data: domains, IP ranges, vendor relationships.
3. Analyze public sources (OSINT): websites, social profiles, job ads, press releases.
4. Correlate findings into a recon map showing public-facing services and personnel.
5. Assess and prioritize findings by exploitability and business impact.
6. Document results, note evidence and confidence levels, and prepare a preliminary testing plan.

**Why this matters**
Effective information gathering turns scattered public data into prioritized, testable leads. It saves time during penetration tests, reduces operational risk, and increases the ethical tester’s ability to discover real weaknesses without causing harm.

---

## الملخّص العربي (ملخّص كامل للكتاب)

**ما هو جمع المعلومات؟**
جمع المعلومات أو الاستطلاع هو المرحلة الأولى والأهم في اختبارات الاختراق. تتضمن جمع بيانات عن الهدف—شركة، موقع إلكتروني، نظام أو شبكة—لبناء صورة مخابراتية دقيقة تُوجّه الاختبارات اللاحقة. كلما كانت المعلومات أوسع وأكثر دقة زادت فرص اكتشاف نقاط ضعف ذات قيمة.

**أنواع الاستطلاع**

* **الاستطلاع السلبي:** جمع معلومات من مصادر عامة دون التفاعل المباشر مع الهدف. تشمل المصادر مواقع الويب العامة، سجلات WHOIS وDNS، وسائل التواصل الاجتماعي، إعلانات التوظيف، المستودعات العامة، وخدمات الطرف الثالث. يقلل الاستطلاع السلبي من احتمالية الكشف ويساعد في تكوين فرضيات أولية.
* **الاستطلاع الفعّال:** تفاعل مباشر مع الهدف للحصول على معلومات فنية دقيقة (منافذ مفتوحة، خدمات، إصدارات، بانرات، استجابات التطبيقات). يعطي الاستطلاع الفعّال بيانات دقيقة لكنه يزيد من احتمال الكشف وتأثيره التشغيلي—لذلك يجب تنفيذه بتصريح وخطة واضحة.

**أهداف جمع المعلومات**

1. **تحديد نطاق الهدف:** التعرف بدقة على الأصول المشمولة بالاختبار وتلك المستثناة، لتجنب الانتهاكات القانونية أو التشغيلية.
2. **كشف نقاط ضعف على مستوى المعلومات:** إيجاد بيانات مكشوفة أو إعدادات خاطئة أو آثار عامة قد تُمكّن مهاجماً لاحقاً دون تنفيذ هجوم فعلي.
3. **إعداد خطة اختبار حسب الأولوية:** ترتيب الأهداف وفق المخاطر والأثر المحتمل للتركيز على أكثر المناطق أهمية في الاختبارات النشطة.
4. **تقليل المفاجآت أثناء الاختبار:** توقع عقبات مثل جدران الحماية وأنظمة الكشف وحدود السرعة أو أوقات الصيانة لتجنب تعطيل الخدمات.

**خطوات العمل المقترحة**

1. تحديد النطاق وقواعد الاشتباك.
2. جمع بيانات على مستوى عالٍ: الدومينات، نطاقات IP، علاقات المزودين.
3. تحليل المصادر العامة (OSINT): المواقع، الملفات الشخصية، إعلانات الوظائف، البيانات الصحفية.
4. بناء خريطة استطلاع تربط الخدمات العامة بالأشخاص والجهات المعنية.
5. تقييم وترتيب النتائج حسب قابلية الاستغلال والأثر على العمل.
6. توثيق النتائج، مع دلائل ومستويات ثقة، وإعداد خطة اختبار تمهيدية.

**لماذا هذا مهم؟**
تحويل المعلومات العامة المبعثرة إلى أدلة قابلة للاختبار يوفر الوقت ويقلل مخاطر التشغيل ويزيد فرص اكتشاف نقاط ضعف حقيقية بطريقة قانونية وأخلاقية.

---

## How to use this README / كيفية استخدام هذا الملف

* Place the English and Arabic summaries at the start of your repository or book.
* Use the summaries as the `README.md` content for distribution, marketing, or as a quick reference.

## License / الترخيص

© 2025 Rashid Al-Tayyar - Ox 3fret. Adjust license in `LICENSE` file as needed.

---

*If you want me to include additional sections (e.g., chapter excerpts, templates, sample recon checklist, or a license file), tell me and I will add them.*
