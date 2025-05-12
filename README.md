# A_Star_Algorithm
Algorithm implementation and analysis for class project

## 🔍 Algoritmanın Ne Yaptığı
A* algoritması, en kısa yolu bulmak için kullanılan bir arama algoritmasıdır.

### 📂 Kategori
- Arama algoritmaları
- Grafik (graph) tabanlı algoritmalar

### ⚙️ Çözüm Yöntemi
- Heuristic (tahmin edici) + Gerçek mesafe = f(n) = g(n) + h(n)

---

## ⏱️ Ne Zaman ve Neden Kullanılır?
- Harita üzerinde yol bulma
- Oyunlarda yapay zekâ hareketi
- Robotik rota planlama

---

## 🧮 Karmaşıklık Analizi
- Zaman: O(b^d)
- Alan: O(b^d)
  - b: dallanma faktörü
  - d: çözümün derinliği

---

## 🪜 Adımlar
1. Başlangıç düğümünü open list’e ekle
2. En düşük `f(n)` değerine sahip düğümü seç
3. Komşularını değerlendir ve güncelle
4. Hedefe ulaşana kadar devam et

---

## 🎯 Kullanım Yerine Ait Örnek
- Başlangıç: (0, 0)
- Hedef: (4, 4)
- 5x5'lik grid üzerinde yol bulur.

---

## ✅ Avantajları
- En kısa yolu bulur
- Heuristik ile hızlandırılabilir

## ❌ Dezavantajları
- Bellek tüketimi yüksektir (çok düğüm saklar)

---

## 📕 Kaynakça

- Hart, P. E., Nilsson, N. J., & Raphael, B. (1968). "A Formal Basis for the Heuristic Determination of Minimum Cost Paths". IEEE Transactions on Systems Science and Cybernetics, 4(2), 100-107.
- Russell, S., & Norvig, P. (2020). Artificial Intelligence: A Modern Approach (4th ed.). Pearson.
- Lester, P. (2005). "A* Pathfinding for Beginners". GameDev.net. [Çevrimiçi]. Erişilebilir: https://www.gamedev.net/reference/articles/article2003.asp
- Stout, B. (1996). "Smart Moves: Intelligent Path-finding". Game Developer Magazine.
- Millington, I., & Funge, J. (2019). Artificial Intelligence for Games (3rd ed.). CRC Press.

---

# Hazırlayanlar

- Yusuf Akın
- Furkan Danışık
