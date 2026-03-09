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

# Server Metrics 2026-03-09 12:49:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 48578.6 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77589
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 869
telemt_upstream_connect_attempt_total 72733
telemt_upstream_connect_success_total 72708
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 72733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72702
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1817995412 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 36267835557 (33.78 GB)
telemt_user_msgs_from_client{user="hello"} 1741495
telemt_user_msgs_to_client{user="hello"} 2295419
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 48577.0 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17244
telemt_connections_bad_total 196
telemt_handshake_timeouts_total 222
telemt_upstream_connect_attempt_total 16283
telemt_upstream_connect_success_total 16279
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 16283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16273
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 489134360 (466.47 MB)
telemt_user_octets_to_client{user="hello"} 10642333227 (9.91 GB)
telemt_user_msgs_from_client{user="hello"} 491028
telemt_user_msgs_to_client{user="hello"} 2785924
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 48577.9 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19077
telemt_connections_bad_total 183
telemt_handshake_timeouts_total 1409
telemt_upstream_connect_attempt_total 13157
telemt_upstream_connect_success_total 13157
telemt_upstream_connect_attempts_per_request{bucket="1"} 13157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13151
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 4262212984 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 5987165418 (5.58 GB)
telemt_user_msgs_from_client{user="hello"} 1667591
telemt_user_msgs_to_client{user="hello"} 1103096
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 48572.5 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20248
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 18360
telemt_upstream_connect_success_total 18326
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 18360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18320
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 302101666 (288.11 MB)
telemt_user_octets_to_client{user="hello"} 13264158730 (12.35 GB)
telemt_user_msgs_from_client{user="hello"} 348602
telemt_user_msgs_to_client{user="hello"} 3639360
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 48577.9 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42660
telemt_connections_bad_total 11961
telemt_handshake_timeouts_total 1114
telemt_upstream_connect_attempt_total 27610
telemt_upstream_connect_success_total 27608
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 27610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27602
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 533465049 (508.75 MB)
telemt_user_octets_to_client{user="hello"} 31947030845 (29.75 GB)
telemt_user_msgs_from_client{user="hello"} 665670
telemt_user_msgs_to_client{user="hello"} 3811732
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```