# mobile_flutter
Flutter'ı kurmak için aşağıdaki adımları izleyebilirsiniz. Bu adımlar, Flutter'ın Windows, macOS ve Linux işletim sistemlerine kurulumu için geçerlidir.

### Windows Üzerine Flutter Kurulumu

1. **Flutter SDK'sini İndirin:**
   - Flutter'ın [resmi web sitesine](https://flutter.dev/docs/get-started/install/windows) gidin.
   - "Get Started" bölümünden Windows'u seçin ve SDK'yı indirin.
   - İndirilen ZIP dosyasını bir klasöre çıkartın. (Örneğin, `C:\src\flutter`)

2. **Çevresel Değişkenleri Ayarlayın:**
   - "Gelişmiş sistem ayarları"na gidin ve "Ortam Değişkenleri"ni seçin.
   - "Path" değişkenini bulun ve düzenleyin.
   - Flutter'ın `bin` klasörünün yolunu (örneğin, `C:\src\flutter\bin`) bu listeye ekleyin.

3. **Gereksinimleri Kontrol Edin:**
   - Komut istemcisini açın ve `flutter doctor` komutunu çalıştırın.
   - Bu komut, eksik bağımlılıkları kontrol eder ve kurulumunuzu tamamlamanız için size rehberlik eder.

4. **Android Studio'yu Kurun:**
   - [Android Studio'yu indirin ve kurun](https://developer.android.com/studio).
   - SDK ve ilgili araçları kurduğunuzdan emin olun.
   - Android Studio'nun "SDK Manager" bölümünde gerekli Android SDK bileşenlerini yükleyin.

5. **Android Emulator Kurulumu:**
   - Android Studio'da "AVD Manager"ı açın ve bir emülatör oluşturun.
   - Emülatörü başlatın ve çalışır durumda olduğundan emin olun.

6. **VS Code (İsteğe Bağlı):**
   - [Visual Studio Code](https://code.visualstudio.com/) yükleyin.
   - VS Code içinde, Flutter ve Dart eklentilerini kurun.

### macOS Üzerine Flutter Kurulumu

1. **Flutter SDK'sini İndirin:**
   - Flutter'ın [resmi web sitesine](https://flutter.dev/docs/get-started/install/macos) gidin.
   - SDK'yı indirin ve bir klasöre çıkartın (örneğin, `~/development/flutter`).

2. **Çevresel Değişkenleri Ayarlayın:**
   - Terminali açın ve `.bashrc`, `.bash_profile` veya `.zshrc` dosyanıza aşağıdaki satırı ekleyin:
     ```sh
     export PATH="$PATH:`pwd`/flutter/bin"
     ```
   - Bu değişikliği etkinleştirmek için terminali yeniden başlatın veya `source ~/.zshrc` komutunu çalıştırın.

3. **Gereksinimleri Kontrol Edin:**
   - Terminalde `flutter doctor` komutunu çalıştırın.
   - Eksik olan bileşenleri yükleyin.

4. **Xcode'u Kurun:**
   - App Store'dan Xcode'u indirin ve kurun.
   - Xcode içinde "Xcode Preferences > Locations" bölümünde komut satırı araçlarını seçin.

5. **Android Studio'yu Kurun (İsteğe Bağlı):**
   - Android Studio'yu indirin ve kurun.
   - SDK ve gerekli araçları kurun.
   - Android emulator oluşturun ve çalıştırın.

### Linux Üzerine Flutter Kurulumu

1. **Flutter SDK'sini İndirin:**
   - Flutter'ın [resmi web sitesine](https://flutter.dev/docs/get-started/install/linux) gidin.
   - SDK'yı indirin ve bir klasöre çıkartın (örneğin, `~/development/flutter`).

2. **Çevresel Değişkenleri Ayarlayın:**
   - Terminali açın ve `.bashrc` veya `.bash_profile` dosyanıza aşağıdaki satırı ekleyin:
     ```sh
     export PATH="$PATH:`pwd`/flutter/bin"
     ```
   - Bu değişikliği etkinleştirmek için terminali yeniden başlatın veya `source ~/.bashrc` komutunu çalıştırın.

3. **Gereksinimleri Kontrol Edin:**
   - Terminalde `flutter doctor` komutunu çalıştırın.
   - Eksik olan bileşenleri yükleyin.

4. **Android Studio'yu Kurun:**
   - Android Studio'yu indirin ve kurun.
   - SDK ve gerekli araçları kurun.
   - Android emulator oluşturun ve çalıştırın.

### İlk Flutter Uygulamasını Oluşturma

1. Terminalde yeni bir Flutter projesi oluşturun:
   ```sh
   flutter create my_app
   ```

2. Proje klasörüne gidin:
   ```sh
   cd my_app
   ```

3. Uygulamayı çalıştırın:
   ```sh
   flutter run
   ```

Bu adımları izleyerek Flutter'ı kurabilir ve ilk Flutter uygulamanızı oluşturabilirsiniz. Herhangi bir sorunla karşılaşırsanız, `flutter doctor` komutunu çalıştırarak eksik veya yanlış yapılandırılmış bileşenleri kontrol edebilirsiniz.
