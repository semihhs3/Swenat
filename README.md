# Her Şeyi At (Drop All) – Fabric 1.20.1

Sandık, büyük sandık, ender sandığı ve shulker kutusu açıldığında GUI'nin sağında 3 buton çıkar:

- **Her Şeyi At** – kutudaki tüm eşyaları yere atar
- **Fişekleri At** – kutudaki havai fişekleri (firework rocket) yere atar
- **Totemleri At** – kutudaki ölümsüzlük totemlerini yere atar

Gereksinim: Minecraft 1.20.1, Fabric Loader 0.15+, Fabric API. (Sunucuda oynanacaksa mod sunucuda da olmalı.)

## GitHub'da derleme
1. Bu klasörün İÇİNDEKİ her şeyi (`.github` klasörü dahil) bir GitHub reposunun köküne yükle.
2. Repo > **Actions** > `build` çalışsın (ya da "Run workflow").
3. Bitince çalışmanın en altındaki **Artifacts > dropall-jar** dosyasını indir, zip'ten çıkan `.jar` mods klasörüne atılır.

Yerelde derlemek için: `gradle build` (Java 17, Gradle 8.7+) → `build/libs/dropall-1.0.0.jar`
