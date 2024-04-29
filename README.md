![Windows Section](https://github.com/xtcorp/browser-benchmark-results/blob/main/images/BrowserBench.png)

Тестирование всех возможных браузеров и их форков, которые только можно будет найти. Эта страница предназначена лишь для определения скорости отрисовки и скорости просчёта браузеров в тестах по типу MotionMark и JetStream.

> Все значения округлены в меньшую сторону, работа идёт лишь с полными числами

## Когда было тестирование?
20 декабря 2023 года - В процессе

## Условия
- Стационарный ПК
- ПК не является виртуальной машиной
- Профиль электропитания - "Максимальная производительность"(Ultimate Performance,  e9a42b02-d5df-448d-aa00-03f14749eb61)
- Отключены фоновые программы
- Отключён спящий режим у монитора и ПК
- Отключены прокси и VPN
- Стандартные DNS, полученные от провайдера (т.е. не изменённые из под Windows)
- Браузер тестируется "из коробки", на стандартных настройках
- Браузер обновлён в дату тестирования
- Нету расширений
- Кэши, куки и профили очищены
- Приватное окно (Инкогнито)
- Вкладки и другие браузеры закрыты
- Браузер установлен на SSD накопитель
- Видеокарта работает на максимальных частотах во время всего тестирования в состоянии P0

## На чем тестировалось?
- Windows 11 Pro, 23H2, 22631.2715
- AMD Ryzen 7 3700X
- Nvidia RTX 2060 Super
- 32GB RAM, 3333MHz
- Samsung 970 EVO Plus
- 2560x1440 144hz
- 350Мбит, проводной интернет, [результаты Speedtest](https://github.com/xtcorp/browser-benchmark-results/blob/main/images/Speedtest.png)

## Тесты
- [JetStream 2.1](https://browserbench.org/JetStream/)
- [MotionMark 1.2](https://browserbench.org/MotionMark1.2/)
- [Speedometer 2.1](https://browserbench.org/Speedometer2.1/)
- [Basemark Web 3.0 (Без проверки на совместимость с HTML5 и CSS)](https://web.basemark.com/)

## Информация
Тест Basemark Web 3.0 проводится без проверки на поддержку функций HTML5, CSS. Тесты HTML5Test и WebXPRT 3 отсутствуют по причине того, что они направлены на проверку HTML5 и CSS.

## Результаты
> Больше = лучше. Чем производительнее, тем быстрее отрисуется страница, загрузятся скрипты и плавнее будут анимации

[Результаты в виде Excel таблицы](https://github.com/xtcorp/browser-benchmark-results/blob/c4a3f871db1915afd184928670f1b98116f28a7b/files/browser-benchmark-results.xlsx);
[Скриншоты результатов](https://github.com/xtcorp/browser-benchmark-results/tree/c4a3f871db1915afd184928670f1b98116f28a7b/images/Browser%20Benchmark%20Results)


### Основные браузеры
| Браузер | JetStream 2.1 | MotionMark 1.2 | Speedometer 2.1 | Basemark Web 3.0 | Среднее |
|          ---: |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| [Google Chrome](https://www.google.com/chrome/) | 220 | 1878 | **282** | 1852 | 1058 |
| [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) | 147 | 1033 | 255 | 1491 | 731 |
| [Edge](https://www.microsoft.com/en-us/edge) | 220 | 1807 | 270 | 2043 | 1085 |

### Форки Chromium(Blink)
| Браузер | JetStream 2.1 | MotionMark 1.2 | Speedometer 2.1 | Basemark Web 3.0 | Среднее |
|          ---: |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| [360 Extreme Explorer](https://www.comss.ru/page.php?id=2416) |  |  |  |  |  |
| [Atom](https://browser.ru/) | 189 | 1409 | 223 | 1630 | 862 |
| [Arc](https://arc.net/) |  |  |  |  |  |
| [Brave](https://brave.com/) | 221 | 1295 | 270 | 1983 | 942 |
| [Cent](https://www.centbrowser.com/) |  |  |  |  |  |
| [Maxthon](https://www.maxthon.com/en/) |  |  |  |  |  |
| [Min](https://minbrowser.org/) | 207 | 1493 | 206 | 1493 | 849 |
| [Opera](https://www.opera.com/) |  |  |  |  |  |
| [Opera GX](https://www.opera.com/gx) |  |  |  |  |  |
| [Thorium AVX2](https://github.com/Alex313031/Thorium-Win-AVX2) | **226** | **2079** | 273 | 2049 | **1156** |
| [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | 210 | 1379 | 198 | 1760 | 886 |
| [Vivaldi](https://vivaldi.com/) |  |  |  |  |  |
| [Яндекс Браузер](https://browser.yandex.ru/) | 210 | 1744 | 275 | **2056** | 1071 |
| [Яндекс Браузер для геймеров](https://www.comss.ru/page.php?id=9481) | 186 | 1656 | 267 | 2050 | 1039 |
| [Яндекс Браузер для организаций](https://www.comss.ru/page.php?id=3799) |  |  |  |  |  |

### Форки Quantum(Gecko)
| Браузер | JetStream 2.1 | MotionMark 1.2 | Speedometer 2.1 | Basemark Web 3.0 | Среднее |
|          ---: |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| [Floorp](https://floorp.app/) | 131 | 860 | 215 | 1465 | 667 |
| [K-Meleon](http://kmeleonbrowser.org/) |  |  |  |  |  |
| [Mercury](https://github.com/Alex313031/Mercury) | 130 | 891 | 215 | 1447 | 670 |
| [Tor](https://www.torproject.org/) |  |  |  |  |  |

### Топ браузеров по среднему значению
1. [Thorium AVX2](https://github.com/Alex313031/Thorium-Win-AVX2)
2. [Edge](https://www.microsoft.com/en-us/edge)
3. [Яндекс Браузер](https://browser.yandex.ru/)
4. [Google Chrome](https://www.google.com/chrome/)
5. [Яндекс Браузер для геймеров](https://www.comss.ru/page.php?id=9481)
6. [Brave](https://brave.com/)
7. [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium)
8. [Atom](https://browser.ru/)
9. [Min](https://minbrowser.org/)
10. [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)
11. [Mercury](https://github.com/Alex313031/Mercury)
12. [Floorp](https://floorp.app/)

## Версии браузеров на момент тестирования
| Браузер | Версия |
|          ---: | :---          |
| [Atom](https://browser.ru/) | 26.0.0.21 (Official Build) (64-bit) |
| [Google Chrome](https://www.google.com/chrome/) | 120.0.6099.130 (Официальная сборка), (64 бит) |
| [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) | 121.0 (64-bit) |
| [Thorium AVX2](https://github.com/Alex313031/Thorium-Win-AVX2) | 117.0.5938.157 (Official Build) (64-bit) |
| [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | 120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit) |
| [Яндекс Браузер](https://browser.yandex.ru/) | 23.11.2.771 (64-bit) |

- Atom на 23% медленнее работает с графикой, чем Яндекс.Браузер, на 33% медленнее, чем Google Chrome, и на 27% быстрее, чем Mozilla Firefox, по результатам MotionMark 1.2.
- Atom на 11% менее производительный, чем Яндекс.Браузер, на 16% менее
производительнее, чем Google Chrome, и на 23% более производительный, чем Mozilla Firefox, по результатам JetStream 2.1.
