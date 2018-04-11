# Title

# Commands:
#### bg_set_default
#### set_default

## toggle / bg_toggle / all_togle
переключить состояние питания на противоположное

**параметры**: *отсутствуют*

**команда оригинал**: `toggle` / `bg_toggle` / `all_togle`


## power / bg_power
управление состоянием питания

**параметры**:
* `action`: `[on/off]`
* `duration` *[ms]*
* `mode` - **TODO**

**команда оригинал**: `set_power` / `bg_set_power`


## bright / bg_bright
управление яркостью

**параметры**:
* `brightness` - [1, 100]
* `duration` *[ms]*

**команда оригинал**: `set_bright` / `bg_set_bright`

## ct / bg_ct
управление цветовой температурой

**параметры**:
* `ct` - цветовая температура _К_
* `duration` *[ms]*

**команда оригинал**: `set_ct_abx` / `bg_set_ct_abx`


# Color commands:
## rgb / bg_rgb
управление цветом

**параметры**:
* `rgb` - [0, 16777215] hex:[0, 0xFFFFFF] или отдельно по каналам `r,g,b` - [0, 255]
* `duration` *[ms]*

**команда оригинал**: `set_rgb` / `bg_set_rgb`


## hsv / bg_hsv
управление цветом по типу "цветовая модель"

**параметры**:
* `hue - [0, 359] - цветовой тон`
* `saturation` или `sat` - [0, 100] - насыщенность
* `duration` *[ms]*

**команда оригинал**: `set_hsv` / `bg_set_hsv`


## start_cf / bg_start_cf
## stop_cf / bg_stop_cf

## scene / bg_scene

# Управление задачами:
## add_cron
добавить задачу

**параметры**:
* `action` - [off]
* `timer` *[m]*

**команда оригинал**: `cron_add`

## del_cron
удалить задачу

**параметры**:
* `action` - [off]

**команда оригинал**: `cron_del`

## get_cron
получить задачу

**параметры**:
* `action` - [off]

**команда оригинал**: `cron_get`


## adjust / bg_adjust
Изменить яркость, цветовую температуру или цвет.

**параметры**:
* `action` - [circle(default), increase, decrease]
* `property` - [bright|brightness, color, ct]

**команда оригинал**: `set_adjust` / `bg_set_adjust`


#### name

#### get_property
