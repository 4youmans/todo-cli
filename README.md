# Todo CLI

Простое приложение управления задачами из терминала.

## Команды

| Команда | Что делает |
|---------|------------|
| `add "title"` | добавить задачу |
| `list` | показать список |
| `done ID` | отметить выполненной |
| `remove ID` | удалить |

## Запуск

```bash
python main.py add "купить хлеб"
python main.py list
python main.py done 1

---

### Шаг 7.2. Коммит и Push

1. Source Control → `+` на `README.md`.
2. Коммит: `docs: add README`
3. Push.

---

### Шаг 7.3. Создай тег релиза

В терминале:
```bash
git tag -a v1.0.0 -m "First release: add, list, done, remove"
git push origin --tags