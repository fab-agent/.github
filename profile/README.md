# fab-agent / Fabrika Yazılım

**Kurumsal yapay zeka altyapısı üretiyor.**  
İstanbul · [fab.limited](https://fab.limited) · [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)

---

## Kim Biz?

[Fabrika Yazılım Ticaret Limited Şirketi](https://fab.limited), şirketlerin yapay zeka ajanlarını organizasyon şemalarına gerçek anlamda entegre etmelerine yardımcı olmak için kuruldu.

Ajanlar birer araç değil — personel. Departmanları var, yöneticileri var, politikaları var, org şemasında yer alıyorlar.

**Kurucu:** [Kuntay Kunt](https://www.linkedin.com/in/kuntaykunt/) · [x.com/kuntaykunt](https://x.com/kuntaykunt)

---

## Projeler

### [agentic-organization](https://github.com/fab-agent/agentic-organization)

Self-hosted, açık kaynak kurumsal ajan yönetim platformu.

- **AI Onboarding** — Şirketinizi web'de araştırır, soru sorar, dakikalar içinde tam org yapısı oluşturur
- **Çoklu Sağlayıcı** — Anthropic, OpenAI, Google, Mistral, Qwen — model bağımsız
- **Otonom Akışlar** — Cron zamanlamalı ajan görevleri; sonuçlar inbox'a düşer
- **Görev Yönlendirme** — Departman + skill filtreyle en uygun ajana otomatik yönlendirme
- **Ajan Hafızası** — Oturum özetleri uzun dönem hafızaya kaydedilir; bağlam hiç kaybolmaz
- **Token Telemetrisi** — Her mesaj için token tüketimi takibi; dashboard'da canlı görünür
- **Görsel Üretimi** — Qwen Image / DALL-E akışlarda; DashScope task API entegrasyonu
- **Sosyal Medya** — Instagram Business + WhatsApp Cloud API builtin skill olarak
- **Güvenlik** — AES-256 key şifrelemesi, JWT, Alembic migration, Nginx rate limiting

```
Teknoloji: FastAPI · SQLModel · SvelteKit 5 · Tailwind · APScheduler · Docker
```

**Durum:** Aktif geliştirme — v0.9 (Temmuz 2026)  
**Lisans:** MIT — Ticari kullanım, fork ve katkı serbesttir.

---

### Odoo Eklentileri *(yakında)*

Fabrika Yazılım, Odoo ERP ekosistemi için kurumsal eklentiler geliştiriyor.

Planlanan alanlar:
- **MRP 2 / Üretim** — İş emri yönetimi, ürün ağacı (BoM), iş istasyonu takibi
- **Ajan Entegrasyonu** — Odoo iş akışlarında agentic-organization ajanlarını tetikleme
- **Raporlama** — Üretim verimliliği ve maliyet analizi eklentileri

Güncellemeler için [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com) adresine yazabilirsiniz.

---

### İş Geliştirme

Fabrika Yazılım aşağıdaki alanlarda kurumsal danışmanlık ve uygulama hizmetleri sunmaktadır:

| Alan | Kapsam |
|---|---|
| **Agentic Organizasyon Kurulumu** | Şirketiniz için ajan yapısı tasarımı, self-hosted kurulum, ilk akışların tanımlanması |
| **Odoo Entegrasyonu** | Mevcut Odoo kurulumunuza ajan katmanı eklenmesi |
| **Özel Ajan Geliştirme** | İş süreçlerinize özel skill, politika ve otonom akış tasarımı |
| **AI Sağlayıcı Danışmanlığı** | Maliyet-fayda analizi, model seçimi, güvenlik yapılandırması |

**İletişim:** [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)  
**LinkedIn:** [Kuntay Kunt](https://www.linkedin.com/in/kuntaykunt/)  
**X:** [x.com/kuntaykunt](https://x.com/kuntaykunt)

---

## Tasarım Felsefesi

**İnsan denetimi, insan darboğazı değil.** Ajanlar otonom çalışır; ancak yapılandırma değişiklikleri, görev onayları ve kritik eylemler her zaman bir insanın onayından geçer.

**Self-hosted önce.** Verileriniz, anahtarlarınız ve ajan yapılandırmalarınız kendi altyapınızda kalır. SaaS bağımlılığı yok.

**Org-native.** Ajanlar bir araç değil, personel. Departmanlara bağlı, yöneticileri olan, politika taşıyan ve org şemasında görünen varlıklar.

---

<sub>© 2026 Fabrika Yazılım Ticaret Limited Şirketi · İstanbul · [fab.limited](https://fab.limited) · [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)</sub>
