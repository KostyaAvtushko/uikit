<!--GITHUB_BLOCK-->

# Accordion

<!--/GITHUB_BLOCK-->

```tsx
import {Accordion} from '@gravity-ui/uikit';
```

Компонент Accordion позволяет создавать складные панели контента, где пользователи могут показывать или скрывать разделы информации. Это полезно для организации большого количества контента в компактном виде.

## Размер

Используйте свойство `size` для управления размером `Accordion`. По умолчанию используется размер `m`.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
<Accordion size="s">
    <Accordion.Item summary="Маленький размер">
        Контент для маленького аккордеона
    </Accordion.Item>
</Accordion>
<Accordion size="m">
    <Accordion.Item summary="Средний размер">
        Контент для среднего аккордеона
    </Accordion.Item>
</Accordion>
<Accordion size="l">
    <Accordion.Item summary="Большой размер">
        Контент для большого аккордеона
    </Accordion.Item>
</Accordion>
<Accordion size="xl">
    <Accordion.Item summary="Очень большой размер">
        Контент для очень большого аккордеона
    </Accordion.Item>
</Accordion>
`}>
    <UIKit.Accordion size="s">
        <UIKit.Accordion.Item summary="Маленький размер">
            Контент для маленького аккордеона
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
    <UIKit.Accordion size="m">
        <UIKit.Accordion.Item summary="Средний размер">
            Контент для среднего аккордеона
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
    <UIKit.Accordion size="l">
        <UIKit.Accordion.Item summary="Большой размер">
            Контент для большого аккордеона
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
    <UIKit.Accordion size="xl">
        <UIKit.Accordion.Item summary="Очень большой размер">
            Контент для очень большого аккордеона
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
<Accordion size="s">
    <Accordion.Item summary="Маленький размер">
        Контент для маленького аккордеона
    </Accordion.Item>
</Accordion>
<Accordion size="m">
    <Accordion.Item summary="Средний размер">
        Контент для среднего аккордеона
    </Accordion.Item>
</Accordion>
<Accordion size="l">
    <Accordion.Item summary="Большой размер">
        Контент для большого аккордеона
    </Accordion.Item>
</Accordion>
<Accordion size="xl">
    <Accordion.Item summary="Очень большой размер">
        Контент для очень большого аккордеона
    </Accordion.Item>
</Accordion>
```

<!--/GITHUB_BLOCK-->

## Внешний вид

`solid`: Основной вид с фоном (используется по умолчанию).

`top-bottom`: Вид с границами сверху и снизу.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
<Accordion view="solid">
    <Accordion.Item summary="Сплошной вид">
        Контент с фоном
    </Accordion.Item>
    <Accordion.Item summary="Другой элемент">
        Больше контента
    </Accordion.Item>
</Accordion>
<Accordion view="top-bottom">
    <Accordion.Item summary="Вид с границами">
        Контент с границами сверху и снизу
    </Accordion.Item>
    <Accordion.Item summary="Другой элемент">
        Больше контента
    </Accordion.Item>
</Accordion>
`}>
    <UIKit.Accordion view="solid">
        <UIKit.Accordion.Item summary="Сплошной вид">
            Контент с фоном
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Другой элемент">
            Больше контента
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
    <UIKit.Accordion view="top-bottom">
        <UIKit.Accordion.Item summary="Вид с границами">
            Контент с границами сверху и снизу
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Другой элемент">
            Больше контента
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
<Accordion view="solid">
    <Accordion.Item summary="Сплошной вид">
        Контент с фоном
    </Accordion.Item>
    <Accordion.Item summary="Другой элемент">
        Больше контента
    </Accordion.Item>
</Accordion>
<Accordion view="top-bottom">
    <Accordion.Item summary="Вид с границами">
        Контент с границами сверху и снизу
    </Accordion.Item>
    <Accordion.Item summary="Другой элемент">
        Больше контента
    </Accordion.Item>
</Accordion>
```

<!--/GITHUB_BLOCK-->

## Позиция стрелки

`end`: Стрелка располагается в конце заголовка (используется по умолчанию).

`start`: Стрелка располагается в начале заголовка.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
<Accordion arrowPosition="end">
    <Accordion.Item summary="Стрелка в конце">
        Контент со стрелкой в конце
    </Accordion.Item>
</Accordion>
<Accordion arrowPosition="start">
    <Accordion.Item summary="Стрелка в начале">
        Контент со стрелкой в начале
    </Accordion.Item>
</Accordion>
`}>
    <UIKit.Accordion arrowPosition="end">
        <UIKit.Accordion.Item summary="Стрелка в конце">
            Контент со стрелкой в конце
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
    <UIKit.Accordion arrowPosition="start">
        <UIKit.Accordion.Item summary="Стрелка в начале">
            Контент со стрелкой в начале
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
<Accordion arrowPosition="end">
    <Accordion.Item summary="Стрелка в конце">
        Контент со стрелкой в конце
    </Accordion.Item>
</Accordion>
<Accordion arrowPosition="start">
    <Accordion.Item summary="Стрелка в начале">
        Контент со стрелкой в начале
    </Accordion.Item>
</Accordion>
```

<!--/GITHUB_BLOCK-->

## Множественное раскрытие

Свойство `multiple` позволяет одновременно раскрывать несколько элементов аккордеона.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
<Accordion multiple>
    <Accordion.Item summary="Первый элемент">
        Контент первого элемента
    </Accordion.Item>
    <Accordion.Item summary="Второй элемент">
        Контент второго элемента
    </Accordion.Item>
    <Accordion.Item summary="Третий элемент">
        Контент третьего элемента
    </Accordion.Item>
</Accordion>
`}>
    <UIKit.Accordion multiple>
        <UIKit.Accordion.Item summary="Первый элемент">
            Контент первого элемента
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Второй элемент">
            Контент второго элемента
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Третий элемент">
            Контент третьего элемента
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
<Accordion multiple>
  <Accordion.Item summary="Первый элемент">Контент первого элемента</Accordion.Item>
  <Accordion.Item summary="Второй элемент">Контент второго элемента</Accordion.Item>
  <Accordion.Item summary="Третий элемент">Контент третьего элемента</Accordion.Item>
</Accordion>
```

<!--/GITHUB_BLOCK-->

## Контролируемое состояние

Вы можете контролировать состояние аккордеона с помощью свойств `value` и `onUpdate`.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
function ControlledAccordion() {
    const [value, setValue] = React.useState('item1');

    return (
        <Accordion value={value} onUpdate={setValue}>
            <Accordion.Item summary="Настройки" value="item1">
                Настройте параметры приложения
            </Accordion.Item>
            <Accordion.Item summary="Уведомления" value="item2">
                Управляйте настройками уведомлений
            </Accordion.Item>
        </Accordion>
    );
}
`}>
    <UIKit.Accordion defaultValue="item1">
        <UIKit.Accordion.Item summary="Настройки" value="item1">
            Настройте параметры приложения
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Уведомления" value="item2">
            Управляйте настройками уведомлений
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
function ControlledAccordion() {
  const [value, setValue] = React.useState('item1');

  return (
    <Accordion value={value} onUpdate={setValue}>
      <Accordion.Item summary="Настройки" value="item1">
        Настройте параметры приложения
      </Accordion.Item>
      <Accordion.Item summary="Уведомления" value="item2">
        Управляйте настройками уведомлений
      </Accordion.Item>
    </Accordion>
  );
}
```

<!--/GITHUB_BLOCK-->

## Кастомный заголовок

Используйте компонент `Accordion.Summary` для создания кастомного заголовка.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
<Accordion>
    <Accordion.Item value="custom">
        <Accordion.Summary>
            {(props) => (
                <Button {...props} view="flat" width="max">
                    <Icon data={Settings} size={16} />
                    Кастомная кнопка заголовка
                </Button>
            )}
        </Accordion.Summary>
        Контент с кастомным заголовком
    </Accordion.Item>
    <Accordion.Item summary="Обычный заголовок">
        Контент с обычным заголовком
    </Accordion.Item>
</Accordion>
`}>
    <UIKit.Accordion>
        <UIKit.Accordion.Item value="custom">
            <UIKit.Accordion.Summary>
                {(props) => (
                    <UIKit.Button {...props} view="flat" width="max">
                        Кастомная кнопка заголовка
                    </UIKit.Button>
                )}
            </UIKit.Accordion.Summary>
            Контент с кастомным заголовком
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Обычный заголовок">
            Контент с обычным заголовком
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
<Accordion>
  <Accordion.Item value="custom">
    <Accordion.Summary>
      {(props) => (
        <Button {...props} view="flat" width="max">
          <Icon data={Settings} size={16} />
          Кастомная кнопка заголовка
        </Button>
      )}
    </Accordion.Summary>
    Контент с кастомным заголовком
  </Accordion.Item>
  <Accordion.Item summary="Обычный заголовок">Контент с обычным заголовком</Accordion.Item>
</Accordion>
```

<!--/GITHUB_BLOCK-->

## Отключенное состояние

Отдельные элементы аккордеона могут быть отключены с помощью свойства `disabled`.

<!--LANDING_BLOCK
<ExampleBlock
    code={`
<Accordion>
    <Accordion.Item summary="Активный элемент">
        Этот элемент активен и может быть раскрыт
    </Accordion.Item>
    <Accordion.Item summary="Отключенный элемент" disabled>
        Этот элемент отключен и не может быть раскрыт
    </Accordion.Item>
</Accordion>
`}>
    <UIKit.Accordion>
        <UIKit.Accordion.Item summary="Активный элемент">
            Этот элемент активен и может быть раскрыт
        </UIKit.Accordion.Item>
        <UIKit.Accordion.Item summary="Отключенный элемент" disabled>
            Этот элемент отключен и не может быть раскрыт
        </UIKit.Accordion.Item>
    </UIKit.Accordion>
</ExampleBlock>
LANDING_BLOCK-->

<!--GITHUB_BLOCK-->

```tsx
<Accordion>
  <Accordion.Item summary="Активный элемент">
    Этот элемент активен и может быть раскрыт
  </Accordion.Item>
  <Accordion.Item summary="Отключенный элемент" disabled>
    Этот элемент отключен и не может быть раскрыт
  </Accordion.Item>
</Accordion>
```

<!--/GITHUB_BLOCK-->

## Свойства

### Accordion

| Имя           | Описание                                              |               Тип               | По умолчанию |
| :------------ | :---------------------------------------------------- | :-----------------------------: | :----------: |
| size          | Размер аккордеона                                     |    `"s"` `"m"` `"l"` `"xl"`     |    `"m"`     |
| view          | Внешний вид аккордеона                                |    `"solid"` `"top-bottom"`     |  `"solid"`   |
| multiple      | Позволяет одновременно раскрывать несколько элементов |            `boolean`            |   `false`    |
| arrowPosition | Позиция стрелки-индикатора                            |        `"start"` `"end"`        |   `"end"`    |
| defaultValue  | Значение по умолчанию для неконтролируемого состояния | `string` `string[]` `undefined` |              |
| value         | Текущее значение для контролируемого состояния        | `string` `string[]` `undefined` |              |
| onUpdate      | Callback функция, вызываемая при изменении состояния  |           `Function`            |              |
| ariaLevel     | Уровень заголовка для accessibility                   |            `number`             |     `3`      |
| className     | CSS класс                                             |            `string`             |              |
| qa            | HTML `data-qa` атрибут, используется в тестах         |            `string`             |              |

### Accordion.Item

| Имя             | Описание                                                      |        Тип        | По умолчанию |
| :-------------- | :------------------------------------------------------------ | :---------------: | :----------: |
| value           | Уникальный идентификатор элемента                             |     `string`      |              |
| summary         | Заголовок элемента аккордеона                                 | `React.ReactNode` |              |
| expanded        | Контролируемое состояние раскрытия                            |     `boolean`     |              |
| defaultExpanded | Состояние раскрытия по умолчанию                              |     `boolean`     |              |
| disabled        | Отключает элемент аккордеона                                  |     `boolean`     |   `false`    |
| keepMounted     | Сохраняет содержимое в DOM даже когда элемент свернут         |     `boolean`     |              |
| onUpdate        | Callback функция, вызываемая при изменении состояния элемента |    `Function`     |              |
| className       | CSS класс                                                     |     `string`      |              |
| qa              | HTML `data-qa` атрибут, используется в тестах                 |     `string`      |              |
