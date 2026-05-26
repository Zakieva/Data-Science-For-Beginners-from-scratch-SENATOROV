# Учёба SENATOROVAI — карта папок

Локальные репозитории: `Documents\GitHub`  
Копия в репозитории курса: `docs/README-УЧЕБА.md`  
Обновлено: **25.05.2026**

---

## С чего начать

| Задача | Куда идти |
|--------|-----------|
| Data Science (текущий курс) | Папка **`DS-course-2026`** → [`START-HERE.md`](../START-HERE.md) |
| Практика Git (#22) | Папка **`Kate-git`** |
| Карта всех папок | `Documents\GitHub\README-УЧЕБА.md` или этот файл |

**В Cursor и GitHub Desktop открывайте:** `DS-course-2026` и `Kate-git`.  
Ветка DS: **`Zakieva`**. Push домашек: `git push fork Zakieva`.

---

## Содержание

1. [Активная учёба](#активная-учёба)
2. [Рутина: отчёты и сдача](#рутина-отчёты-и-сдача)
3. [Git: remotes и push](#git-remotes-и-push)
4. [GitHub Desktop](#github-desktop)
5. [Архив и другие проекты](#архив-и-другие-проекты)

---

## Активная учёба

### DS-course-2026 — курс Data Science 2026

**Папка:** `DS-course-2026`  
**Ветка:** `Zakieva`  
**Домашки:** `projects/Zakieva/`  
**Лог уроков:** `projects/Zakieva/log.ipynb`

| Репозиторий | Назначение |
|-------------|------------|
| [SENATOROVAI/Data-Science-For-Beginners-from-scratch-course](https://github.com/SENATOROVAI/Data-Science-For-Beginners-from-scratch-course) | Upstream (школа), pull отсюда |
| [Zakieva/Data-Science-For-Beginners-from-scratch-SENATOROV](https://github.com/Zakieva/Data-Science-For-Beginners-from-scratch-SENATOROV) | Ваш форк — **push сюда** |

Подробный чеклист и команды: [`START-HERE.md`](../START-HERE.md)

### Kate-git — практика Git

**Папка:** `Kate-git`  
**Задание:** [#22 в SENATOROVAI/docs](https://github.com/SENATOROVAI/docs/issues/22)  
**Репозиторий:** [Zakieva/Kate-git](https://github.com/Zakieva/Kate-git)

---

## Рутина: отчёты и сдача

| Что | Куда |
|-----|------|
| Отчёт **пн и чт** до 21:00 (GMT+3) | [SCRUM discussions #3](https://github.com/SENATOROVAI/scrum/discussions/3) |
| Домашки + ссылка на коммит | [Telegram, топик](https://t.me/c/1937296927/765) |
| Инструкция стажировки | [SENATOROVAI/intro](https://github.com/SENATOROVAI/intro) |

---

## Git: remotes и push

Настроено в **`DS-course-2026`**:

| Remote | URL |
|--------|-----|
| `origin`, `upstream` | `https://github.com/SENATOROVAI/Data-Science-For-Beginners-from-scratch-course.git` |
| `fork` | `https://github.com/Zakieva/Data-Science-For-Beginners-from-scratch-SENATOROV.git` |

```powershell
cd DS-course-2026
git checkout Zakieva
git push fork Zakieva
```

История коммитов на форке: [ветка Zakieva](https://github.com/Zakieva/Data-Science-For-Beginners-from-scratch-SENATOROV/commits/Zakieva)

---

## GitHub Desktop

1. **File → Add local repository**
2. Добавить **`DS-course-2026`** и **`Kate-git`**
3. При необходимости — **`Zakieva`** (README профиля GitHub)
4. В `DS-course-2026`: ветка **`Zakieva`**, для push — remote **`fork`**

---

## Архив и другие проекты

Не путать с текущим курсом DS.

| Папка | Назначение |
|-------|------------|
| **ARCHIVE-Data-Science-SENATOROV** | Старая программа DS (2024–2026). Новые домашки **не** здесь |
| **Zakieva** | README профиля → [github.com/Zakieva](https://github.com/Zakieva) |
| **BUSINESS-ANALYST** | Курс бизнес-анализа (отдельно от DS) |
| **chinese-tech-transfer-oil-gas** | Проект: китайские технологии (нефтегаз) |
