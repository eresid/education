## Задача на порівняння об'єктів

#### Дано:
Маємо екземпляр класу User:

```java
class User {
    String name;
    int age;
    String position;
}
```

Він містить дані користувача Oleg:

```java
public class Main {

    public static void main(String[] args) {
        User user = new User();
        user.name = "Oleg";
        user.age = 20;
        user.position = "Java Developer";
    }
}
```

#### Задача:
1) Створити інший екземпляр на основі екземпляра Oleg.
2) Порівняти їх на ідентичність за допомогою методу equals. Має бути результат true.
3) Змінити будь-яке поле у другого екземпляра.
4) Порівняти їх на ідентичність за допомогою методу equals. Має бути результат false.

При необхідності клас User можна змінювати.
