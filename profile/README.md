# fab-agent / Fabrika Yazılım

**Building the infrastructure for agentic enterprises.**
Istanbul · [fab.engineering](https://fab.engineering) · [infab.cloud](https://infab.cloud) · [fab.limited](https://fab.limited) · [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)

---

## Who We Are

[Fabrika Yazılım Ticaret Limited Şirketi](https://fab.limited) (operating as **fab.engineering**) was founded to help companies genuinely integrate AI agents into their organizational charts — not bolt them on as a side tool.

Agents aren't tools — they're personnel. They belong to departments, report to managers, follow policies, and show up on the org chart.

**Founder:** [Kuntay Kunt](https://www.linkedin.com/in/kuntaykunt/) · [x.com/kuntaykunt](https://x.com/kuntaykunt)

---

## Products & Projects

### [agentic-organization](https://github.com/fab-agent/agentic-organization) — [agent.fab.engineering](https://agent.fab.engineering)

Self-hosted, open-source enterprise agent management platform.

- **AI Onboarding** — researches your company on the web, asks clarifying questions, and builds a complete org structure in minutes
- **Multi-Provider** — Anthropic, OpenAI, Google, Mistral, Qwen — model-agnostic by design
- **Autonomous Flows** — cron-scheduled agent tasks; results land in an inbox
- **Task Routing** — automatic routing to the best-fit agent by department + skill filter
- **Agent Memory** — session summaries persist to long-term memory; context is never lost
- **Token Telemetry** — per-message token consumption tracked live on the dashboard
- **Image Generation** — Qwen Image / DALL-E built into flows; DashScope task API integration
- **Social Media** — Instagram Business + WhatsApp Cloud API as built-in skills
- **Security** — AES-256 key encryption, JWT, Alembic migrations, Nginx rate limiting

```
Stack: FastAPI · SQLModel · SvelteKit 5 · Tailwind · APScheduler · Docker
```

**Status:** Active development — v0.9 (July 2026)
**License:** MIT — free for commercial use, forking, and contribution.

---

### [infab.cloud](https://infab.cloud)

The on-prem / installable production tracking platform for order-driven, multi-operation manufacturers.

- **Dynamic recipe + actual cost engine** — real-time cost tracking against live production data
- **ERP integration layer** — Netsis, Odoo, Logo, Paraşüt
- **Air-gap compatible** — designed to run fully on-premise, no cloud dependency required
- **Enterprise-grade engineering** — 100% test coverage gate, CI + AI code review on every PR, self-hosted error tracking and audit logging

```
Stack: Next.js 15 · FastAPI (Python 3.12) · PostgreSQL 16 · Keycloak · MinIO · Docker Compose
```

**Status:** Active development — private repository, source ships only as packaged installers.

---

### Odoo Plugins *(coming soon)*

Fabrika Yazılım is building enterprise plugins for the Odoo ERP ecosystem.

Planned areas:
- **MRP 2 / Manufacturing** — work order management, Bill of Materials (BoM), work center tracking
- **Agent Integration** — triggering agentic-organization agents from Odoo workflows
- **Reporting** — production efficiency and cost analysis plugins

For updates, reach out at [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com).

---

### Professional Services

Fabrika Yazılım offers enterprise consulting and implementation services in the following areas:

| Area | Scope |
|---|---|
| **Agentic Organization Setup** | Agent structure design, self-hosted deployment, defining initial workflows for your company |
| **infab.cloud Deployment** | On-prem rollout of the production tracking platform, ERP integration, recipe/cost engine configuration |
| **Odoo Integration** | Adding an agent layer to your existing Odoo deployment |
| **Custom Agent Development** | Bespoke skills, policies, and autonomous flow design for your business processes |
| **AI Provider Consulting** | Cost-benefit analysis, model selection, security configuration |

**Contact:** [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)
**LinkedIn:** [Kuntay Kunt](https://www.linkedin.com/in/kuntaykunt/)
**X:** [x.com/kuntaykunt](https://x.com/kuntaykunt)

---

## Design Philosophy

**Human oversight, not a human bottleneck.** Agents run autonomously, but configuration changes, task approvals, and critical actions always pass through human sign-off.

**Self-hosted first.** Your data, your keys, your agent configurations stay on your own infrastructure. No SaaS lock-in.

**Org-native.** Agents aren't tools — they're personnel: attached to departments, reporting to managers, carrying policies, visible on the org chart.

---

<sub>© 2026 Fabrika Yazılım Ticaret Limited Şirketi · Istanbul · [fab.engineering](https://fab.engineering) · [infab.cloud](https://infab.cloud) · [fab.limited](https://fab.limited) · [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)</sub>

<br>

---

<div align="center">

## 🇹🇷 Türkçe

</div>

---

# fab-agent / Fabrika Yazılım

**Kurumsal yapay zeka altyapısı üretiyor.**
İstanbul · [fab.engineering](https://fab.engineering) · [infab.cloud](https://infab.cloud) · [fab.limited](https://fab.limited) · [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)

---

## Kim Biz?

[Fabrika Yazılım Ticaret Limited Şirketi](https://fab.limited) (**fab.engineering** markasıyla faaliyet gösterir), şirketlerin yapay zeka ajanlarını organizasyon şemalarına gerçek anlamda entegre etmelerine yardımcı olmak için kuruldu.

Ajanlar birer araç değil — personel. Departmanları var, yöneticileri var, politikaları var, org şemasında yer alıyorlar.

**Kurucu:** [Kuntay Kunt](https://www.linkedin.com/in/kuntaykunt/) · [x.com/kuntaykunt](https://x.com/kuntaykunt)

---

## Ürünler & Projeler

### [agentic-organization](https://github.com/fab-agent/agentic-organization) — [agent.fab.engineering](https://agent.fab.engineering)

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

### [infab.cloud](https://infab.cloud)

Sipariş bazlı, çok operasyonlu üreticiler için on-prem / kurulabilir üretim takip platformu.

- **Dinamik reçete + gerçek maliyet motoru** — canlı üretim verisine karşı gerçek zamanlı maliyet takibi
- **ERP entegrasyon katmanı** — Netsis, Odoo, Logo, Paraşüt
- **Air-gap uyumlu** — buluta bağımlı kalmadan tamamen şirket içinde çalışacak şekilde tasarlandı
- **Kurumsal düzeyde mühendislik** — %100 test coverage gate, her PR'da CI + AI code review, self-hosted hata takibi ve audit log

```
Teknoloji: Next.js 15 · FastAPI (Python 3.12) · PostgreSQL 16 · Keycloak · MinIO · Docker Compose
```

**Durum:** Aktif geliştirme — private repo, kaynak kod sadece paketlenmiş kurulum dosyaları olarak müşteriye ulaşır.

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
| **infab.cloud Kurulumu** | Üretim takip platformunun on-prem devreye alınması, ERP entegrasyonu, reçete/maliyet motoru yapılandırması |
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

<sub>© 2026 Fabrika Yazılım Ticaret Limited Şirketi · İstanbul · [fab.engineering](https://fab.engineering) · [infab.cloud](https://infab.cloud) · [fab.limited](https://fab.limited) · [bilgi@kuntaykunt.com](mailto:bilgi@kuntaykunt.com)</sub>
</content>
