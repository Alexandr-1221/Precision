# Отчёт о тестировании приложения "Precision"

## Краткое описание

14.01.2021 - 14.01.2021 было проведено функциональное тестирование приложения Precision. Цель тестирования: проверить работоспособность приложения.

В ходе работы было воссоздано базовое приложение, проведён тест и заведён [баг-репорт](https://github.com/Alexandr-1221/Precision/issues/1) на обнаруженную ошибку.

## Описание тестов

Проведено функциональное тестирование функции расчёта бонуса.

Приложение (код):
```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Тест 1:

Рассчитать сумму двух видов бонуса, где:
```
    double regularBonus = 0.3;
    double specialBonus = 0.6;
```

## Результаты

* 0% успешных тестов
* Баг-репорт: https://github.com/Alexandr-1221/Precision/issues/1

## Общие рекомендации
Итог тестирования - приложение неверно выполняет свою основную функцию (см. [баг-репорт](https://github.com/Alexandr-1221/Precision/issues/1)). Рекомендуется его исправление.
