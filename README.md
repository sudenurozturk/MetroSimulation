# MetroSimulation
Akbank Python ve Yapay Zeka Bootcamp'i Metro Simülasyonu projesi.  

## **Proje Tanımı**  
Bu proje, metro istasyonları arasında **en az aktarmalı** ve **en hızlı rotayı** hesaplayan bir sistemdir. **BFS (Breadth-First Search)** algoritması en az aktarma yapılan rotayı, **A* algoritması** ise en kısa sürede ulaşılacak rotayı bulmak için kullanılmıştır.  

## **Teknik Detaylar**  
- **İstasyonlar:** Her istasyon, bağlı olduğu hat ve komşu istasyon bilgilerini içerir.  
- **Bağlantılar:** İki istasyon arasındaki geçiş süresi ile birlikte tanımlanır.  
- **Algoritmalar:**  
  - **BFS:** En az aktarmalı rota için kullanılır.  
  - **A***: En kısa sürede hedefe ulaşmak için kullanılır.  

## **Test Sonuçları**  
1. **AŞTİ → OSB**  
   - **En az aktarma:** AŞTİ → Kızılay → Ulus → Demetevler → OSB  
   - **En hızlı rota (14 dk):** AŞTİ → Kızılay → Demetevler → OSB  

2. **Batıkent → Keçiören**  
   - **En az aktarma:** Batıkent → Demetevler → Gar → Keçiören  
   - **En hızlı rota (21 dk):** Batıkent → Demetevler → Gar → Keçiören  

3. **Keçiören → AŞTİ**  
   - **En az aktarma:** Keçiören → Gar → Sıhhiye → Kızılay → AŞTİ  
   - **En hızlı rota (24 dk):** Keçiören → Gar → Sıhhiye → Kızılay → AŞTİ  

## **Sonuç**  
Sistem, **BFS** ve **A*** algoritmalarını kullanarak farklı istasyonlar arasında en uygun güzergahları başarıyla hesaplamaktadır.
