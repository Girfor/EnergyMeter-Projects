# EnergyMeter — проекты для Visual Studio

Публичный репозиторий учебных C# проектов EnergyMeter. Исходники распределены по папкам в каталоге `projects/`. Каждая папка содержит отдельный проект или версию.

## Быстрый запуск

1. Установите Visual Studio 2022 и .NET 8 SDK.
2. Откройте нужный файл `.sln` из `projects/`.
3. Восстановите пакеты NuGet и запустите F5.

## Демонстрационные проекты

| Раздел | Решение Visual Studio |
| --- | --- |
| REST API, Swagger и CSRF | `projects/EnergyMeter_API_Swagger_CSRF_Demo_F5/EnergyMeter.Api.Demo.sln` |
| DPAPI, BCrypt и X.509 | `projects/EnergyMeter_Security_Demo_F5/EnergyMeter.Security.Demo.sln` |
| Офлайн-буфер, SQLite, EF Core и Polly | `projects/EnergyMeter_Offline_Demo_F5/EnergyMeter.Offline.sln` |
| Автоматическое обновление | `projects/EnergyMeter_AutoUpdater_Demo_F5/EnergyMeter.Updater.sln` |
| Резервное копирование и SAT | `projects/EnergyMeter_Backup_SAT_Demo_F5_v2/EnergyMeter.BackupSAT.Demo.sln` |
| Общее решение для Visual Studio | `projects/EnergyMeter_Full_VisualStudio_Solution/EnergyMeterPortfolio/EnergyMeterPortfolio.sln` |
| ПР3, ПР4, ПР6 | `projects/EnergyMeter_Full_Solution/EnergyMeterProjects/EnergyMeter.sln` |

В каталоге также размещены отдельные ПР3/ПР4 и более ранние версии модулей, сохранённые для сравнения.

## Безопасность

Учебные тестовые данные не следует применять в промышленной системе. Реальные пароли и токены не публикуются. Для локального демонстрационного входа ПР4 задайте собственную переменную среды `Demo__Password`.
