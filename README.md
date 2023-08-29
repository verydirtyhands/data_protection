# Защита персональных данных клиентов

## Описание проекта

Цель проекта заключается в разработке метода преобразования данных, который обеспечит надежную защиту персональной информации клиентов страховой компании "Хоть потоп". Этот метод должен гарантировать, что после преобразования данные будут труднопонимаемыми для злоумышленников, при этом сохраняя качество моделей машинного обучения, построенных на этих данных.

## Инструменты:

`Python==3.9.16`
`Pandas==1.5.3`
`sklearn==1.2.2`
`seaborn==0.12.2`
`matplotlib==3.6.3`
`numpy==1.23.5`
`pandas_profiling==3.6.6`
`imblearn`
`deep_translator==1.11.4`
`scipy==1.9.3`

## Описание клиентских данных:

- Пол
- Зарплата
- Возраст
- Количество членов семьи	
- Страховые выплаты (сколько всего страховых выплат произведено за жизнь)

## Краткое описание проведённой работы:
<i> 
Проанализированы зависимости между различными персональными данными клиентов и страховыми выплатами .Данные зашифрованы при помощи Гомоморфное шифрования (матричное перемножение) Построена модели на основе TweedieRegressor  </i>

## Выводы
<i> проект по защите персональных данных клиентов страховой компании "Хоть потоп" был успешно выполнен. Мы работали с основной информацией, представленной в столбцах 'gender', 'age', 'salary', 'family_members' и использовали целевую переменную 'insurance_payments'. Путем проведения экспериментов с моделями машинного обучения нам удалось достичь значительно высокого значения коэффициента детерминации R2, равного 0.75. 

проект успешно сочетает в себе две важные цели: обеспечение высокого качества моделей машинного обучения и защиту приватности данных клиентов. Полученные результаты и разработанный метод "Coder" позволят страховой компании "Хоть потоп" поддерживать высокий уровень обслуживания клиентов, не подвергая их персональные данные риску.</i>

## Рекомендации
<i>При реализации метода гомоморфного шифрования важно обеспечить, чтобы ключи шифрования были хранены в надежном месте. Рассмотрите использование аппаратных модулей безопасности (HSM) для хранения и управления ключами.
</i>

---

#### Если проект не открывается или вы хотите посмотреть со всеми интерактивными ячейками(plotly,ydata-profiling), его можно открыть по ссылке: <a href='https://nbviewer.org/github/verydirtyhands/data_protection/blob/main/p9f.ipynb'>Защита персональных данных клиентов</a>
