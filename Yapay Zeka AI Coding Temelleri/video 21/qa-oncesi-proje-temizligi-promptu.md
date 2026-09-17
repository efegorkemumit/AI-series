# Mini Support Desk — QA Öncesi Proje Temizliği Promptu

QA başlamadan önce küçük bir proje temizliği yap.

Backend teammate'in daha önce yanlışlıkla oluşturduğu şu kapsam dışı klasörleri kontrol et:

- `.agents/skills/prisma-*`
- `.windsurf/skills/prisma-*`
- `.claude/skills/prisma-*`

Bunlar Mini Support Desk planının parçası değilse ve uygulama tarafından kullanılmıyorsa kaldır.

Şu dosya ve klasörlere **kesinlikle dokunma**:

- `prisma/`
- `lib/prisma.ts`
- `.env`
- `.claude/skills/frontend-design/`
- `.claude/skills/code-review/`
- `.claude/skills/ticket-feature/`

Başka hiçbir implementation dosyasını değiştirme.

Temizlik bittikten sonra sadece ne kaldırdığını kısa şekilde bildir.

Henüz `Q1` task'ını başlatma.
