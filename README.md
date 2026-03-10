# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-10 09:01:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 121315.6 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246472
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2123
telemt_upstream_connect_attempt_total 231226
telemt_upstream_connect_success_total 231156
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 231226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 231144
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 5754612846 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 136608211923 (127.23 GB)
telemt_user_msgs_from_client{user="hello"} 5589889
telemt_user_msgs_to_client{user="hello"} 8670734
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 121314.1 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74444
telemt_connections_bad_total 3227
telemt_handshake_timeouts_total 1019
telemt_upstream_connect_attempt_total 66342
telemt_upstream_connect_success_total 66300
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 66342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66288
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2303767494 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 31341503969 (29.19 GB)
telemt_user_msgs_from_client{user="hello"} 1860358
telemt_user_msgs_to_client{user="hello"} 8935671
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 121314.7 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107703
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 5071
telemt_upstream_connect_attempt_total 75903
telemt_upstream_connect_success_total 75901
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 75903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75889
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 6332331841 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 60544349822 (56.39 GB)
telemt_user_msgs_from_client{user="hello"} 3989023
telemt_user_msgs_to_client{user="hello"} 9640572
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 121309.5 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108141
telemt_connections_bad_total 929
telemt_handshake_timeouts_total 1295
telemt_upstream_connect_attempt_total 100469
telemt_upstream_connect_success_total 100252
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 100469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100240
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2870350293 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 73855989528 (68.78 GB)
telemt_user_msgs_from_client{user="hello"} 2605091
telemt_user_msgs_to_client{user="hello"} 16770674
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 121314.8 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165987
telemt_connections_bad_total 26702
telemt_handshake_timeouts_total 4172
telemt_upstream_connect_attempt_total 128104
telemt_upstream_connect_success_total 127303
telemt_upstream_connect_fail_total 801
telemt_upstream_connect_attempts_per_request{bucket="1"} 128104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 801
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 127291
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1963797664 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 104364291837 (97.20 GB)
telemt_user_msgs_from_client{user="hello"} 2715855
telemt_user_msgs_to_client{user="hello"} 14108738
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```