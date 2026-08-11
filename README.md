<p align="center"><img src="icon.png" width="128" alt="ВАЛЄРА"></p>

# ВАЛЄРА · VALERA — вільний перемикач розкладок

[![release](https://img.shields.io/github/v/release/nsrosbr/valera?label=release&color=0F6CBD)](../../releases/latest)
![Ціна — безкоштовно](https://img.shields.io/badge/%D1%86%D1%96%D0%BD%D0%B0-%D0%B1%D0%B5%D0%B7%D0%BA%D0%BE%D1%88%D1%82%D0%BE%D0%B2%D0%BD%D0%BE-2e7d32)
![Телеметрія — відсутня](https://img.shields.io/badge/%D1%82%D0%B5%D0%BB%D0%B5%D0%BC%D0%B5%D1%82%D1%80%D1%96%D1%8F-%D0%BD%D0%B5%D0%BC%D0%B0%D1%94-3a2b96)
![Windows 10 / 11](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6)
![Розкладки — UA · RU · EN](https://img.shields.io/badge/%D1%80%D0%BE%D0%B7%D0%BA%D0%BB%D0%B0%D0%B4%D0%BA%D0%B8-UA%20%C2%B7%20RU%20%C2%B7%20EN-5560e6)

**Вільний локальний перемикач розкладок · UA · RU · EN**
_Free, private, spyware-free keyboard-layout switcher for Windows_

**ВАЛЄРА** автоматично виправляє текст, набраний не в тій розкладці, і перемикає
**UA / RU / English** за аналізом слова. Повністю **локально**: без мережі, без телеметрії,
без збору даних. Мережа задіюється лише тоді, коли ви самі натискаєте «Перевірити оновлення».

| Світла тема | Темна тема |
|---|---|
| ![Параметри, світла тема](docs/img/settings_light.png) | ![Параметри, темна тема](docs/img/settings_dark.png) |
| ![Про програму, світла тема](docs/img/about_light.png) | ![Про програму, темна тема](docs/img/about_dark.png) |
| ![Довідка, світла тема](docs/img/help_light.png) | ![Довідка, темна тема](docs/img/help_dark.png) |

<sub>Ці знімки не намальовані вручну: їх перезнімає `tools\ThemeProof.exe` зі **справжніх**
вікон на екрані, разом із DWM-заголовком, в обох темах — і перед UI-релізом їх звіряє око.
Аудит темної теми — частина повної верифікації збірки.</sub>

Написана на C# і збирається **компілятором, який уже вбудований у Windows**
(`.NET Framework 4.x`) — без Visual Studio, без SDK, без NuGet. Збірки **підписані**;
оновлення приймається лише від сертифіката автора.

**Автор:** Павло Ісаєв · [caussa.blog](https://caussa.blog)

---

## Українською

Проєкт **для всіх** — без винятків, без умов. Це історія про **якісне, чесне програмне
забезпечення**:

- **Безкоштовно й назавжди.** Жодних передплат, реклами чи прихованих умов.
- **Приватність передусім.** Без мережі, без телеметрії, без збору даних — усе працює
  **локально** на вашому комп'ютері.
- **Зроблено ретельно.** Підписані збірки, автоматичні тести, вимірна точність
  перемикання, світла й темна теми у стилі Windows.

### Можливості
- Автоперемикання **UA / RU / English** за аналізом слова
- Знає айтішну лексику: `ьмз` → `mvp`, `оіщт` → `json` — і не ламає `jwt`, `sql`, `dns`,
  набрані в англійській
- Ручна конвертація (**Break** / подвійний **Shift**), зміна регістру, транслітерація
- Вчиться на ваших відкотах: слово, яке ви повернули, більше ніколи не чіпається само
- Власні словники та автозаміни, нормалізація термінології (нато → NATO, зсу → ЗСУ)
- Не чіпає поля паролів; діагностика — **лише за вашою згодою**
- Світла / темна / системна тема, як у сучасному Windows

### Встановлення
Завантажте найновішу **підписану** збірку на сторінці **[Releases](../../releases/latest)**
і запустіть. Оновлення — прямо із застосунку: трей → «Перевірити оновлення…».

---

## In English

**VALERA** automatically fixes text typed in the wrong keyboard layout and switches
**UA / RU / English** based on word analysis. Made **for everyone** — no exceptions,
no strings attached.

A project about **honest, quality software**:

- **Free, forever.** No subscriptions, ads, or hidden terms.
- **Privacy first.** No network, no telemetry, no data collection — everything runs
  **locally** on your machine. The network is used only when you press
  "Check for updates" yourself.
- **Built with care.** Signed builds, automated tests, measured switching accuracy,
  native light & dark themes.

Download the latest **signed** build from **[Releases](../../releases/latest)**.

---

## Підтримати проєкт · Support

Проєкт **вільний і таким залишиться**. Якщо ВАЛЄРА стала вам у пригоді й ви хочете
підтримати розробку якісного ПЗ — скористайтеся **кнопками підтримки** прямо в застосунку
(**Про програму → Монобанк / Ko-fi**) або тут:

[![Підтримати на Ko-fi](https://img.shields.io/badge/Ko--fi-%E2%98%95%20%D0%BF%D1%96%D0%B4%D1%82%D1%80%D0%B8%D0%BC%D0%B0%D1%82%D0%B8-2e7d32?style=for-the-badge)](https://ko-fi.com/pavloisaiev)
&nbsp;
[![Банка Монобанк](https://img.shields.io/badge/Monobank-%D0%B1%D0%B0%D0%BD%D0%BA%D0%B0-2e7d32?style=for-the-badge)](https://send.monobank.ua/jar/52FQ1MSqEK)

Кожна підтримка йде на розвиток і нове обладнання. Це не обов'язково — але дуже допомагає. Дякую 🙏

_The project is free and always will be. If it's useful to you, supporting the development
of quality software is warmly appreciated — but never required._

---

**Автор · Author:** Павло Ісаєв · [caussa.blog](https://caussa.blog)
