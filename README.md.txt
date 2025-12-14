# CPU Scheduling Algorithms Project

Bu projede işletim sistemlerinde kullanılan CPU zamanlama
algoritmaları implement edilmiştir ve performansları
iki farklı veri seti (Case 1 ve Case 2) üzerinden
karşılaştırılmıştır.

## Kullanılan Algoritmalar
- First Come First Served (FCFS)
- Shortest Job First (Preemptive)
- Shortest Job First (Non-Preemptive)
- Round Robin
- Priority Scheduling (Preemptive)
- Priority Scheduling (Non-Preemptive)

## Çalışma Mantığı
- Giriş verileri data klasöründen okunur
- Algoritmalar src klasöründe çalışır
- Sonuçlar otomatik olarak results klasörüne yazılır
- Her algoritma ve her case için ayrı çıktı dosyası üretilir

## Değerlendirilen Metrikler
- Gantt Chart (Zaman Tablosu)
- Ortalama ve Maksimum Bekleme Süresi
- Ortalama ve Maksimum Turnaround Süresi
- Throughput
- CPU Utilization
- Context Switch Sayısı
