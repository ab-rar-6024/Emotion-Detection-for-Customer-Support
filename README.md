Text review/email.
Voice note (transcribe with Whisper → NLU).
Optional uploaded image (e.g., damaged product photo → describe with LLaVA or CLIP + fuse with text).

Core NLU tasks:

Joint intent classification (refund request, technical issue, praise, etc.).
Fine-grained emotion + urgency detection (angry + high urgency → escalate).
Aspect-based sentiment on specific issues (delivery delay, product defect).
Generate empathetic, personalized response using fine-tuned LLM (e.g., Llama-3-8B or Mistral).

Advanced twist: Build a small agent that decides next action (reply, escalate to human, search internal KB, generate return label).
Use datasets: SemEval ABSA, customer support on Kaggle, Indic language complaint datasets.
This combines classic NLU with emerging multimodal + agent capabilities.
