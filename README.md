# Subra Cache

Chrome и Microsoft Edge разширение за бързо изчистване на кеша на Subra.

## Какво прави?

Разширението добавя 3 бутона:

- **Clear Localization Cache**
- **Clear Database Cache**
- **Clear All Cache**

Не е необходимо да въвеждате потребителско име или парола. Разширението използва текущата ви login сесия в Subra.

---

# Инсталация

## Google Chrome

### 1. Изтеглете проекта

Клонирайте repository-то:

```bash
git clone https://github.com/YOUR-ORGANIZATION/subra-cache.git
```

или изтеглете проекта като ZIP и го разархивирайте.

### 2. Отворете Chrome Extensions

В адресната лента отворете:

```text
chrome://extensions/
```

### 3. Включете Developer mode

В горния десен ъгъл включете:

```text
Developer mode
```

### 4. Заредете разширението

Натиснете:

```text
Load unpacked
```

и изберете папката на проекта:

```text
subra-cache/
```

Готово. **Subra Cache** вече е инсталиран.

---

# Microsoft Edge

### 1. Изтеглете проекта

Изтеглете repository-то като ZIP и го разархивирайте.

### 2. Отворете Edge Extensions

В адресната лента отворете:

```text
edge://extensions/
```

### 3. Включете Developer mode

Включете:

```text
Developer mode
```

### 4. Заредете разширението

Натиснете:

```text
Load unpacked
```

и изберете папката:

```text
subra-cache/
```

Готово. **Subra Cache** вече е инсталиран.

---

# Използване

1. Влезте в административния панел на Subra.
2. Отворете `subra.bg`.
3. Натиснете иконата **Subra Cache** в браузъра.
4. Изберете какво искате да изчистите.

### Clear Localization Cache

Изчиства кеша за локализацията.

### Clear Database Cache

Изчиства кеша на базата данни.

### Clear All Cache

Изчиства целия кеш.

За **Clear All Cache** ще се появи потвърждение преди изпълнението.

---

# Keyboard Shortcuts

Можете да използвате и клавишни комбинации:

| Комбинация | Действие |
|---|---|
| `Ctrl + Shift + L` | Localization Cache |
| `Ctrl + Shift + D` | Database Cache |
| `Ctrl + Shift + A` | All Cache |

---

# Context Menu

Можете да използвате и десния бутон на мишката:

```text
Right Click
    ↓
Subra Cache
    ├── Clear Localization Cache
    ├── Clear Database Cache
    └── Clear All Cache
```

---

# Важно

Разширението работи само със Subra домейни:

```text
https://subra.bg
https://*.subra.bg
```

Трябва предварително да сте влезли в административния панел на Subra.

Разширението **не съхранява пароли и данни за вход**.

---

## Версия

**1.0.0**
