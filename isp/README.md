# Interface segregation principle (ISP)

## Принцип изоляции (разделения) нитерфейса

### Формулировка:

Клиенты не должны закисеть от методов, которые они не используют.

Много специализированый интерфейсов лучше чем один универсальный.

### Почему?

Если определим большой универсальный интерфейс, тогда в наследниках возможно появление множества заглушек, а соответственно, много лишнего кода, который необходимо поддерживать.