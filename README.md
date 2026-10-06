# ZINK презентация

Този проект генерира PowerPoint презентация на български език за ZINK (Zero Ink) технологията.

## Стартиране

```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
python scripts/generate_presentation.py
```

Готовият файл се създава в:

`dist/ZINK_Tehnologiya_Digitalen_Pechat.pptx`

Презентацията е създадена от нулата във формат 16:9 с тъмносини и светли слайдове, CMY акценти, технически схеми, таблици и слайд с видео линк.
