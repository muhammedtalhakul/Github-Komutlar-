Git ve GitHub ile Proje Yönetimi
Git, projelerinizi takip etmek, versiyon kontrolü sağlamak ve işbirliği yapmak için kullanılan bir sistemdir. GitHub ise Git’in bulut tabanlı bir platformu olarak, projelerinizi barındırmanıza ve diğer geliştiricilerle işbirliği yapmanıza olanak tanır.

Git Komutları ve İşlevleri
git init

İşlevi: Yeni bir Git deposu oluşturur.
Açıklama: Mevcut dizini Git deposuna dönüştürmek için kullanılır. Bu komut ile .git adlı gizli bir dizin oluşturulur ve proje bilgileri burada saklanır.
Kullanım:
bash
Kopyala
git init
git clone <repository_url>

İşlevi: Var olan bir uzak depoyu yerel makinenize kopyalar.
Açıklama: Uzak bir depodaki tüm dosyaları ve commit geçmişini yerel bilgisayarınıza indirir.
Kullanım:
bash
Kopyala
git clone <repository_url>
git status

İşlevi: Çalışma dizinindeki değişikliklerin durumunu gösterir.
Açıklama: Hangi dosyaların değiştirildiğini, sahneye eklendiğini veya commit edilmeye hazır olduğunu görmek için kullanılır.
Kullanım:
bash
Kopyala
git status
git add <file_name>

İşlevi: Değişiklikleri sahneye ekler.
Açıklama: Belirli dosyaları veya tüm değişiklikleri bir sonraki commit için hazırlamak amacıyla kullanılır.
Kullanım:
bash
Kopyala
git add <file_name>
git add .
git commit -m "Commit mesajı"

İşlevi: Sahneye eklenen değişiklikleri kaydeder.
Açıklama: Değişiklikleri yerel depoya kalıcı olarak ekler ve bir commit mesajı ile saklar.
Kullanım:
bash
Kopyala
git commit -m "Commit mesajı"
git push origin <branch_name>

İşlevi: Yerel değişiklikleri uzak depoya gönderir.
Açıklama: Yerel depodaki commit’leri uzak depoya aktarır, böylece projedeki diğer işbirlikçilerin değişiklikleri görmesini sağlar.
Kullanım:
bash
Kopyala
git push origin <branch_name>
git pull origin <branch_name>

İşlevi: Uzak depodaki değişiklikleri yerel depoya çeker ve birleştirir.
Açıklama: Uzak depodaki en son değişiklikleri yerel depoya alır ve birleştirir.
Kullanım:
bash
Kopyala
git pull origin <branch_name>
git branch

İşlevi: Dalları listelemek, oluşturmak veya silmek için kullanılır.
Açıklama: Mevcut dalları göstermek, yeni dallar oluşturmak veya var olan dalları silmek için kullanılır.
Kullanım:
bash
Kopyala
git branch
git branch <new_branch_name>
git branch -d <branch_name>
git fetch origin

İşlevi: Uzak depodaki değişiklikleri yerel depoya indirir.
Açıklama: Uzak depodaki değişiklikleri yerel depoya indirir ancak birleştirme yapmaz.
Kullanım:
bash
Kopyala
git fetch origin
git rebase <branch_name>

İşlevi: Bir dalın tabanını başka bir dalın sonuna taşır.
Açıklama: Daha temiz bir commit geçmişi oluşturur ve git merge yerine git rebase kullanarak, dalların birleşiminde daha düz bir tarihçe sağlar.
Kullanım:
bash
Kopyala
git rebase <branch_name>
GitHub'a Resim Yükleme Yöntemleri
GitHub'a resim yüklemek için üç farklı yöntem kullanılabilir. Her bir yöntemde, resminizi yükleyebilir ve Markdown dosyalarında veya GitHub sayfalarında gösterebilirsiniz.

Yöntem 1: Resmi Depoya Yüklemek ve Markdown Dosyasında Kullanmak
Resmi Depoya Yüklemek:

Resmi bilgisayarınıza uygun bir dizine kaydedin.
Git komutları ile resmi depoya ekleyin ve commit yapın.
bash
Kopyala
git add <resim_dosya_yolu>
git commit -m "Resim eklendi"
git push origin <branch_name>
Markdown Dosyasında Resmi Kullanmak:

Resminizi Markdown dosyasında aşağıdaki şekilde görüntüleyebilirsiniz:
markdown
Kopyala
![Resim Açıklaması](resim_dosya_yolu)
Örnek:
markdown
Kopyala
![Örnek Resim](images/example.png)
Yöntem 2: GitHub Arayüzü ile Resim Yüklemek
GitHub Arayüzü ile Resim Yüklemek:

GitHub deposuna gidin ve Add file butonuna tıklayın.
Upload files seçeneği ile yüklemek istediğiniz resmi seçin ve yükleyin.
Değişiklikleri commit edin.
Markdown Dosyasında Resmi Kullanmak:

Eklediğiniz resmin URL'sini kopyalayın ve Markdown dosyanızda aşağıdaki gibi kullanın:
markdown
Kopyala
![Resim Açıklaması](https://github.com/kullanici_adi/depo_adi/raw/main/images/example.png)
Yöntem 3: GitHub Issues veya Pull Requests Kullanarak Resim Yüklemek
GitHub Issues veya Pull Requests Kullanarak Resim Yüklemek:

Bir Issue veya Pull Request oluşturun.
Resmi sürükleyip bırakın veya Attach files alanına tıklayarak yükleyin.
Yüklenen resmin URL’sini kopyalayın.
Markdown Dosyasında Resmi Kullanmak:

Kopyaladığınız URL'yi aşağıdaki gibi kullanabilirsiniz:
markdown
Kopyala
![Resim Açıklaması](https://user-images.githubusercontent.com/kullanici_adi/resim_id.png)



