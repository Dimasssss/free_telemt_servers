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

# Server Metrics 2026-03-09 17:10:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 64214.6 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119058
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 989
telemt_upstream_connect_attempt_total 111555
telemt_upstream_connect_success_total 111515
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 111555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111509
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 2975851026 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 61260145436 (57.05 GB)
telemt_user_msgs_from_client{user="hello"} 2784999
telemt_user_msgs_to_client{user="hello"} 3934022
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 64213.6 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32559
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 30689
telemt_upstream_connect_success_total 30671
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 30689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30665
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1012690354 (965.78 MB)
telemt_user_octets_to_client{user="hello"} 16258928389 (15.14 GB)
telemt_user_msgs_from_client{user="hello"} 870862
telemt_user_msgs_to_client{user="hello"} 4543845
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 64214.1 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41526
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1837
telemt_upstream_connect_attempt_total 31894
telemt_upstream_connect_success_total 31894
telemt_upstream_connect_attempts_per_request{bucket="1"} 31894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31888
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 4486927602 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 19043610501 (17.74 GB)
telemt_user_msgs_from_client{user="hello"} 2018361
telemt_user_msgs_to_client{user="hello"} 2582588
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 64208.7 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47015
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 889
telemt_upstream_connect_attempt_total 43015
telemt_upstream_connect_success_total 42912
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 43015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42904
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1984690975 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 32243373212 (30.03 GB)
telemt_user_msgs_from_client{user="hello"} 1324070
telemt_user_msgs_to_client{user="hello"} 8159686
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 64214.2 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76242
telemt_connections_bad_total 15473
telemt_handshake_timeouts_total 1723
telemt_upstream_connect_attempt_total 55575
telemt_upstream_connect_success_total 55573
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55565
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 933850905 (890.59 MB)
telemt_user_octets_to_client{user="hello"} 56393118692 (52.52 GB)
telemt_user_msgs_from_client{user="hello"} 1281425
telemt_user_msgs_to_client{user="hello"} 7011062
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```