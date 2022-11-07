# merge-sort
merge sort projesi

Merge-Sort-Projesi
Merge Sort Projesi (Patika) Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

Çözüm:

[16,21,11,8,12,22] dizinin sort türüne göre aşamalarını yazınız.

Adım 1: İlk aşamada diziyi ortadan ikiye bölelim. Adım 2: Dizi 6 elemanlı olduğu için 3’erli iki tane dizi oluşturmuş oluruz. [16,21,11] [8,12,22] Adım3 : İkiye bölünmüş olan dizileri de kendi içinde ikiye bölelim. [16,21] [11] [8,12] [22] Adım4: Elimizde 4 tane dizi oldu. Bu dizilerin bazıları tek elemanlı. Tek eleman olana kadar diğer dizileri de bölelim. [16] [21] [11] [8] [12] [22] Adım5: Tüm elemanlar bölündü. Şimdi kendi içlerinde bir sıralama yapacağız. [16,21] [11] [8,12] [22] Adım6: Tamamen bölünen diziyi birleştirmeye devam ediyoruz. [11,16,21] [8,12,22] Adım 7: Bu aşamada elimizde 2 tane dizi olmuş oldu. Birleştiriyoruz ve birleşirken sıralanıyorlar. [8,11,12,16,21,22]

Big-O gösterimini yazınız. O(nlogn)
patika.dev
