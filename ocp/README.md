# Open/close principle (OCP)

## Принцип открытости/закрытости

### Формулировка:

Программные сущности (классы, модули, функции и т.д.) должны быть открыты для расширения, но закрыты для изменения.

* **Открыт для расширений** - поведение может быть расширено путем добавления новых объектов, реализующих новые аспекты поведения
* **Закрыд для модификации** - в результате расширения поведения код объекта не может быть изменен

### Почему?

Потому что это позволяет быстро и безболезненно реагировать  на изменения бизнес-логики.