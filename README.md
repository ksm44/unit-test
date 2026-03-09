AppVeyor нужен для автоматизации сборки, тестирования и развёртывания программного обеспечения.
AppVeyor, после подключения по токену GitHub, отслеживает изменения в репозитории. При изменении репо в AppVeyor выполняются инструкции, указанные в прилагающемся к репо файлу - .appveyor.yml

Далее каждый git push в репо будет запускать процесс непрерывной интеграции (CI).

В статус-бейдже можно отслеживать статус сборки и состояния интеграции.
Статус-бейдж GitHub Actions AppVeyor:
[![Build status](https://ci.appveyor.com/api/projects/status/fi5s4ja3b5c2qk09?svg=true)](https://ci.appveyor.com/project/ksm44/unit-test)
