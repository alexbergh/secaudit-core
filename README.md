> SecAudit-core

**SecAudit-core** —  CLI-инструмент для аудита безопасности Linux-систем по профилям ФСТЭК, СТЭК, NIST и ISO.  
Ориентирован на автоматизацию, масштабируемость и гибкость (через YAML).

- Поддержка YAML-профилей
- Аудит SSH, PAM, SUDO, root-настроек
- JSON-отчёт с PASS/FAIL
- Расширяемая архитектура

```bash
git clone https://github.com/alexbergh/secaudit-core.git
cd secaudit-core
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 main.py
