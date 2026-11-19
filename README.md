# Wiki в git

Стартер с доклада: база знаний команды в git и процедуры для агента.

Агент отвечает **со страницы wiki** и даёт ссылку, которую можно открыть. Ошибку правят в странице. Merge в основную ветку нажимаете вы.

Сегодня нужны два скилла:

- `kb-search` — вопрос → ответ со ссылкой
- `kb-maintain` — заметка → страница → PR

Потом, когда появятся живой трекер и доки в других местах: `kb-snapshot` и `kb-index`. Это **шаблоны правил**, не готовые скиллы «подставьте Jira — заработает как у докладчика». Перед первым вызовом допишите свой источник — [GETTING-STARTED.md](GETTING-STARTED.md), раздел «Потом».

```
.
├── knowledge-base/     образец базы
│   └── AGENTS.md       правила для агента
└── skills/
    ├── kb-search/
    ├── kb-maintain/
    ├── kb-snapshot/    потом
    └── kb-index/       потом
```

Не отдавайте агенту merge. Не копируйте в wiki то, у чего уже есть дом (спека в другом репо, портал). `knowledge-base/AGENTS.md` и файлы `SKILL.md` читает агент.

Формат страниц — [OKF](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md). Процесс — [llm-wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

## Ваши шаги

На GitHub: **Использовать этот шаблон** — не Fork. Сюда не пушить и не открывать PR. Дальше — [GETTING-STARTED.md](GETTING-STARTED.md).
