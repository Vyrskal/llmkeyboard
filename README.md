# LLM Keyboard - models and lab packs

Files for the LLM Keyboard Android app (an on-device language model replaces autocorrection and the suggestion strip):

- **NPU models** for MediaTek Dimensity 9500 (MT6993) - `files/npu` (big models in parts of < 100 MB, joined by the app)
- **the Russian corrector** sage-fredt5-distilled-95m (ai-forever, MIT) as GGUF Q8_0 - `files/fix` (in parts)
- **experiment packs** for the app's lab - `files/lab`
- **catalog.json** - the list the app's *Downloads* screen shows (it also links Google's official MT6993 models on Hugging Face)

The app downloads everything itself (Settings → Model → Downloads, or the lab). Only data files: nothing downloaded is executed.

---

Файлы для Android-приложения LLM Keyboard: модели для NPU (Dimensity 9500), пакеты опытов для лаборатории и
`catalog.json` - список для экрана «Загрузки» в приложении. Приложение скачивает всё само.
