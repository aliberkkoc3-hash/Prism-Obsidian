
# 🖤 Prism Obsidian

**Prism Crew tarafından geliştirilen siyah, gümüş ve altın temalı Visual Studio Code renk eklentisi.**

Bazı temalar neon ışıklarla bağırır. Prism Obsidian ise takım elbisesini giyer, sessizce odaya girer ve kod yazmaya başlar.

Derin siyah arka plan, dengeli gümüş tonları ve kararında altın vurgular. Gösteriş var ama gözünüze altın külçesi fırlatmıyoruz.

> **Prism Crew — Beyond The Spectrum.**

## ✨ Özellikler

- 🖤 **Obsidyen Siyahı:** `#08090D` tabanlı karanlık editör arka planı.
- 🥈 **Gümüş Tonları:** Metinler ve arayüz öğeleri için dengeli gri tonları.
- 🥇 **Altın Vurgular:** Aktif sekmeler, imleç ve önemli arayüz öğelerinde altın detaylar.
- 🎨 **Sözdizimi Renklendirmesi:** Anahtar kelimeler, dizeler, fonksiyonlar ve sabitler için ayrı renkler.
- 🖥️ **Terminal Uyumu:** Terminal renkleri de temanın genel tasarımına uygun.
- ⚡ **Hafif ve Bağımsız:** Tema, görünümü özelleştirir; kendi arka plan sunucusunu çalıştırmaz.

## 🎨 Renk Paleti

| Renk | HEX | Kullanım |
|---|---|---|
| Obsidyen | `#08090D` | Editör arka planı |
| Koyu Grafit | `#0C0D12` | Yan panel |
| Gümüş | `#D8D9DD` | Ana metin |
| Mat Gri | `#858892` | İkincil metin |
| Şampanya Altını | `#D6B76A` | Anahtar kelimeler ve vurgular |
| Açık Altın | `#E4C778` | İmleç ve etkin öğeler |
| Adaçayı Yeşili | `#A9C49A` | Metin dizeleri |
| Soluk Mavi | `#8EA7C8` | Terminal renkleri |

## 💻 Dil Uyumluluğu

VS Code'un ve kurulu dil eklentilerinin sağladığı sözdizimi renklendirmesinden yararlanır.

Örnek diller:

- JavaScript ve TypeScript
- HTML ve CSS
- Java
- Lua
- Haxe
- JSON
- Python

Bazı renkler dilin gramerine ve anlamsal renklendirme desteğine göre değişebilir.

## 🚀 Geliştirme Sürümünü Test Etme

Henüz `.vsix` paketi oluşturmadan temayı geliştirme ortamında deneyebilirsin.

1. Bu klasörü VS Code'da aç.
2. **Run and Debug** panelini aç.
3. `Run Prism Obsidian Extension` yapılandırmasını seç.
4. `F5` tuşuna bas.
5. Açılan geliştirme penceresinde `Ctrl + K`, ardından `Ctrl + T` tuşlarına bas.
6. **Prism Obsidian** temasını seç.

Bu işlem normal VS Code pencerenden ayrı bir geliştirme penceresi açar.

## 📦 VSIX Paketi Oluşturma

Önce Node.js ve npm kurulu olmalıdır.

```bash
npm install -g @vscode/vsce
```

Proje klasöründe şu komutu çalıştır:

```bash
vsce package
```

Başarılı olursa `prism-obsidian-1.0.0.vsix` dosyası oluşturulur.

Paketi VS Code'a yüklemek için:

```bash
code --install-extension ./prism-obsidian-1.0.0.vsix
```

Dosya adı farklıysa komutta oluşan gerçek adı kullan.

Bu işlem eklentiyi yerel olarak yükler; Marketplace'e yayımlamaz.

## 🛠️ Temayı Özelleştirme

Ana tema dosyası:

`themes/prism-obsidian-color-theme.json`

- `colors`: Editör ve arayüz renklerini belirler.
- `tokenColors`: Kod sözdizimi renklerini belirler.

Altın vurguları artırmak mümkün. Ancak her şeyi altın yaparsak editör değil, kuyumcu vitrini olur.

## 📁 Proje Yapısı

```text
PrismObsidian/
├── .vscode/
│   └── launch.json
├── themes/
│   └── prism-obsidian-color-theme.json
├── .gitignore
├── .vscodeignore
├── CHANGELOG.md
├── LICENSE.md
├── package.json
├── README.md
└── SECURITY.md
```

## 🔒 Güvenlik

Güvenlik bildirimleri ve sorumlu bildirim süreci için proje içindeki `SECURITY.md` dosyasına bak.

## 📜 Lisans

Prism Obsidian, MIT Lisansı kapsamında dağıtılmak üzere hazırlanmıştır. Ayrıntılar için `LICENSE.md` dosyasını incele.

## 👥 Geliştirici

**Prism Crew**

*Beyond The Spectrum.*

Prism Obsidian bağımsız bir topluluk projesidir. Microsoft veya Visual Studio Code'un resmî ürünü değildir.
