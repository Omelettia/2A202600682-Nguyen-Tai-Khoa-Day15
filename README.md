# TRACK DECISION MEMO – Day 15

**Họ tên:** Nguyễn Tài Khoa　　　　　　**Pathway:** B

---

## ① ĐỊNH HƯỚNG – vài job/role mình hướng tới + kỹ năng mỗi job đòi hỏi (từ JD thật + report)

- Job **Backend Engineer**　→ kỹ năng cần: API design, database (SQL/NoSQL), system design, Docker, CI/CD, testing
- Job **AI/MLOps Engineer**　→ kỹ năng cần: Docker/Kubernetes, cloud (AWS/GCP), CI/CD cho ML pipeline, model serving, monitoring, data pipeline
- Job **AI Engineer**　→ kỹ năng cần: LLM API, RAG pipeline, embedding/vector store, prompt engineering, eval framework, Python

---

## ② ĐỐI CHIẾU BẢN THÂN – từ Phase 1

- Những việc mình đã làm được (liệt kê tự do, không giới hạn):

  Build được chatbot RAG tư vấn pháp luật (Luật BVDLCN / NĐ 13 / NĐ 356). Test được với eval (RAGAS — faithfulness, context recall, answer relevancy). Trace được lỗi trong pipeline. Kết nối với vector database (ChromaDB). Deploy được ứng dụng lên cloud (Railway). Thử với nhiều embedding model (multilingual-e5, Vietnamese-bi-encoder). Thiết kế chunking theo điều/khoản để giữ citation. Viết guardrails (disclaimer, chống hallucination, từ chối câu ngoài phạm vi). Có nền tảng backend Laravel/PHP — đã build và deploy Shopify app (API design, PostgreSQL, Redis, S3, queue). Làm việc với Docker, CI/CD cơ bản.

- Loại công việc cho mình năng lượng, muốn làm tiếp: Build hệ thống end-to-end từ backend đến AI pipeline, thấy sản phẩm chạy được trên production

---

## ③ KỸ NĂNG MÌNH ĐỊNH PHÁT TRIỂN TỚI

- **MLOps / CI/CD cho AI** , **Cloud Infrastructure (AWS/GCP)** , **Model Serving & Monitoring**
- Gap lớn nhất + thứ mình sẽ build để cho thấy tiến bộ: Chưa có kinh nghiệm production-level infrastructure (Kubernetes, GPU FinOps, model drift monitoring) → sẽ build một AI pipeline hoàn chỉnh với CI/CD, monitoring stack, và auto-scaling trên cloud

---

## ④ QUYẾT ĐỊNH TRACK

- Track chọn: **T2 Data & Infrastructure**
  vì: Nền tảng backend sẵn có + Track 2 stack trực tiếp lên đó (Docker → Kubernetes → MLOps → Model Serving). Kỹ năng infra khó tự học nếu không có môi trường thực hành với pipeline thật. Thị trường VN đang thiếu MLOps Engineer (nhu cầu tăng ~22%/năm). Foundation phase đã cover đủ nội dung Track 3 (RAG, multi-agent, tool calling) nên không cần học lại.
- Track cân nhắc nhưng KHÔNG chọn + lý lẽ mạnh nhất cho nó: **T1 AI Product** — giúp cân bằng kỹ năng business/product thinking, hiểu PRD, stakeholder management. Lý lẽ mạnh nhất: nếu muốn chuyển hướng sang Product Manager hoặc AI PM thì Track 1 sẽ cho nền tảng tốt hơn.
- Dấu hiệu sẽ khiến mình xem lại lựa chọn: Nếu nhận ra mình muốn pivot sang product/strategy thay vì engineering, hoặc nếu thị trường backend + infra bão hòa đột ngột trong khi AI PM demand tăng mạnh

---

## ⑤ ĐỊNH HƯỚNG & CHUẨN BỊ (ghi mở – có gì ghi nấy)

- Định hướng tiếp theo: Đi sâu vào AI Infrastructure trong 3 tuần specialization → tận dụng môi trường có pipeline thật để thực hành Kubernetes, model serving, GPU FinOps. Song song đó, tiếp tục phát triển chatbot pháp luật như side project (đã có MVP) để có portfolio AI end-to-end. Sau chương trình, target vị trí Backend/AI Engineer hoặc MLOps Engineer — ưu tiên công ty có hệ thống AI production thật, không nhất thiết ở Vin. Câu hỏi còn mở: liệu có nên invest thêm vào Golang/Rust cho high-performance backend, hay tập trung Python ecosystem cho AI?