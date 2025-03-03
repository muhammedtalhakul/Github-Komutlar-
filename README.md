GitHub, Git versiyon kontrol sistemini kullanarak projelerinizi yönetmenize ve işbirliği yapmanıza olanak tanır.

Git Komutları ve İşlevleri

   1.	git init
•	İşlevi: Yeni bir Git deposu oluşturur.
•	Kullanım Amacı: Mevcut bir dizini bir Git deposuna dönüştürmek için kullanılır. Bu komut, dizinde .git adlı gizli bir dizin oluşturur ve bu dizin, Git'in proje ile ilgili tüm bilgileri sakladığı yerdir.
   git init

   2.	git clone
•	İşlevi: Var olan bir uzak depoyu yerel makinenize kopyalar.
•	Kullanım Amacı: Uzak bir depodaki tüm dosyaları ve commit geçmişini yerel makinenize indirmek için kullanılır. Bu, projeye katkıda bulunmak veya projeyi incelemek için gereklidir.
   git clone <repository_url>
   
   3.	git status
•	İşlevi: Çalışma dizinindeki değişikliklerin durumunu gösterir.
•	Kullanım Amacı: Hangi dosyaların değiştirildiğini, hangilerinin sahneye eklendiğini ve hangilerinin commit edilmeye hazır olduğunu görmek için kullanılır.
   git status

   4.	git add
•	İşlevi: Değişiklikleri sahneye ekler.
•	Kullanım Amacı: Belirli dosyaları veya tüm değişiklikleri bir sonraki commit için hazırlamak için kullanılır. Bu komut, değişikliklerin commit edilmeden önce gözden geçirilmesini sağlar.
   git add <file_name>
   git add .


   5.	git commit
•	İşlevi: Sahneye eklenen değişiklikleri kaydeder.
•	Kullanım Amacı: Değişiklikleri yerel depoya kalıcı olarak eklemek ve bir commit mesajı ile birlikte saklamak için kullanılır. Bu, değişikliklerin kaydedilmesini ve geri alınabilir olmasını sağlar.
   git commit -m "Commit mesajı"


   6.	git push
•	İşlevi: Yerel değişiklikleri uzak depoya gönderir.
•	Kullanım Amacı: Yerel depodaki commit'leri uzak depoya aktarmak için kullanılır. Bu, projedeki diğer işbirlikçilerin değişiklikleri görmesini ve kullanmasını sağlar.
   git push origin <branch_name>


   7.	git pull
•	İşlevi: Uzak depodaki değişiklikleri yerel depoya çeker ve birleştirir.
•	Kullanım Amacı: Uzak depodaki en son değişiklikleri yerel depoya almak ve bu değişiklikleri yerel çalışma dizini ile birleştirmek için kullanılır.
   git pull origin <branch_name>

   8.	git branch
•	İşlevi: Dalları listelemek, oluşturmak veya silmek için kullanılır.
•	Kullanım Amacı: Mevcut dalları göstermek, yeni dallar oluşturmak veya var olan dalları silmek için kullanılır. Dallar, projede paralel geliştirme yapılmasını sağlar.
   git branch
   git branch <new_branch_name>
   git branch -d <branch_name>

   9.	git fetch
•	İşlevi: Uzak depodaki değişiklikleri yerel depoya indirir, ancak birleştirme yapmaz.
•	Kullanım Amacı: Uzak depodaki en son değişiklikleri yerel depoya almak, ancak bu değişiklikleri hemen birleştirmemek için kullanılır.
   git fetch origin

  10.	git rebase
•	İşlevi: Bir dalın tabanını başka bir dalın sonuna taşır.
•	Kullanım Amacı: Daha temiz bir commit geçmişi oluşturmak için kullanılır. git merge yerine git rebase kullanarak, dalların birleşiminde daha düz bir tarihçe elde edebilirsiniz.
git rebase <branch_name>


