# Сказ о том, как я ООП изучал

<img src="https://cs4.pikabu.ru/post_img/2015/04/06/7/1428317216_2115088709.jpg " width=700>

## Содержание

### Часть I: Основы ООП
- [Глава 1: Введение в объектно-ориентированное программирование](#глава-1-введение-в-объектно-ориентированное-программирование)
  - [Почему ООП? Эволюция программирования](#почему-ооп-эволюция-программирования)
  - [Основные концепции ООП: Четыре кита](#основные-концепции-ооп-четыре-кита)
- [Глава 2: Классы и объекты - фундамент ООП](#глава-2-классы-и-объекты---фундамент-ооп)
  - [Что такое класс? Глубокое понимание](#что-такое-класс-глубокое-понимание)
  - [Что такое объект? Философия экземпляра](#что-такое-объект-философия-экземпляра)
  - [Ключевое слово $this - магия самоссылки](#ключевое-слово-this---магия-самоссылки)
- [Глава 3: Конструкторы - рождение объектов](#глава-3-конструкторы---рождение-объектов)
  - [Зачем нужны конструкторы? Проблема инициализации](#зачем-нужны-конструкторы-проблема-инициализации)
  - [Конструктор с логикой и валидацией](#конструктор-с-логикой-и-валидацией)
- [Глава 4: Модификаторы доступа - защита и контроль](#глава-4-модификаторы-доступа---защита-и-контроль)
  - [Почему скрывать данные - это хорошо?](#почему-скрывать-данные---это-хорошо)
  - [Принцип "минимальных привилегий"](#принцип-минимальных-привилегий)

### Часть II: Продвинутые концепции ООП
- [Глава 5: Наследование - сила переиспользования](#глава-5-наследование---сила-переиспользования)
  - [Наследование как естественный процесс](#наследование-как-естественный-процесс)
  - [Преимущества наследования: почему это мощно](#преимущества-наследования-почему-это-мощно)
- [Глава 6: Полиморфизм - многообразие форм](#глава-6-полиморфизм---многообразие-форм)
  - [Что такое полиморфизм?](#что-такое-полиморфизм)
  - [Полиморфизм в действии](#полиморфизм-в-действии)
  - [Преимущества полиморфизма](#преимущества-полиморфизма)
- [Глава 7: Абстрактные классы и методы](#глава-7-абстрактные-классы-и-методы)
  - [Зачем нужны абстрактные классы?](#зачем-нужны-абстрактные-классы)
  - [Абстрактные методы - контракт реализации](#абстрактные-методы---контракт-реализации)
  - [Когда использовать абстрактные классы?](#когда-использовать-абстрактные-классы)
- [Глава 8: Интерфейсы - чистые контракты](#глава-8-интерфейсы---чистые-контракты)
  - [Интерфейсы vs Абстрактные классы](#интерфейсы-vs-абстрактные-классы)
  - [Множественная реализация интерфейсов](#множественная-реализация-интерфейсов)
  - [Практическое применение интерфейсов](#практическое-применение-интерфейсов)

### Часть III: Дополнительные возможности ООП в PHP
- [Глава 9: Статические свойства и методы](#глава-9-статические-свойства-и-методы)
  - [Статические члены класса](#статические-члены-класса)
  - [Паттерн Singleton](#паттерн-singleton)
  - [Когда использовать статические методы?](#когда-использовать-статические-методы)
- [Глава 10: Трейты (Traits) - горизонтальное повторное использование](#глава-10-трейты-traits---горизонтальное-повторное-использование)
  - [Проблема множественного наследования](#проблема-множественного-наследования)
  - [Трейты как решение](#трейты-как-решение)
  - [Конфликты трейтов и их разрешение](#конфликты-трейтов-и-их-разрешение)
- [Глава 11: Магические методы](#глава-11-магические-методы)
  - [__get и __set - управление доступом к свойствам](#__get-и-__set---управление-доступом-к-свойствам)
  - [__call и __callStatic - перехват вызовов методов](#__call-и-__callstatic---перехват-вызовов-методов)
  - [__toString и __invoke - объекты как строки и функции](#__tostring-и-__invoke---объекты-как-строки-и-функции)

### Часть IV: Практическое применение ООП
- [Глава 12: Практический пример - система блога](#глава-12-практический-пример---система-блога)
  - [Проектирование архитектуры](#проектирование-архитектуры)
  - [Реализация классов](#реализация-классов)
  - [Тестирование системы](#тестирование-системы)
- [Глава 13: Паттерны проектирования для начинающих](#глава-13-паттерны-проектирования-для-начинающих)
  - [Фабрика (Factory)](#фабрика-factory)
  - [Стратегия (Strategy)](#стратегия-strategy)
  - [Наблюдатель (Observer)](#наблюдатель-observer)
- [Глава 14: Принципы SOLID](#глава-14-принципы-solid)
  - [Single Responsibility Principle](#single-responsibility-principle-принцип-единственной-ответственности)
  - [Open/Closed Principle](#openclosed-principle-принцип-открытостизакрытости)
  - [Liskov Substitution Principle](#liskov-substitution-principle-принцип-подстановки-барбары-лисков)
  - [Interface Segregation Principle](#interface-segregation-principle-принцип-разделения-интерфейсов)
  - [Dependency Inversion Principle](#dependency-inversion-principle-принцип-инверсии-зависимостей)

### Часть V: Дополнительные материалы
- [Введение](#введение-почему-ооп---это-круто)
- [Приложение A: Часто задаваемые вопросы](#приложение-a-часто-задаваемемые-вопросы)
- [Приложение B: Лучшие практики ООП](#приложение-b-лучшие-практики-ооп-)
- [Приложение C: Распространенные ошибки и как их избежать](#приложение-c-распространенные-ошибки-и-как-их-избежать)
- [Заключение: Путь к мастерству ООП](#заключение-путь-к-мастерству-ооп)

---

# Часть I: Основы ООП

## Глава 1: Введение в объектно-ориентированное программирование

### Почему ООП? Эволюция программирования

>>Если ты это читаешь, значит ты уже прошел путь от простых скриптов к более сложным программам. Но настал момент, когда твой код стал напоминать спагетти - все переплетено, сложно изменять, а добавление новой функциональности вызывает головную боль.

**Историческая справка:** В начале времен программисты писали линейный код. Потом появились функции - и это была революция! Мы научились группировать код. Но когда проекты стали сложнее, потребовался новый подход. Так родилось ООП.

**Простая аналогия:** Представь, что твой код - это конструктор:
- **Процедурный подход** - у тебя есть куча отдельных деталей
- **ООП** - у тебя есть готовые модули: колеса, двери, окна, которые сами знают, как работать

**Проще говоря:** ООП - это когда твой код начинает вести себя как кот: он независим, иногда непредсказуем, но если найти к нему подход, становится лучшим другом.

### Основные концепции ООП: Четыре кита

ООП стоит на четырех основных принципах, которые мы подробно изучим:

1. **Инкапсуляция** - сокрытие сложности
2. **Наследование** - переиспользование кода  
3. **Полиморфизм** - единый интерфейс для разных типов
4. **Абстракция** - работа с концепциями, а не деталями

## Глава 2: Классы и объекты - фундамент ООП

### Что такое класс? Глубокое понимание

Класс - это не просто "шаблон" или "чертеж". Это полноценный тип данных, который ты создаешь сам. Так же как `int`, `string`, `array` - встроенные типы, класс - это твой собственный тип.

**Ментальная модель:** Представь, что класс - это фабрика по производству объектов. На фабрике есть:
- **Инструкции** (методы) - что могут делать создаваемые объекты
- **Спецификации** (свойства) - какие характеристики будут у объектов
- **Производственная линия** (конструктор) - как собирать объекты

```php
<?php
// Создаем новый тип данных "Студент"
class Student {
    // Свойства - характеристики студента
    public $name;
    public $age;
    public $specialty;
    public $grades = [];
    public $isStudying = false;
    
    // Методы - поведение студента
    public function study($subject) {
        $this->isStudying = true;
        return $this->name . " изучает " . $subject;
    }
    
    public function takeExam($subject, $grade) {
        $this->grades[$subject] = $grade;
        $this->isStudying = false;
        return $this->name . " сдал экзамен по " . $subject . " на " . $grade;
    }
    
    public function getAverageGrade() {
        if (empty($this->grades)) {
            return "У студента пока нет оценок";
        }
        $sum = array_sum($this->grades);
        $count = count($this->grades);
        return "Средний балл: " . ($sum / $count);
    }
}
?>
```

### Что такое объект? Философия экземпляра

Объект - это конкретная реализация класса. Но важно понимать: объект живет своей жизнью! Он имеет состояние (значения свойств) и поведение (методы).

**Важная аналогия:** Класс `Человек` описывает, что у человека есть имя, возраст, методы `говорить()`, `ходить()`. Объект `$иван = new Человек()` - это конкретный Иван с конкретным именем и возрастом.

```php
<?php
// Создаем объекты - конкретных студентов
$student1 = new Student();
$student1->name = "Анна Иванова";
$student1->age = 20;
$student1->specialty = "Информатика";

$student2 = new Student();
$student2->name = "Петр Сидоров";
$student2->age = 21;
$student2->specialty = "Математика";

// Каждый объект живет своей жизнью
echo $student1->study("PHP") . "\n";  // Анна изучает PHP
echo $student2->study("Алгебру") . "\n"; // Петр изучает Алгебру

echo $student1->takeExam("PHP", 5) . "\n"; // Анна сдала экзамен по PHP на 5
echo $student2->takeExam("Алгебру", 4) . "\n"; // Петр сдал экзамен по Алгебре на 4

echo $student1->getAverageGrade() . "\n"; // Средний балл: 5
echo $student2->getAverageGrade() . "\n"; // Средний балл: 4

// Объекты независимы - изменение одного не влияет на другой
$student1->name = "Анна Петрова";
echo $student1->name . "\n"; // Анна Петрова
echo $student2->name . "\n"; // Петр Сидоров (не изменился!)
?>
```

### Ключевое слово $this - магия самоссылки

`$this` - это, пожалуй, самое важное ключевое слово в ООП. Оно ссылается на текущий объект. 

**Простое объяснение:** Когда объект говорит "мой возраст" или "я учусь" - он использует `$this`. Это способ объекта ссылаться на самого себя.

Приведу пример реализации класса `Car`. Машина знает свой бренд (`public $brand`), текущую скорость (`public $speed`) и заведен ли у нее двигатель (`public &isEngineOn`), а также она умеет заводить свой двигатель (метод `startEngine`), ускоряться (метод `accelerate`) и выводить информацию о своем текущем состоянии (метод `getInfo`).

```php
<?php
class Car {
    public $brand;
    public $speed = 0;
    public $isEngineOn = false;
    
    public function startEngine() {
        if (!$this->isEngineOn) {
            $this->isEngineOn = true;
            return "Двигатель " . $this->brand . " завелся!";
        }
        return "Двигатель уже работает";
    }
    
    public function accelerate($kmh) {
        if ($this->isEngineOn) {
            $this->speed += $kmh;
            return $this->brand . " ускоряется до " . $this->speed . " км/ч";
        }
        return "Сначала заведите двигатель!";
    }
    
    public function getInfo() {
        return $this->brand . " - скорость: " . $this->speed . " км/ч, двигатель: " . 
               ($this->isEngineOn ? "включен" : "выключен");
    }
}

// Пример работы экземпляров класса. У нас получилось 2 разных авто со своими характеристиками.

$car1 = new Car();
$car1->brand = "Toyota";

$car2 = new Car();
$car2->brand = "BMW";

echo $car1->startEngine() . "\n";  // Двигатель Toyota завелся!
echo $car1->accelerate(50) . "\n"; // Toyota ускоряется до 50 км/ч

echo $car2->getInfo() . "\n";      // BMW - скорость: 0 км/ч, двигатель: выключен
?>
```

>>`$this` - это как самосознание у объекта. Без него объект не знал бы, кто он и что у него есть.

## Глава 3: Конструкторы - рождение объектов

### Зачем нужны конструкторы? Проблема инициализации

Без конструктора создание объектов напоминает сборку мебели без инструкции - можно забыть важные детали!

**Проблема:**
```php
$student = new Student();
// А что дальше? Нужно не забыть задать все свойства!
$student->name = "???";
$student->age = "???";
// Легко забыть что-то важное!
```

**Решение - конструктор:**
```php
<?php
class Student {
    public $name;
    public $age;
    public $specialty;
    public $yearOfStudy;
    public $grades = [];
    
    // Конструктор гарантирует правильную инициализацию
    public function __construct($name, $age, $specialty, $yearOfStudy = 1) {
        $this->name = $name;
        $this->age = $age;
        $this->specialty = $specialty;
        $this->yearOfStudy = $yearOfStudy;
        
        echo "Зачислен новый студент: " . $this->name . 
             " на специальность '" . $this->specialty . "'\n";
    }
    
    public function getInfo() {
        return $this->name . " (" . $this->age . " лет), " . 
               $this->specialty . ", " . $this->yearOfStudy . " курс";
    }
}

// Теперь создание объекта безопасно и понятно
$student1 = new Student("Мария Козлова", 19, "Программирование");
$student2 = new Student("Алексей Новиков", 20, "Дизайн", 2);

echo $student1->getInfo() . "\n"; // Мария Козлова (19 лет), Программирование, 1 курс
echo $student2->getInfo() . "\n"; // Алексей Новиков (20 лет), Дизайн, 2 курс
?>
```

### Конструктор с логикой и валидацией

Конструктор может содержать не только присваивание значений, но и сложную логику:

```php
<?php
class BankAccount {
    public $accountNumber;
    public $ownerName;
    private $balance;
    private $isActive;
    private $openDate;
    
    public function __construct($ownerName, $initialDeposit) {
        // Валидация данных
        if (empty($ownerName)) {
            throw new Exception("Имя владельца не может быть пустым");
        }
        
        if ($initialDeposit < 0) {
            throw new Exception("Начальный депозит не может быть отрицательным");
        }
        
        // Генерация номера счета
        $this->accountNumber = $this->generateAccountNumber();
        
        // Инициализация свойств
        $this->ownerName = $ownerName;
        $this->balance = $initialDeposit;
        $this->isActive = true;
        $this->openDate = date('Y-m-d H:i:s');
        
        // Логирование
        $this->log("Открыт счет №" . $this->accountNumber . 
                   " для " . $this->ownerName . 
                   " с начальным депозитом " . $initialDeposit . " руб.");
    }
    
    private function generateAccountNumber() {
        return "40702" . mt_rand(1000000000, 9999999999);
    }
    
    private function log($message) {
        echo "[БАНК] " . date('Y-m-d H:i:s') . " - " . $message . "\n";
    }
    
    public function getAccountInfo() {
        return "Счет №" . substr($this->accountNumber, -4) . 
               " | Владелец: " . $this->ownerName . 
               " | Баланс: " . $this->balance . " руб." .
               " | Открыт: " . $this->openDate;
    }
}

// Использование
try {
    $account1 = new BankAccount("Иван Петров", 5000);
    $account2 = new BankAccount("Ольга Сидорова", 10000);
    
    echo $account1->getAccountInfo() . "\n";
    echo $account2->getAccountInfo() . "\n";
    
    // $account3 = new BankAccount("", 1000); // Ошибка!
    // $account4 = new BankAccount("Петр", -100); // Ошибка!
    
} catch (Exception $e) {
    echo "Ошибка при создании счета: " . $e->getMessage() . "\n";
}
?>
```

>>**Философская заметка:** Конструктор - это как церемония инициации для объекта. Он не просто рождается, а сразу получает предназначение и правила жизни.

## Глава 4: Модификаторы доступа - защита и контроль

### Почему скрывать данные - это хорошо?

Представь, что твой банковский счет - это объект. Хочешь ли ты, чтобы любой мог изменить твой баланс? Конечно нет! Модификаторы доступа - это система безопасности твоих объектов.

**в ООП есть три уровня доступа:**

1. **public** - публичная площадь (все видят)
2. **protected** - семейный дом (только семья и родственники)  
3. **private** - личный сейф (только ты)

```php
<?php
class SmartHouse {
    // public - доступно всем
    public $address;
    public $ownerName;
    
    // protected - доступно классу и наследникам
    protected $securityLevel = "standard";
    protected $energyConsumption;
    
    // private - только для внутреннего использования
    private $adminPassword;
    private $secretRooms = [];
    private $selfDestructCode;
    
    public function __construct($address, $ownerName, $password) {
        $this->address = $address;
        $this->ownerName = $ownerName;
        $this->adminPassword = $password;
        $this->selfDestructCode = rand(1000, 9999);
        
        echo "Умный дом по адресу " . $address . " активирован!\n";
    }
    
    // Публичные методы - интерфейс для взаимодействия
    public function welcomeGuest($guestName) {
        return "Добро пожаловать, " . $guestName . "! Владелец: " . $this->ownerName;
    }
    
    public function changeSecurityLevel($newLevel, $password) {
        if ($this->verifyPassword($password)) {
            $this->securityLevel = $newLevel;
            return "Уровень безопасности изменен на: " . $newLevel;
        }
        return "Неверный пароль!";
    }
    
    public function getHouseInfo() {
        return $this->address . " | Владелец: " . $this->ownerName . 
               " | Безопасность: " . $this->securityLevel;
    }
    
    // Защищенные методы - для внутренней логики и наследников
    protected function calculateEnergyUsage() {
        // Сложная логика расчета энергопотребления
        $this->energyConsumption = rand(50, 200);
        return $this->energyConsumption;
    }
    
    protected function emergencyProtocol() {
        return "Активирован протокол экстренной ситуации!";
    }
    
    // Приватные методы - строго внутренние
    private function verifyPassword($password) {
        return $password === $this->adminPassword;
    }
    
    private function activateSelfDestruct($code) {
        if ($code === $this->selfDestructCode) {
            return "Самоликвидация активирована!";
        }
        return "Неверный код!";
    }
    
    private function addSecretRoom($roomName) {
        $this->secretRooms[] = $roomName;
    }
}

// Использование
$house = new SmartHouse("ул. Программистов, 123", "Сергей", "secret123");

// Что можно делать:
echo $house->address . "\n";                    // OK - публичное
echo $house->welcomeGuest("Анна") . "\n";       // OK - публичный метод
echo $house->getHouseInfo() . "\n";             // OK - публичный метод
echo $house->changeSecurityLevel("high", "secret123") . "\n"; // OK

// Что НЕЛЬЗЯ делать:
// echo $house->adminPassword;                  // ОШИБКА! приватное свойство
// echo $house->securityLevel;                  // ОШИБКА! защищенное свойство
// $house->activateSelfDestruct(1234);          // ОШИБКА! приватный метод
// $house->secretRooms = ["комната страха"];    // ОШИБКА! приватное свойство

// Попытка взлома защиты:
$house->address = "ул. Хакеров, 1"; // OK, но это не критично
echo $house->getHouseInfo() . "\n"; // Адрес изменился, но безопасность не пострадала

// $house->adminPassword = "легкийпароль";     // Невозможно! Защищено
?>
```

### Принцип "минимальных привилегий"

Золотое правило ООП: давать минимально необходимый доступ. Начинай с `private`, и только если действительно нужно - повышай до `protected` или `public`.

**Почему это важно:**
- **Безопасность** - предотвращаешь нежелательные изменения
- **Стабильность** - код меньше ломается при изменениях  
- **Простота** - проще понимать, что делает класс
- **Гибкость** - можешь менять внутреннюю реализацию, не ломая внешний код

>>Модификаторы доступа - это как воспитание детей. Сначала все под строгим контролем (private), потом даешь больше свободы (protected), и только когда уверен - отпускаешь в самостоятельную жизнь (public).

# Часть II: Продвинутые концепции ООП

## Глава 5: Наследование - сила переиспользования

### Наследование как естественный процесс

В природе все наследует признаки предков. Яблоня наследует свойства дерева, но добавляет способность давать яблоки. Собака наследует свойства млекопитающего, но добавляет лай.

В программировании то же самое! Наследование позволяет создавать новые классы на основе существующих.

```php
<?php
// Базовый класс - общие характеристики всех транспортных средств
class Vehicle {
    public $brand;
    public $model;
    public $year;
    public $speed = 0;
    public $isMoving = false;
    
    public function __construct($brand, $model, $year) {
        $this->brand = $brand;
        $this->model = $model;
        $this->year = $year;
        echo "Создано транспортное средство: " . $this->getFullName() . "\n";
    }
    
    public function start() {
        if (!$this->isMoving) {
            $this->isMoving = true;
            return $this->getFullName() . " начинает движение";
        }
        return $this->getFullName() . " уже в движении";
    }
    
    public function stop() {
        if ($this->isMoving) {
            $this->isMoving = false;
            $this->speed = 0;
            return $this->getFullName() . " останавливается";
        }
        return $this->getFullName() . " уже остановился";
    }
    
    public function accelerate($kmh) {
        if ($this->isMoving) {
            $this->speed += $kmh;
            return $this->getFullName() . " ускоряется до " . $this->speed . " км/ч";
        }
        return "Сначала нужно начать движение!";
    }
    
    public function getFullName() {
        return $this->year . " " . $this->brand . " " . $this->model;
    }
    
    public function getInfo() {
        return $this->getFullName() . " | Скорость: " . $this->speed . 
               " км/ч | Состояние: " . ($this->isMoving ? "движется" : "стоит");
    }
}

// Класс Car наследует все от Vehicle и добавляет автомобильные особенности
class Car extends Vehicle {
    public $fuelType;
    public $fuelLevel;
    public $doorsCount;
    private $isRadioOn = false;
    
    public function __construct($brand, $model, $year, $fuelType, $doorsCount) {
        // Вызываем конструктор родителя
        parent::__construct($brand, $model, $year);
        
        // Инициализируем специфические свойства
        $this->fuelType = $fuelType;
        $this->doorsCount = $doorsCount;
        $this->fuelLevel = 100; // полный бак
        
        echo "Это автомобиль с " . $doorsCount . " дверями, топливо: " . $fuelType . "\n";
    }
    
    // Переопределяем метод start с дополнительной логикой
    public function start() {
        if ($this->fuelLevel > 0) {
            parent::start(); // вызываем родительский метод
            return $this->getFullName() . " завелась! Топлива: " . $this->fuelLevel . "%";
        }
        return "Не могу завестись - нет топлива!";
    }
    
    // Специфические методы для автомобиля
    public function refuel($amount) {
        $this->fuelLevel = min(100, $this->fuelLevel + $amount);
        return "Заправлено! Уровень топлива: " . $this->fuelLevel . "%";
    }
    
    public function turnOnRadio() {
        $this->isRadioOn = true;
        return "Радио включено!";
    }
    
    public function turnOffRadio() {
        $this->isRadioOn = false;
        return "Радио выключено!";
    }
    
    public function honk() {
        return "Би-бип!";
    }
}

// Класс Motorcycle также наследует от Vehicle
class Motorcycle extends Vehicle {
    public $engineSize;
    public $hasSidecar = false;
    private $isKickstandUp = true;
    
    public function __construct($brand, $model, $year, $engineSize, $hasSidecar = false) {
        parent::__construct($brand, $model, $year);
        $this->engineSize = $engineSize;
        $this->hasSidecar = $hasSidecar;
        
        echo "Это мотоцикл с двигателем " . $engineSize . "cc";
        if ($hasSidecar) {
            echo " с коляской";
        }
        echo "\n";
    }
    
    // Переопределяем метод start с проверкой подножки
    public function start() {
        if ($this->isKickstandUp) {
            parent::start();
            return $this->getFullName() . " заурчал!";
        }
        return "Сначала подними подножку!";
    }
    
    // Специфические методы для мотоцикла
    public function raiseKickstand() {
        $this->isKickstandUp = true;
        return "Подножка поднята!";
    }
    
    public function lowerKickstand() {
        $this->isKickstandUp = false;
        return "Подножка опущена!";
    }
    
    public function doWheelie() {
        if ($this->isMoving && $this->speed > 30) {
            return $this->getFullName() . " делает вилли!";
        }
        return "Слишком медленно для вилли!";
    }
}

// Класс Bicycle наследует от Vehicle (велосипед - тоже транспорт)
class Bicycle extends Vehicle {
    public $gears;
    public $currentGear = 1;
    private $isBellRung = false;
    
    public function __construct($brand, $model, $year, $gears) {
        parent::__construct($brand, $model, $year);
        $this->gears = $gears;
        echo "Это велосипед с " . $gears . " скоростями\n";
    }
    
    // Переопределяем метод accelerate - у велосипеда ограниченная скорость
    public function accelerate($kmh) {
        if ($this->isMoving) {
            $this->speed = min(40, $this->speed + $kmh); // максимум 40 км/ч
            return $this->getFullName() . " крутит педали! Скорость: " . $this->speed . " км/ч";
        }
        return "Сначала нужно начать движение!";
    }
    
    // Специфические методы для велосипеда
    public function changeGear($gear) {
        if ($gear >= 1 && $gear <= $this->gears) {
            $this->currentGear = $gear;
            return "Переключился на " . $gear . " скорость";
        }
        return "Неверная скорость!";
    }
    
    public function ringBell() {
        $this->isBellRung = true;
        return "Дзинь-дзинь!";
    }
}

// Демонстрация наследования в действии
echo "=== ДЕМОНСТРАЦИЯ НАСЛЕДОВАНИЯ ===\n\n";

$car = new Car("Toyota", "Camry", 2022, "бензин", 4);
$motorcycle = new Motorcycle("Harley-Davidson", "Sportster", 2021, 1200);
$bicycle = new Bicycle("Trek", "FX", 2023, 21);

echo "\n--- Общие методы (унаследованные) ---\n";
echo $car->getInfo() . "\n";
echo $motorcycle->getInfo() . "\n";
echo $bicycle->getInfo() . "\n";

echo "\n--- Запуск транспорта ---\n";
echo $car->start() . "\n";
echo $motorcycle->start() . "\n";
echo $bicycle->start() . "\n";

echo "\n--- Ускорение ---\n";
echo $car->accelerate(60) . "\n";
echo $motorcycle->accelerate(80) . "\n";
echo $bicycle->accelerate(15) . "\n";

echo "\n--- Специфические методы ---\n";
echo $car->honk() . "\n";
echo $car->turnOnRadio() . "\n";

echo $motorcycle->doWheelie() . "\n";
echo $motorcycle->lowerKickstand() . "\n";

echo $bicycle->changeGear(3) . "\n";
echo $bicycle->ringBell() . "\n";

echo "\n--- Информация после действий ---\n";
echo $car->getInfo() . "\n";
echo $motorcycle->getInfo() . "\n";
echo $bicycle->getInfo() . "\n";

echo "\n--- Остановка ---\n";
echo $car->stop() . "\n";
echo $motorcycle->stop() . "\n";
echo $bicycle->stop() . "\n";
?>
```

### Преимущества наследования: почему это мощно

1. **Повторное использование кода** - не изобретаем велосипед каждый раз
2. **Иерархическая организация** - логичная структура классов
3. **Расширяемость** - легко добавлять новую функциональность
4. **Поддержка** - исправления в базовом классе автоматически применяются ко всем наследникам

**Ментальная модель:** Наследование - это как семейное древо. Общие черты передаются из поколения в поколение, но каждое новое поколение добавляет что-то свое.

>>Наследование - это программистская версия "яблочко от яблоньки недалеко падает", но с возможностью добавить апельсиновые ветки!

## Глава 6: Полиморфизм - многообразие форм

### Что такое полиморфизм?

Полиморфизм - это возможность объектов разных классов реагировать на одно и то же сообщение (вызов метода) по-разному. Если наследование - это "что", то полиморфизм - это "как".

**Простая аналогия:** Представьте кнопки в реальной жизни. Кнопка лифта, кнопка звонка, кнопка на пульте - все они кнопки (общий интерфейс - "нажать"), но делают разное.

```php
<?php
// Базовый класс для всех животных
class Animal {
    protected $name;
    
    public function __construct($name) {
        $this->name = $name;
    }
    
    // Этот метод будет переопределен в дочерних классах
    public function makeSound() {
        return $this->name . " издает звук";
    }
    
    public function getName() {
        return $this->name;
    }
}

// Конкретные реализации
class Dog extends Animal {
    public function makeSound() {
        return $this->name . " громко лает: Гав-гав!";
    }
    
    public function fetch($item) {
        return $this->name . " приносит " . $item;
    }
}

class Cat extends Animal {
    public function makeSound() {
        return $this->name . " нежно мурлычет: Мяу!";
    }
    
    public function climbTree() {
        return $this->name . " ловко залезает на дерево";
    }
}

class Bird extends Animal {
    public function makeSound() {
        return $this->name . " весело чирикает: Чик-чирик!";
    }
    
    public function fly() {
        return $this->name . " взлетает в небо";
    }
}

class Cow extends Animal {
    public function makeSound() {
        return $this->name . " мычит: Муууу!";
    }
    
    public function giveMilk() {
        return $this->name . " дает молоко";
    }
}

// Функция, демонстрирующая полиморфизм
function animalConcert(array $animals) {
    echo "=== НАЧИНАЕТСЯ КОНЦЕРТ ЖИВОТНЫХ ===\n";
    
    foreach ($animals as $animal) {
        // Важно: функция работает с Animal, но вызывает переопределенные методы
        echo "🎵 " . $animal->makeSound() . "\n";
    }
    
    echo "=== КОНЦЕРТ ЗАКОНЧИЛСЯ ===\n\n";
}

// Другая полиморфная функция
function interactWithAnimal(Animal $animal) {
    echo "Взаимодействуем с " . $animal->getName() . ":\n";
    echo "- Звук: " . $animal->makeSound() . "\n";
    
    // Дополнительные возможности в зависимости от конкретного типа
    if ($animal instanceof Dog) {
        echo "- Особенность: " . $animal->fetch("мячик") . "\n";
    } elseif ($animal instanceof Cat) {
        echo "- Особенность: " . $animal->climbTree() . "\n";
    } elseif ($animal instanceof Bird) {
        echo "- Особенность: " . $animal->fly() . "\n";
    } elseif ($animal instanceof Cow) {
        echo "- Особенность: " . $animal->giveMilk() . "\n";
    }
    echo "\n";
}

// Создаем животных разных типов
$animals = [
    new Dog("Шарик"),
    new Cat("Мурка"),
    new Bird("Кеша"),
    new Cow("Зорька"),
    new Dog("Бобик"),
    new Cat("Васька")
];

// Демонстрация полиморфизма
animalConcert($animals);

// Взаимодействие с каждым животным
foreach ($animals as $animal) {
    interactWithAnimal($animal);
}

// Полиморфизм в массиве - разные типы, общий интерфейс
echo "=== ОБХОД МАССИВА ПОЛИМОРФНЫХ ОБЪЕКТОВ ===\n";
foreach ($animals as $index => $animal) {
    echo ($index + 1) . ". " . get_class($animal) . " " . $animal->getName() . 
         " говорит: " . $animal->makeSound() . "\n";
}
?>
```

### Полиморфизм в действии

Полиморфизм особенно мощно проявляется в комбинации с интерфейсами:

```php
<?php
// Интерфейс определяет контракт для всех транспортных средств
interface Vehicle {
    public function start();
    public function stop();
    public function getInfo();
}

// Разные классы реализуют один интерфейс по-разному
class Car implements Vehicle {
    private $brand;
    private $speed = 0;
    
    public function __construct($brand) {
        $this->brand = $brand;
    }
    
    public function start() {
        return $this->brand . " заводит двигатель: Врум-врум!";
    }
    
    public function stop() {
        $this->speed = 0;
        return $this->brand . " тормозит: Скрииип!";
    }
    
    public function getInfo() {
        return "Автомобиль " . $this->brand . ", скорость: " . $this->speed . " км/ч";
    }
}

class Bicycle implements Vehicle {
    private $type;
    
    public function __construct($type) {
        $this->type = $type;
    }
    
    public function start() {
        return $this->type . " велосипед: Начинаю крутить педали!";
    }
    
    public function stop() {
        return $this->type . " велосипед: Останавливаюсь!";
    }
    
    public function getInfo() {
        return $this->type . " велосипед";
    }
}

class Airplane implements Vehicle {
    private $model;
    private $altitude = 0;
    
    public function __construct($model) {
        $this->model = $model;
    }
    
    public function start() {
        return "Самолет " . $this->model . ": Запускаю двигатели! Рёв двигателей!";
    }
    
    public function stop() {
        $this->altitude = 0;
        return "Самолет " . $this->model . ": Иду на посадку!";
    }
    
    public function getInfo() {
        return "Самолет " . $this->model . ", высота: " . $this->altitude . " м";
    }
}

// Класс для управления транспортными средствами
class TransportManager {
    public static function testVehicle(Vehicle $vehicle) {
        echo "=== ТЕСТИРУЕМ ТРАНСПОРТ ===\n";
        echo $vehicle->getInfo() . "\n";
        echo "Запуск: " . $vehicle->start() . "\n";
        echo "Остановка: " . $vehicle->stop() . "\n";
        echo "Тест завершен!\n\n";
    }
    
    public static function startAll(array $vehicles) {
        echo "=== МАССОВЫЙ ЗАПУСК ТРАНСПОРТА ===\n";
        foreach ($vehicles as $vehicle) {
            echo $vehicle->start() . "\n";
        }
        echo "Все транспортные средства запущены!\n\n";
    }
}

// Создаем различные транспортные средства
$vehicles = [
    new Car("Toyota"),
    new Bicycle("горный"),
    new Airplane("Boeing 747"),
    new Car("BMW"),
    new Bicycle("городской")
];

// Тестируем каждое средство
foreach ($vehicles as $vehicle) {
    TransportManager::testVehicle($vehicle);
}

// Массовый запуск - полиморфизм в действии!
TransportManager::startAll($vehicles);

// Дополнительный пример: полиморфизм с параметрами
function createAndTestVehicle($type, $model) {
    switch ($type) {
        case 'car':
            return new Car($model);
        case 'bicycle':
            return new Bicycle($model);
        case 'airplane':
            return new Airplane($model);
        default:
            throw new Exception("Неизвестный тип транспорта");
    }
}

// Создаем и тестируем транспорт динамически
$vehicleTypes = [
    ['car', 'Mercedes'],
    ['bicycle', 'шоссейный'],
    ['airplane', 'Airbus A320']
];

foreach ($vehicleTypes as $vehicleInfo) {
    $vehicle = createAndTestVehicle($vehicleInfo[0], $vehicleInfo[1]);
    TransportManager::testVehicle($vehicle);
}
?>
```

### Преимущества полиморфизма

1. **Гибкость кода** - можно легко добавлять новые типы
2. **Сокращение кода** - общие функции работают с разными типами
3. **Упрощение поддержки** - изменения локализованы
4. **Чистый код** - логика отделена от конкретных реализаций

>>Полиморфизм - это как универсальный пульт, который работает с телевизором, кондиционером и музыкальным центром. Нажимаешь одну кнопку "включить", а устройство само решает, как именно это сделать.

## Глава 7: Абстрактные классы и методы

### Зачем нужны абстрактные классы?

Абстрактные классы - это классы, которые не предназначены для создания объектов напрямую. Они служат шаблонами для других классов.

**Аналогия:** Абстрактный класс "Геометрическая фигура" описывает общие свойства и методы, но нельзя создать объект "просто фигура". Можно создать конкретные фигуры: круг, квадрат, треугольник.

```php
<?php
// Абстрактный класс для всех сотрудников
abstract class Employee {
    protected $name;
    protected $salary;
    protected $position;
    
    public function __construct($name, $salary, $position) {
        $this->name = $name;
        $this->salary = $salary;
        $this->position = $position;
    }
    
    // Конкретные методы - общие для всех сотрудников
    public function getName() {
        return $this->name;
    }
    
    public function getSalary() {
        return $this->salary;
    }
    
    public function getPosition() {
        return $this->position;
    }
    
    public function work() {
        return $this->name . " работает на должности " . $this->position;
    }
    
    // Абстрактный метод - должен быть реализован в дочерних классах
    abstract public function calculateBonus();
    abstract public function getResponsibilities();
    
    // Еще один абстрактный метод
    abstract public function reportWork();
}

// Конкретные классы-наследники
class Developer extends Employee {
    private $programmingLanguage;
    private $completedTasks = 0;
    
    public function __construct($name, $salary, $programmingLanguage) {
        parent::__construct($name, $salary, "Разработчик");
        $this->programmingLanguage = $programmingLanguage;
    }
    
    // Реализация абстрактных методов
    public function calculateBonus() {
        // Бонус разработчика зависит от завершенных задач
        $bonus = $this->completedTasks * 1000;
        return $bonus;
    }
    
    public function getResponsibilities() {
        return [
            "Написание кода на " . $this->programmingLanguage,
            "Тестирование программ",
            "Участие в код-ревью"
        ];
    }
    
    public function reportWork() {
        return $this->name . " завершил " . $this->completedTasks . " задач. Бонус: " . $this->calculateBonus() . " руб.";
    }
    
    // Специфические методы разработчика
    public function completeTask() {
        $this->completedTasks++;
        return $this->name . " завершил задачу! Всего завершено: " . $this->completedTasks;
    }
    
    public function writeCode() {
        return $this->name . " пишет код на " . $this->programmingLanguage;
    }
}

class Manager extends Employee {
    private $teamSize;
    private $projectsCompleted = 0;
    
    public function __construct($name, $salary, $teamSize) {
        parent::__construct($name, $salary, "Менеджер");
        $this->teamSize = $teamSize;
    }
    
    // Реализация абстрактных методов (своя для менеджера)
    public function calculateBonus() {
        // Бонус менеджера зависит от размера команды и завершенных проектов
        $bonus = ($this->teamSize * 500) + ($this->projectsCompleted * 2000);
        return $bonus;
    }
    
    public function getResponsibilities() {
        return [
            "Управление командой из " . $this->teamSize . " человек",
            "Планирование проектов",
            "Отчетность перед руководством"
        ];
    }
    
    public function reportWork() {
        return $this->name . " управляет командой из " . $this->teamSize . 
               " человек. Завершено проектов: " . $this->projectsCompleted . 
               ". Бонус: " . $this->calculateBonus() . " руб.";
    }
    
    // Специфические методы менеджера
    public function completeProject() {
        $this->projectsCompleted++;
        return $this->name . " успешно завершил проект! Всего проектов: " . $this->projectsCompleted;
    }
    
    public function conductMeeting() {
        return $this->name . " проводит собрание с командой";
    }
}

class Designer extends Employee {
    private $designTools = [];
    private $designsCreated = 0;
    
    public function __construct($name, $salary, $designTools) {
        parent::__construct($name, $salary, "Дизайнер");
        $this->designTools = $designTools;
    }
    
    // Реализация абстрактных методов (своя для дизайнера)
    public function calculateBonus() {
        // Бонус дизайнера зависит от созданных дизайнов
        $bonus = $this->designsCreated * 1500;
        return $bonus;
    }
    
    public function getResponsibilities() {
        $tools = implode(", ", $this->designTools);
        return [
            "Создание дизайнов с использованием: " . $tools,
            "Работа с клиентами",
            "Подготовка макетов"
        ];
    }
    
    public function reportWork() {
        return $this->name . " создал " . $this->designsCreated . 
               " дизайнов. Использует инструменты: " . implode(", ", $this->designTools) . 
               ". Бонус: " . $this->calculateBonus() . " руб.";
    }
    
    // Специфические методы дизайнера
    public function createDesign() {
        $this->designsCreated++;
        return $this->name . " создал новый дизайн! Всего создано: " . $this->designsCreated;
    }
    
    public function useTool($tool) {
        if (in_array($tool, $this->designTools)) {
            return $this->name . " использует " . $tool . " для работы";
        }
        return $this->name . " не работает с " . $tool;
    }
}

// Демонстрация работы с абстрактными классами
echo "=== СИСТЕМА УПРАВЛЕНИЯ СОТРУДНИКАМИ ===\n\n";

// Создаем сотрудников разных специальностей
$employees = [
    new Developer("Алексей", 100000, "PHP"),
    new Manager("Ольга", 120000, 5),
    new Designer("Мария", 90000, ["Photoshop", "Figma", "Illustrator"]),
    new Developer("Дмитрий", 110000, "JavaScript")
];

// Нельзя создать объект абстрактного класса!
// $employee = new Employee("Иван", 50000, "Сотрудник"); // ОШИБКА!

// Работа с сотрудниками через абстрактный интерфейс
foreach ($employees as $employee) {
    echo "=== " . strtoupper($employee->getPosition()) . " ===\n";
    echo "Имя: " . $employee->getName() . "\n";
    echo "Зарплата: " . $employee->getSalary() . " руб.\n";
    echo "Работа: " . $employee->work() . "\n";
    
    // Абстрактные методы - разная реализация для разных классов
    echo "Отчет: " . $employee->reportWork() . "\n";
    
    echo "Обязанности:\n";
    foreach ($employee->getResponsibilities() as $responsibility) {
        echo "- " . $responsibility . "\n";
    }
    
    // Вызов специфических методов в зависимости от типа
    if ($employee instanceof Developer) {
        echo "Действие: " . $employee->completeTask() . "\n";
        echo "Действие: " . $employee->writeCode() . "\n";
    } elseif ($employee instanceof Manager) {
        echo "Действие: " . $employee->completeProject() . "\n";
        echo "Действие: " . $employee->conductMeeting() . "\n";
    } elseif ($employee instanceof Designer) {
        echo "Действие: " . $employee->createDesign() . "\n";
        echo "Действие: " . $employee->useTool("Figma") . "\n";
    }
    
    echo "\n";
}

// Функция, работающая с абстрактным классом
function calculateTotalBonuses(array $employees) {
    $total = 0;
    foreach ($employees as $employee) {
        $total += $employee->calculateBonus();
    }
    return "Общая сумма бонусов для всех сотрудников: " . $total . " руб.";
}

echo calculateTotalBonuses($employees) . "\n";
?>
```

### Абстрактные методы - контракт реализации

Абстрактные методы - это методы без реализации, которые должны быть реализованы в дочерних классах. Они определяют "контракт" - что должен уметь делать каждый наследник.

**Важно:** Если класс содержит хотя бы один абстрактный метод, весь класс должен быть объявлен абстрактным.

### Когда использовать абстрактные классы?

1. **Когда есть общая логика** для группы родственных классов
2. **Когда нужно обеспечить** определенный интерфейс для наследников
3. **Когда нужно избежать** создания объектов базового класса

>>Абстрактный класс - это как родитель, который говорит: "Я дам тебе фамилию и ДНК, но профессию и характер ты должен выбрать сам!"

## Глава 8: Интерфейсы - чистые контракты

### Интерфейсы vs Абстрактные классы

Если абстрактные классы - это "неполные родители", то интерфейсы - это "чистые контракты". Интерфейс определяет ЧТО должен делать класс, но не говорит КАК это делать.

**Простая аналогия:** Интерфейс - это как должностная инструкция. В ней написано, какие функции должен выполнять сотрудник, но не указано, как именно он это будет делать.

```php
<?php
// Интерфейс для всего, что может летать
interface Flyable {
    public function takeOff();
    public function land();
    public function getAltitude();
}

// Интерфейс для всего, что может перевозить грузы
interface CargoTransport {
    public function loadCargo($weight);
    public function unloadCargo();
    public function getCurrentLoad();
}

// Интерфейс для всего, что требует обслуживания
interface Maintainable {
    public function performMaintenance();
    public function getNextMaintenanceDate();
}

// Класс самолета реализует несколько интерфейсов
class Airplane implements Flyable, CargoTransport, Maintainable {
    private $altitude = 0;
    private $cargoWeight = 0;
    private $maintenanceDate;
    
    public function __construct() {
        $this->maintenanceDate = date('Y-m-d', strtotime('+30 days'));
    }
    
    // Реализация методов Flyable
    public function takeOff() {
        $this->altitude = 10000;
        return "Самолет взлетает! Высота: " . $this->altitude . " метров";
    }
    
    public function land() {
        $this->altitude = 0;
        return "Самолет совершает посадку";
    }
    
    public function getAltitude() {
        return $this->altitude;
    }
    
    // Реализация методов CargoTransport
    public function loadCargo($weight) {
        $this->cargoWeight += $weight;
        return "Загружено " . $weight . " кг груза. Общий вес: " . $this->cargoWeight . " кг";
    }
    
    public function unloadCargo() {
        $weight = $this->cargoWeight;
        $this->cargoWeight = 0;
        return "Выгружено " . $weight . " кг груза";
    }
    
    public function getCurrentLoad() {
        return $this->cargoWeight;
    }
    
    // Реализация методов Maintainable
    public function performMaintenance() {
        $this->maintenanceDate = date('Y-m-d', strtotime('+30 days'));
        return "Техническое обслуживание выполнено. Следующее: " . $this->maintenanceDate;
    }
    
    public function getNextMaintenanceDate() {
        return $this->maintenanceDate;
    }
}

// Дрон тоже может летать, но по-другому
class Drone implements Flyable, Maintainable {
    private $altitude = 0;
    private $batteryLevel = 100;
    private $maintenanceDate;
    
    public function __construct() {
        $this->maintenanceDate = date('Y-m-d', strtotime('+7 days'));
    }
    
    // Реализация методов Flyable (своя реализация)
    public function takeOff() {
        $this->altitude = 100;
        $this->batteryLevel -= 10;
        return "Дрон взлетает! Высота: " . $this->altitude . " метров. Батарея: " . $this->batteryLevel . "%";
    }
    
    public function land() {
        $this->altitude = 0;
        return "Дрон совершает посадку";
    }
    
    public function getAltitude() {
        return $this->altitude;
    }
    
    // Реализация методов Maintainable
    public function performMaintenance() {
        $this->maintenanceDate = date('Y-m-d', strtotime('+7 days'));
        $this->batteryLevel = 100;
        return "Обслуживание дрона выполнено. Батарея заряжена до 100%";
    }
    
    public function getNextMaintenanceDate() {
        return $this->maintenanceDate;
    }
    
    // Специфический метод дрона
    public function takePhoto() {
        $this->batteryLevel -= 5;
        return "Дрон делает фото! Батарея: " . $this->batteryLevel . "%";
    }
}

// Птица - тоже летает, но это живое существо
class Bird implements Flyable {
    private $altitude = 0;
    private $name;
    private $energy = 100;
    
    public function __construct($name) {
        $this->name = $name;
    }
    
    // Реализация методов Flyable (совсем другая)
    public function takeOff() {
        $this->altitude = 50;
        $this->energy -= 20;
        return $this->name . " взлетает с ветки! Высота: " . $this->altitude . " метров. Энергия: " . $this->energy . "%";
    }
    
    public function land() {
        $this->altitude = 0;
        return $this->name . " садится на ветку";
    }
    
    public function getAltitude() {
        return $this->altitude;
    }
    
    // Специфические методы птицы
    public function eat() {
        $this->energy = min(100, $this->energy + 30);
        return $this->name . " клюет зерно. Энергия: " . $this->energy . "%";
    }
    
    public function sing() {
        return $this->name . " поет: Чик-чирик!";
    }
}

// Класс для управления летающими объектами
class FlightControl {
    public static function conductFlightTest(Flyable $flyingObject) {
        echo "=== НАЧАЛО ТЕСТИРОВАНИЯ ===\n";
        echo "Объект типа: " . get_class($flyingObject) . "\n";
        
        // Тестируем взлет
        echo "1. Взлет: " . $flyingObject->takeOff() . "\n";
        echo "   Текущая высота: " . $flyingObject->getAltitude() . " метров\n";
        
        // Тестируем посадку
        echo "2. Посадка: " . $flyingObject->land() . "\n";
        echo "   Текущая высота: " . $flyingObject->getAltitude() . " метров\n";
        
        // Дополнительные тесты в зависимости от типа объекта
        if ($flyingObject instanceof Maintainable) {
            echo "3. Обслуживание: " . $flyingObject->performMaintenance() . "\n";
            echo "   Следующее ТО: " . $flyingObject->getNextMaintenanceDate() . "\n";
        }
        
        if ($flyingObject instanceof CargoTransport) {
            echo "4. Тест груза: " . $flyingObject->loadCargo(100) . "\n";
            echo "   Текущая загрузка: " . $flyingObject->getCurrentLoad() . " кг\n";
        }
        
        echo "=== ТЕСТИРОВАНИЕ ЗАВЕРШЕНО ===\n\n";
    }
    
    public static function massTakeOff(array $flyingObjects) {
        echo "=== МАССОВЫЙ ВЗЛЕТ ===\n";
        foreach ($flyingObjects as $object) {
            echo "✈️  " . $object->takeOff() . "\n";
        }
        echo "Все объекты в воздухе!\n\n";
    }
}

// Демонстрация работы с интерфейсами
echo "=== СИСТЕМА УПРАВЛЕНИЯ ПОЛЕТАМИ ===\n\n";

// Создаем различные летающие объекты
$flyingObjects = [
    new Airplane(),
    new Drone(),
    new Bird("Воробей"),
    new Bird("Орел")
];

// Тестируем каждый объект
foreach ($flyingObjects as $object) {
    FlightControl::conductFlightTest($object);
}

// Массовый взлет - полиморфизм в действии!
FlightControl::massTakeOff($flyingObjects);

// Работа с конкретными интерфейсами
function handleMaintenance(Maintainable $maintainableObject) {
    echo "=== СЛУЖБА ТЕХНИЧЕСКОГО ОБСЛУЖИВАНИЯ ===\n";
    echo "Объект: " . get_class($maintainableObject) . "\n";
    echo "Статус: " . $maintainableObject->performMaintenance() . "\n";
    echo "Следующее ТО: " . $maintainableObject->getNextMaintenanceDate() . "\n\n";
}

function handleCargo(CargoTransport $cargoTransport) {
    echo "=== СЛУЖБА ГРУЗОПЕРЕВОЗОК ===\n";
    echo "Объект: " . get_class($cargoTransport) . "\n";
    echo "Загрузка: " . $cargoTransport->loadCargo(500) . "\n";
    echo "Текущий груз: " . $cargoTransport->getCurrentLoad() . " кг\n";
    echo "Разгрузка: " . $cargoTransport->unloadCargo() . "\n\n";
}

// Применяем функции к подходящим объектам
foreach ($flyingObjects as $object) {
    if ($object instanceof Maintainable) {
        handleMaintenance($object);
    }
    
    if ($object instanceof CargoTransport) {
        handleCargo($object);
    }
}
?>
```

### Множественная реализация интерфейсов

В отличие от наследования (где можно наследовать только от одного класса), PHP позволяет реализовывать множество интерфейсов. Это дает огромную гибкость!

```php
<?php
// Дополнительные интерфейсы для демонстрации множественного наследования
interface GPSNavigator {
    public function setDestination($address);
    public function getCurrentRoute();
}

interface EntertainmentSystem {
    public function playMusic($song);
    public function playMovie($movie);
}

interface ClimateControl {
    public function setTemperature($degrees);
    public function setFanSpeed($level);
}

// Современный автомобиль реализует все интерфейсы
class ModernCar implements GPSNavigator, EntertainmentSystem, ClimateControl {
    private $destination;
    private $currentSong;
    private $temperature = 22;
    private $fanSpeed = 2;
    
    // Реализация GPSNavigator
    public function setDestination($address) {
        $this->destination = $address;
        return "Задан маршрут до: " . $address;
    }
    
    public function getCurrentRoute() {
        if ($this->destination) {
            return "Текущий маршрут: Дом → " . $this->destination;
        }
        return "Маршрут не задан";
    }
    
    // Реализация EntertainmentSystem
    public function playMusic($song) {
        $this->currentSong = $song;
        return "Включаю музыку: " . $song;
    }
    
    public function playMovie($movie) {
        return "Включаю фильм: " . $movie . " (только для пассажиров!)";
    }
    
    // Реализация ClimateControl
    public function setTemperature($degrees) {
        $this->temperature = $degrees;
        return "Установлена температура: " . $degrees . "°C";
    }
    
    public function setFanSpeed($level) {
        $this->fanSpeed = max(1, min(5, $level));
        return "Установлена скорость вентилятора: " . $this->fanSpeed;
    }
    
    // Собственные методы автомобиля
    public function startJourney() {
        return "Начинаем поездку! " . $this->getCurrentRoute();
    }
}

// Функции, работающие с конкретными интерфейсами
function planRoute(GPSNavigator $navigator, $destination) {
    echo "=== ПЛАНИРОВАНИЕ МАРШРУТА ===\n";
    echo $navigator->setDestination($destination) . "\n";
    echo $navigator->getCurrentRoute() . "\n\n";
}

function provideEntertainment(EntertainmentSystem $entertainment, $song) {
    echo "=== РАЗВЛЕЧЕНИЯ В ДОРОГЕ ===\n";
    echo $entertainment->playMusic($song) . "\n";
    echo $entertainment->playMovie("Интерстеллар") . "\n\n";
}

function adjustComfort(ClimateControl $climate, $temperature, $fanSpeed) {
    echo "=== КОМФОРТ В САЛОНЕ ===\n";
    echo $climate->setTemperature($temperature) . "\n";
    echo $climate->setFanSpeed($fanSpeed) . "\n\n";
}

// Использование
$car = new ModernCar();

// Каждая функция работает только со своим интерфейсом
planRoute($car, "ул. Программистов, 123");
provideEntertainment($car, "Queen - Bohemian Rhapsody");
adjustComfort($car, 23, 3);

echo $car->startJourney() . "\n";
?>
```

### Практическое применение интерфейсов

Интерфейсы особенно полезны в больших проектах и при работе в команде:

```php
<?php
// Интерфейсы для системы оплаты
interface PaymentGateway {
    public function processPayment($amount, $currency);
    public function refund($transactionId);
    public function getBalance();
}

interface Logger {
    public function log($message, $level = 'INFO');
}

interface NotificationSender {
    public function sendReceipt($email, $amount);
    public function sendRefundNotification($email, $amount);
}

// Реализация PayPal
class PayPalGateway implements PaymentGateway, Logger {
    private $balance = 10000;
    private $transactions = [];
    
    public function processPayment($amount, $currency) {
        if ($amount > $this->balance) {
            $this->log("Недостаточно средств для платежа: " . $amount, 'ERROR');
            return false;
        }
        
        $transactionId = 'PP_' . uniqid();
        $this->balance -= $amount;
        $this->transactions[$transactionId] = $amount;
        
        $this->log("Платеж обработан: " . $amount . " " . $currency . " (ID: " . $transactionId . ")");
        return $transactionId;
    }
    
    public function refund($transactionId) {
        if (!isset($this->transactions[$transactionId])) {
            $this->log("Транзакция не найдена: " . $transactionId, 'ERROR');
            return false;
        }
        
        $amount = $this->transactions[$transactionId];
        $this->balance += $amount;
        unset($this->transactions[$transactionId]);
        
        $this->log("Возврат средств: " . $amount . " (ID: " . $transactionId . ")");
        return true;
    }
    
    public function getBalance() {
        return $this->balance;
    }
    
    public function log($message, $level = 'INFO') {
        $timestamp = date('Y-m-d H:i:s');
        echo "[PAYPAL][$level][$timestamp] $message\n";
    }
}

// Реализация Stripe
class StripeGateway implements PaymentGateway, NotificationSender {
    private $balance = 15000;
    
    public function processPayment($amount, $currency) {
        if ($amount > $this->balance) {
            return false;
        }
        
        $transactionId = 'ST_' . uniqid();
        $this->balance -= $amount;
        
        // Отправляем квитанцию
        $this->sendReceipt("client@example.com", $amount);
        
        return $transactionId;
    }
    
    public function refund($transactionId) {
        // В реальности здесь была бы логика поиска транзакции
        $refundAmount = 500; // Примерная сумма
        $this->balance += $refundAmount;
        
        $this->sendRefundNotification("client@example.com", $refundAmount);
        return true;
    }
    
    public function getBalance() {
        return $this->balance;
    }
    
    public function sendReceipt($email, $amount) {
        echo "Stripe: Отправка квитанции на $email на сумму $amount\n";
    }
    
    public function sendRefundNotification($email, $amount) {
        echo "Stripe: Уведомление о возврате на $email на сумму $amount\n";
    }
}

// Сервис для работы с платежами
class PaymentService {
    private $gateway;
    private $logger;
    
    public function __construct(PaymentGateway $gateway) {
        $this->gateway = $gateway;
        
        // Если шлюз поддерживает логирование, используем его
        if ($gateway instanceof Logger) {
            $this->logger = $gateway;
        }
    }
    
    public function makePayment($amount, $currency) {
        if ($this->logger) {
            $this->logger->log("Попытка платежа: " . $amount . " " . $currency);
        }
        
        $result = $this->gateway->processPayment($amount, $currency);
        
        if ($result && $this->gateway instanceof NotificationSender) {
            $this->gateway->sendReceipt("customer@example.com", $amount);
        }
        
        return $result;
    }
    
    public function getGatewayBalance() {
        return $this->gateway->getBalance();
    }
}

// Использование с разными платежными системами
echo "=== ТЕСТИРОВАНИЕ ПЛАТЕЖНЫХ СИСТЕМ ===\n\n";

$paypalService = new PaymentService(new PayPalGateway());
$stripeService = new PaymentService(new StripeGateway());

echo "PayPal платеж: ";
$paypalTransaction = $paypalService->makePayment(1000, 'USD');
echo "ID транзакции: " . ($paypalTransaction ?: 'Ошибка') . "\n";
echo "Баланс PayPal: " . $paypalService->getGatewayBalance() . "\n\n";

echo "Stripe платеж: ";
$stripeTransaction = $stripeService->makePayment(1500, 'USD');
echo "ID транзакции: " . ($stripeTransaction ?: 'Ошибка') . "\n";
echo "Баланс Stripe: " . $stripeService->getGatewayBalance() . "\n";
?>
```

>>Интерфейсы - это как список требований к идеальной паре: "должен уметь готовить, смешить, зарабатывать". Каждый кандидат решает эти задачи по-своему, но контракт соблюден!

# Часть III: Дополнительные возможности ООП в PHP

## Глава 9: Статические свойства и методы

### Статические члены класса

Статические свойства и методы принадлежат классу, а не объекту. Их можно использовать без создания экземпляра класса.

**Аналогия:** Если обычные свойства - это личные вещи каждого объекта, то статические - это общие для всех объекты класса, как мебель в офисе.

```php
<?php
class Counter {
    // Статическое свойство - общее для всех объектов
    public static $totalCount = 0;
    
    // Обычное свойство - индивидуальное для каждого объекта
    public $instanceCount = 0;
    
    public function __construct() {
        // Увеличиваем общий счетчик
        self::$totalCount++;
        
        // Увеличиваем индивидуальный счетчик
        $this->instanceCount++;
    }
    
    // Статический метод - работает без создания объекта
    public static function getTotalCount() {
        return "Всего создано объектов: " . self::$totalCount;
    }
    
    // Обычный метод - требует объект
    public function getInstanceInfo() {
        return "Это объект №" . $this->instanceCount . " из " . self::$totalCount;
    }
    
    // Статический метод может создавать объекты (фабричный метод)
    public static function createMultiple($count) {
        $objects = [];
        for ($i = 0; $i < $count; $i++) {
            $objects[] = new self();
        }
        return $objects;
    }
}

// Использование статических методов без создания объектов
echo Counter::getTotalCount() . "\n"; // Всего создано объектов: 0

// Создаем объекты
$obj1 = new Counter();
$obj2 = new Counter();
$obj3 = new Counter();

echo $obj1->getInstanceInfo() . "\n"; // Это объект №1 из 3
echo $obj2->getInstanceInfo() . "\n"; // Это объект №1 из 3
echo $obj3->getInstanceInfo() . "\n"; // Это объект №1 из 3

// Статическое свойство общее для всех
echo Counter::getTotalCount() . "\n"; // Всего создано объектов: 3

// Фабричный метод
$moreObjects = Counter::createMultiple(2);
echo Counter::getTotalCount() . "\n"; // Всего создано объектов: 5
?>
```

### Паттерн Singleton

Один из самых известных паттернов, использующих статические свойства - Singleton (Одиночка). Он гарантирует, что у класса будет только один экземпляр. Реализуется за счет приватного конструктора (`private function __construct`)

```php
<?php
class DatabaseConnection {
    // Статическое свойство для хранения единственного экземпляра
    private static $instance = null;
    
    // Приватный конструктор - нельзя создать извне
    private function __construct() {
        echo "Установлено подключение к базе данных\n";
        // Здесь была бы реальная логика подключения
    }
    
    // Статический метод для получения экземпляра
    public static function getInstance() {
        if (self::$instance === null) {
            self::$instance = new self();
        }
        return self::$instance;
    }
    
    // Запрещаем клонирование
    private function __clone() {}
    
    // Запрещаем десериализацию
    public function __wakeup() {
        throw new Exception("Cannot unserialize singleton");
    }
    
    // Методы работы с базой данных
    public function query($sql) {
        return "Выполнен запрос: " . $sql;
    }
    
    public function getConnectionInfo() {
        return "Активное подключение к БД (Singleton)";
    }
}

// Класс для логирования (тоже Singleton)
class Logger {
    private static $instance = null;
    private $logs = [];
    
    private function __construct() {
        echo "Логгер инициализирован\n";
    }
    
    public static function getInstance() {
        if (self::$instance === null) {
            self::$instance = new self();
        }
        return self::$instance;
    }
    
    public function log($message) {
        $timestamp = date('Y-m-d H:i:s');
        $this->logs[] = "[$timestamp] $message";
        echo "LOG: $message\n";
    }
    
    public function getLogs() {
        return $this->logs;
    }
    
    private function __clone() {}
    public function __wakeup() {
        throw new Exception("Cannot unserialize singleton");
    }
}

// Класс конфигурации (тоже Singleton)
class Config {
    private static $instance = null;
    private $settings = [];
    
    private function __construct() {
        // Загрузка настроек из файла или базы данных
        $this->settings = [
            'db_host' => 'localhost',
            'db_name' => 'myapp',
            'debug' => true,
            'version' => '1.0.0'
        ];
        echo "Конфигурация загружена\n";
    }
    
    public static function getInstance() {
        if (self::$instance === null) {
            self::$instance = new self();
        }
        return self::$instance;
    }
    
    public function get($key) {
        return $this->settings[$key] ?? null;
    }
    
    public function set($key, $value) {
        $this->settings[$key] = $value;
    }
    
    private function __clone() {}
    public function __wakeup() {
        throw new Exception("Cannot unserialize singleton");
    }
}

// Демонстрация работы Singleton
echo "=== ДЕМОНСТРАЦИЯ PATTERN SINGLETON ===\n\n";

// Получаем экземпляры синглтонов
$db1 = DatabaseConnection::getInstance();
$db2 = DatabaseConnection::getInstance();

$logger1 = Logger::getInstance();
$logger2 = Logger::getInstance();

$config1 = Config::getInstance();
$config2 = Config::getInstance();

// Проверяем, что это действительно один и тот же объект
echo "Проверка синглтонов:\n";
echo "DB1 и DB2 - один объект? " . ($db1 === $db2 ? "ДА" : "НЕТ") . "\n";
echo "Logger1 и Logger2 - один объект? " . ($logger1 === $logger2 ? "ДА" : "НЕТ") . "\n";
echo "Config1 и Config2 - один объект? " . ($config1 === $config2 ? "ДА" : "НЕТ") . "\n\n";

// Использование
$logger1->log("Приложение запущено");

echo "Версия приложения: " . $config1->get('version') . "\n";
echo "Хост базы данных: " . $config1->get('db_host') . "\n";

echo $db1->query("SELECT * FROM users") . "\n";
echo $db2->getConnectionInfo() . "\n\n";

// Попытка создать новый экземпляр (не сработает)
// $db3 = new DatabaseConnection(); // Ошибка! Конструктор приватный

// Дополнительный пример: Registry pattern с статическими свойствами
class ServiceRegistry {
    private static $services = [];
    
    public static function register($name, $service) {
        self::$services[$name] = $service;
    }
    
    public static function get($name) {
        if (!isset(self::$services[$name])) {
            throw new Exception("Сервис '$name' не зарегистрирован");
        }
        return self::$services[$name];
    }
    
    public static function getAll() {
        return self::$services;
    }
}

// Регистрируем сервисы
ServiceRegistry::register('database', $db1);
ServiceRegistry::register('logger', $logger1);
ServiceRegistry::register('config', $config1);

// Используем сервисы через регистри
echo "=== ИСПОЛЬЗОВАНИЕ SERVICE REGISTRY ===\n";
$db = ServiceRegistry::get('database');
$logger = ServiceRegistry::get('logger');
$config = ServiceRegistry::get('config');

echo $db->query("SELECT * FROM products") . "\n";
$logger->log("Запрос к базе данных выполнен");
echo "Режим отладки: " . ($config->get('debug') ? 'ВКЛ' : 'ВЫКЛ') . "\n";
?>
```

### Когда использовать статические методы?

**Правильно:**
- Для фабричных методов (создание объектов)
- Для утилитарных функций (математические операции)
- Для реализации паттернов (Singleton, Registry)

**Неправильно:**
- Когда нужно состояние объекта
- Когда метод зависит от свойств объекта
- Для замены глобальных переменных

>>Статические методы - как городские услуги: вода, электричество. Они всегда доступны, не нужно строить свою электростанцию, но и кастомизировать не получится.

## Глава 10: Трейты (Traits) - горизонтальное повторное использование

### Проблема множественного наследования

Представьте, что PHP - это строгий родитель, который говорит: "Можно унаследовать только от одного класса!". Это как если бы вам разрешили иметь только одного биологического родителя. А что если вам нужны черты от обоих?

```php
<?php

// Допустим, у нас есть два класса с полезной функциональностью
class Mathematician {
    public function add($a, $b) {
        return $a + $b;
    }
}

class Writer {
    public function writeText($text) {
        return "Writing: $text";
    }
}

// Хотим создать класс "Scientist", который умеет и то, и другое
// Но так НЕЛЬЗЯ в PHP:
// class Scientist extends Mathematician, Writer {} // ФАТАЛЬНАЯ ОШИБКА!

echo "PHP не поддерживает множественное наследование :(\n";

?>
```

>>PHP в вопросе наследования как строгий учитель - "Выбирай одного родителя и не спорь!"

### Трейты как решение

**Что такое трейты?** Трейты - это как "швейцарские ножи" для классов. Это кусочки кода, которые можно "вклеивать" в разные классы.

```php
<?php

// Создаем трейты - это как наборы навыков
trait MathSkills {
    // Публичный метод сложения
    public function add($a, $b) {
        echo "Adding $a and $b...\n";
        return $a + $b;
    }
    
    // Приватный метод - доступен только внутри трейта/класса
    private function multiply($a, $b) {
        return $a * $b;
    }
    
    // Метод, использующий приватный метод
    public function square($number) {
        echo "Squaring $number...\n";
        return $this->multiply($number, $number);
    }
}

trait LiterarySkills {
    public function writeBook($title) {
        return "Writing book '$title' 📚";
    }
    
    public function writePoem($theme) {
        return "Composing poem about $theme ✍️";
    }
}

// Теперь создаем классы, которые используют эти трейты
class Scientist {
    // "Включаем" трейты в класс с помощью ключевого слова use
    use MathSkills, LiterarySkills;
    
    public function makeDiscovery() {
        $result = $this->add(2, 2); // Метод из первого трейта
        $book = $this->writeBook("My Discovery"); // Метод из второго трейта
        return "$book: 2+2=$result";
    }
}

class Student {
    use MathSkills; // Берем только математические навыки
    
    public function passExam() {
        $answer = $this->square(5); // Используем публичный метод
        return "On exam I calculated that 5² = $answer ✅";
    }
    
    // Попытка использовать приватный метод напрямую не сработает:
    // public function test() {
    //     return $this->multiply(2, 3); // ОШИБКА! Приватный метод
    // }
}

// Используем наши классы
$scientist = new Scientist();
echo $scientist->makeDiscovery() . "\n";
echo $scientist->writePoem("mathematics") . "\n";

$student = new Student();
echo $student->passExam() . "\n";

?>
```

### Конфликты трейтов и их разрешение

**Что такое конфликт?** Это когда два трейта имеют методы с одинаковыми именами. Представьте, что два повара пытаются готовить на одной кухне и оба хотят использовать одну и ту же сковородку!

```php
<?php

// Два трейта с методами-тезками
trait ItalianChef {
    public function cookPasta() {
        return "Cooking carbonara pasta 🍝";
    }
    
    public function greet() {
        return "Ciao! 🇮🇹";
    }
    
    private function secretRecipe() {
        return "Secret of Italian cuisine...";
    }
}

trait FrenchChef {
    public function cookPasta() {
        return "Cooking pasta with truffles 🍄";
    }
    
    public function greet() {
        return "Bonjour! 🇫🇷";
    }
    
    public function bakeCroissant() {
        return "Baking croissant 🥐";
    }
}

class InternationalChef {
    use ItalianChef, FrenchChef {
        // РАЗРЕШАЕМ КОНФЛИКТЫ:
        
        // 1. Говорим использовать метод из ItalianChef вместо FrenchChef
        ItalianChef::cookPasta insteadof FrenchChef;
        
        // 2. Даем методу из FrenchChef псевдоним (алиас)
        FrenchChef::cookPasta as cookFrenchPasta;
        
        // 3. Для приветствия выбираем французский вариант
        FrenchChef::greet insteadof ItalianChef;
        
        // 4. Даем итальянскому приветствию псевдоним
        ItalianChef::greet as greetInItalian;
    }
    
    public function showMenu() {
        $menu = "";
        $menu .= $this->cookPasta() . "\n"; // Итальянская версия
        $menu .= $this->cookFrenchPasta() . "\n"; // Французская версия
        $menu .= $this->bakeCroissant() . "\n"; // Метод только из французского трейта
        return $menu;
    }
}

// Создаем шефа-универсала
$chef = new InternationalChef();

echo "=== Greetings ===\n";
echo "Main: " . $chef->greet() . "\n";
echo "Italian: " . $chef->greetInItalian() . "\n";

echo "\n=== Chef's Menu ===\n";
echo $chef->showMenu();

// Попытка использовать приватный метод приведет к ошибке:
// echo $chef->secretRecipe(); // ФАТАЛЬНАЯ ОШИБКА!

?>
```

## Глава 11: Магические методы

**Что такое магические методы?** Это специальные методы в PHP, которые начинаются с двойного подчеркивания `__` и автоматически вызываются в определенных ситуациях. Они как "волшебные" способности ваших объектов!

### __get и __set - управление доступом к свойствам

**Простыми словами:** Эти методы - как строгие секретари, которые контролируют доступ к свойствам объекта.

```php
<?php

class SmartObject {
    // Приватные свойства - доступны только внутри класса
    private $data = [];
    private $secretInfo = "This is a secret! 🤫";
    
    // Магический метод __set() вызывается ПРИ ПОПЫТКЕ УСТАНОВИТЬ 
    // значение несуществующему или недоступному свойству
    public function __set($propertyName, $value) {
        echo "🔧 Magic __set() called for property '$propertyName' with value '$value'\n";
        
        // Проверяем валидность данных перед сохранением
        if ($propertyName === 'age' && $value < 0) {
            throw new Exception("Age cannot be negative! ❌");
        }
        
        if ($propertyName === 'name' && !is_string($value)) {
            throw new Exception("Name must be a string! ❌");
        }
        
        // Сохраняем данные в массив
        $this->data[$propertyName] = $value;
        echo "✅ Property '$propertyName' successfully set\n";
    }
    
    // Магический метод __get() вызывается ПРИ ПОПЫТКЕ ПОЛУЧИТЬ 
    // значение несуществующего или недоступного свойства
    public function __get($propertyName) {
        echo "🔍 Magic __get() called for property '$propertyName'\n";
        
        // Проверяем, существует ли свойство в нашем массиве
        if (array_key_exists($propertyName, $this->data)) {
            echo "✅ Found property '$propertyName'\n";
            return $this->data[$propertyName];
        }
        
        // Если свойство не найдено
        echo "❌ Property '$propertyName' does not exist\n";
        return null;
    }
    
    // Магический метод __isset() для функции isset()
    public function __isset($propertyName) {
        echo "❓ Checking if property '$propertyName' exists...\n";
        return isset($this->data[$propertyName]);
    }
    
    // Магический метод __unset() для функции unset()
    public function __unset($propertyName) {
        echo "🗑️ Deleting property '$propertyName'...\n";
        unset($this->data[$propertyName]);
    }
    
    // Обычный публичный метод для демонстрации
    public function showAllData() {
        echo "\n=== ALL OBJECT DATA ===\n";
        print_r($this->data);
        echo "==========================\n\n";
    }
}

// Создаем объект и экспериментируем
$object = new SmartObject();

echo "=== TESTING __set() ===\n";
$object->name = "Anna";        // Вызовет __set()
$object->age = 25;             // Вызовет __set()
$object->city = "Moscow";      // Вызовет __set()

// Попытка установить некорректные значения
try {
    // $object->age = -5;      // Вызовет исключение!
} catch (Exception $e) {
    echo "ERROR: " . $e->getMessage() . "\n";
}

echo "\n=== TESTING __get() ===\n";
echo "Name: " . $object->name . "\n";       // Вызовет __get()
echo "Age: " . $object->age . "\n";         // Вызовет __get()
echo "Non-existent: " . $object->salary . "\n"; // Вызовет __get()

echo "\n=== TESTING __isset() and __unset() ===\n";
var_dump(isset($object->name));     // Вызовет __isset()
var_dump(isset($object->salary));   // Вызовет __isset()

unset($object->city);               // Вызовет __unset()
var_dump(isset($object->city));     // Проверяем удаление

$object->showAllData();

?>
```

### __call и __callStatic - перехват вызовов методов

Эти методы - как "универсальные пульты дистанционного управления" для ваших объектов.

```php
<?php

class UniversalRemote {
    private $devices = [
        'tv' => 'off',
        'light' => 'off', 
        'ac' => 'off'
    ];
    
    // Магический метод __call() перехватывает вызовы НЕСУЩЕСТВУЮЩИХ методов
    public function __call($methodName, $arguments) {
        echo "🎮 __call() intercepted method call: '$methodName'\n";
        echo "📦 Arguments: " . implode(', ', $arguments) . "\n";
        
        // Анализируем имя метода
        if (strpos($methodName, 'turnOn') === 0) {
            $device = substr($methodName, 6); // Убираем "turnOn"
            $device = strtolower($device);
            return $this->turnOnDevice($device, $arguments);
        }
        
        if (strpos($methodName, 'turnOff') === 0) {
            $device = substr($methodName, 7); // Убираем "turnOff"
            $device = strtolower($device);
            return $this->turnOffDevice($device, $arguments);
        }
        
        return "❌ Unknown command: $methodName";
    }
    
    // Магический метод __callStatic() перехватывает вызовы НЕСУЩЕСТВУЮЩИХ статических методов
    public static function __callStatic($methodName, $arguments) {
        echo "⚡ __callStatic() intercepted static call: '$methodName'\n";
        echo "📦 Arguments: " . implode(', ', $arguments) . "\n";
        
        return "Static magic! ✨";
    }
    
    // Вспомогательные методы
    private function turnOnDevice($device, $arguments) {
        if (array_key_exists($device, $this->devices)) {
            $this->devices[$device] = 'on';
            $additional = !empty($arguments) ? " (" . implode(', ', $arguments) . ")" : "";
            return "✅ Device '$device' turned on$additional";
        }
        return "❌ Device '$device' not found";
    }
    
    private function turnOffDevice($device, $arguments) {
        if (array_key_exists($device, $this->devices)) {
            $this->devices[$device] = 'off';
            return "✅ Device '$device' turned off";
        }
        return "❌ Device '$device' not found";
    }
    
    public function showStatus() {
        echo "\n=== DEVICES STATUS ===\n";
        foreach ($this->devices as $device => $status) {
            echo "$device: $status\n";
        }
        echo "=======================\n";
    }
}

// Тестируем магию __call()
$remote = new UniversalRemote();

echo "=== TESTING DYNAMIC METHODS ===\n";
echo $remote->turnOnTv("channel 5") . "\n";
echo $remote->turnOnLight("brightness 80%") . "\n";
echo $remote->turnOffAc() . "\n";
echo $remote->turnOnNonExistent() . "\n"; // Неизвестное устройство

$remote->showStatus();

echo "\n=== TESTING STATIC METHODS ===\n";
// Вызываем несуществующие статические методы
echo UniversalRemote::magicMethod("arg1", "arg2") . "\n";
echo UniversalRemote::anotherMagic(123, 456) . "\n";

?>
```

### __toString и __invoke - объекты как строки и функции

Эти методы превращают ваши объекты в "хамелеонов" - они могут вести себя как строки или как функции!

```php
<?php

class SmartProduct {
    public $name;
    public $price;
    public $discount = 0;
    
    public function __construct($name, $price) {
        $this->name = $name;
        $this->price = $price;
        echo "Created product: $name for $price rub.\n";
    }
    
    // Магический метод __toString() вызывается при попытке 
    // преобразовать объект в строку (например, при echo)
    public function __toString() {
        echo "🔤 Magic __toString() called!\n";
        $priceWithDiscount = $this->price * (1 - $this->discount / 100);
        
        $info = "=== PRODUCT INFORMATION ===\n";
        $info .= "Name: {$this->name}\n";
        $info .= "Price: {$this->price} rub.\n";
        $info .= "Discount: {$this->discount}%\n";
        $info .= "Final price: {$priceWithDiscount} rub.\n";
        $info .= "============================\n";
        
        return $info;
    }
    
    // Магический метод __invoke() позволяет вызывать объект как функцию
    public function __invoke($action, $value = null) {
        echo "⚡ Magic __invoke() called with action: '$action'\n";
        
        switch ($action) {
            case 'setDiscount':
                if ($value >= 0 && $value <= 100) {
                    $this->discount = $value;
                    return "✅ Discount set: $value%";
                } else {
                    return "❌ Invalid discount value: $value%";
                }
                
            case 'getPrice':
                $finalPrice = $this->price * (1 - $this->discount / 100);
                return "💰 Final price: $finalPrice rub.";
                
            case 'updatePrice':
                if ($value > 0) {
                    $this->price = $value;
                    return "✅ Price updated: $value rub.";
                }
                return "❌ Invalid price: $value rub.";
                
            default:
                return "❌ Unknown action: $action";
        }
    }
    
    // Обычный метод для сравнения
    public function regularMethod() {
        return "This is a regular object method";
    }
}

// Создаем продукт и тестируем магию
$phone = new SmartProduct("iPhone 15", 100000);

echo "\n=== TESTING __toString() ===\n";
// Просто используем объект в echo - автоматически вызовется __toString()
echo $phone;

echo "\n=== TESTING __invoke() ===\n";
// Вызываем объект как функцию - вызывается __invoke()
echo $phone('setDiscount', 15) . "\n";
echo $phone('getPrice') . "\n";
echo $phone('updatePrice', 90000) . "\n";
echo $phone('unknownAction') . "\n";

echo "\n=== CHECKING RESULT ===\n";
echo $phone; // Снова выводим информацию

echo "\n=== COMPARISON WITH REGULAR METHOD ===\n";
echo $phone->regularMethod() . "\n";

// Дополнительный пример с использованием в массиве
echo "\n=== USING IN ARRAY ===\n";
$products = [
    'phone' => $phone,
    'text' => 'regular string'
];

// При преобразовании в строку в массиве тоже сработает __toString()
echo $products['phone'];

?>
```

>>Теперь ваши объекты стали настоящими волшебниками! Они умеют прятать данные, перехватывать вызовы и даже превращаться в строки и функции. Осторожно - с большой силой приходит большая ответственность! 😄

# Часть IV: Практическое применение ООП

## Глава 12: Практический пример - система блога

### Проектирование архитектуры

Тут мы будем создавать систему блога. Это как построить дом для твоих мыслей, только вместо кирпичей - код, а вместо крыши - база данных.

**Архитектура нашего блога:**
- Модели (сущности): Пост, Комментарий, Пользователь
- Репозитории (хранилища): Для работы с базой данных
- Сервисы (бизнес-логика): Вся магия происходит здесь
- Контроллеры (обработчики запросов): Принимают HTTP-запросы и выдают ответы

```php
<?php
// Это как план этажа нашего блога
class BlogArchitecture {
    // Модели - описывают данные (как чертежи мебели)
    // Репозитории - работают с базой данных (как склад)
    // Сервисы - бизнес-логика (как прораб на стройке)
    // Контроллеры - обрабатывают запросы (как reception в отеле)
}
?>
```

### Реализация классов

#### Модель Поста

```php
<?php
/**
 * Класс Post - это как дневниковая запись, только в коде
 * Представляет собой статью в блоге
 */
class Post {
    // Свойства - то, что характеризует наш пост
    private ?int $id;           // ID - как паспорт поста
    private string $title;      // Заголовок - чтобы привлекать внимание
    private string $content;    // Содержание - самое вкусное
    private string $author;     // Автор - кто написал этот шедевр
    private DateTime $createdAt; // Дата создания - чтобы знать, когда хвастаться
    
    /**
     * Конструктор - как рождение нового поста
     */
    public function __construct(?int $id, string $title, string $content, string $author) {
        $this->id = $id;
        $this->title = $title;
        $this->content = $content;
        $this->author = $author;
        $this->createdAt = new DateTime(); // Пост рождается прямо сейчас!
    }
    
    // Геттеры - как оконца, через которые можно посмотреть на свойства
    public function getId(): ?int {
        return $this->id;
    }
    
    public function getTitle(): string {
        return $this->title;
    }
    
    // Сеттеры - как дверцы, через которые можно изменить свойства
    public function setTitle(string $title): void {
        // Проверяем, что заголовок не пустой (а то стыдно будет)
        if (empty(trim($title))) {
            throw new InvalidArgumentException("Заголовок не может быть пустым!");
        }
        $this->title = $title;
    }
    
    /**
     * Метод для представления поста в виде массива
     * Это как упаковать пост в коробку для пересылки
     */
    public function toArray(): array {
        return [
            'id' => $this->id,
            'title' => $this->title,
            'content' => $this->content,
            'author' => $this->author,
            'createdAt' => $this->createdAt->format('Y-m-d H:i:s')
        ];
    }
    
    /**
     * Проверяем, является ли пост новым (еще не сохранен в БД)
     * Если ID нет - значит пост только что родился
     */
    public function isNew(): bool {
        return $this->id === null;
    }
}
?>
```

#### Репозиторий для работы с постами

```php
<?php
/**
 * PostRepository - складской работник для постов
 * Знает все о хранении и поиске постов в базе данных
 */
class PostRepository {
    private PDO $db; // Объект для работы с базой данных
    
    /**
     * Конструктор принимает PDO - наш пропуск в базу данных
     */
    public function __construct(PDO $db) {
        $this->db = $db;
    }
    
    /**
     * Сохраняем пост в базе данных
     * Если пост новый - создаем запись, если старый - обновляем
     */
    public function save(Post $post): Post {
        // Если пост новый (без ID) - вставляем новую запись
        if ($post->isNew()) {
            return $this->insert($post);
        } 
        // Если пост уже существует - обновляем
        else {
            return $this->update($post);
        }
    }
    
    /**
     * Вставляем новый пост в базу данных
     * Это как записать новую песню на диск
     */
    private function insert(Post $post): Post {
        $sql = "INSERT INTO posts (title, content, author, created_at) 
                VALUES (:title, :content, :author, :created_at)";
        
        $stmt = $this->db->prepare($sql);
        
        // Привязываем значения к параметрам (чтобы SQL-инъекции не пролезли)
        $stmt->bindValue(':title', $post->getTitle());
        $stmt->bindValue(':content', $post->getContent());
        $stmt->bindValue(':author', $post->getAuthor());
        $stmt->bindValue(':created_at', $post->getCreatedAt()->format('Y-m-d H:i:s'));
        
        $stmt->execute();
        
        // Получаем ID нового поста (как номерок в гардеробе)
        $postId = (int)$this->db->lastInsertId();
        
        // Создаем новый объект с ID (теперь пост официально существует!)
        return new Post($postId, $post->getTitle(), $post->getContent(), $post->getAuthor());
    }
    
    /**
     * Находим пост по ID
     * Это как найти книгу в библиотеке по номеру
     */
    public function findById(int $id): ?Post {
        $sql = "SELECT * FROM posts WHERE id = :id";
        $stmt = $this->db->prepare($sql);
        $stmt->bindValue(':id', $id, PDO::PARAM_INT);
        $stmt->execute();
        
        $data = $stmt->fetch(PDO::FETCH_ASSOC);
        
        // Если пост не найден - возвращаем null (ничего не нашли)
        if (!$data) {
            return null;
        }
        
        // Создаем объект Post из данных базы
        return $this->hydrate($data);
    }
    
    /**
     * Превращаем массив данных из базы в объект Post
     * Это как собрать мебель из IKEA по инструкции
     */
    private function hydrate(array $data): Post {
        $post = new Post(
            (int)$data['id'],
            $data['title'],
            $data['content'],
            $data['author']
        );
        
        // Устанавливаем дату создания (она приходит из базы как строка)
        $createdAt = DateTime::createFromFormat('Y-m-d H:i:s', $data['created_at']);
        if ($createdAt) {
            // Здесь был бы сеттер для createdAt, но мы его не сделали для простоты
        }
        
        return $post;
    }
    
    /**
     * Получаем все посты (для главной страницы блога)
     */
    public function findAll(): array {
        $sql = "SELECT * FROM posts ORDER BY created_at DESC"; // Сначала новые
        $stmt = $this->db->query($sql);
        
        $posts = [];
        while ($data = $stmt->fetch(PDO::FETCH_ASSOC)) {
            $posts[] = $this->hydrate($data);
        }
        
        return $posts;
    }
}
?>
```

#### Сервис для работы с блогом

```php
<?php
/**
 * BlogService - мозг нашего блога
 * Здесь содержится вся бизнес-логика
 */
class BlogService {
    private PostRepository $postRepository;
    
    public function __construct(PostRepository $postRepository) {
        $this->postRepository = $postRepository;
    }
    
    /**
     * Создаем новый пост
     * Проверяем данные и сохраняем через репозиторий
     */
    public function createPost(string $title, string $content, string $author): Post {
        // Проверяем, что заголовок не слишком длинный (а то в базе не поместится)
        if (strlen($title) > 255) {
            throw new InvalidArgumentException("Заголовок слишком длинный! Максимум 255 символов.");
        }
        
        // Проверяем, что контент не пустой (а то зачем такой пост?)
        if (empty(trim($content))) {
            throw new InvalidArgumentException("Содержание поста не может быть пустым!");
        }
        
        // Создаем новый пост (пока еще без ID)
        $post = new Post(null, $title, $content, $author);
        
        // Сохраняем в базе данных (теперь у него появится ID)
        return $this->postRepository->save($post);
    }
    
    /**
     * Получаем пост по ID с проверкой существования
     */
    public function getPost(int $id): Post {
        $post = $this->postRepository->findById($id);
        
        if (!$post) {
            throw new Exception("Пост с ID $id не найден! Может, его хакеры украли?");
        }
        
        return $post;
    }
    
    /**
     * Получаем все посты для главной страницы
     */
    public function getAllPosts(): array {
        return $this->postRepository->findAll();
    }
}
?>
```

### Тестирование системы

Тестирование - это как проверка торта перед подачей на стол. Убеждаемся, что все работает!

```php
<?php
/**
 * Класс для тестирования нашей системы блога
 * Проверяем, что все работает как задумано
 */
class BlogSystemTest {
    private PDO $db;
    private PostRepository $postRepository;
    private BlogService $blogService;
    
    public function __construct() {
        // Создаем тестовую базу данных в памяти (чтобы не засорять настоящую)
        $this->db = new PDO('sqlite::memory:');
        $this->setupTestDatabase();
        
        $this->postRepository = new PostRepository($this->db);
        $this->blogService = new BlogService($this->postRepository);
    }
    
    /**
     * Создаем тестовую таблицу постов
     */
    private function setupTestDatabase(): void {
        $sql = "
        CREATE TABLE posts (
            id INTEGER PRIMARY KEY AUTOINCREMENT,
            title VARCHAR(255) NOT NULL,
            content TEXT NOT NULL,
            author VARCHAR(100) NOT NULL,
            created_at DATETIME DEFAULT CURRENT_TIMESTAMP
        )";
        
        $this->db->exec($sql);
        echo "✅ Тестовая база данных создана!\n";
    }
    
    /**
     * Тестируем создание поста
     */
    public function testCreatePost(): void {
        echo "\n🧪 Тестируем создание поста...\n";
        
        $post = $this->blogService->createPost(
            "Мой первый пост", 
            "Это содержание моего первого поста! Ура!", 
            "Вася Пупкин"
        );
        
        // Проверяем, что пост создался с правильными данными
        assert($post->getTitle() === "Мой первый пост");
        assert($post->getAuthor() === "Вася Пупкин");
        assert($post->getId() !== null); // Должен быть присвоен ID
        
        echo "✅ Создание поста работает отлично!\n";
        echo "📝 Создан пост: '{$post->getTitle()}' от {$post->getAuthor()}\n";
    }
    
    /**
     * Тестируем получение поста
     */
    public function testGetPost(): void {
        echo "\n🧪 Тестируем получение поста...\n";
        
        // Сначала создаем пост
        $post = $this->blogService->createPost(
            "Тестовый пост", 
            "Содержание тестового поста", 
            "Тестер"
        );
        
        $postId = $post->getId();
        
        // Пытаемся получить пост по ID
        $foundPost = $this->blogService->getPost($postId);
        
        // Проверяем, что получили тот же пост
        assert($foundPost->getId() === $postId);
        assert($foundPost->getTitle() === "Тестовый пост");
        
        echo "✅ Получение поста работает отлично!\n";
    }
    
    /**
     * Тестируем получение всех постов
     */
    public function testGetAllPosts(): void {
        echo "\n🧪 Тестируем получение всех постов...\n";
        
        // Очищаем таблицу перед тестом
        $this->db->exec("DELETE FROM posts");
        
        // Создаем несколько постов
        $this->blogService->createPost("Пост 1", "Содержание 1", "Автор 1");
        $this->blogService->createPost("Пост 2", "Содержание 2", "Автор 2");
        
        $posts = $this->blogService->getAllPosts();
        
        // Проверяем, что получили 2 поста
        assert(count($posts) === 2);
        assert($posts[0]->getTitle() === "Пост 2"); // Должен быть первым, т.к. сортируем по дате
        
        echo "✅ Получение всех постов работает отлично!\n";
        echo "📚 Найдено постов: " . count($posts) . "\n";
    }
    
    /**
     * Запускаем все тесты
     */
    public function runAllTests(): void {
        echo "🚀 Запускаем тесты системы блога!\n";
        echo "================================\n";
        
        $this->testCreatePost();
        $this->testGetPost();
        $this->testGetAllPosts();
        
        echo "\n🎉 Все тесты пройдены успешно! Система блога работает как часы!\n";
    }
}

// Запускаем тесты
$test = new BlogSystemTest();
$test->runAllTests();
?>
```

## Глава 13: Паттерны проектирования 

Паттерны проектирования - это как кулинарные рецепты для программистов. Зачем изобретать велосипед, если можно воспользоваться готовым решением?

### Фабрика (Factory)

Фабрика - это как конвейер на заводе. Ты говоришь "хочу автомобиль", а фабрика тебе его производит.

```php
<?php
/**
 * Паттерн Фабрика - создает объекты без указания точного класса
 * Это как заказ пиццы: ты говоришь "пепперони", а кухня сама знает как ее готовить
 */

// Базовый класс для всех постов (как тесто для пиццы)
abstract class AbstractPost {
    protected string $title;
    protected string $content;
    
    public function __construct(string $title, string $content) {
        $this->title = $title;
        $this->content = $content;
    }
    
    abstract public function display(): string;
}

// Конкретные типы постов (разные виды пиццы)
class NewsPost extends AbstractPost {
    private string $source;
    
    public function __construct(string $title, string $content, string $source) {
        parent::__construct($title, $content);
        $this->source = $source;
    }
    
    public function display(): string {
        return "[НОВОСТЬ] {$this->title}\nИсточник: {$this->source}\n{$this->content}";
    }
}

class TutorialPost extends AbstractPost {
    private string $technology;
    
    public function __construct(string $title, string $content, string $technology) {
        parent::__construct($title, $content);
        $this->technology = $technology;
    }
    
    public function display(): string {
        return "[УРОК] {$this->title}\nТехнология: {$this->technology}\n{$this->content}";
    }
}

/**
 * Фабрика постов - наш главный повар на кухне
 */
class PostFactory {
    const TYPE_NEWS = 'news';
    const TYPE_TUTORIAL = 'tutorial';
    
    /**
     * Создаем пост в зависимости от типа
     * Это как сказать повару: "сделай пиццу" и указать какую
     */
    public static function createPost(string $type, string $title, string $content, array $params = []): AbstractPost {
        return match($type) {
            self::TYPE_NEWS => new NewsPost($title, $content, $params['source'] ?? 'Неизвестный источник'),
            self::TYPE_TUTORIAL => new TutorialPost($title, $content, $params['technology'] ?? 'PHP'),
            default => throw new InvalidArgumentException("Неизвестный тип поста: $type")
        };
    }
}

// Используем нашу фабрику
echo "🍕 Демонстрация паттерна Фабрика:\n";

// Создаем новостной пост (как заказываем пепперони)
$newsPost = PostFactory::createPost(
    PostFactory::TYPE_NEWS,
    "Новая версия PHP вышла!",
    "Сегодня вышла новая версия PHP с кучей крутых фич...",
    ['source' => 'Официальный сайт PHP']
);

// Создаем обучающий пост (как заказываем маргариту)
$tutorialPost = PostFactory::createPost(
    PostFactory::TYPE_TUTORIAL,
    "Учим паттерны проектирования",
    "Паттерны проектирования - это круто...",
    ['technology' => 'Паттерны проектирования']
);

echo $newsPost->display() . "\n\n";
echo $tutorialPost->display() . "\n";

echo "✅ Фабрика работает! Мы создали посты разных типов без лишних сложностей!\n";
?>
```

### Стратегия (Strategy)

Стратегия - это как выбор маршрута в навигаторе. Ты можешь выбрать "быстрый", "короткий" или "экономный" маршрут.

```php
<?php
/**
 * Паттерн Стратегия - позволяет менять алгоритмы на лету
 * Это как выбрать способ доставки пиццы: курьер, самовывоз, или дрон
 */

// Интерфейс стратегии - контракт для всех алгоритмов сортировки
interface SortStrategy {
    public function sort(array $posts): array;
}

// Конкретные стратегии (разные алгоритмы сортировки)
class DateSortStrategy implements SortStrategy {
    public function sort(array $posts): array {
        echo "🔢 Сортируем по дате (новые сначала)...\n";
        // Здесь была бы реальная сортировка по дате
        return $posts;
    }
}

class TitleSortStrategy implements SortStrategy {
    public function sort(array $posts): array {
        echo "🔤 Сортируем по заголовку (А-Я)...\n";
        // Сортировка по алфавиту
        usort($posts, function($a, $b) {
            return strcmp($a->getTitle(), $b->getTitle());
        });
        return $posts;
    }
}

class PopularitySortStrategy implements SortStrategy {
    public function sort(array $posts): array {
        echo "🔥 Сортируем по популярности...\n";
        // Сортировка по количеству просмотров (если бы они были)
        return $posts;
    }
}

/**
 * Контекст - класс, который использует стратегии
 * Это как навигатор, который может использовать разные алгоритмы поиска пути
 */
class PostManager {
    private SortStrategy $sortStrategy;
    private array $posts = [];
    
    public function __construct(SortStrategy $strategy) {
        $this->sortStrategy = $strategy;
    }
    
    /**
     * Меняем стратегию сортировки на лету
     * Это как переключиться с "быстрого" маршрута на "экономный"
     */
    public function setSortStrategy(SortStrategy $strategy): void {
        $this->sortStrategy = $strategy;
        echo "🔄 Стратегия сортировки изменена!\n";
    }
    
    public function addPost(Post $post): void {
        $this->posts[] = $post;
    }
    
    /**
     * Сортируем посты используя текущую стратегию
     */
    public function getSortedPosts(): array {
        return $this->sortStrategy->sort($this->posts);
    }
}

// Демонстрация работы стратегий
echo "\n🗺️ Демонстрация паттерна Стратегия:\n";

// Создаем менеджер постов с сортировкой по дате
$postManager = new PostManager(new DateSortStrategy());

// Добавляем тестовые посты
$postManager->addPost(new Post(1, "Яблоки", "Содержание о яблоках", "Автор 1"));
$postManager->addPost(new Post(2, "Бананы", "Содержание о бананах", "Автор 2"));
$postManager->addPost(new Post(3, "Апельсины", "Содержание об апельсинах", "Автор 3"));

// Сортируем по дате (текущая стратегия)
$posts = $postManager->getSortedPosts();

// Меняем стратегию на сортировку по заголовку
$postManager->setSortStrategy(new TitleSortStrategy());
$posts = $postManager->getSortedPosts();

// Меняем стратегию на сортировку по популярности
$postManager->setSortStrategy(new PopularitySortStrategy());
$posts = $postManager->getSortedPosts();

echo "✅ Стратегия работает! Мы можем менять алгоритмы сортировки как перчатки!\n";
?>
```

### Наблюдатель (Observer)

Наблюдатель - это как подписка на рассылку. Ты подписываешься на канал, и когда выходит новое видео - тебе приходит уведомление.

```php
<?php
/**
 * Паттерн Наблюдатель - уведомляет подписчиков о событиях
 * Это как YouTube: подписываешься на канал и получаешь уведомления о новых видео
 */

// Интерфейс наблюдателя - контракт для всех подписчиков
interface PostObserver {
    public function onPostPublished(Post $post): void;
}

// Конкретные наблюдатели (разные подписчики)
class EmailNotifier implements PostObserver {
    public function onPostPublished(Post $post): void {
        echo "📧 Отправляем email: 'Новый пост: {$post->getTitle()}'\n";
        // Здесь была бы реальная отправка email
    }
}

class SMSNotifier implements PostObserver {
    public function onPostPublished(Post $post): void {
        echo "📱 Отправляем SMS: 'Новый пост: {$post->getTitle()}'\n";
        // Здесь была бы реальная отправка SMS
    }
}

class SocialMediaPublisher implements PostObserver {
    public function onPostPublished(Post $post): void {
        echo "📢 Публикуем в соцсетях: 'Прочитайте новый пост: {$post->getTitle()}'\n";
        // Здесь была бы реальная публикация в соцсетях
    }
}

/**
 * Субъект (издатель) - тот, за кем наблюдают
 * Это как YouTube-канал, который публикует видео
 */
class PostPublisher {
    private array $observers = [];
    
    /**
     * Подписываем наблюдателя на уведомления
     */
    public function subscribe(PostObserver $observer): void {
        $this->observers[] = $observer;
        echo "✅ Новый подписчик добавлен!\n";
    }
    
    /**
     * Отписываем наблюдателя
     */
    public function unsubscribe(PostObserver $observer): void {
        $key = array_search($observer, $this->observers, true);
        if ($key !== false) {
            unset($this->observers[$key]);
            echo "❌ Подписчик удален!\n";
        }
    }
    
    /**
     * Публикуем новый пост и уведомляем всех подписчиков
     * Это как выпустить новое видео на YouTube-канале
     */
    public function publishPost(Post $post): void {
        echo "🎉 Публикуем новый пост: '{$post->getTitle()}'\n";
        
        // Уведомляем всех подписчиков
        $this->notifyObservers($post);
    }
    
    /**
     * Рассылаем уведомления всем подписчикам
     */
    private function notifyObservers(Post $post): void {
        foreach ($this->observers as $observer) {
            $observer->onPostPublished($post);
        }
    }
}

// Демонстрация работы наблюдателя
echo "\n👀 Демонстрация паттерна Наблюдатель:\n";

// Создаем издателя (наш блог)
$publisher = new PostPublisher();

// Создаем наблюдателей (разные способы уведомления)
$emailNotifier = new EmailNotifier();
$smsNotifier = new SMSNotifier();
$socialMedia = new SocialMediaPublisher();

// Подписываем наблюдателей
$publisher->subscribe($emailNotifier);
$publisher->subscribe($smsNotifier);
$publisher->subscribe($socialMedia);

// Создаем тестовый пост
$post = new Post(1, "Мой первый пост с паттернами", "Содержание...", "Автор");

// Публикуем пост (все подписчики получат уведомления)
$publisher->publishPost($post);

echo "\n🔥 Отписываем SMS-уведомления и публикуем еще один пост:\n";

// Отписываем SMS-уведомления
$publisher->unsubscribe($smsNotifier);

// Публикуем еще один пост (SMS уже не придет)
$post2 = new Post(2, "Второй пост", "Еще содержание...", "Автор");
$publisher->publishPost($post2);

echo "✅ Наблюдатель работает! Подписчики получают уведомления автоматически!\n";
?>

```

>>Помни: паттерны - это не священное писание, а инструменты. Используй их там, где они действительно нужны!


## Глава 14: Принципы SOLID

<img src="https://cs8.pikabu.ru/post_img/2017/11/30/8/1512049877163235168.png">

Тут мы изучим принципы SOLID - это как 10 заповедей для программистов, только их всего 5 и они про код. 

SOLID - это аббревиатура, придуманная дядей Бобом (Робертом Мартином), чтобы мы писали код, который не стыдно показать маме.

### Single Responsibility Principle (Принцип единственной ответственности)

Один класс - одна обязанность. Это как на кухне: повар готовит, посудомойка моет, а официант подает. Не стоит заставлять повара мыть посуду!

```php
<?php
/**
 * НЕПРАВИЛЬНО: Класс делает слишком много всего!
 * Это как швейцарский нож, который пытается быть также молотком и отверткой
 */
class GodObject {
    public function createPost($title, $content) {
        // Создает пост
    }
    
    public function sendEmail($to, $subject, $body) {
        // Отправляет email
    }
    
    public function generatePDF($content) {
        // Генерирует PDF
    }
    
    public function calculateStatistics() {
        // Считает статистику
    }
}

/**
 * ПРАВИЛЬНО: Разделяем ответственность по разным классам
 * Каждый класс делает только то, для чего он предназначен
 */

// Класс только для работы с постами
class PostManager {
    public function createPost(string $title, string $content): Post {
        // Только создание поста
        return new Post($title, $content);
    }
    
    public function updatePost(Post $post, string $title, string $content): void {
        // Только обновление поста
        $post->setTitle($title);
        $post->setContent($content);
    }
}

// Класс только для отправки email
class EmailService {
    public function sendNotification(string $to, string $subject, string $body): bool {
        // Только отправка email
        echo "📧 Отправляем email на $to: $subject\n";
        return true;
    }
}

// Класс только для генерации PDF
class PDFGenerator {
    public function generateFromPost(Post $post): string {
        // Только генерация PDF
        echo "📄 Генерируем PDF для поста '{$post->getTitle()}'\n";
        return "pdf_content_{$post->getId()}";
    }
}

// Класс только для статистики
class StatisticsCalculator {
    public function calculatePostStats(array $posts): array {
        // Только расчет статистики
        return [
            'total_posts' => count($posts),
            'average_title_length' => array_sum(array_map('strlen', 
                array_map(fn($p) => $p->getTitle(), $posts))) / count($posts)
        ];
    }
}

// Демонстрация принципа
echo "🎯 Демонстрация Single Responsibility Principle:\n";

$postManager = new PostManager();
$emailService = new EmailService();
$pdfGenerator = new PDFGenerator();
$statsCalculator = new StatisticsCalculator();

// Каждый класс делает свою работу
$post = $postManager->createPost("Принципы SOLID", "Изучаем SOLID...");
$emailService->sendNotification("user@example.com", "Новый пост", "Посмотрите новый пост!");
$pdf = $pdfGenerator->generateFromPost($post);
$stats = $statsCalculator->calculatePostStats([$post]);

echo "✅ Каждый класс имеет только одну ответственность!\n";
echo "📊 Статистика: " . json_encode($stats) . "\n";

/**
 * Реальный пример из нашей системы блога
 */

// ПЛОХО: Класс делает все
class BadBlogManager {
    public function createPost($title, $content) {
        // Создаем пост
        $post = new Post(null, $title, $content, "Автор");
        
        // Сохраняем в базу
        $this->saveToDatabase($post);
        
        // Отправляем email
        $this->sendEmailToSubscribers($post);
        
        // Обновляем статистику
        $this->updateStatistics($post);
        
        // Логируем действие
        $this->logAction("post_created", $post);
        
        return $post;
    }
    
    private function saveToDatabase($post) { /* ... */ }
    private function sendEmailToSubscribers($post) { /* ... */ }
    private function updateStatistics($post) { /* ... */ }
    private function logAction($action, $post) { /* ... */ }
}

// ХОРОШО: Разделяем ответственность
class GoodPostService {
    private PostRepository $postRepository;
    private EmailService $emailService;
    private StatisticsService $statsService;
    private Logger $logger;
    
    public function __construct(
        PostRepository $postRepository,
        EmailService $emailService,
        StatisticsService $statsService,
        Logger $logger
    ) {
        $this->postRepository = $postRepository;
        $this->emailService = $emailService;
        $this->statsService = $statsService;
        $this->logger = $logger;
    }
    
    public function createPost(string $title, string $content, string $author): Post {
        $post = new Post(null, $title, $content, $author);
        
        // Каждая зависимость делает свою работу
        $this->postRepository->save($post);
        $this->emailService->notifyAboutNewPost($post);
        $this->statsService->recordPostCreation($post);
        $this->logger->info("Post created: " . $post->getTitle());
        
        return $post;
    }
}

echo "\n🎉 Single Responsibility Principle освоен! Запомни: один класс - одна работа!\n";
?>
```

### Open/Closed Principle (Принцип открытости/закрытости)

Классы должны быть открыты для расширения, но закрыты для изменения. Это как LEGO: ты не меняешь сами детали LEGO, но можешь собирать из них новые конструкции.

```php
<?php
/**
 * НЕПРАВИЛЬНО: При добавлении нового типа поста нужно изменять существующий код
 */
class BadPostExporter {
    public function export(Post $post, string $format): string {
        if ($format === 'json') {
            return json_encode($post->toArray());
        } elseif ($format === 'xml') {
            return $this->convertToXml($post);
        } elseif ($format === 'csv') {
            return $this->convertToCsv($post);
        }
        // Добавление нового формата требует изменения этого метода!
        throw new Exception("Unsupported format: $format");
    }
    
    private function convertToXml(Post $post): string {
        return "<post><title>{$post->getTitle()}</title></post>";
    }
    
    private function convertToCsv(Post $post): string {
        return "{$post->getTitle()},{$post->getAuthor()}";
    }
}

/**
 * ПРАВИЛЬНО: Используем интерфейсы для поддержки новых форматов без изменения существующего кода
 */

// Интерфейс для всех экспортеров
interface PostExporterInterface {
    public function export(Post $post): string;
    public function supports(string $format): bool;
}

// Конкретные реализации для каждого формата
class JsonPostExporter implements PostExporterInterface {
    public function export(Post $post): string {
        return json_encode($post->toArray(), JSON_PRETTY_PRINT);
    }
    
    public function supports(string $format): bool {
        return $format === 'json';
    }
}

class XmlPostExporter implements PostExporterInterface {
    public function export(Post $post): string {
        $title = htmlspecialchars($post->getTitle());
        $author = htmlspecialchars($post->getAuthor());
        return "<?xml version=\"1.0\"?>\n<post>\n    <title>$title</title>\n    <author>$author</author>\n</post>";
    }
    
    public function supports(string $format): bool {
        return $format === 'xml';
    }
}

class CsvPostExporter implements PostExporterInterface {
    public function export(Post $post): string {
        return "{$post->getTitle()},{$post->getAuthor()},{$post->getCreatedAt()->format('Y-m-d')}";
    }
    
    public function supports(string $format): bool {
        return $format === 'csv';
    }
}

/**
 * Главный класс, который не нужно изменять при добавлении новых форматов
 */
class GoodPostExporter {
    /** @var PostExporterInterface[] */
    private array $exporters = [];
    
    // Добавляем экспортеры через конструктор (Dependency Injection)
    public function __construct(PostExporterInterface ...$exporters) {
        $this->exporters = $exporters;
    }
    
    // Добавляем возможность регистрации новых экспортеров
    public function addExporter(PostExporterInterface $exporter): void {
        $this->exporters[] = $exporter;
    }
    
    public function export(Post $post, string $format): string {
        foreach ($this->exporters as $exporter) {
            if ($exporter->supports($format)) {
                return $exporter->export($post);
            }
        }
        
        throw new Exception("Unsupported format: $format");
    }
}

// Демонстрация принципа
echo "\n🎯 Демонстрация Open/Closed Principle:\n";

$post = new Post(1, "Принцип Open/Closed", "Классы открыты для расширения...", "Автор");

// Создаем экспортер с поддержкой форматов
$exporter = new GoodPostExporter(
    new JsonPostExporter(),
    new XmlPostExporter(),
    new CsvPostExporter()
);

// Экспортируем в разные форматы
echo "JSON:\n" . $exporter->export($post, 'json') . "\n\n";
echo "XML:\n" . $exporter->export($post, 'xml') . "\n\n";
echo "CSV:\n" . $exporter->export($post, 'csv') . "\n";

// Теперь добавляем поддержку нового формата БЕЗ изменения существующего кода!
class HtmlPostExporter implements PostExporterInterface {
    public function export(Post $post): string {
        return "<div class='post'><h1>{$post->getTitle()}</h1><p>Автор: {$post->getAuthor()}</p></div>";
    }
    
    public function supports(string $format): bool {
        return $format === 'html';
    }
}

// Просто добавляем новый экспортер
$exporter->addExporter(new HtmlPostExporter());
echo "HTML:\n" . $exporter->export($post, 'html') . "\n";

echo "✅ Open/Closed Principle работает! Мы добавили новый формат без изменения существующего кода!\n";

/**
 * Еще один пример с системой уведомлений
 */

interface NotificationInterface {
    public function send(string $message): bool;
    public function canSend(): bool;
}

class EmailNotification implements NotificationInterface {
    public function send(string $message): bool {
        echo "📧 Отправляем email: $message\n";
        return true;
    }
    
    public function canSend(): bool {
        return true; // Проверяем доступность email сервиса
    }
}

class SmsNotification implements NotificationInterface {
    public function send(string $message): bool {
        echo "📱 Отправляем SMS: $message\n";
        return true;
    }
    
    public function canSend(): bool {
        return true; // Проверяем доступность SMS шлюза
    }
}

class PushNotification implements NotificationInterface {
    public function send(string $message): bool {
        echo "📱 Отправляем push: $message\n";
        return true;
    }
    
    public function canSend(): bool {
        return true;
    }
}

class NotificationManager {
    /** @var NotificationInterface[] */
    private array $notifications;
    
    public function __construct(NotificationInterface ...$notifications) {
        $this->notifications = $notifications;
    }
    
    public function addNotification(NotificationInterface $notification): void {
        $this->notifications[] = $notification;
    }
    
    public function notify(string $message): void {
        foreach ($this->notifications as $notification) {
            if ($notification->canSend()) {
                $notification->send($message);
            }
        }
    }
}

// Используем систему уведомлений
$notificationManager = new NotificationManager(
    new EmailNotification(),
    new SmsNotification()
);

// Позже добавляем push-уведомления без изменения NotificationManager
$notificationManager->addNotification(new PushNotification());
$notificationManager->notify("Новый пост опубликован!");

echo "🎉 Open/Closed Principle освоен! Расширяй функциональность, не ломая существующий код!\n";
?>
```

### Liskov Substitution Principle (Принцип подстановки Барбары Лисков)

Наследующие классы должны быть взаимозаменяемы с родительскими. Если утка наследуется от птицы, она должна уметь делать все то же, что и птица, а не взрываться при попытке полететь.

```php
<?php
/**
 * НЕПРАВИЛЬНО: Нарушение принципа подстановки Лисков
 */
class Bird {
    public function fly(): string {
        return "Я лечу!";
    }
}

class Duck extends Bird {
    // Утка летает - все ок
}

class Ostrich extends Bird {
    // Страус не умеет летать, но наследует метод fly!
    public function fly(): string {
        throw new Exception("Страусы не летают! 💥");
    }
}

// Функция ожидает любую птицу
function makeBirdFly(Bird $bird) {
    echo $bird->fly() . "\n";
}

// Это работает
makeBirdFly(new Duck());

// Это падает! Нарушение LSP!
// makeBirdFly(new Ostrich());

/**
 * ПРАВИЛЬНО: Перепроектируем иерархию классов
 */

// Базовый класс для всех птиц
abstract class Bird {
    public function speak(): string {
        return "Я птица!";
    }
}

// Интерфейс для летающих птиц
interface FlyingBirdInterface {
    public function fly(): string;
}

// Интерфейс для бегающих птиц
interface RunningBirdInterface {
    public function run(): string;
}

class Duck extends Bird implements FlyingBirdInterface, RunningBirdInterface {
    public function fly(): string {
        return "Утка летит! 🦆";
    }
    
    public function run(): string {
        return "Утка бежит! 🦆";
    }
}

class Ostrich extends Bird implements RunningBirdInterface {
    public function run(): string {
        return "Страус бежит очень быстро! 🏃‍♂️";
    }
}

class Eagle extends Bird implements FlyingBirdInterface {
    public function fly(): string {
        return "Орел парит в небе! 🦅";
    }
}

// Теперь функции работают с конкретными возможностями
function makeBirdFly(FlyingBirdInterface $bird) {
    echo $bird->fly() . "\n";
}

function makeBirdRun(RunningBirdInterface $bird) {
    echo $bird->run() . "\n";
}

// Демонстрация принципа
echo "\n🎯 Демонстрация Liskov Substitution Principle:\n";

$duck = new Duck();
$ostrich = new Ostrich();
$eagle = new Eagle();

// Утка может и летать и бегать
makeBirdFly($duck);
makeBirdRun($duck);

// Страус только бегает
makeBirdRun($ostrich);

// Орел только летает
makeBirdFly($eagle);

echo "✅ LSP работает! Все классы взаимозаменяемы в рамках своих контрактов!\n";

/**
 * Практический пример с системой блога
 */

// НЕПРАВИЛЬНО
class BadPost {
    public function publish(): void {
        echo "Публикуем пост...\n";
    }
    
    public function validate(): bool {
        return !empty($this->title) && !empty($this->content);
    }
}

class BadScheduledPost extends BadPost {
    private DateTime $publishDate;
    
    public function publish(): void {
        if ($this->publishDate > new DateTime()) {
            throw new Exception("Нельзя опубликовать запланированный пост раньше времени!");
        }
        parent::publish();
    }
}

// ПРАВИЛЬНО
abstract class Post {
    protected string $title;
    protected string $content;
    
    public function __construct(string $title, string $content) {
        $this->title = $title;
        $this->content = $content;
    }
    
    abstract public function publish(): void;
    
    public function validate(): bool {
        return !empty($this->title) && !empty($this->content);
    }
}

class ImmediatePost extends Post {
    public function publish(): void {
        echo "📢 Публикуем пост сразу: {$this->title}\n";
    }
}

class ScheduledPost extends Post {
    private DateTime $publishDate;
    
    public function __construct(string $title, string $content, DateTime $publishDate) {
        parent::__construct($title, $content);
        $this->publishDate = $publishDate;
    }
    
    public function publish(): void {
        if ($this->publishDate > new DateTime()) {
            echo "⏰ Пост '{$this->title}' запланирован на {$this->publishDate->format('Y-m-d H:i:s')}\n";
            return;
        }
        echo "📢 Публикуем запланированный пост: {$this->title}\n";
    }
    
    public function shouldPublish(): bool {
        return $this->publishDate <= new DateTime();
    }
}

// Функция для публикации любого поста
function publishPost(Post $post) {
    if (!$post->validate()) {
        throw new Exception("Пост не прошел валидацию!");
    }
    $post->publish();
}

// Демонстрация
$immediatePost = new ImmediatePost("Срочная новость", "Важный контент");
$scheduledPost = new ScheduledPost("Запланированная новость", "Контент", 
    (new DateTime())->modify('+1 day'));

publishPost($immediatePost);
publishPost($scheduledPost); // Не падает, а корректно обрабатывается

echo "🎉 Liskov Substitution Principle освоен! Наследники должны дополнять, а не ломать поведение!\n";
?>
```

### Interface Segregation Principle (Принцип разделения интерфейсов)

Лучше много маленьких интерфейсов, чем один большой. Это как набор инструментов: лучше иметь отдельные отвертки разных размеров, чем одну универсальную, которая плохо делает все.

```php
<?php
/**
 * НЕПРАВИЛЬНО: Один толстый интерфейс, который заставляет классы реализовывать ненужные методы
 */
interface BadWorkerInterface {
    public function code(): string;    // Программист умеет
    public function test(): string;    // Программист умеет
    public function design(): string;  // Программист не умеет (это дизайнер)
    public function manage(): string;  // Программист не умеет (это менеджер)
    public function cook(): string;    // Программист может уметь, но это не его работа
}

class BadProgrammer implements BadWorkerInterface {
    public function code(): string {
        return "Пишу код...";
    }
    
    public function test(): string {
        return "Пишу тесты...";
    }
    
    // Программист вынужден реализовывать ненужные методы!
    public function design(): string {
        throw new Exception("Я не дизайнер! 🎨");
    }
    
    public function manage(): string {
        throw new Exception("Я не менеджер! 📊");
    }
    
    public function cook(): string {
        throw new Exception("Я не повар! 👨‍🍳");
    }
}

/**
 * ПРАВИЛЬНО: Разделяем интерфейсы по ответственностям
 */

// Маленькие специализированные интерфейсы
interface CoderInterface {
    public function code(): string;
}

interface TesterInterface {
    public function test(): string;
}

interface DesignerInterface {
    public function design(): string;
}

interface ManagerInterface {
    public function manage(): string;
}

interface CookInterface {
    public function cook(): string;
}

// Теперь классы реализуют только нужные интерфейсы
class Programmer implements CoderInterface, TesterInterface {
    public function code(): string {
        return "💻 Пишу чистый код...";
    }
    
    public function test(): string {
        return "🧪 Пишу unit-тесты...";
    }
}

class Designer implements DesignerInterface {
    public function design(): string {
        return "🎨 Создаю красивые интерфейсы...";
    }
}

class ProjectManager implements ManagerInterface {
    public function manage(): string {
        return "📊 Управляю проектом...";
    }
}

class Chef implements CookInterface {
    public function cook(): string {
        return "👨‍🍳 Готовлю вкусную еду...";
    }
}

// Универсальный сотрудник (реализует несколько интерфейсов)
class FullStackDeveloper implements CoderInterface, TesterInterface, DesignerInterface {
    public function code(): string {
        return "💻 Пишу код на фронтенде и бэкенде...";
    }
    
    public function test(): string {
        return "🧪 Тестирую все подряд...";
    }
    
    public function design(): string {
        return "🎨 Делаю прототипы...";
    }
}

// Демонстрация принципа
echo "\n🎯 Демонстрация Interface Segregation Principle:\n";

$programmer = new Programmer();
$designer = new Designer();
$manager = new ProjectManager();
$chef = new Chef();
$fullStack = new FullStackDeveloper();

// Каждый работает в своей области
echo "Программист: " . $programmer->code() . "\n";
echo "Дизайнер: " . $designer->design() . "\n";
echo "Менеджер: " . $manager->manage() . "\n";
echo "Повар: " . $chef->cook() . "\n";
echo "Фуллстек: " . $fullStack->code() . " " . $fullStack->design() . "\n";

// Функции принимают только нужные интерфейсы
function developSoftware(CoderInterface $coder) {
    echo "Разработка: " . $coder->code() . "\n";
}

function createDesign(DesignerInterface $designer) {
    echo "Дизайн: " . $designer->design() . "\n";
}

developSoftware($programmer);
developSoftware($fullStack);
createDesign($designer);
createDesign($fullStack);

echo "✅ ISP работает! Интерфейсы разделены по функциям, классы не реализуют лишнего!\n";

/**
 * Практический пример с системой блога
 */

// НЕПРАВИЛЬНО: Один большой интерфейс
interface BadPostInterface {
    public function getTitle(): string;
    public function getContent(): string;
    public function getAuthor(): string;
    public function getSeoKeywords(): array;    // Не все посты имеют SEO
    public function getTags(): array;          // Не все посты имеют теги
    public function getCategory(): string;     // Не все посты имеют категорию
    public function isPublished(): bool;       // Черновики не опубликованы
    public function publish(): void;           // Черновики могут не поддерживать публикацию
}

// ПРАВИЛЬНО: Разделенные интерфейсы
interface BasicPostInterface {
    public function getTitle(): string;
    public function getContent(): string;
    public function getAuthor(): string;
}

interface PublishableInterface {
    public function isPublished(): bool;
    public function publish(): void;
    public function unpublish(): void;
}

interface CategorizableInterface {
    public function getCategory(): string;
    public function setCategory(string $category): void;
}

interface TaggableInterface {
    public function getTags(): array;
    public function addTag(string $tag): void;
    public function removeTag(string $tag): void;
}

interface SeoableInterface {
    public function getSeoKeywords(): array;
    public function getMetaDescription(): string;
}

// Теперь классы реализуют только нужные интерфейсы
class SimplePost implements BasicPostInterface {
    public function __construct(
        private string $title,
        private string $content,
        private string $author
    ) {}
    
    public function getTitle(): string { return $this->title; }
    public function getContent(): string { return $this->content; }
    public function getAuthor(): string { return $this->author; }
}

class BlogPost implements BasicPostInterface, PublishableInterface, TaggableInterface, CategorizableInterface {
    public function __construct(
        private string $title,
        private string $content,
        private string $author
    ) {}
    
    // BasicPostInterface
    public function getTitle(): string { return $this->title; }
    public function getContent(): string { return $this->content; }
    public function getAuthor(): string { return $this->author; }
    
    // PublishableInterface
    public function isPublished(): bool { return true; }
    public function publish(): void { echo "Публикуем пост...\n"; }
    public function unpublish(): void { echo "Снимаем пост с публикации...\n"; }
    
    // CategorizableInterface
    public function getCategory(): string { return "Общее"; }
    public function setCategory(string $category): void { echo "Устанавливаем категорию: $category\n"; }
    
    // TaggableInterface
    public function getTags(): array { return ["php", "solid"]; }
    public function addTag(string $tag): void { echo "Добавляем тег: $tag\n"; }
    public function removeTag(string $tag): void { echo "Удаляем тег: $tag\n"; }
}

// Использование
$simplePost = new SimplePost("Простой пост", "Содержание", "Автор");
$blogPost = new BlogPost("Пост блога", "Содержание", "Автор");

function displayPost(BasicPostInterface $post) {
    echo "📝 {$post->getTitle()} от {$post->getAuthor()}\n";
}

function managePublication(PublishableInterface $post) {
    if (!$post->isPublished()) {
        $post->publish();
    }
}

displayPost($simplePost);
displayPost($blogPost);
managePublication($blogPost);

echo "🎉 Interface Segregation Principle освоен! Дроби интерфейсы как профи!\n";
?>
```

### Dependency Inversion Principle (Принцип инверсии зависимостей)

Зависимости должны быть от абстракций, а не от конкретных реализаций. Это как розетка: тебе не важно, какой именно прибор ты включаешь, главное что у него подходящая вилка.

```php
<?php
/**
 * НЕПРАВИЛЬНО: Зависимость от конкретных реализаций
 */
class BadPostService {
    private MySQLDatabase $database;     // Зависимость от конкретной БД
    private SmtpMailer $mailer;         // Зависимость от конкретного почтовика
    private FileLogger $logger;         // Зависимость от конкретного логгера
    
    public function __construct() {
        $this->database = new MySQLDatabase(); // Жесткая привязка
        $this->mailer = new SmtpMailer();     // Жесткая привязка  
        $this->logger = new FileLogger();     // Жесткая привязка
    }
    
    public function createPost($title, $content) {
        // Используем конкретные реализации
        $this->database->query("INSERT INTO posts ...");
        $this->mailer->sendEmail("admin@site.com", "New post", $title);
        $this->logger->log("Post created: $title");
    }
}

// Конкретные классы, от которых зависит BadPostService
class MySQLDatabase {
    public function query($sql) { echo "Выполняем MySQL запрос: $sql\n"; }
}

class SmtpMailer {
    public function sendEmail($to, $subject, $body) { 
        echo "Отправляем email через SMTP: $subject\n"; 
    }
}

class FileLogger {
    public function log($message) { 
        echo "Пишем в файл лога: $message\n"; 
    }
}

/**
 * ПРАВИЛЬНО: Зависимость от абстракций (интерфейсов)
 */

// Абстракции (интерфейсы)
interface DatabaseInterface {
    public function query(string $sql): void;
    public function find(string $table, int $id): ?array;
}

interface MailerInterface {
    public function send(string $to, string $subject, string $body): bool;
}

interface LoggerInterface {
    public function log(string $message, string $level = 'info'): void;
}

// Высокоуровневый модуль зависит от абстракций
class GoodPostService {
    private DatabaseInterface $database;
    private MailerInterface $mailer;
    private LoggerInterface $logger;
    
    // Dependency Injection через конструктор
    public function __construct(
        DatabaseInterface $database,
        MailerInterface $mailer, 
        LoggerInterface $logger
    ) {
        $this->database = $database;
        $this->mailer = $mailer;
        $this->logger = $logger;
    }
    
    public function createPost(string $title, string $content): void {
        // Работаем через абстракции
        $this->database->query("INSERT INTO posts (title, content) VALUES ('$title', '$content')");
        $this->mailer->send("admin@site.com", "New post: $title", $content);
        $this->logger->log("Post created: $title");
    }
}

// Конкретные реализации абстракций
class PostgreSQLDatabase implements DatabaseInterface {
    public function query(string $sql): void {
        echo "🛢️ Выполняем PostgreSQL запрос: $sql\n";
    }
    
    public function find(string $table, int $id): ?array {
        echo "🛢️ Ищем в PostgreSQL: $table id=$id\n";
        return ['id' => $id, 'title' => 'Test'];
    }
}

class SendGridMailer implements MailerInterface {
    public function send(string $to, string $subject, string $body): bool {
        echo "📧 Отправляем через SendGrid: $subject\n";
        return true;
    }
}

class CloudLogger implements LoggerInterface {
    public function log(string $message, string $level = 'info'): void {
        echo "☁️ Пишем в облачный лог [$level]: $message\n";
    }
}

// Еще одна реализация для тестов
class MockDatabase implements DatabaseInterface {
    public function query(string $sql): void {
        echo "🧪 Тестовый запрос: $sql\n";
    }
    
    public function find(string $table, int $id): ?array {
        echo "🧪 Тестовый поиск: $table id=$id\n";
        return ['id' => $id, 'title' => 'Mock Post'];
    }
}

class MockMailer implements MailerInterface {
    public function send(string $to, string $subject, string $body): bool {
        echo "🧪 Тестовая отправка email: $subject\n";
        return true;
    }
}

class MockLogger implements LoggerInterface {
    public function log(string $message, string $level = 'info'): void {
        echo "🧪 Тестовый лог [$level]: $message\n";
    }
}

// Демонстрация принципа
echo "\n🎯 Демонстрация Dependency Inversion Principle:\n";

// Продакшен версия с реальными сервисами
$productionService = new GoodPostService(
    new PostgreSQLDatabase(),
    new SendGridMailer(),
    new CloudLogger()
);

$productionService->createPost("Продакшен пост", "Содержание");

echo "\n";

// Тестовая версия с mock-сервисами
$testService = new GoodPostService(
    new MockDatabase(),
    new MockMailer(),
    new MockLogger()
);

$testService->createPost("Тестовый пост", "Содержание");

echo "✅ DIP работает! Мы легко подменяем реализации без изменения основного кода!\n";

/**
 * Практический пример с системой кэширования
 */

interface CacheInterface {
    public function get(string $key): ?string;
    public function set(string $key, string $value, int $ttl = 3600): void;
    public function delete(string $key): void;
}

class RedisCache implements CacheInterface {
    public function get(string $key): ?string {
        echo "🔴 Redis: получаем ключ '$key'\n";
        return "cached_value_$key";
    }
    
    public function set(string $key, string $value, int $ttl = 3600): void {
        echo "🔴 Redis: устанавливаем ключ '$key' с TTL $ttl\n";
    }
    
    public function delete(string $key): void {
        echo "🔴 Redis: удаляем ключ '$key'\n";
    }
}

class FileCache implements CacheInterface {
    public function get(string $key): ?string {
        echo "📁 FileCache: получаем ключ '$key'\n";
        return "file_cached_$key";
    }
    
    public function set(string $key, string $value, int $ttl = 3600): void {
        echo "📁 FileCache: устанавливаем ключ '$key'\n";
    }
    
    public function delete(string $key): void {
        echo "📁 FileCache: удаляем ключ '$key'\n";
    }
}

class MemoryCache implements CacheInterface {
    private array $storage = [];
    
    public function get(string $key): ?string {
        echo "💾 MemoryCache: получаем ключ '$key'\n";
        return $this->storage[$key] ?? null;
    }
    
    public function set(string $key, string $value, int $ttl = 3600): void {
        echo "💾 MemoryCache: устанавливаем ключ '$key'\n";
        $this->storage[$key] = $value;
    }
    
    public function delete(string $key): void {
        echo "💾 MemoryCache: удаляем ключ '$key'\n";
        unset($this->storage[$key]);
    }
}

class PostServiceWithCache {
    private DatabaseInterface $database;
    private CacheInterface $cache;
    
    public function __construct(DatabaseInterface $database, CacheInterface $cache) {
        $this->database = $database;
        $this->cache = $cache;
    }
    
    public function getPost(int $id): ?array {
        $cacheKey = "post_$id";
        
        // Пытаемся получить из кэша
        $cachedPost = $this->cache->get($cacheKey);
        if ($cachedPost) {
            echo "✅ Нашли в кэше!\n";
            return json_decode($cachedPost, true);
        }
        
        // Если нет в кэше - ищем в базе
        echo "🔍 Не найдено в кэше, ищем в базе...\n";
```


## Введение: Почему ООП - это круто?

Представьте, что вы строите дом. Без ООП - это как таскать кирпичи голыми руками. С ООП - у вас есть целый набор профессиональных инструментов!

**ООП (Объектно-Ориентированное Программирование)** - это подход, где программа состоит из объектов, которые взаимодействуют друг с другом. Как в реальном мире: машина состоит из двигателя, колес, кузова - каждый объект знает свою работу.

---

# Часть V: Дополнительные материалы

## Приложение A: Часто задаваемемые вопросы

### 1. "Что такое класс и объект? Это одно и то же?"

**Класс** - это чертеж, **объект** - готовый дом по этому чертежу.

```php
<?php
// Это КЛАСС - чертеж кота
class Cat {
    // Свойства (характеристики кота)
    public $name;
    public $color;
    public $isSleeping = false;
    
    // Методы (что кот умеет делать)
    public function sleep() {
        $this->isSleeping = true;
        return "{$this->name} заснул! Zzz...";
    }
    
    public function wakeUp() {
        $this->isSleeping = false;
        return "{$this->name} проснулся! Мяу!";
    }
}

// А это ОБЪЕКТЫ - реальные коты по чертежу
$cat1 = new Cat();  // Создаем первого кота
$cat1->name = "Барсик";
$cat1->color = "рыжий";

$cat2 = new Cat();  // Создаем второго кота
$cat2->name = "Мурка";
$cat2->color = "серая";

echo $cat1->sleep();  // Барсик заснул! Zzz...
echo $cat2->wakeUp(); // Мурка проснулась! Мяу!
?>
```

### 2. "Зачем нужны конструкторы?"

**Конструктор** - как паспортный стол для объекта. Он вызывается автоматически при создании объекта и помогает "зарегистрировать" его правильно.

```php
<?php
class Cat {
    public $name;
    public $color;
    
    // Конструктор - вызывается при создании new Cat()
    public function __construct($catName, $catColor) {
        $this->name = $catName;
        $this->color = $catColor;
        echo "Родился новый кот: {$this->name} цветом {$this->color}! 🐱<br>";
    }
}

// Теперь создавать котов стало проще!
$cat1 = new Cat("Барсик", "рыжий");  // Автоматически вызовется __construct
$cat2 = new Cat("Мурка", "серая");

// Раньше пришлось бы делать так:
// $cat1 = new Cat();
// $cat1->name = "Барсик";
// $cat1->color = "рыжий";
?>
```

### 3. "Что такое $this?"

**$this** - это волшебное слово, которое означает "я, этот конкретный объект". Как когда вы говорите "я голоден" - "я" относится именно к вам.

```php
<?php
class Cat {
    public $name;
    
    public function sayMeow() {
        // $this->name означает "имя этого конкретного кота"
        return "{$this->name} говорит: Мяу!";
    }
    
    public function eat($food) {
        return "{$this->name} кушает {$food}. Вкусно!";
    }
}

$cat = new Cat();
$cat->name = "Васька";

echo $cat->sayMeow();  // Васька говорит: Мяу!
echo $cat->eat("рыбу"); // Васька кушает рыбу. Вкусно!
?>
```

---

## Приложение B: Лучшие практики ООП 🏆

### 1. Инкапсуляция: Не все должно быть публичным!

**Инкапсуляция** - принцип "упаковки" данных. Как аптечка: вы знаете, КАК ей пользоваться, но не видите, что внутри.

```php
<?php
class BankAccount {
    // private - значит, что напрямую к балансу обратиться нельзя
    private $balance = 0;
    
    // public методы - это "интерфейс" для работы с объектом
    public function deposit($amount) {
        if ($amount > 0) {
            $this->balance += $amount;
            return "Положили {$amount}. Баланс: {$this->balance}";
        } else {
            return "Нельзя положить отрицательную сумму!";
        }
    }
    
    public function withdraw($amount) {
        if ($amount > 0 && $amount <= $this->balance) {
            $this->balance -= $amount;
            return "Сняли {$amount}. Баланс: {$this->balance}";
        } else {
            return "Недостаточно средств или неверная сумма!";
        }
    }
    
    public function getBalance() {
        return "Текущий баланс: {$this->balance}";
    }
}

$account = new BankAccount();
echo $account->deposit(1000);  // Положили 1000. Баланс: 1000
echo $account->withdraw(500);  // Сняли 500. Баланс: 500
echo $account->getBalance();   // Текущий баланс: 500

// Так НЕЛЬЗЯ - баланс private!
// echo $account->balance;  // Ошибка!
?>
```

### 2. Наследование: Не изобретай велосипед!

**Наследование** позволяет создавать новые классы на основе существующих.

```php
<?php
// Базовый класс - общие характеристики всех животных
class Animal {
    protected $name;
    protected $sound;
    
    public function __construct($name, $sound) {
        $this->name = $name;
        $this->sound = $sound;
    }
    
    public function makeSound() {
        return "{$this->name} издает звук: {$this->sound}!";
    }
    
    public function sleep() {
        return "{$this->name} спит... Zzz...";
    }
}

// Класс Cat наследует все от Animal
class Cat extends Animal {
    public function __construct($name) {
        // parent::__construct вызывает конструктор родителя
        parent::__construct($name, "Мяу");
    }
    
    // Дополнительный метод, специфичный для кошек
    public function climbTree() {
        return "{$this->name} лазает по деревьям!";
    }
}

class Dog extends Animal {
    public function __construct($name) {
        parent::__construct($name, "Гав");
    }
    
    public function fetchBall() {
        return "{$this->name} приносит мячик!";
    }
}

// Используем наследование
$cat = new Cat("Барсик");
$dog = new Dog("Шарик");

echo $cat->makeSound();  // Барсик издает звук: Мяу!
echo $dog->makeSound();  // Шарик издает звук: Гав!
echo $cat->climbTree();  // Барсик лазает по деревьям!
echo $dog->fetchBall();  // Шарик приносит мячик!

// Методы из родительского класса работают у всех!
echo $cat->sleep();  // Барсик спит... Zzz...
echo $dog->sleep();  // Шарик спит... Zzz...
?>
```

### 3. Полиморфизм: Одно действие - разные реализации

**Полиморфизм** - это когда разные объекты могут по-разному реагировать на одно и то же действие.

```php
<?php
// Абстрактный класс - нельзя создать объект, только наследовать
abstract class Shape {
    abstract public function calculateArea();  // Абстрактный метод - без реализации
}

class Circle extends Shape {
    private $radius;
    
    public function __construct($radius) {
        $this->radius = $radius;
    }
    
    // Каждый класс реализует метод по-своему
    public function calculateArea() {
        return 3.14 * $this->radius * $this->radius;
    }
}

class Rectangle extends Shape {
    private $width;
    private $height;
    
    public function __construct($width, $height) {
        $this->width = $width;
        $this->height = $height;
    }
    
    public function calculateArea() {
        return $this->width * $this->height;
    }
}

// Полиморфизм в действии!
$shapes = [
    new Circle(5),
    new Rectangle(4, 6),
    new Circle(3)
];

foreach ($shapes as $shape) {
    // Один метод, но разное поведение для разных фигур!
    echo "Площадь: " . $shape->calculateArea() . "<br>";
}
?>
```

---

## Приложение C: Распространенные ошибки и как их избежать 

### 1. Ошибка: "Слишком много всего в одном классе"

**Проблема:** Класс-бог (God Class), который делает все.

```php
<?php
// ПЛОХО: Класс делает слишком много!
class SuperClass {
    public function connectToDatabase() { /* ... */ }
    public function sendEmail() { /* ... */ }
    public function calculateTaxes() { /* ... */ }
    public function generatePDF() { /* ... */ }
    public function cookDinner() { /* ... */ }  // Серьезно? 😄
}

// ХОРОШО: Разделяем ответственность
class DatabaseManager {
    public function connect() { /* ... */ }
}

class EmailService {
    public function send() { /* ... */ }
}

class TaxCalculator {
    public function calculate() { /* ... */ }
}

class PDFGenerator {
    public function generate() { /* ... */ }
}

// Каждый класс отвечает за одну конкретную задачу
?>
```

### 2. Ошибка: "Игнорирование инкапсуляции"

**Проблема:** Все свойства публичные, любой может их изменить.

```php
<?php
// ПЛОХО: Прямой доступ к свойствам
class User {
    public $password;  // Ой-ой, пароль публичный!
}

$user = new User();
$user->password = "123456";  // Так делать нельзя!

// ХОРОШО: Используем геттеры и сеттеры
class SecureUser {
    private $password;
    
    public function setPassword($newPassword) {
        if (strlen($newPassword) >= 6) {
            $this->password = password_hash($newPassword, PASSWORD_DEFAULT);
            return "Пароль установлен!";
        } else {
            return "Пароль слишком короткий!";
        }
    }
    
    public function verifyPassword($inputPassword) {
        return password_verify($inputPassword, $this->password);
    }
}

$user = new SecureUser();
echo $user->setPassword("123456");  // Пароль установлен!
echo $user->setPassword("123");     // Пароль слишком короткий!
?>
```

### 3. Ошибка: "Наследование вместо композиции"

**Проблема:** Используем наследование там, где лучше подходит композиция.

```php
<?php
// ПЛОХО: Неправильное наследование
class Duck extends Animal {
    public function fly() {
        return "Утка летит!";
    }
}

class RubberDuck extends Duck {
    // Резиновая утка не должна летать!
    public function fly() {
        return "Резиновая утка не может летать!";  // Нарушение принципа!
    }
}

// ХОРОШО: Используем композицию
interface Flyable {
    public function fly();
}

class RealDuck extends Animal implements Flyable {
    public function fly() {
        return "Утка летит!";
    }
}

class RubberDuck extends Animal {
    // У резиновой утки нет метода fly() - проблема решена!
    public function squeak() {
        return "Пик-пик!";
    }
}
?>
```

---

## Заключение: Путь к мастерству ООП 

### Этапы становления ООП-мастера:

#### 1. **Новичок** ("Что такое класс?")
- Понимает базовые понятия
- Пишет простые классы
- Часто ошибается с областями видимости

#### 2. **Продолжающий** ("Наследование - это круто!")
- Активно использует наследование
- Начинает понимать инкапсуляцию
- Иногда создает слишком сложные иерархии

#### 3. **Опытный** ("Композиция лучше наследования")
- Использует паттерны проектирования
- Понимает принципы SOLID
- Пишет тестируемый код

#### 4. **Мастер** ("ООП - это инструмент, а не религия")
- Выбирает правильные подходы под задачу
- Понимает, когда ООП уместно, а когда нет
- Пишет простой и поддерживаемый код

### Философская мысль напоследок:

*"ООП - как кулинария: сначала вы следуете рецептам, потом создаете свои, а в итоге понимаете, что главное - чтобы было вкусно и полезно, а не как именно вы этого добились."*

Помните: даже самые крутые программисты начинали с "Hello World". Главное - практиковаться и не бояться ошибок!

**Удачи в изучении ООП! 🚀 Помните: каждый эксперт когда-то был новичком.**