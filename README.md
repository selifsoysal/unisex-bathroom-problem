# Unisex Bathroom Problem

Bu proje, **Unisex Bathroom Problem** olarak bilinen klasik bir semafor problemini çözmeyi amaçlamaktadır. 
Problemin çıkış noktası, bir çalışan tarafından kadın tuvaletinin uzakta olması nedeniyle erkek tuvaletinin unisex olarak kullanılmasının önerilmesidir.

---

## Problem Tanımı

- Aynı anda yalnızca bir cinsiyet tuvaleti kullanabilir.
- Aynı cinsiyetten en fazla üç kişi aynı anda tuvaleti kullanabilir.
- Bu eşzamanlılık koşullarının sağlanması için uygun senkronizasyon ve semafor teknikleri gereklidir.

---

## Problemin Zorlukları

- **Deadlock**: Erkekler ve kadınlar karşılıklı olarak birbirlerinin girişini engellerse, tuvaleti kimse kullanamaz.
- **Starvation**: Bir cinsiyet sürekli tuvalete erişim sağlarken, diğer grup uzun süre bekleyebilir.

---
