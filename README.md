# -Plant-Description-Filler-Python-Gemini-AI
This script auto-fills descriptive fields for 600+ plant names using Google Gemini API and Python. Ideal for gardeners, nurseries, and plant sellers.

## 🔧 Features

- Uses Gemini 1.5 Pro API (Free Tier)
- Inputs plant names from Excel (A2:A611)
- Outputs:
  - Botanical Name
  - Common Name
  - Blooming Season
  - Max Height
  - Light
  - Water
  - Soil
  - Uses
- Auto-resume + save after each row

## 🧪 Example Output

| Plant               | Botanical Name | Common Name | Blooming | Height | Light     | Water | Soil | Uses         |
|--------------------|----------------|-------------|----------|--------|-----------|-------|------|--------------|
| Nerium Mini        | Nerium oleander| Oleander    | Summer   | 3m     | Full Sun  | Medium| Loamy| Ornamental   |

## 📦 Setup

```bash
pip install google-generativeai openpyxl
