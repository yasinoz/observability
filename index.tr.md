---
title: Gözlemlenebilirlik Laboratuvarları
lang: tr
slug: index
section: index
order: 0
status: updated
upstream: index.md
---
# Gözlemlenebilirlik Laboratuvarları

Metrikler, loglar ve dağıtık izler — sisteminizin ne yaptığını bilmek.

> 🇬🇧 [English version](index.md)

## Ön Koşullar

İlk lab'a başlamadan **önce** şunları yapın:

1. **[Ortamınızı kurun](setup/README.md)** — Docker, Git ve bir terminal.
2. **Lab dosyalarını indirin:**

   ```
   git clone https://github.com/yasinoz/observability.git
   cd observability
   ```

3. **Docker Hub'a giriş yapın** (ücretsiz hesap). Sınıf ortamında bu opsiyonel
   değil: Docker Hub anonim imaj çekme işlemlerini *IP adresi başına*
   sınırlıyor; aynı bağlantıyı paylaşan yirmi kişi limiti doldurur ve lab'ın
   ortasında `toomanyrequests` hatası alır.

   ```
   docker login
   ```


<!-- labs:start -->

## Metrikler

Metrik toplamak, sorgulamak ve görselleştirmek.

| Lab | Süre | Gerekir |
|---|---|---|
| [Metrik Yayınlamak](labs/metrics/README.md) _(EN)_ | 45 dk | docker |
| [Prometheus](labs/prometheus/README.md) _(EN)_ | 45 dk | docker |
| [PromQL ile Metrik Sorgulamak](labs/promql/README.md) _(EN)_ | 45 dk | docker |
| [Grafana](labs/grafana/README.md) _(EN)_ | 40 dk | docker |
| [Grafana Dashboard'ları Kurmak](labs/grafana-dashboard/README.md) _(EN)_ | 45 dk | docker |

## Loglar

Uygulama loglarını yazmak, taşımak, saklamak ve aramak.

| Lab | Süre | Gerekir |
|---|---|---|
| [Log Yazmak](labs/logging/README.md) _(EN)_ | 40 dk | docker |
| [Elasticsearch Çalıştırmak](labs/elasticsearch/README.md) _(EN)_ | 45 dk | docker |
| [Logstash ile Log Toplamak](labs/logstash/README.md) _(EN)_ | 45 dk | docker |
| [Kibana](labs/kibana/README.md) _(EN)_ | 45 dk | docker |
| [Query DSL ile Arama](labs/query-dsl/README.md) _(EN)_ | 45 dk | docker |
| [Kibana Dashboard'ları](labs/kibana-dashboard/README.md) _(EN)_ | 40 dk | docker |

## Dağıtık İzleme

Bir isteği servisler arasında takip etmek.

| Lab | Süre | Gerekir |
|---|---|---|
| [Uygulama İzleri](labs/tracing/README.md) _(EN)_ | 45 dk | docker |
| [Jaeger Çalıştırmak](labs/jaeger/README.md) _(EN)_ | 35 dk | docker |
| [Özel Span'ler](labs/custom-spans/README.md) _(EN)_ | 45 dk | docker |

## Gerçek Dünya

Bir sorunu bulmak için üç sinyali birlikte kullanmak.

| Lab | Süre | Gerekir |
|---|---|---|
| [Gözlemlenebilirlikte Sorun Giderme](labs/troubleshooting/README.md) _(EN)_ | 50 dk | docker |

<!-- labs:end -->

## Bir lab nasıl işler

Her lab aynı kalıbı izler:

- **Kaynaklar** — gerçek dökümantasyona bağlantılar.
- **Anlatım** — adım adım yönlendirme, komutlar kopyala-yapıştır çalışır.
- 📋 **Görevler** — bunları kendiniz çözeceksiniz; cevap hemen altındaki
  `Takıldınız mı?` bloğunda gizli.
- **Lab** — anlatımı olmayan, daha zor bir alıştırma. `hints` yol gösterir,
  `solution` cevabı verir.
- **Temizlik** — mutlaka çalıştırın; yoksa sonraki lab aynı portlar için
  kavga eder.

> Henüz Türkçeye çevrilmemiş lablar listede _(EN)_ işaretiyle görünür ve
> İngilizce sürümüne bağlanır. Çeviri durumu dosya varlığından okunur.

## Durum

Lablar 2021-2025 arası bir kaynaktan modernize edildi. Mekanik düzeltmeler
(compose v2, güncel imaj sürümleri, kırık bağlantılar) uygulandı; lablar
henüz uçtan uca çalıştırılarak doğrulanmadı.

Bozuk bir şey bulursanız issue açın — derste patlayan bir lab, hiç olmayan
lab'dan kötüdür.

## Emeği Geçenler

[Elton Stoneman](https://github.com/sixeyed) tarafından hazırlanan
[courselabs/observability](https://github.com/courselabs/observability) çalışmasından
türetilmiştir; CC BY-SA 4.0 kapsamında kullanılmış ve yeniden dağıtılmıştır.
Ayrıntı: [ATTRIBUTION.md](ATTRIBUTION.md).

Türkçe çeviri, modernizasyon ve lab altyapısı:
[Mehmet Yasin Özkasapoğlu](https://github.com/yasinoz) — `sudo2go`.
