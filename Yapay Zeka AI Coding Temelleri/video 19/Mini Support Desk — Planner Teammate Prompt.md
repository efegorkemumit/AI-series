Mini Support Desk projesi için yalnızca **implementation plan** hazırla.

## Project

**Mini Support Desk**

### Stack

- Next.js
- TypeScript
- Tailwind CSS
- Prisma
- SQLite

### MVP

- Dashboard
- Ticket listesi
- Yeni ticket oluşturma
- Ticket detay
- Priority: `Low` / `Medium` / `High`
- Status: `Open` / `In Progress` / `Closed`
- Ticket yorumları
- Basit istatistikler

### Scope boundaries

Projede:

- Auth yok
- Ödeme yok
- Kullanıcı rolleri yok
- Microservice yok
- Ayrı backend servisi yok
- Gereksiz enterprise mimari yok

MVP dışına çıkma ve gelecekte lazım olabilir düşüncesiyle ekstra özellik ekleme.

## Your task

1. Önce mevcut proje yapısını incele.
2. Projeyi küçük, uygulanabilir ve net görevlere böl.
3. İşleri şu kategoriler altında grupla:
   - Foundation
   - UI
   - Backend
   - QA
4. Her görev için en uygun teammate'i **önerilen owner** olarak belirt:
   - `planner`
   - `ui-designer`
   - `backend-developer`
   - `qa-reviewer`
5. Görevler arasındaki dependency'leri açıkça belirt.
6. Birbirinden bağımsız ve güvenli şekilde paralel yapılabilecek işleri özellikle göster.
7. Geliştirmeden önce tamamlanması gereken Foundation işlerini belirle.
8. UI ve Backend arasında gerekiyorsa veri contract/handoff noktalarını belirt.
9. Her görevi mümkün olduğunca küçük tut; gereksiz abstraction veya mimari katman ekleme.
10. MVP dışına çıkma.

## Important constraints

Bu aşamada **yalnızca planlama yap**.

- Hiçbir proje dosyası oluşturma.
- Hiçbir proje dosyasını değiştirme.
- Kod yazma.
- Prisma migration oluşturma veya çalıştırma.
- Package kurma.
- Build/test/dev server çalıştırma.
- Diğer teammate'lere henüz görev dağıtma veya implementation başlatma.
- Shared task list'e implementation task atama.
- UI veya Backend geliştirmesine başlama.

Agent isimlerini yalnızca plan içindeki **önerilen owner** olarak kullan.

Plan tamamlandığında dur ve önce bana raporla.

## Required output

### Project Phases

Projenin uygulanma aşamalarını sırala.

### Tasks

Her görev için:

- Task ID
- Phase
- Task
- Kısa açıklama
- Done when

### Owner

Her Task ID için önerilen teammate'i belirt.

### Dependencies

Her görevin hangi görevlere bağlı olduğunu belirt.

Bağımsız görevlerde `None` yaz.

### Parallel Work

Aynı anda güvenli şekilde yapılabilecek görev gruplarını açıkça belirt.

Dosya çakışması veya data-contract riski varsa bunu da belirt.

### Recommended Execution Order

Foundation'dan başlayarak önerilen çalışma sırasını yaz.

Planın sonunda:

**STOP — Waiting for approval before assigning implementation work.**

yaz ve başka işlem yapma.