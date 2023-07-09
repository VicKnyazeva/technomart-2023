# Technomart - грейдирование

## Коментарии по использованию стилей

1. Использованы стили для тени в карточке товара: 
```
box-shadow: 0 4px 13px rgba(0, 0, 0, 0.25); 
```
Они взяты из стайлгайда с самой карточки товара.
Но по то му же стайлгайду есть стили для теней и самая большая box-shadow: 
```
box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.15),
```
которая для карточки товара из стайлгайда не подходит.


2. Для блока cart-navigation:
- Есть два класса bookmarks и bookmarks-empty: при непустых закладках добавляется число и меняем класс на bookmarks
- Есть два класса basket и basket-empty-empty: при непустых закладках добавляется число и меняем класс на basket; 
- при пустой корзине должно быть
```
<a class="cart-navigation-link basket-empty" href="#">&nbsp;</a>
```

3. Для блока user-navigation: 

Разлогиненный стейт:
```
<section class="user-navigation hidden">
    ...          
    <a class="user-navigation-link login" href="#">Войти</a>
    <a class="user-navigation-link profile hidden" href="#">Равшан Джамшутович</a>
    <a class="user-navigation-link logout hidden" href="#"><span class="visually-hidden">Выйти</span></a>
```

Залогиненный стейт:
```
<section class="user-navigation logged-in">
    ...          
    <a class="user-navigation-link login hidden" href="#">Войти</a>
    <a class="user-navigation-link profile" href="#">Равшан Джамшутович</a>
    <a class="user-navigation-link logout" href="#"><span class="visually-hidden">Выйти</span></a>
```


4. PopUp: два попапа для логина и профайла включаются и отключаются стилями:
```
.user-popup.login {
    display: none;
    ...
}

.user-popup.profile {
    display: none;
    ...
}
```

### Верстка заняла 26 часов.