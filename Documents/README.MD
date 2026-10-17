www.workartgroup.com

G0.079/ctrl7+xi

فهمت القصد يا عرّاب تماماً. سنقوم بهيكلة وتوثيق المشروع على خطى مستودعات `github` ولكن بتركيز تقني بحت وخالٍ من الحشو، بحيث يتم اختصار عمليات التشغيل في **اقل عدد أوامر أساسية** فقط، وجعل المرجعية متصلة ومحدثة مباشرة عبر الرابط `[https://raw.githubusercontent.com/Thebigboss1978/talk27/refs/heads/main/Documents/README.MD](https://raw.githubusercontent.com/Thebigboss1978/talk27/refs/heads/main/Documents/README.MD)`.

إليك الهيكلية التقنية المباشرة التي يتم تخزينها وتحديثها للتشغيل الفوري:

```markdown
# SEVEN-NEXUS SYSTEM

[![System Status](https://img.shields.io/badge/STATUS-SOVEREIGN-success.svg)]()
[![Engine](https://img.shields.io/badge/ENGINE-Kokoro%20%2F%20LocalAI-blue.svg)]()

ممر العمليات المركزية لنظام الأراب 777. معمارية موحدة لإدارة وكلاء الذكاء الاصطناعي، التوجيه الصوتي، والبوابات المحلية.

## 4 Core Operational Commands (أوامر التشغيل الأساسية)

1. **تشغيل النواة والمحرك الأساسي 
```

2. **تشغيل بوابة العمليات الخلفية (FastAPI Gateway):**
```bash
uvicorn main:app --host 127.0.0.1 --port 8000 --reload

```


3. **تشغيل محرك التوليد الصوتي المتقدم (Kokoro TTS):**
```bash
python -m mlx_audio.server --host 0.0.0.0 --port 5001

```


4. **تشغيل واجهة التفاعل والمراقبة (seVen/UI):**
```bash
npm run dev -- --port 3700

```



---

## Technical Routing & Gates

* **Port 8000:** OpenAI-compatible REST API & Core Gateway.
* **Port 5001:** Kokoro-82M High-Fidelity Audio Pipeline.
* **Port 3700 / 3600:** Real-time Web UI & Audio Control Nodes.
* **Port 7682:** Active Persistent Web Terminal (`ttyd`).

```

```
