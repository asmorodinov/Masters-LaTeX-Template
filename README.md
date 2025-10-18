# Описание

Немного модифицированный шаблон для магистерской ВКР СКН из репозитория https://github.com/DimaTrushin/Term-Paper-LaTeX-Template

Основные изменения:
- `\usepackage{mathptmx}` - 14pt, Times New Roman
- `\counterwithin{figure}{section}`, `\counterwithin{lstlisting}{section}` (нумерация диаграмм и фрагментов кода)
- `\bibliographystyle{ugost2008}`
- Пример презентации в beamer
- в остальном, можно клонировать репозиторий Димы

# Пререквезиты
- perl
- inkscape (для svg)

# Как собрать
- VS Code + Latex Workshop
(нужно добавить `--shell-escape` в аргументы команд, но у меня всё равно заработало только на linux)
- либо можно использовать overleaf
