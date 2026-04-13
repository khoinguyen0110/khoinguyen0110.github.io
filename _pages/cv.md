---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 2022 - Hiện tại: Sinh viên Kỹ thuật, Học viện Công nghệ Bưu chính Viễn thông (PTIT).
* Lĩnh vực nghiên cứu: Internet of Things (IoT), Hệ thống nhúng và Edge AI.

Work experience
======
* Xuân 2026: Thực tập sinh Dự án AIoT
  * Học viện Công nghệ Bưu chính Viễn thông (PTIT)
  * Nhiệm vụ: Phát triển hệ thống giám sát nhiệt độ LM35, thiết kế giao diện PC App và xây dựng hệ thống Smart Home cho người cao tuổi.
  * Công cụ: Arduino, C#, SolidWorks, Proteus.

Skills
======
* Hệ thống nhúng & IoT: 
  * Lập trình vi điều khiển: Arduino, ESP32, STM32.
  * Giao tiếp: MQTT, HTTP, UART, I2C.
* Thiết kế & Mô phỏng:
  * 3D Modeling: SolidWorks.
  * Mô phỏng mạch: Proteus.
* Phần mềm & Dữ liệu:
  * Ngôn ngữ: C/C++, C#, Python.
  * Công cụ: Git/GitHub, Docker, PostgreSQL.
* AI biên: 
  * Huấn luyện mô hình TinyML trên Edge Impulse.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Tham gia các dự án nghiên cứu nhóm về Smart City và Edge Computing tại Lab trường.