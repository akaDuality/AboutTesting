# Типы тестов

Тесты бывают разных видов поверх разных инструментов. Давайте просто перечислим все и посмотрим какие комбинацию из этого бывают. 

## По охвату кода
- На функцию 
- На класс
- На связку классов
- На сценарий внутри модуля
- Сквозной сценарий в приложении между модулями
- На архитектуру всего приложения или кода

@Image(source: CodeCoverageTypes, alt: "Разные виды тестов")

## По стабильности зависимостей

**Юнит-тесты:** все зависимости подконтрольны, поэтому тесты должны быть максимально стабильными. У тестов может быть разный охват, но пока зависимости стабильным мы можем считать их юнит-тестами. 
**Интеграционные тесты:** какая-то из зависимостей настоящая, а значит нестабильная. Например, мы 

### По структуре тестов
- Атомарные тесты: XCTest, Swift Testing
- Спецификации: Quick

## По типу тестирования UI

### Снепшот-тесты

**Снепшот-тесты для данных**: 

Snapshot Testing

**Скриншот-тесты** интерфейса

Можно применять и для других изображений. Например скриншотить чеки, ценники, генерацию нейросети и т.п.

**Логика экрана**

KIF

## UI-тесты
 
Продолжение фреймворка XCTest, но запускаются через отдельное приложение. 

@Image(source: UITestTypes, alt: "Разные виды тестов")
