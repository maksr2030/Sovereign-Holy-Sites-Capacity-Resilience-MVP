# Sovereign Holy Sites Capacity & Resilience Intelligence Platform™
## Operational MVP | النسخة التشغيلية التجريبية

منصة ذكاء قرار سيادي مخصصة لإدارة السعة والمرونة التشغيلية في المشاعر المقدسة. يقدّم هذا المستودع نسخة عرض تشغيلية عامة توضح بصورة تفاعلية كيفية احتساب السعة الآمنة الديناميكية، تحديد القيد التشغيلي الحاكم، اختبار السيناريوهات، قياس هامش السعة المتبقي، وإنتاج سجل أدلة للقرار.

هذه النسخة العامة تستخدم بيانات محاكاة فقط لأغراض العرض، ولا تمثل بيانات ميدانية أو حدوداً تشغيلية أو نظامية معتمدة. كما أنها لا تنشر كامل السجل الهندسي للمنصة أو جميع الخوارزميات ونماذج التدريب أو تفاصيل الملكية الفكرية المحمية.

Public operational demonstration of a sovereign decision-intelligence platform for Holy Sites capacity and resilience management. The MVP demonstrates dynamic safe-capacity computation, governing-constraint identification, operational scenario testing, residual capacity assessment, and evidence-backed decision logging.

All values shown in the public MVP are simulated for demonstration purposes. They do not represent field measurements, approved operating limits, or statutory values. The complete 220-feature engineering register, proprietary algorithms, training models, and protected implementation details are intentionally excluded from this public repository.

## Public Operational Demo
https://holy-sites-capacity-resilience-qb9avqfw7.vercel.app

## Repository and Deployment Architecture

**GitHub is the public source-of-truth and development-history record for this MVP.**

**Vercel is the public deployment layer.** The repository is structured for direct Vercel Git integration so approved changes to the `main` branch can be deployed through Vercel after repository connection is enabled in the Vercel project.

The repository includes an automated validation workflow that verifies required files, JavaScript syntax, Vercel configuration, and core operational wiring on every push or pull request to `main`.

## Operational capabilities demonstrated
- Dynamic safe-capacity computation across multiple constraints
- Governing-constraint identification
- Pedestrian-flow, egress, utilities, thermal and medical-response constraints
- Asset reliability, emergency readiness and data-confidence factors
- Current occupancy and residual-capacity margin
- Decision states: ALLOW, REVIEW, CONSTRAIN, BLOCK, ABSTAIN
- Interactive operating scenarios
- Decision Evidence Record with SHA-256 input and trace hashes
- Arabic and English interfaces
- Downloadable evidence record

## Public Repository Boundary

This repository is intentionally selective. It demonstrates the operating concept without publishing the full engineering specification, the complete 220-feature register, proprietary algorithm implementations, training-model internals, protected configuration, or trade-secret material.

## Intellectual Property
All rights reserved to Eng. Mohamed A. S. Rihan.

This repository is a selective public demonstration and does not transfer, license, disclose, or waive rights in the underlying platform architecture, algorithms, models, engineering specifications, trade secrets, or associated intellectual property.
