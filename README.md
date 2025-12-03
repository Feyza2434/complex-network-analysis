# Complex Network Analysis
Bu proje, NetworkX kütüphanesi kullanılarak karmaşık ağların analizini gerçekleştirmektedir. 
InputFileEdges.csv ve InputFileNodes.csv dosyalarındaki veriler kullanılarak hem yönsüz (Graph)
hem de yönlü (DiGraph) ağlar oluşturulmuş ve çeşitli ağ istatistikleri hesaplanmıştır.


1. Veri Yükleme ve Ön İşleme
- Kenar ve düğüm verileri CSV dosyalarından okunmuştur.
- Yinelenen kenarlar temizlenmiştir.

2. Yönsüz ve Yönlü Ağ Oluşturma
- 'nx.Graph()' ile yönsüz ağ
- 'nx.DiGraph()' ile yönlü ağ oluşturulmuştur.
- Ağlar matplotlib kullanılarak görselleştirilmiştir.

3. Derece ve Derece Dağılımı Analizi
- Her düğümün derecesi hesaplanmıştır.
- Ortalama derece bulunmuştur.
- Derece histogramı çizilmiştir.

4. Merkezilik Ölçümleri
Aşağıdaki merkezilik türleri hesaplanmıştır:
- Degree centrality
- Closeness centrality
- Betweenness centrality
- Eigenvector centrality
- Katz centrality
- PageRank

5. Topluluk Bulma ve Modularity
- Greedy modularity yöntemi ile topluluklar çıkarılmıştır.
- Topluluk yapısına göre 'modularity' değeri hesaplanmıştır.

6. Ağın Temel Özellikleri
- Yoğunluk (density)
- Ortalama kümeleşme katsayısı 
- Graf bağlantılı ise çap 

7. Kritik Düğümlerin Belirlenmesi
- PageRank değerlerine göre en güçlü 3 düğüm tespit edilmiştir.
- Bu düğümler ağdan çıkarılarak yeni ağın yapısı görselleştirilmiştir.

Amaç
Bu proje, karmaşık ağ analizi konularını uygulamalı olarak deneyimlemek, ağ yapısını ve ağ içindeki kritik noktaları veri bilimi perspektifinden incelemek amacıyla hazırlanmıştır.
