# User guide / Руководство

## English

1. Open Text Cleaner in Figma Design.
2. Choose Selection or Current page, optionally enable Visible layers only, and select rules.
3. Click Find issues. After this first scan, live checking starts for the session.
4. Click an issue to locate it on the canvas. Click the replacement icon when a correction is offered, or ignore an issue using the crossed-circle icon.
5. Fix (N) applies eligible batch corrections after confirmation. Review the proposed scope before applying. Rescan performs a full scan; Restore all clears ignored issues for the session.
6. RU / EN switches the interface without changing the rules or document text.

### Checks
Multiple spaces; spaces before punctuation; straight quotes; possible dash issues; units of measurement; numeric ranges; missing spaces after punctuation.

The rules primarily target Russian typography and partially support English. Some ambiguous findings require manual review. Compound units such as 5mg/mL may not be flagged. Not every finding has an automatic correction.

The plugin is designed to preserve existing text styles using targeted character edits. Locked layers, component instances, bound text and unavailable fonts may be skipped. Review the correction report. If an unexpected or partial edit occurs, stop and inspect the document; use Figma Undo (Cmd+Z / Ctrl+Z) as appropriate.

## Русский

1. Откройте Text Cleaner в Figma Design.
2. Выберите «Выделение» или «Текущая страница», при необходимости включите «Только видимые слои» и отметьте правила.
3. Нажмите «Найти ошибки». После первой проверки активируется автопроверка до закрытия плагина.
4. Нажмите на замечание для перехода к нему. Используйте значок замены для доступной правки или перечёркнутый круг для игнорирования.
5. «Исправить (N)» применяет доступные массовые исправления после подтверждения. Проверьте область изменений. «Проверить повторно» запускает полный поиск, «Вернуть все» сбрасывает игнорирование.
6. RU / EN переключает только интерфейс, не меняя текст и правила.

### Правила
Двойные пробелы, пробелы перед пунктуацией, прямые кавычки, возможные ошибки с тире, единицы измерения, числовые диапазоны, пропущенные пробелы после пунктуации.

Правила ориентированы преимущественно на русский язык; английская типографика поддерживается частично. Неоднозначные замечания требуют ручной проверки. Составные единицы вроде 5мг/мл могут пропускаться. Не для всех замечаний предусмотрено исправление.

Плагин старается сохранять форматирование с помощью точечных изменений символов. Заблокированные слои, экземпляры компонентов, связанный текст и недоступные шрифты могут пропускаться. Проверяйте отчёт. При неожиданной или частичной правке проверьте документ и при необходимости используйте отмену Figma (Cmd+Z / Ctrl+Z).
