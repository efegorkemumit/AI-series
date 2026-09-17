# Mini Support Desk — Claude Code Skills Hazırlama Promptu

Aşağıdaki iki hazır Claude Code Skill dosyasını GitHub üzerinden açıp incele:

## Hazır Skill Kaynakları

### Frontend Design

https://github.com/anthropics/claude-plugins-official/blob/main/plugins/frontend-design/skills/frontend-design/SKILL.md

### Code Review

https://github.com/anthropics/knowledge-work-plugins/blob/main/engineering/skills/code-review/SKILL.md

Ayrıca **Mini Support Desk** projem için sıfırdan üçüncü bir Skill oluştur:

- `ticket-feature`

---

## Proje

### Stack

- Next.js
- TypeScript
- Tailwind CSS
- Prisma
- SQLite

### MVP

- Dashboard
- Ticket listesi
- Yeni ticket
- Ticket detay
- Priority: `Low / Medium / High`
- Status: `Open / In Progress / Closed`
- Ticket yorumları
- Basit istatistikler

Projede **auth, ödeme, kullanıcı rolleri, microservice veya gereksiz enterprise yapı yok.**

---

## 1. `frontend-design`

Hazır Skill'in ana tasarım prensiplerini koru fakat **Mini Support Desk** projesine göre düzenle.

- Next.js + TypeScript + Tailwind odaklı olsun.
- Dashboard ve support uygulamalarına uygun olsun.
- Responsive ve accessible UI prensiplerini korusun.
- Bilgi hiyerarşisi ve kullanılabilirliği önceliklendirsin.
- Generic AI/SaaS görünümünden kaçınsın.
- Gereksiz hero, landing page ve aşırı animasyon yaklaşımını sadeleştir.
- Backend, Prisma veya database sorumluluğu üstlenmesin.

---

## 2. `code-review`

Hazır Skill'in yararlı code review yaklaşımını koru fakat **Mini Support Desk** projesine göre düzenle.

Özellikle şu konuları kontrol etsin:

- TypeScript
- Next.js
- Prisma
- SQLite
- Ticket CRUD
- Status
- Priority
- Comments
- Input validation
- Error handling
- Empty states
- Build
- Lint
- Maintainability

Aşağıdaki gereksiz zorunlulukları kaldır:

- PR zorunlulukları
- Connector bağımlılıkları
- Project tracker akışları
- Auth / role kontrolleri
- Enterprise workflow'ları

---

## 3. `ticket-feature`

Bu Skill'i **sıfırdan oluştur**.

### Amaç

Ticket sistemiyle ilgili yeni bir özellik veya değişiklik istendiğinde hemen kodlamaya başlamadan önce değişikliğin bütün etkisini analiz etmek.

### Workflow

1. Requirement'ı netleştir.
2. Mevcut davranışı kontrol et.
3. Prisma / data model etkisini belirle.
4. Backend / API etkisini belirle.
5. UI / component etkisini belirle.
6. Validation ve error state etkisini belirle.
7. Mevcut verilere etkisini düşün.
8. QA senaryolarını çıkar.
9. Hangi agent'ın hangi işi yapacağını belirle.
10. Dependency'leri ve paralel yapılabilecek işleri belirle.

### Kurallar

- Auth önermesin.
- Ödeme sistemi önermesin.
- Kullanıcı rolleri eklemesin.
- Microservice önermesin.
- Basit değişiklikleri gereksiz yere büyütmesin.
- Sadece gerçekten etkilenen katmanları plana dahil etsin.
- Planner, UI Designer, Backend Developer ve QA Reviewer görev sınırlarına saygı göstersin.
- Kodlamadan önce kısa bir implementation impact planı oluştursun.

---

## Genel Kurallar

- Üç Skill de geçerli Claude Code `SKILL.md` formatında olsun.
- `name` ve `description` alanlarını doğru oluştur.
- Hayali veya desteklenmeyen frontmatter alanları ekleme.
- Hazır iki Skill'in mevcut kaynak/lisans attribution bilgisini kaldırma.
- Açıklamayı kısa tut.
- Proje kapsamını gereksiz yere büyütme.

---

## İstenen Çıktı

Sonuçta bana **üç ayrı indirilebilir dosya** oluştur:

1. `frontend-design/SKILL.md`
2. `code-review/SKILL.md`
3. `ticket-feature/SKILL.md`

Dosyalar doğrudan şu konumlara koyulabilecek durumda olsun:

```text
.claude/skills/frontend-design/SKILL.md
.claude/skills/code-review/SKILL.md
.claude/skills/ticket-feature/SKILL.md
```
