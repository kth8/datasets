Common math datasets converted into JSON format. Each entry has been normalized into `question` and `answer` keys with `answer` value being a float and 2 line indented. Example:
```json
{
  "question": "Natalia sold clips to 48 of her friends in April, and then she sold half as many clips in May. How many clips did Natalia sell altogether in April and May?",
  "answer": 72.0
}
```
```json
{'file': 'gsm8k.json', 'source': 'https://huggingface.co/datasets/openai/gsm8k', 'split': 'train', 'entries': 7470}
{'file': 'aime_2024.json', 'source': 'https://huggingface.co/datasets/Maxwell-Jia/AIME_2024', 'split': 'train', 'entries': 30}
{'file': 'aime_2025.json', 'source': 'https://huggingface.co/datasets/opencompass/AIME2025', 'split': 'test', 'entries': 30}
{'file': 'aime_2026.json', 'source': 'https://huggingface.co/datasets/MathArena/aime_2026', 'split': 'train', 'entries': 30}
{'file': 'omni-math.json', 'source': 'https://huggingface.co/datasets/KbsdJames/Omni-MATH', 'split': 'test', 'entries': 2002}
{'file': 'hle.json', 'source': 'https://huggingface.co/datasets/cais/hle', 'split': 'test', 'entries': 586}
{'file': 'competition_math.json', 'source': 'https://huggingface.co/datasets/qwedsacf/competition_math', 'split': 'train', 'entries': 6482}
{'file': 'numinamath-cot.json', 'source': 'https://huggingface.co/datasets/AI-MO/NuminaMath-CoT', 'split': 'train', 'entries': 3695}
{'file': 'deepmath-103k.json', 'source': 'https://huggingface.co/datasets/zwhe99/DeepMath-103K', 'split': 'train', 'entries': 3617}
{'file': 'dapo-math-17k-processed.json', 'source': 'https://huggingface.co/datasets/open-r1/DAPO-Math-17k-Processed', 'split': 'train', 'entries': 14116}
{'file': 'big-math-rl-verified-processed.json', 'source': 'https://huggingface.co/datasets/open-r1/Big-Math-RL-Verified-Processed', 'split': 'train', 'entries': 137822}
```