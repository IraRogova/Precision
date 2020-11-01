# Отчёт о тестировании приложения "Precision"

## Краткое описание

Исрользовали гововое приложение для подсчета бонусов для клиентов

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
2. https://github.com/IraRogova/Precision/issues/1

## Общие рекомендации

Для итоговой суммы необходимо использовать переменную  float totalBonus = (float) (regularBonus + specialBonus);
