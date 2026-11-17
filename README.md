<p align="center">
  <img src="assets/Sketchware-Pro.png" style="width: 30%;" />
</p>

# Sketchware Pro
[![GitHub contributors](https://img.shields.io/github/contributors/Sketchware-Pro/Sketchware-Pro)](https://github.com/Sketchware-Pro/Sketchware-Pro/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/Sketchware-Pro/Sketchware-Pro)](https://github.com/Sketchware-Pro/Sketchware-Pro/commits/)
[![Discord server stats](https://img.shields.io/discord/790686719753846785)](http://discord.gg/kq39yhT4rX)
[![Total downloads](https://img.shields.io/github/downloads/Sketchware-Pro/Sketchware-Pro/total)](https://github.com/Sketchware-Pro/Sketchware-Pro/releases)
[![Repository Size](https://img.shields.io/github/repo-size/Sketchware-Pro/Sketchware-Pro)](https://github.com/Sketchware-Pro/Sketchware-Pro)

> [!NOTE]
> **🇹🇷 Türkçe Sketchware Pro** — Bu fork, [Sketchware Pro](https://github.com/Sketchware-Pro/Sketchware-Pro)'nun **Türkçe arayüzlü** sürümüdür. Resmî değildir. Topluluk için hazırlanmıştır.
>
> - **Tam Türkçe arayüz:** ~2000 metin çevrildi (menüler, pencereler, bildirimler, ayarlar).
> - **Uygulama içi dil seçimi:** Ayarlar → Görünüm → **Dil** → *Sistem dili / English / Türkçe*.
> - **Türkçe "i/I" hatası düzeltildi:** Telefon dili Türkçe olunca üretilen kod artık bozulmuyor (`@drawable/ıcon`, `REQ_CD_PİCKER` gibi).
>
> **📥 Hazır APK:** [Releases](https://github.com/banadabi/Sketchware-Pro/releases) sayfası. Release kaldırılırsa APK'yı aşağıdaki talimatla kendiniz derleyebilirsiniz.

## ⚖️ Sketchware Pro geliştiricilerine not / Note to the Sketchware Pro developers

**🇹🇷 Türkçe**

Bu fork ve Releases sayfasındaki APK, Sketchware Pro'yu kendi dilinde kullanmak isteyen Türk kullanıcılar için hazırlandı. Ticari bir amacı yoktur. Projenin kurallarına uygun olarak hiçbir uygulama mağazasında yayınlanmaz. İngilizce bilmeyen birçok Türk kullanıcı için Türkçe arayüz, Sketchware Pro'yu öğrenip kullanabilmenin en önemli koşuludur. Bu yüzden bu APK, Türk kullanıcılar için gerçekten önemlidir.

Yine de projenin kurallarına ve emeğinize saygı duyuyoruz. **Sketchware Pro geliştiricileri release'in veya APK'nın kaldırılmasını ister ya da bir şikâyet iletirse, release ve APK derhal kaldırılacaktır.** Talebinizi bu fork'ta bir [issue](https://github.com/banadabi/Sketchware-Pro/issues) açarak ya da [#2134](https://github.com/Sketchware-Pro/Sketchware-Pro/pull/2134) numaralı PR'a yorum yazarak iletebilirsiniz. Release kaldırılsa bile kaynak kod ve aşağıdaki derleme talimatı burada kalır. Böylece kullanıcılar Türkçe APK'yı kendileri derleyebilir.

**🇬🇧 English**

This fork and the APK on its Releases page were made for Turkish users who want to use Sketchware Pro in their own language. It is non-commercial. In line with the project's rules, it is not published on any app store. For many Turkish users who do not speak English, a Turkish interface is what makes it possible to learn and use Sketchware Pro at all. That is why this APK matters a lot to the Turkish community.

We respect the project's rules and your work. **If the Sketchware Pro developers ask for the release or the APK to be taken down, or raise any complaint, the release and the APK will be removed promptly.** Please open an [issue on this fork](https://github.com/banadabi/Sketchware-Pro/issues) or comment on [#2134](https://github.com/Sketchware-Pro/Sketchware-Pro/pull/2134). Even if the release is removed, the source code and the build instructions below will stay, so users can build the Turkish APK themselves.

## 🛠️ Kendi Türkçe APK'nı derle / Build your own Turkish APK

### 📱 Yöntem 1: Bilgisayarsız, yalnız telefonla (GitHub Actions)

Bilgisayarınız yoksa APK'yı GitHub'ın kendi sunucularında, ücretsiz olarak derleyebilirsiniz. Yalnız bir telefon, internet ve ücretsiz bir GitHub hesabı yeterlidir.

**🇹🇷 Adım adım:**

1. **Hesap açın:** Telefonun tarayıcısından (Chrome vb.) [github.com/signup](https://github.com/signup) adresine girip ücretsiz bir hesap açın. Hesabınız varsa giriş yapın.
   > İpucu: GitHub mobil sayfasında bazı düğmeler gizli olabilir. Tarayıcı menüsünden **"Masaüstü sitesi"** seçeneğini açarsanız her şey görünür.
2. **Fork alın:** [github.com/banadabi/Sketchware-Pro](https://github.com/banadabi/Sketchware-Pro) sayfasına girin ve sağ üstteki **Fork** düğmesine basın. Açılan sayfada hiçbir şeyi değiştirmeden **Create fork** düğmesine basın. (Varsayılan dal Türkçe kodun bulunduğu `turkce` dalıdır, otomatik kopyalanır.)
3. **Actions'ı açın:** Kendi fork'unuzda (adres `github.com/KULLANICI-ADINIZ/Sketchware-Pro` olur) üstteki **Actions** sekmesine girin. **"I understand my workflows, go ahead and enable them"** düğmesine basın.
4. **Derlemeyi başlatın:** Soldaki listeden **Türkçe APK derle (Build Turkish APK)** iş akışına dokunun. Sağdaki **Run workflow** düğmesine basın. Açılan küçük pencerede dal olarak **`turkce`** seçili olsun, sonra yeşil **Run workflow** düğmesine basın.
5. **Bekleyin:** Listede yeni bir çalışma belirir. Derleme yaklaşık **5-10** dakika sürer. Bitince yanında yeşil ✅ işareti çıkar. Sayfayı yenileyerek durumu görebilirsiniz.
6. **APK'yı indirin:** Yeşil ✅ çalışmaya dokunun. Sayfanın en altındaki **Artifacts** bölümünde `SketchwarePro-turkce-…` adlı dosyaya dokunun ve indirin.
7. **Kurun:** İnen dosya bir **zip** dosyasıdır. Telefonun **Dosyalar** uygulamasıyla açıp içindeki `app-debug.apk` dosyasını çıkarın ve ona dokunarak kurun. Telefon izin isterse **"bilinmeyen kaynaklardan yükleme"** iznini verin.

> Not: İndirilen dosya GitHub'da 90 gün saklanır. Daha sonra yeniden indirmek isterseniz 4. adımdan tekrar derleyebilirsiniz. Bu derleme ücretsizdir.

**🇬🇧 Step by step (no computer needed, phone only):**

You can build the APK for free on GitHub's own servers. All you need is a phone, an internet connection and a free GitHub account.

1. **Create an account:** In your phone's browser, go to [github.com/signup](https://github.com/signup) and create a free account, or sign in.
   > Tip: Some buttons are hidden on GitHub's mobile layout. Turn on **"Desktop site"** in your browser menu to see everything.
2. **Fork:** Open [github.com/banadabi/Sketchware-Pro](https://github.com/banadabi/Sketchware-Pro) and tap **Fork** at the top right. Leave the options as they are and tap **Create fork**. (The default branch is `turkce`, which holds the Turkish code, so it is copied automatically.)
3. **Enable Actions:** In your fork (`github.com/YOUR-USERNAME/Sketchware-Pro`), open the **Actions** tab and tap **"I understand my workflows, go ahead and enable them"**.
4. **Start the build:** In the list on the left, tap **Türkçe APK derle (Build Turkish APK)**. Tap **Run workflow**, make sure the branch is **`turkce`**, then tap the green **Run workflow** button.
5. **Wait:** A new run appears in the list. It takes about **5-10** minutes and shows a green ✅ when done. Refresh the page to check.
6. **Download:** Tap the finished run. Under **Artifacts** at the bottom of the page, tap `SketchwarePro-turkce-…` to download it.
7. **Install:** The download is a **zip** file. Open it with your phone's **Files** app, extract `app-debug.apk` and tap it to install. Allow **"install from unknown sources"** if asked.

> Note: The artifact is kept on GitHub for 90 days. You can always run step 4 again to build a new one. It is free.

### Yöntem 2: Bilgisayarda komut satırıyla (Windows / Linux / macOS)

Gerekenler: [Git](https://git-scm.com/) + [Git LFS](https://git-lfs.com/), **JDK 17 veya üstü**, **Android SDK** ([Android Studio](https://developer.android.com/studio) ile birlikte gelir).

```bash
git lfs install
git clone https://github.com/banadabi/Sketchware-Pro.git
cd Sketchware-Pro
# Android SDK yolunu bildirin (ANDROID_HOME ortam değişkeni de olur):
echo "sdk.dir=/home/KULLANICI/Android/Sdk" > local.properties
./gradlew assembleDebug        # Windows: gradlew.bat assembleDebug
```

APK `app/build/outputs/apk/debug/app-debug.apk` konumuna çıkar. İlk derleme birkaç GB indirir ve 5-20 dakika sürebilir. Lisans hatası alırsanız `sdkmanager --licenses` komutunu çalıştırın.

> Git LFS kurulmadan klonlanırsa derleme `gradle-wrapper.jar` gibi dosyalarda hata verir. Bu durumda klasörün içinde `git lfs pull` çalıştırın.

### Yöntem 3: Android Studio ile

1. Önce Git LFS'i kurun (`git lfs install`).
2. Android Studio'da **File → New → Project from Version Control** seçin ve `https://github.com/banadabi/Sketchware-Pro.git` adresini girip klonlayın.
3. Gradle senkronizasyonu bitince **Build → Build App Bundle(s) / APK(s) → Build APK(s)** seçin.

**🇬🇧 With a computer:** clone it with Git LFS and run `./gradlew assembleDebug` with JDK 17+ and the Android SDK.

---

Welcome to Sketchware Pro! Here you'll find the source code of many classes in Sketchware Pro and, most importantly, the place to contribute to Sketchware Pro.

## Building the App
To build the app, you must use Gradle. It's highly recommended to use Android Studio for the best experience.

### Source Code Map

| Class           | Role                                        |
| --------------- | ------------------------------------------- |
| `a.a.a.ProjectBuilder`      | Helper for compiling an entire project       |
| `a.a.a.Ix`      | Responsible for generating AndroidManifest.xml |
| `a.a.a.Jx`      | Generates source code of activities          |
| `a.a.a.Lx`      | Generates source code of components, such as listeners, etc. |
| `a.a.a.Ox`      | Responsible for generating XML files of layouts |
| `a.a.a.qq`      | Registry of built-in libraries' dependencies |
| `a.a.a.tq`      | Responsible for the compiling dialog's quizzes |
| `a.a.a.yq`      | Organizes Sketchware projects' file paths    |

> [!TIP]
> You can also check the `mod` package, which contains the majority of contributors' changes.

## Contributing

If you'd like to contribute to Sketchware Pro, follow these steps:

1. Fork this repository.
2. Make changes in your forked repository.
3. Test out those changes.
4. Create a pull request in this repository.
5. Your pull request will be reviewed by the repository members and merged if accepted.

We welcome contributions focused on core stability, modern Android tooling, compiler updates, and visual block functionality. Please note that all contributions are thoroughly reviewed.

> [!NOTE]
> Generative AI, LLM coding assistants, and AI-agent integrations are strictly out of scope for Sketchware Pro and will not be accepted.

### Commit Message

When you make changes to one or more files, you need to commit those changes with a commit message adhering to [Conventional Commits](https://www.conventionalcommits.org/) (enforced by repository ruleset):

- Use lowercase commit types with an optional scope: `<type>(<scope>): <subject>` or `<type>: <subject>`
  - `feat:` for a feature or enhancement.
  - `fix:` for a bug fix.
  - `build:` for build system, Gradle, or dependency changes.
  - `refactor:` for code refactoring without behavior change.
  - `style:` for formatting, themes, or visual adjustments.
  - `docs:` for documentation changes.
  - `test:` for test changes.
  - `ci:` for CI/CD workflow updates.
  - `chore:` for tooling and maintenance.
- Keep the commit message short, imperative, and descriptive.
- Do not use emojis in the commit prefix, as pushes failing the conventional regex pattern will be rejected.

Examples:
- `feat(editor): speed up compiling with new technique`
- `fix(runtime): fix crash during launch on certain devices`
- `build(deps): bump androidx core dependencies`

> [!IMPORTANT]
> If you want to add new features that don't require editing other packages other than `pro.sketchware`, make your changes in `pro.sketchware` package, and respect the directories and files structure and names. Also, even though the project compiles just fine with Kotlin classes that you might add, try to make your changes or additions in Java, not Kotlin unless it is more than necessary.

## Thanks for Contributing

Thank you for contributing to Sketchware Pro! Your contributions help keep Sketchware Pro alive. Each accepted contribution will be noted down in the "About Team" activity. We'll use your GitHub name and profile picture initially, but they can be changed, of course.

## Discord

Want to chat with us, discuss changes, or just hang out? We have a Discord server just for that.

[![Join our Discord server!](https://img.shields.io/discord/790686719753846785?label=Discord&logo=discord&logoColor=white&color=5865F2)](https://discord.gg/kq39yhT4rX)

## Disclaimer

This mod was not created for any harmful purposes, such as harming Sketchware; quite the opposite, actually. It was made to keep Sketchware alive by the community for the community. Please use it at your own discretion.

We do NOT permit publishing Sketchware Pro as it is, or with modifications, on Play Store or on any other app store. Keep in mind that this project is still a mod. Unauthorized modding of apps is considered illegal and we discourage such behavior.

We love Sketchware very much and are grateful to Sketchware's developers for creating such an amazing app. However, we haven't received updates for a long time. That's why we decided to keep Sketchware alive by creating this mod, and it's completely free. We don't demand any money :)
