# Technomart - грейдирование

## Коментарии по использованию стилей

1. Использовала стили для тени в карточке товара: box-shadow: 0 4px 13px rgba(0, 0, 0, 0.25); 
Взяла их из стайлгайда с самой карточки товара.
Но по то му же стайлгайду есть стили для теней и самая большая box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.15),
которая для карточки твара из стайлгайда не подходит.


2. Для блока cart-navigation:
- Есть два класса bookmarks и bookmarks-empty: при непустых закладках добавляется число и меняем класс на bookmarks
- Есть два класса basket и basket-empty-empty: при непустых закладках добавляется число и меняем класс на basket

3. Для блока user-navigation для залогиненного стейта (и наоборот для разлогиненного): 
- добавить класс logged-in к классу user-navigation
- добавить класс hidden к user-navigation-link login
- убрать класс hidden в классе user-navigation-link profile
- убрать класс hidden в классе user-navigation-link logout