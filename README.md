![Windows Section](https://github.com/xtcorp/browser-benchmark-results/blob/main/images/BrowserBench.png)

Тестирование всех возможных браузеров и их форков, которые только можно будет найти. Эта страница предназначена лишь для определения скорости отрисовки и скорости просчёта браузеров в тестах по типу MotionMark и JetStream.

## Когда было тестирование?
20 декабря 2023 года

## Условия
- Стационарный ПК
- Отключены фоновые программы
- Отключён спящий режим у монитора и ПК
- Отключены прокси и VPN
- Браузер тестируется "из коробки", на стандартных настройках
- Браузер обновлён в дату тестирования
- Нету расширений
- Кэши, куки и профили очищены
- Приватное окно (Инкогнито)
- Вкладки и другие браузеры закрыты
- Браузер установлен на SSD накопитель

## На чем тестировалось?
- Windows 11 Pro, 23H2, 22631.2715
- AMD Ryzen 7 3700X
- Nvidia RTX 2060 Super
- 32GB RAM, 3333MHz
- Samsung 970 EVO Plus
- 2560x1440 144hz
- 350Мбит, проводной интернет

## Тесты
- [JetStream 2.1](https://browserbench.org/JetStream/)
- [MotionMark 1.2](https://browserbench.org/MotionMark1.2/)
- [Speedometer 2.1](https://browserbench.org/Speedometer2.1/)
- [Basemark Web 3.0 (Без проверки на совместимость с HTML5 и CSS)](https://web.basemark.com/)

## Информация
Тест Basemark Web 3.0 проводится без проверки на поддержку функций HTML5, CSS. Тесты HTML5Test и WebXPRT 3 отсутвуют по причине того, что они направлены на проверку HTML5 и CSS.

## Результаты

[Полная таблица с результатами](https://github.com/xtcorp/browser-benchmark-results/releases/latest)

### Основные браузеры
| Браузер | JetStream 2.1 | MotionMark 1.2 | Speedometer 2.1 | Basemark Web 3.0 | Среднее |
|          ---: |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| Google Chrome | 220 | 1878 | 282 | 1852 | 1058 |
| Mozilla Firefox | 147 | 1033 | 255 | 1491 | 731 |

### Форки Chromium
| Браузер | JetStream 2.1 | MotionMark 1.2 | Speedometer 2.1 | Basemark Web 3.0 | Среднее |
|          ---: |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| Brave |  |  |  |  |  |
| Thorium |  |  |  |  |  |
### Форки Quantum
| Браузер | JetStream 2.1 | MotionMark 1.2 | Speedometer 2.1 | Basemark Web 3.0 | Среднее |
|          ---: |     :---:      |     :---:      |     :---:      |     :---:      |     :---:      |
| Floorp |  |  |  |  |  |

```Тестирование и поиск новых браузеров в процессе```
