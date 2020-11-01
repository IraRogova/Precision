# Отчёт о тестировании приложения "Precision"

## Краткое описание

public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}

## Описание тестов

Проводилось функциональное тестирование  использованием входных данных. 

## Результаты

1. Тест был не успешный
2. Ссылки на баг-репорты

## Общие рекомендации

Для итоговой суммы необходимо использовать переменную  float totalBonus = (float) (regularBonus + specialBonus);