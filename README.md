Git ve GitHub Komutları: Temel İşlevler ve Kullanımlar
Git, yazılım geliştirme projelerinde versiyon kontrolü sağlamak için kullanılan güçlü bir araçtır. GitHub ise bu Git depolarını barındıran, işbirliğine dayalı bir platformdur. Aşağıda Git ve GitHub üzerinde en çok kullanılan komutlar ile açıklamaları yer alıyor.

1. git init
İşlevi: Yeni bir Git deposu oluşturur.
Açıklama: Mevcut bir dizini Git depoya dönüştürmek için kullanılır. Bu komut, .git adlı gizli bir dizin oluşturur ve Git, proje hakkında tüm bilgileri burada saklar.
Kullanım: git init

2. git clone <repository_url>
İşlevi: Uzak bir depoyu yerel makinenize kopyalar.
Açıklama: GitHub’daki bir depoyu yerel bilgisayarınıza indirir. Hem dosyaları hem de commit geçmişini alır.
Kullanım:git clone https://github.com/kullanici_adi/depo_adi.git

3. git status
İşlevi: Çalışma dizinindeki değişikliklerin durumunu gösterir.
Açıklama: Hangi dosyaların değiştirildiğini, hangilerinin sahneye eklendiğini ve hangilerinin commit edilmeye hazır olduğunu görmenizi sağlar.
Kullanım:git status

4. git add <file_name>
İşlevi: Değişiklikleri sahneye ekler.
Açıklama: Dosyadaki değişiklikleri veya tüm değişiklikleri bir sonraki commit için hazırlamak amacıyla kullanılır.
Kullanım:git add <file_name>    # Belirli dosya
         git add .              # Tüm dosyalar
5. git commit -m "Commit mesajı"
İşlevi: Değişiklikleri kaydeder.
Açıklama: Yapılan değişiklikleri yerel depoya kalıcı olarak ekler ve bir commit mesajı ile saklar.
Kullanım: git commit -m "Fix typo in README"

6. git push origin <branch_name>
İşlevi: Yerel değişiklikleri uzak depoya gönderir.
Açıklama: Yerel depodaki commit'leri uzak depoya gönderir ve diğer işbirlikçilerle paylaşılmasını sağlar.
Kullanım: git push origin main

7. git pull origin <branch_name>
İşlevi: Uzak depodaki değişiklikleri yerel depoya çeker.
Açıklama: Uzak depodaki en son değişiklikleri yerel bilgisayarınıza alır ve yerel çalışma dizininde birleştirir.
Kullanım: git pull origin main

8. git branch
İşlevi: Dalları listelemek, oluşturmak veya silmek için kullanılır.
Açıklama: Mevcut dalları listeleyebilir, yeni dallar oluşturabilir veya var olan dalları silebilirsiniz.
Kullanım:git branch                   # Dalları listele
         git branch <new_branch_name> # Yeni bir dal oluştur
         git branch -d <branch_name>  # Dalı sil

9. git merge <branch_name>
İşlevi: Bir dalı mevcut dala birleştirir.
Açıklama: Farklı bir dalda yapılan değişiklikleri ana dal ile birleştirir.
Kullanım:git merge <branch_name>

10. git fetch
İşlevi: Uzak depodaki değişiklikleri yerel depoya indirir, ancak birleştirme yapmaz.
Açıklama: Uzak depodaki son değişiklikleri yerel depoya alır, ancak hemen birleştirme işlemi yapmaz.
Kullanım: git fetch origin

