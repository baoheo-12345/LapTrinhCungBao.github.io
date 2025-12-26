---
title: "Bài 4: Tạo giao diện người dùng với Java Swing"
date: 2025-12-26T21:10:00+07:00
draft: false
categories: ["Java"]
summary: "Thiết kế giao diện người dùng trực quan cho ứng dụng Desktop bằng thư viện Java Swing."
---
Swing giúp chúng ta tạo các cửa sổ, nút bấm (JButton), ô nhập liệu (JTextField) cho ứng dụng Desktop.

```java
JFrame frame = new JFrame("Ứng dụng của Bảo");
JButton btn = new JButton("Click Me");
frame.add(btn);
frame.setSize(300, 200);
frame.setVisible(true);