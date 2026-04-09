Baktım. Net değerlendirmem şu:

Şu an profilin artık “sadece frontend öğrenci profili” değil; “web development temelinden cybersecurity’ye dönen, dokümantasyon ve güvenlik kontrolleri düşünen aday” profiline dönmeye başlamış. En büyük sıçrama da secure-auth-admin-demo ile olmuş. Repositories sekmesinde şu an secure-auth-admin-demo, ValerPay, cntzemir.github.io, e-bike-rental-demo, javascript-exchange, javascript-calculator ve profil README reposu görünüyor; bio kısmın da artık “web development to cybersecurity through secure systems, Linux labs, and technical documentation” diye konumlanıyor.

Genel izlenim

Güçlü tarafın şu: profilinde “dokümantasyon”, “clean structure”, “predictable behavior”, “validation”, “audit”, “RBAC”, “threat model” gibi işe yarar mühendislik sinyalleri var. Profil README’ında “fewer projects with stronger engineering signals: docs, tests, CI, and clear demos” diyorsun; bu iyi bir yaklaşım ve admissions açısından da olgun duruyor. Aynı README’de ValerPay’i ledger-based workflow, role-based access, audit logs ve docs üzerinden anlatman da değerli.

Zayıf tarafın şu: portföy siten hâlâ ağırlıklı olarak “web development / intern-junior” kimliği taşıyor. Ana sayfada “Computer Science • Web Development • Security-minded” yazıyor, hedef kısmında da “Join a team as an intern / junior” diyorsun; featured projects bölümünde ise şu an yalnızca calculator, currency exchange ve Renters.hu var. Bu, GitHub’daki yeni cyber yönüyle tam senkron değil.

Repo repo analiz
1) secure-auth-admin-demo

Bu şu an en güçlü repo ve başvuruda en öne koyman gereken çalışma. README açık biçimde session-based authentication, RBAC, audit logging, CSRF protection, rate limiting, temporary account lockout, generic auth errors, suspicious-pattern review ve threat model anlatıyor. Ayrıca architecture summary, documentation links, screenshots, known limitations ve local run akışı da var. Bu repo “login/register CRUD yaptım” değil, gerçekten “defensive software engineering demo” gibi sunulmuş.

Bunu nasıl sunmalısın:
“Ben cyber’a sıfırdan soyut ilgiyle gelmiyorum; auth, authorization, abuse reduction, audit visibility ve admin monitoring içeren küçük ama bilinçli sistemler kuruyorum.”
Bu repo için en doğru etiket zihinde şu: security reasoning > UI.

Eksik tarafı: repo adı ve README güçlü; ama bunu portföyde ve profil overview’da daha görünür hale getirmen lazım. Şu an GitHub’da var, ama portföy ana vitrinde aynı güçte görünmüyor.

2) ValerPay

Bu ikinci en güçlü repo. README’de append-only ledger mantığı, immutable DEBIT/CREDIT lines, derived balance, admin approval workflow, seeded demo accounts, API/UI ayrımı, docs klasörü, tests ve CI sinyali var. Bu, öğrenci düzeyinde oldukça iyi bir “domain + workflow + auditability” örneği. Özellikle mutable balance yerine ledger yaklaşımını anlatman, sıradan demo düzeyinin üstüne çıkarıyor.

Bunu nasıl sunmalısın:
“ValerPay benim en olgun full-stack çalışmam; payment workflow, state transitions, admin review, traceability ve balance integrity mantığını gösteriyor.”
Yani bunu “payment app yaptım” diye değil, workflow integrity + audit-friendly design diye anlat.

Riskli tarafı: admissions tarafında bunu yanlış sunarsan “fintech hevesi var, cyber değil” gibi okunabilir. O yüzden cyber başvuruda ValerPay’in öne çıkacak kısmı:

role separation
JWT/auth
admin approvals
auditability
ledger integrity
olmalı; “cool payment app” tarafı değil.
3) javascript-exchange

Bu repo daha junior seviyede ama kötü değil. README’de wallet balances, base-currency model, single conversion function, validation, predictable invalid-action behavior ve inline error feedback anlatılıyor. Ayrıca “progression from early prototypes to a more production-minded approach” diye çerçeveliyorsun; bu da doğru.

Bunu nasıl sunmalısın:
“Bu proje frontend süsü değil; validation, state clarity ve maintainability pratiği.”
Admissions’ta bunu ana vitrin değil, foundation repo olarak kullan.

4) e-bike-rental-demo

Bu repo da temelde UI + user flow + repo hygiene göstergesi. README’de responsive UI, login → dashboard → rent request flow, in-memory auth/state, modal-based request ve code hygiene/structure açıkça yazılmış. “What a reviewer can verify quickly” kısmı da iyi düşünülmüş.

Bunu nasıl sunmalısın:
“Ben uçan kaçan şeylerden önce kullanıcı akışı, yapı ve gözden geçirilebilir demo üretebiliyorum.”
Yani yine foundation repo.

5) javascript-calculator

Bu repo en zayıf değil ama en aşağıda durması gereken repo. Çünkü basit bir öğrenme projesi; README’de de bunu dürüstçe “when I first started learning JavaScript — later refactored” diye söylüyorsun. Yine de validation, keyboard support, divide-by-zero handling, formatting limits ve clean structure göstermesi nedeniyle tamamen çöpe atılacak repo değil.

Bunu nasıl sunmalısın:
“Small project, but shows refactoring discipline and defensive edge-case handling.”
Ana repo değil, destekleyici repo.

6) cntzemir.github.io

Portföy siten hızlı, responsive ve reviewer-friendly diye sunuluyor; README’de bunu açıkça böyle anlatıyorsun. Sitede de README, setup steps, features ve “easy to evaluate” mantığı vurgulanıyor. Bu güzel. Ama şu an featured kısmı senin bugünkü en güçlü kimliğini tam taşımıyor. Hâlâ eski üç demo ağırlıklı.

Bunu nasıl düzeltmelisin:

featured project #1: secure-auth-admin-demo
featured project #2: ValerPay
featured project #3: javascript-exchange veya linux-hardening-lab (yaparsan)
calculator en alta insin
e-bike demo yardımcı repo gibi kalsın
Howest için seni nasıl sunmalıyız?

Senin dosyanın doğru anlatısı şu:

“I started from practical web development, then became increasingly interested in secure systems, authentication, authorization, validation, logging, and defensive design. My portfolio reflects that transition: from UI and flow demos to security-aware projects with audit logging, RBAC, threat modeling, and documentation.”

Bu anlatıyı destekleyen gerçek kanıtların var:

profil bio’da cyber transition vurgusu var,
secure-auth repo’da auth + RBAC + CSRF + rate limiting + lockout + threat model var,
ValerPay’de ledger/audit/workflow integrity mantığı var,
eski projelerde de validation + predictable behavior + refactor çizgisi var.

Yani seni “cybersecurity expert” diye sunmayacağız.
Doğru framing:

“secure-software-minded CS student transitioning into cybersecurity.”

Bu çok daha inandırıcı ve güçlü.

Profilde şu an en iyi çalışan şeyler

Bir admissions officer veya reviewer senin GitHub’ına girince şu şeyler olumlu çalışıyor:

boş profil değil; bio, README, pinned work ve docs kültürü var.
repo açıklamaları kısa ama ne gösterdiğini anlatıyor.
birden fazla repoda docs, CHANGELOG, screenshots ve live demo mantığı var.
secure-auth repo küçük olmasına rağmen en profesyonel repo hissini veriyor.
Şu an en çok zarar veren şeyler

En büyük üç problem şunlar:

Birincisi, portfolio ile GitHub aynı hikâyeyi anlatmıyor. GitHub cyber’a dönmüş, portföy hâlâ web intern/junior vitrini gibi.

İkincisi, repo hiyerarşin başvuru amacına göre sert değil. Secure-auth ve ValerPay açık ara en önemli iki çalışma; bunun her yerde görünmesi lazım. Şu an sadece GitHub tarafında belirgin. Portföyde aynı netlik yok.

Üçüncüsü, headline’larında bazen internship odaklı, bazen cyber transition odaklı, bazen full-stack odaklı konuşuyorsun. Hepsi doğru parçalar ama tek mesaj şu olmalı:
“CS student in Budapest transitioning from practical web development to cybersecurity through secure systems and documented projects.”
Şu an repos tab bio’su buna yakın; bunu her yere aynı şekilde taşıman lazım.

Sana önerdiğim nihai sunum sırası

Howest / admissions / CV / GitHub / portfolio hepsinde bu sıra çalışsın:

Secure Auth & Admin Panel Demo
Bunu “security-focused auth, RBAC, audit logging, CSRF, rate limiting, lockout” diye koy.
ValerPay
Bunu “ledger-based balances, admin workflow, audit-friendly payment logic” diye koy.
JavaScript Exchange
Bunu “validation, predictable behavior, refactoring discipline” diye koy.
E-Bike Rental Demo
Bunu “end-to-end UI flow and repo hygiene” diye koy.
JavaScript Calculator
Bunu “small but well-refactored fundamentals project” diye koy.
Portföy ana sayfasında nasıl görünmeli?

Şu an girişte “Building clean, usable web apps” dili var. Bu kötü değil ama cyber başvuru için biraz dar. Daha iyi yön şu olur:

“Building secure, reviewable software projects — from practical web apps to security-aware systems.”

Ve featured projects kısmında:

Secure Auth Demo
ValerPay
One validation/refactor project

olmalı. Çünkü şu an featured bölüm sadece UI ağırlıklı üç demo gösteriyor.

GitHub README nasıl konumlanmalı?

README’nin en doğru kimliği şu:

1 satır: kim olduğunu söyle
1 satır: geçiş anlatısı
2 flagship repo
engineering habits
learning focus
contact

Ama “Target roles: Frontend / Full-stack Intern” gibi eski cümleler artık olmamalı. İlk baktığım overview’da bu vardı; yeni repos bio’su ise cyber transition çizgisine geçmiş. Yani doğru yoldasın, bunu tam konsolide etmen gerekiyor.

Kısa sonuç

Bugünkü en doğru teşhis:

Artık elinde başvuruda gerçekten kullanılabilecek iki ciddi repo var: secure-auth-admin-demo ve ValerPay.
Diğer projeler ise “temel oluşturucu, refactor ve validation disiplini” kanıtı olarak destekleyici rol oynuyor. Bu çok iyi bir kurgu olabilir — ama yalnızca hepsini tek hikâye altında toplarsan.

Bir sonraki adımda sana direkt kopyala-yapıştır kullanmalık şu üç şeyi çıkarayım:

yeni GitHub profile README metni
portföy ana sayfa metni
her repo için 1–2 satırlık profesyonel açıklama paketi
