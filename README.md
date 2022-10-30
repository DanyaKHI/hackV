# Надо подумать
Метод решения предложенной задачи представляет собой модель классификации,
основанную на методе наивного байеса реализации sklearn. Анализируя изменения
объема крови в сосудах испытуемого во время психофизиологического теста, можно
выявить его эмоциональное состояние.

## Входные данные:
- *(|Mean(Max - Min)| - |(Max - Min)|)*
  - **Разности между средним максимумом и минимумом по одному человеку и максимумом и минимумом по одной записи человека**

- *(|Mean(Sum)| - |(Sum)|)*
  - **Разности между средней суммы по одному человеку и суммы по одной записи человека**

- *(|Mean([0]-[1])| - |([0]-[1])|)*
  - **Разности между средним началом и концом по одному человеку и началом и концом по одной записи человека**

## Ключевые особенности нашего решения:
- **Простота алгоритма**
- **Классификации**
- **Использование**
