# Dhofar Flavor Chat (RAG)

هذا المشروع شات بوت متخصص في أكلات محافظة ظفار.
يعتمد على أسلوب RAG (استرجاع + توليد) باستخدام:
- استخراج البيانات من ملف DOCX
- تقسيمها إلى Sections (وصف/مكونات/طريقة...)
- بناء Vector Store باستخدام FAISS + Embeddings
- توليد الإجابات عبر Ollama (محليًا)

## Structure
- data/raw: الملف الأصلي
- data/processed: مخرجات المعالجة (recipes, docs, variants)
- vectorstore/faiss_index: قاعدة FAISS المحفوظة
- interface: واجهة Gradio (لاحقًا يمكن ربطها بموقع)

Generated: 2026-01-14 23:14
