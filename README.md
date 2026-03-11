# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 05:14:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 53302.3 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135929
telemt_connections_bad_total 3400
telemt_handshake_timeouts_total 2977
telemt_upstream_connect_attempt_total 123394
telemt_upstream_connect_success_total 123350
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 123394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123344
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 3090425303 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 87627971344 (81.61 GB)
telemt_user_msgs_from_client{user="hello"} 3227464
telemt_user_msgs_to_client{user="hello"} 6125214
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 53301.6 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55609
telemt_connections_bad_total 435
telemt_handshake_timeouts_total 2972
telemt_upstream_connect_attempt_total 49335
telemt_upstream_connect_success_total 49324
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 49335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49318
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 4493825425 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 46517584689 (43.32 GB)
telemt_user_msgs_from_client{user="hello"} 2666003
telemt_user_msgs_to_client{user="hello"} 10983463
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 53301.2 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76406
telemt_connections_bad_total 714
telemt_handshake_timeouts_total 4323
telemt_upstream_connect_attempt_total 67028
telemt_upstream_connect_success_total 67025
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 67028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67019
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 11781798864 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71249000546 (66.36 GB)
telemt_user_msgs_from_client{user="hello"} 5193634
telemt_user_msgs_to_client{user="hello"} 13407170
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 53300.2 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79714
telemt_connections_bad_total 158
telemt_handshake_timeouts_total 587
telemt_upstream_connect_attempt_total 76314
telemt_upstream_connect_success_total 76146
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 76314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76140
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1833200065 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 49189682945 (45.81 GB)
telemt_user_msgs_from_client{user="hello"} 1742591
telemt_user_msgs_to_client{user="hello"} 10812117
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 53301.6 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126323
telemt_connections_bad_total 12009
telemt_handshake_timeouts_total 1709
telemt_upstream_connect_attempt_total 107212
telemt_upstream_connect_success_total 106962
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 107211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 106956
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 2402195898 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 102449857737 (95.41 GB)
telemt_user_msgs_from_client{user="hello"} 2617939
telemt_user_msgs_to_client{user="hello"} 13125849
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32270.9 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```