# Отчёт о тестировании приложения "Precision"

## Бонусная система для клиентов

Было проведено бэкенд тестирование приложения Precision, со следующими вводными:

public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

## Описание тестов

Проводилось функциональное тестирование бэкенда приложения, с использованием языка Java, и установленными входными данными (см. выше).
По итогу проверки программы в строке кода TotalBonus выводится неверное значение.

## Результаты

1. 0% успешных/100% не успешных тестов
2. Ссылка на баг-репорт https://github.com/LenoreCldg/2.Precision/issues/1

