# 👁️ Computer Vision HCMUS
**Nhóm Nghiên cứu & Phát triển Thị giác Máy tính — VNUHCM-US**

[![GitHub Organization](https://img.shields.io/badge/GitHub-Organization-181717?style=for-the-badge&logo=github)](https://github.com/Computer-Vision-HCMUS)
[![Focus](https://img.shields.io/badge/Focus-Computer_Vision_&_AIoT-blue?style=for-the-badge&logo=pytorch)](#)
[![Location](https://img.shields.io/badge/Location-HCMUS_VNUHCM-00529B?style=for-the-badge)](#)

*Tập hợp các dự án nghiên cứu, sản phẩm mã nguồn mở và ứng dụng AI thực tiễn do sinh viên & cộng tác viên tại Trường Đại học Khoa học Tự nhiên, ĐHQG-HCM thực hiện.*

---

## 📌 Giới thiệu

**Computer-Vision-HCMUS** tập trung giải quyết các bài toán cốt lõi trong **Thị giác Máy tính**, **Hệ thống Đa phương thức (Multimodal)** và **AIoT nhúng**. Các sản phẩm của nhóm hướng tới khả năng triển khai thực tế (production-ready) cùng tài liệu và pipeline có thể tái lập (reproducible).

---

## 🎯 Hướng nghiên cứu cốt lõi

```ascii
┌─────────────────────────────────────────────────────────────────────────┐
│                    COMPUTER VISION & AI LAB (HCMUS)                     │
├──────────────────────────────────┬──────────────────────────────────────┤
│ 🔍 Multimodal Retrieval          │ 🎬 Video Intelligence                │
│  · Embeddings hợp nhất (SCALE)   │  · Tóm tắt động (Frame Importance)    │
│  · Chỉ mục Faiss HNSW & Rerank   │  · Fusion: Vision + Speech + Text    │
├──────────────────────────────────┼──────────────────────────────────────┤
│ 🤖 AIoT & Edge Intelligence      │ 📐 Applied Mathematics               │
│  · Cảm xúc thời gian thực (ESP32)│  · Canonical Correlation Analysis    │
│  · AI Assistant & Cloud Backend  │  · Diễn giải hình học Multivariate   │
└──────────────────────────────────┴──────────────────────────────────────┘
```

---

## 🚀 Dự án tiêu biểu

| Repository | Mô tả & Giải pháp | Công nghệ | Status |
| :--- | :--- | :--- | :---: |
| [**Product-Ecommerce-Image-Retrieval**](https://github.com/Computer-Vision-HCMUS/Product-Ecommerce-Image-Retrieval) | Truy hồi sản phẩm E-commerce đa phương thức (M5Product) dựa trên SCALE, Faiss HNSW và metadata reranking. | `Python` `PyTorch` `FastAPI` `React` `Faiss` | `Active` |
| [**AIoT-Server**](https://github.com/Computer-Vision-HCMUS/AIoT-Server) | Backend cho hệ thống EmotiCare AIoT: pairing thiết bị, đồng bộ emotion session, gợi ý hoạt động, AI Chatbot. | `FastAPI` `PostgreSQL` `Gemini` `Whisper` | `Active` |
| [**AIoT-Hardware**](https://github.com/Computer-Vision-HCMUS/AIoT-Hardware) | Firmware ESP32 cho thiết bị EmotiCare: giao diện TFT, đo cảm xúc, phát media, chat đồng hành, Wi-Fi provisioning. | `C++` `PlatformIO` `Arduino` | `Active` |
| [**video-summarize**](https://github.com/Computer-Vision-HCMUS/video-summarize) | Tóm tắt video dựa trên độ quan trọng khung hình (SumMe/TVSum) kết hợp ResNet-50, Whisper, SBERT & BiLSTM Attention. | `PyTorch` `FFmpeg` `Streamlit` | `Research` |
| [**MSA-CCA**](https://github.com/Computer-Vision-HCMUS/MSA-CCA) | Nghiên cứu CCA cho bài toán MSA: diễn giải hình học, báo cáo LaTeX và demo minh họa lý thuyết. | `Python` `Streamlit` `LaTeX` | `Research` |

---

## ⚡ Bắt đầu nhanh

Chọn dự án bạn muốn làm việc và thực hiện clone về máy local:

**1. Truy hồi sản phẩm đa phương thức (SCALE + Faiss)**
```bash
git clone https://github.com/Computer-Vision-HCMUS/Product-Ecommerce-Image-Retrieval.git
cd Product-Ecommerce-Image-Retrieval
python -m venv .venv && source .venv/bin/activate  # Trên Windows: .venv\Scripts\Activate.ps1
pip install -r app/requirements-windows.txt
```

**2. AIoT Server (Backend EmotiCare)**
```bash
git clone https://github.com/Computer-Vision-HCMUS/AIoT-Server.git
cd AIoT-Server
pip install -r requirements.txt
alembic upgrade head
uvicorn app.main:app --reload
```

**3. AIoT Hardware (Firmware ESP32)**
```bash
git clone https://github.com/Computer-Vision-HCMUS/AIoT-Hardware.git
cd "AIoT-Hardware/Smart Device"
pio run
```

**4. Tóm tắt Video**
```bash
git clone https://github.com/Computer-Vision-HCMUS/video-summarize.git
cd video-summarize
python -m venv .venv && source .venv/bin/activate  # Trên Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

**5. Lý thuyết MSA / CCA**
```bash
git clone https://github.com/Computer-Vision-HCMUS/MSA-CCA.git
cd MSA-CCA
pip install -r requirements.txt
```

---

## 🤝 Quy trình Đóng góp (Contribution)

Chúng tôi hoan nghênh mọi đóng góp từ sinh viên, cộng tác viên và các nhà nghiên cứu!

* **Mở Issue:** Mô tả lỗi, đề xuất ý tưởng mới hoặc đặt câu hỏi về lý thuyết.
* **Tạo Pull Request:** Fork repo → tạo branch mới → gửi PR ngắn gọn, mô tả rõ thay đổi.
* **Tiêu chuẩn Model/Algorithm:** Với các thay đổi về thuật toán hoặc model, vui lòng đính kèm số liệu / ablation study hoặc link đến notebook/báo cáo.

> 💡 *Xem README riêng tại từng repository để biết quy trình chi tiết.*

---

<div align="center">
  <sub>Developed with ❤️ by Students & Researchers at Faculty of IT, HCMUS</sub>
</div>
