# Git & GitHub Workflow Öğrenme Projesi

Bu depo, Git ve GitHub üzerinde kurumsal bir yazılım geliştirme ekibinin günlük iş akışını uygulamalı olarak öğrenmek amacıyla oluşturulmuştur.

## Bu Depoda Neler Uygulandı

- **Feature Branch Workflow:** Her değişiklik için ayrı branch açma (`feature/...`), geliştirme ve birleştirme
- **Pull Request Süreci:** GitHub üzerinden gerçek Pull Request'ler açma, açıklama yazma
- **Code Review:** Satır bazlı yorum bırakma, "Start a review" ve "Submit review" akışını kullanma
- **Merge Conflict Çözümü:** İki branch'in aynı satırı farklı şekilde değiştirmesiyle oluşan gerçek bir çakışmayı hem GitHub web arayüzünde hem de terminalde çözme
- **Branch Yönetimi:** İşi biten branch'leri hem local'den hem remote'tan temizleme (`git branch -d`, `git push origin --delete`)

## Öğrenilen Komutlar

```bash
git checkout -b feature/ornek
git add .
git commit -m "..."
git push -u origin feature/ornek
git merge main
git rebase main
git branch -d feature/ornek
```

## Amaç

Bu depo bir üretim projesi değil, Git'in temel ve orta seviye özelliklerini gerçek senaryolarla (dahil olmak üzere karşılaşılan hatalar ve çözümleri) deneyimlemek için kullanılan bir öğrenme alanıdır.
