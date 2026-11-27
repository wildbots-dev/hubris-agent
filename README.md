# Hubris — агент для кода

Агент для кода на моделях Claude, GPT, Gemini, DeepSeek и других: читает и правит файлы проекта, запускает команды,
перед правкой и командой спрашивает разрешение. Вход через аккаунт [Hubris](https://hubris.pro), оплата в рублях.

Здесь — готовые файлы выпусков. Номер версии общий для всех редакторов.

| Где | Как поставить |
|---|---|
| VS Code | [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=hubris.hubris-agent) · [инструкция](https://hubris.pro/docs/integrations/vscode) |
| VSCodium и другие редакторы с Open VSX | [Open VSX](https://open-vsx.org/extension/hubris/hubris-agent) · [инструкция](https://hubris.pro/docs/integrations/vscodium) |
| Cursor | файл `.vsix` своей системы из [выпусков](https://github.com/wildbots-dev/hubris-agent/releases) · [инструкция](https://hubris.pro/docs/integrations/cursor) |
| OpenIDE, GigaIDE и другие среды на платформе IntelliJ 2026.1+ | каталог плагинов `https://hubris.pro/plugins/intellij/updatePlugins.xml` (Settings → Plugins → ⚙ → Manage Plugin Repositories) или файл `hubris-agent-<версия>.zip` из [выпусков](https://github.com/wildbots-dev/hubris-agent/releases) (⚙ → Install Plugin from Disk) · [инструкция](https://hubris.pro/docs/integrations/openide#плагин-hubris) |

Файлы `.vsix` — по одному на систему: `win32-x64`, `win32-arm64`, `darwin-x64`, `darwin-arm64`, `linux-x64`,
`linux-arm64`. Плагин для сред на платформе IntelliJ — один `hubris-agent-<версия>.zip` на все системы. Суммы — в `SHA256SUMS` каждого выпуска.

Лицензия — MIT. Условия сервиса Hubris — [оферта](https://hubris.pro/legal/terms).
