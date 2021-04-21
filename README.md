# Базовый проект NodeJS с Babel 7, Eslint, Jest.

- Babel - это компилятор языка JavaScript и настраиваемый странспайлер.
- Eslint для автоматической проверки синтаксиса набираемого кода.
- Jest фреймворк для тестирования.

## Babel

@babel/core - непосредственно сам трансплайнер.

@babel/cli - позволяет нам компилировать файлы с помощью командной строки для преобразования кода к версии языка ES5.

@babel/node - утилита командной строки, которая работает также, как и Node cli, но дополнительно использует
установленные babel-плагины и пресеты, прогоняя код через них перед запуском.

@babel/preset-env - открывает нам доступ к новым возможностям языка JavaScript.

## Eslint

```
yarn run eslint .
```

[eslint-config-airbnb](https://github.com/airbnb/javascript) - Подготовленная конфигурация с правилами от команды
airbnb.

[eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) - Данный плагин добавит в ваш проект проверки
для всех ваших импортов и будет следить за тем, чтобы все импортируемые зависимости присутствовали в проекте,
подключались в удобном для последующей работы порядке, и так далее.

[eslint-plugin-lodash](https://github.com/wix/eslint-plugin-lodash) - Подсказывает где лучше использовать Lodash.

[eslint-plugin-promise](https://github.com/xjamundx/eslint-plugin-promise) - Плагин, который поможет вам писать
правильные промисы и защитит вас от типичных ошибок при работе с ними.

## Jest
