## Мобільний клієнт для блогу

Потрібно створити мобільний клієнт для [персонального блогу](Blog.md). Блог міститиме пости, мітки та коментарі. Інтерфейс повинен відповідати концепціям платформ (для Android - [Material Design](https://material.io/guidelines/), для iOS - [HIG](https://developer.apple.com/ios/human-interface-guidelines/)). Дозволяється використовувати наявні реалізації для прикладу та запозичення шматків коду, але потрібно повністю розбиратись у тому, що копіюється у проект.

### Основні задачі
1) Головний екран міститиме список постів, завантажених по АРІ
2) При кліку на пост, відкривати його деталі, які міститимуть мітки
3) Підтягувати коментарі до обраного поста
4) Реалізувати пагінацію для постів
5) Використати Java чи [Kotlin](https://kotlinlang.org/) для Android та Swift для iOS.
6) Використати [Android Studio](https://developer.android.com/studio/index.html) для Android та [XCode](https://developer.apple.com/xcode/) для iOS
7) Використати для роботи з API [Retrofit](http://square.github.io/retrofit/) для Android та [Alamofire
](https://github.com/Alamofire/Alamofire) для iOS
7) Використати [GitHub](https://github.com/) як систему контроля версій
8) Використати для організації задач [Trello](https://trello.com/)

### Додаткові задачі
1) Кешувати дані у локальній базі даних (Android: [SQLBrite](https://github.com/square/sqlbrite) чи [Realm](https://realm.io/docs/java/latest/), iOS: [CoreData](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/CoreData/index.html) чи [Realm](https://realm.io/docs/tutorials/realmtasks/))
2) Покрити проект тестами ([Android](https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html), [iOS](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/01-introduction.html))
3) Реалізувати авторизацію через Facebook ([Android](https://developers.facebook.com/docs/android/), [iOS](https://developers.facebook.com/docs/ios/)
4) Реалізувати можливість додавання коментарів до постів
5) Реалізувати альбомну і портретну орієнтації
6) Використати архітектурний паттерн [MVP](https://uk.wikipedia.org/wiki/Model-View-Presenter) чи [MVVM](https://uk.wikipedia.org/wiki/Model-View-ViewModel)

### Примітки
1) Дизайн можна реалізовувати будь-який, не потрібно переускладнювати, але потрібно підтримати хоча б декілька різних розширень екрану.
2) Можна об'єднуватись у команди і розподіляти задачі, головне розбиратись у коді партнерів
3) Дана задача є хорошим фінальним тестовим завданням, якісно реалізувавши яку, можна вже говорити про працевлаштування
