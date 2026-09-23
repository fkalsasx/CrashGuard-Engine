# CrashGuard Engine

**Windows oyunları için bütünlük taraması, çökme analizi ve güvenli kurtarma merkezi.**  
**Integrity scanning, crash analysis, and safer recovery for Windows games.**

CrashGuard Engine; oyun kurulumlarını keşfetmek, dosya bütünlüğünü incelemek, çökme kanıtlarını anlaşılır hâle getirmek ve mod kaynaklı sorunları araştırmak için geliştirilmiş bir Windows masaüstü uygulamasıdır.

## Öne çıkan özellikler

- Steam, Epic, GOG, Xbox, EA ve Ubisoft kurulumlarını bilinen başlatıcı kayıtlarından keşfeder.
- Oyun dosyalarını **salt okunur** ve iptal edilebilir biçimde tarar.
- Windows çökme kayıtlarını, ana EXE bütünlüğünü ve mod eşleşmelerini kanıta göre sıralar.
- Önem düzeyi, çözüm güveni, risk ve doğrulama planını açıkça gösterir.
- Değişiklik gerektiren işlemlerden önce kullanıcı onayı ve geri dönüş noktası ister.
- Sonuç doğrulanmazsa güvenli geri alma yaklaşımını kullanır.
- Türkçe ve İngilizce arayüz sunar.
- Resmî Steam kapaklarını doğrular; geçersiz görseller yerine CrashGuard Engine kapağını kullanır.

## İndir

En güncel Windows 10/11 x64 sürümünü [GitHub Releases](https://github.com/fkalsasx/CrashGuard-Engine/releases/latest) sayfasından indirebilirsiniz.

1. `CrashGuardEngine-v1.0.0.exe` dosyasını indirin.
2. Sürüm sayfasındaki SHA-256 değeriyle dosyayı doğrulayın.
3. EXE dosyasını çalıştırın.

Uygulama tek dosyalı ve bağımsızdır; ayrıca .NET kurulumu gerektirmez.

## Güvenlik yaklaşımı

CrashGuard Engine, eksik kanıtı kesin sonuç gibi göstermez. Oyun yolları, hash sonuçları ve tanılama kayıtları varsayılan olarak bilgisayarınızda kalır. İnternet araştırması ve destek paketi dışa aktarma işlemleri yalnızca kullanıcı tarafından başlatılır. Güvenlik yazılımınızı kapatmanız önerilmez.

## Son doğrulama

23 Eylül 2026 bakım derlemesi:

- 154/154 otomatik test başarılı.
- Release derlemesi 0 hatayla tamamlandı.
- NuGet taramasında bilinen güvenlik açığı bulunmadı.
- Arayüz ve paketlenmiş EXE başlangıç testleri kararlı tamamlandı.

Ayrıntılar için [en güncel sürüm notlarına](https://github.com/fkalsasx/CrashGuard-Engine/releases/latest) bakın.

## Sorun bildirme

Tekrarlanabilir bir sorun bulursanız [Issues](https://github.com/fkalsasx/CrashGuard-Engine/issues) bölümünde oyun adı, uygulanan adımlar, beklenen sonuç ve görülen sonuçla birlikte bildirin. Parola, hesap bilgisi veya kişisel dosya içeriği paylaşmayın.

---

## English

CrashGuard Engine is a Windows desktop utility for discovering game installations, checking file integrity, organizing crash evidence, and investigating mod-related problems.

### Highlights

- Discovers installations from major PC game launchers.
- Performs read-only, cancellable integrity scans.
- Ranks crash evidence and recovery suggestions by confidence and risk.
- Requests approval before changes and favors reversible recovery steps.
- Supports Turkish and English.
- Ships as a standalone Windows x64 executable; no separate .NET installation is required.

Download the latest build from [GitHub Releases](https://github.com/fkalsasx/CrashGuard-Engine/releases/latest). For reproducible problems, open an [Issue](https://github.com/fkalsasx/CrashGuard-Engine/issues).
