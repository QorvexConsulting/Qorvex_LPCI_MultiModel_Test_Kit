# Qorvex_TestRunner™ – LPCI Multi-Model Test Kit

This package contains the official test runner from Qorvex Consulting to evaluate Logic-layer Prompt Control Injection (LPCI) risks across multiple large language models (LLMs).

## Included Models:
- Meta LLaMA 3 (via OpenRouter)
- Mixtral-8x7b (via OpenRouter)
- Gemini 2.5 Pro (via Google)

## Files:
- `Qorvex_TestRunner_LPCI_MultiModel.py` – Full multi-model test script
- `README.md` – This guide
- `LICENSE.txt` – Use restrictions

## Usage:
1. Install dependencies:
   ```bash
   pip install pandas requests tqdm google-generativeai
   ```
2. Replace the API keys in the script.
3. Place your test CSV (e.g., `LPCI_Interactive_Manual_Test_Logbook.csv`) in the same folder.
4. Run:
   ```bash
   python Qorvex_TestRunner_LPCI_MultiModel.py
   ```

## Output:
- `LLaMA3_Results.csv`
- `Mixtral_Results.csv`
- `Gemini_Results.csv`

---

© 2025 Qorvex Consulting. All rights reserved.
