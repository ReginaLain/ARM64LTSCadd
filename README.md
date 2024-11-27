# ARM64LTSCaddMSstore
Adds Microsoft Store and dependencies to Windows 10 LTSC 21h2/2021 ARM64

Скрипт гарантировано сработает на LTSC2021 и скорее всего на LTSC2024, "LTSC2019 не поддерживается"
Процесс установки:
1. Распаковать архив в любую удобную папку "рекомендуется корневая папка диска, для избежания путей содержащих имена пользователей или название папок на языках отличных от английского".
2. Запустить файл Add-Store.cmd. При запуске автоматический запрашиваются права администратора, если они не будут выданы, скрипт прекратит работу.
Что конкретно будет установлено:
Microsoft.DesktopAppInstaller - менеджер пакетов UWP приложений, будет полезен, если ставите приложения без магазина, например из store.rg-adguard.net.
Microsoft.NET.Native.Framework.2.2, Microsoft.NET.Native.Runtime.2.2, Microsoft.UI.Xaml.2.4, Microsoft.VCLibs.140.00.UWPDesktop, Microsoft.VCLibs.140.00_14.0.33519.0_arm64  - зависимости, необходимые для работы UWP приложений
Microsoft.StorePurchaseApp - приложение для покупок внутри магазина
Microsoft.XboxIdentityProvider - приложение для полноценной работы сервисов xbox
Microsoft.WindowsStore - магазин Microsoft Store

English version
The script is guaranteed to work on LTSC2021 and most likely on LTSC2024, “LTSC2019 is not supported”
Installation process:
1. Extract the archive to any convenient folder “root folder of the disk is recommended, to avoid paths containing usernames or folder names in languages other than English”.
2. Run the Add-Store.cmd file. At startup, administrator rights are automatically requested, if they are not granted, the script will stop working.
What exactly will be installed:
Microsoft.DesktopAppInstaller - UWP application folder manager, will be useful if you install applications without a store, for example from store.rg-adguard.net.
Microsoft.NET.Native.Framework.2.2, Microsoft.NET.Native.Runtime.2.2, Microsoft.UI.Xaml.2.4, Microsoft.VCLibs.140.00.UWPDesktop, Microsoft.VCLibs.140.00_14.0.33519.0_arm64 - dependencies required for UWP applications to work.
Microsoft.StorePurchaseApp - applications for in-store purchases
Microsoft.XboxIdentityProvider - applications for full operation of xbox services
Microsoft.WindowsStore - Microsoft Store
