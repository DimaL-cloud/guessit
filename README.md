# GuessIt
Гра на JavaFX та Spring Boot

## Ідея :bulb:
Користувачу дається перелік тем. Він обирає тему, за якою буде обиратися рандомно слово та його значення. За обмежений час та кількість спроб гравець має вгадати слово

## Стек :computer:
Java, Spring Boot, JavaFX

## Деталі реалізації :page_with_curl:
В якості мови програмування було обрано Java, так як вона є кросплатформленою, тобто додаток можна буде запустити на будь-якій платформі, яка підтримує JVM (Наприклад: Windows, MacOS, Linux). В Java є два основних інструменти для написання десктопних програм: JavaFX та Swing. JavaFX є більш сучасною бібліотекою.

Spring Boot - це фреймворк для створення додатків на Java, який має вбудовану систему Dependency Injection (DI). Dependency Injection - це процес забезпечення об'єктам необхідних залежностей безпосередньо, через передачу залежностей у конструктор або метод об'єкта.

Spring Boot робить Dependency Injection легким і зручним для використання. Завдяки DI, класи додатка можуть працювати з іншими класами та залежностями, не відомих їм напряму. Використання DI дозволяє забезпечити слабку зв'язність (low coupling) між компонентами додатку, що дозволяє легко змінювати окремі частини додатку без необхідності змінювати його загальну архітектуру.

У загальному, використання Spring Boot дозволяє створювати додатки, які легко масштабуються та підтримуються.

Програма написана за архітектурою MVC. MVC (Model-View-Controller) - це архітектурний підхід, який використовується в додатках для створення графічного інтерфейсу користувача. Це розділяє додаток на три компоненти: модель (Model), представлення (View) та контролер (Controller). MVC дозволяє зберігати різні компоненти додатку відокремлено один від одного, що дозволяє легше розробляти, тестувати та підтримувати додаток.

На даному етапі реалізовані можливості вибору тем, вгадування слова та музика. Музика грає нескінченно в рандомному порядку. Є 6 музик в приємному стилі Lo-Fi. 

## Скріншоти гри :framed_picture:

![main-menu](https://user-images.githubusercontent.com/78265212/230082590-9723ba7d-b60e-44c8-94fa-1b578bdb7ba6.png)

![topics](https://user-images.githubusercontent.com/78265212/230082662-937b5b02-4b33-46e9-b676-0238a960f4fd.png)

![game-menu](https://user-images.githubusercontent.com/78265212/230082877-626c261d-23ae-4c01-b5f3-f5d283ec2853.png)

![win](https://user-images.githubusercontent.com/78265212/230083160-8c1571b4-db80-44a8-94c0-5adb9ab6a7eb.png)


