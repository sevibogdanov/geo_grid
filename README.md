# geo_grid
Пример подготовки данных и визуализации концентрации точек на карте

[Дашборд в DataLens](https://datalens.yandex.cloud/qk97nm2ebiayd-karta)

В проекте детально описан пример подготовки и визуализации данных для определения концентрации точек продаж в Москве по административным округам.
Концентрацияю определяется на основе сетки 1100м x 600м путем поиска выбросов по кол-ву тчоек внутри административного округа.

К плюсам можно отнести простоту данного метода и предсказуемый, воспроизводимый результат.
Очевидным минусом подхода является возможное делением фактического центра скопления точек на несколько частей (если они будут отнесены к разным прямоугольникам сетки).
