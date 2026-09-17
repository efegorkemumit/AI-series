# Mini Support Desk — Q1 QA Review Promptu

Şimdi `Q1` task'ını `qa` teammate'e ata ve `In Progress` olarak başlat.

QA Reviewer gerçek Mini Support Desk implementation'ını inceleyecek.

Project-level `code-review` Skill'ini kullanmasını iste.

## Review kapsamı

- Ticket oluşturma
- Ticket listeleme
- Ticket detay yükleme
- Status değiştirme
- Priority değiştirme
- Yorum ekleme
- Dashboard istatistiklerinin doğru güncellenmesi
- TypeScript correctness
- Next.js build ve lint
- Prisma / SQLite tutarlılığı
- UI / Backend contract uyumu
- Input validation
- Error state'ler
- Empty state'ler
- Not-found davranışı
- Server Action ve revalidation davranışı
- MVP kapsamındaki regresyonlar

## Kurallar

- Yeni feature önermesin.
- Auth, ödeme veya kullanıcı rolleri eklemesin.
- Tasarımı baştan yazmasın.
- QA kendi başına implementation kodunu değiştirmesin.
- Önce yalnızca sorunları bulsun ve raporlasın.
- Mümkünse her sorun için ilgili dosyayı ve reproduce adımını versin.
- Emin olmadığı şeyi bug olarak uydurmasın.

## Önem seviyeleri

Sorunları şu önem seviyeleriyle grupla:

- Critical
- High
- Medium
- Low

## Doğrulama

Review sırasında mevcut komutlarla build / lint / runtime doğrulaması yapabiliyorsa yapsın.

Bir kontrol mevcut araçlarla gerçekten doğrulanamıyorsa bunu açıkça belirtsin; geçmiş gibi varsaymasın.

Review tamamlandığında sonucu önce Team Lead'e gönder.

Henüz düzeltme task'larını başlatma.
