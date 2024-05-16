# Prompt Engineering For Developer

## Deskripsi

Repository ini berisi tutorial menggunakan Large Language Model (LLM), terutama model GPT dari OpenAI. LLM yang dikembangkan oleh OpenAI (GPT 3 - GPT 4) merupakan model LLM hasil tuning menggunakan Reinforment Learning Human Feedback (RLHF) dengan instruksi.

## Referensi

- Github repo berisi contoh dan teknik promt dari OpenAI [openai cookbook](https://github.com/openai/openai-cookbook)
- Situs kumpulan informasi untuk belajar prompt [learnprompting.org](https://learnprompting.org/)
- Resource untuk mempelajari deep learning [d2l.ai](https://www.d2l.ai/)

## Prerequisite

- API key dari akun OpenAI (bisa daftar menggunakan trial)
- API key disimpan di file `.env` dengan format `OPENAI_API_KEY=<api-key>`.
- Python requirements:
  - `python==3.10.0`
  - `openai==0.27.0`
  - `python-dotenv-vault`
  - `ipykernel`

## Daftar Isi

### Prompt Engineering

| Nama Notebook | Summary |
|---------------|---------|
|[l2-guidelines.ipynb](./Prompt%20Engineering/l2-guidelines.ipynb)| Beberapa cara dasar menggunankan prompt di model GPT 3.5 Turbo |
|[l3-iterative-prompt-development.ipynb](./Prompt%20Engineering/l3-iterative-prompt-development.ipynb) | Metode development dan perbaikan prompt untuk mendapatkan prompt terbaik|
|[l4-summarizing.ipynb](./Prompt%20Engineering/l4-summarizing.ipynb) | Teknik prompt untuk summary data teks|
|[l5-inferring.ipynb](./Prompt%20Engineering/l5-inferring.ipynb) | Teknik prompt untuk membuat klasifikasi atau analisa|
| [l6-transforming](./Prompt%20Engineering/l6-transforming.ipynb) | Notebook ini berisi contoh prompt untuk melakukan transformasi teks data. Seperti melakukan translate |
| [l7-expanding.ipynb](./Prompt%20Engineering/l7-expanding.ipynb) | Menggunakan teknik prompt yang sudah dipelajari sebelumnya untuk membuat customer service email berdasarkan review yang diberikan customer |
| [l8-chatbot.ipynb](./Prompt%20Engineering/l8-chatbot.ipynb) | Membuat prompt di dalam bentuk percakapan. Melakukan personalisasi untuk task dan sifat tertentu |

### LangChain

| Nama Notebook | Summary |
|---------------|---------|
| [L1-Model_prompt_parser.ipynb](./LangChain/L1-Model_prompt_parser.ipynb) | Contoh menggunakan prompt template, output parser, python dictionary untuk mendesain prompt menjadi lebih modular |
| [L2-Memory.ipynb](./LangChain/L2-Memory.ipynb) | Contoh penggunaan memory dan berbagai macam jenis memory yang ada di LangChain |
| [L3=Chains.ipynb](/LangChain/L3-Chains.ipynb) | Pengenalan dan contoh penggunaan chain |
