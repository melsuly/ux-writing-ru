# ux-writing-ru

Скилл для Claude Code: правила интерфейсных текстов на русском. Кнопки, ошибки, подтверждения удаления, тосты, пустые экраны, подсказки в формах, онбординг, сообщения ботов.

Claude подхватывает его сам, когда пишет или правит тексты интерфейса. Вызвать вручную: `/ux-writing-ru`.

## Установка

Для себя, во всех проектах:

```bash
git clone https://github.com/melsuly/ux-writing-ru.git ~/.claude/skills/ux-writing-ru
```

Только для одного проекта (запускать из корня проекта):

```bash
git clone https://github.com/melsuly/ux-writing-ru.git .claude/skills/ux-writing-ru
```

Без git, одним файлом:

```bash
mkdir -p ~/.claude/skills/ux-writing-ru && curl -fsSL https://raw.githubusercontent.com/melsuly/ux-writing-ru/main/SKILL.md -o ~/.claude/skills/ux-writing-ru/SKILL.md
```

Перезапусти Claude Code, если он был открыт. Проверка: в списке скиллов появится `ux-writing-ru`.

Обновить:

```bash
git -C ~/.claude/skills/ux-writing-ru pull
```

## Что внутри

Всё в [SKILL.md](SKILL.md): что выяснить до того, как писать, правила по типам элементов, язык и тон, запрещённые тёмные паттерны, чек-лист и примеры «было → стало».

## Источники

Правила собраны и пересказаны по статьям:

- [Хабр, блог МойОфис](https://habr.com/ru/companies/ncloudtech/articles/765504/)
- [Блог агентства «Сделаем»](https://sdelaem.agency/blog/kto-takoj-ux-kopirajter-i-kak-pisat-ux-teksty/)
- [Блог in-aim.ru](https://www.in-aim.ru/blog/kak-napisat-ponyatnyy-ux-tekst/)
- [Журнал Яндекс Образования](https://education.yandex.ru/journal/interfejsnye-teksty)
- [Хабр, блог Dodo Engineering](https://habr.com/ru/companies/dododev/articles/744670/)
