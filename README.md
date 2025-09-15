⚖️ Indian Law AI — Fine-Tuning Falcon-7B & LLaMA 2

AI meets Indian law.
This project fine-tunes Falcon-7B and LLaMA 2 with carefully crafted datasets to make them proficient in Indian constitutional and legal knowledge.

It’s more than just a training run — it’s a step toward AI-assisted legal reasoning.

🌟 Project Highlights

Dual Models: Falcon-7B & LLaMA 2, optimized for Indian law understanding

Lightweight Fine-Tuning: Using PEFT & QLoRA for memory-efficient adaptation

Rich Dataset: Thousands of curated instructions on constitutional law, rights, and case contexts

Practical Application: Towards building AI assistants for legal research, drafting, and education

📚 Dataset Journey

We started small with 150 handcrafted Q&As.
Now, the dataset has grown into 3,300+ structured instructions.

Each record follows a four-column schema:

instruction → the task/question

input → optional context

output → model’s target response

prompt → combined instruction for training

Datasets available on Hugging Face:

Constitution of India Instruction Set

Articles Constitution 3300+

LLAMA2 Legal Dataset 4.4k

📸 Dataset pipeline visualization:


🛠️ Fine-Tuning Workflow

We apply parameter-efficient fine-tuning (PEFT + QLoRA), enabling large models to adapt with:

Lower memory usage

Faster iteration cycles

Retention of general knowledge while specializing in law

📸 Training architecture overview:


📊 Monitoring Training

TensorBoard Integration: Track metrics like loss, accuracy, and validation performance in real time

Visualization First: Progress graphs and embeddings help in debugging and optimization

Transparent Process: Anyone can reproduce or extend the experiments

🚀 What’s Next?

Expand dataset beyond constitutional law into case law, contracts, and criminal law

Deploy a law-aware chatbot demo using Falcon-7B & LLaMA 2

Benchmark against baseline GPT models for legal accuracy

🤝 Contributing

Want to help? Contributions are welcome — whether through dataset enrichment, model experiments, or evaluation benchmarks. Open a PR or start a discussion.

📜 License

This project is released under the MIT License.

clone

https://github.com/Jalagamdolu/Law_Affirm_AI_Gpt.git
