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

# Server Metrics 2026-03-04 14:01:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 9299.0 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15283
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 14371
telemt_upstream_connect_success_total 14369
telemt_upstream_connect_attempts_per_request{bucket="1"} 14367
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14367
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 421912747 (402.37 MB)
telemt_user_octets_to_client{user="hello"} 13795443553 (12.85 GB)
telemt_user_msgs_from_client{user="hello"} 468812
telemt_user_msgs_to_client{user="hello"} 2166605
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 9301.8 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3358
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3125
telemt_upstream_connect_success_total 3124
telemt_upstream_connect_attempts_per_request{bucket="1"} 3123
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3122
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 170426156 (162.53 MB)
telemt_user_octets_to_client{user="hello"} 3357379908 (3.13 GB)
telemt_user_msgs_from_client{user="hello"} 130972
telemt_user_msgs_to_client{user="hello"} 1056849
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 9299.9 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1539
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1486
telemt_upstream_connect_success_total 1486
telemt_upstream_connect_attempts_per_request{bucket="1"} 1486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1484
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 64966854 (61.96 MB)
telemt_user_octets_to_client{user="hello"} 681996314 (650.40 MB)
telemt_user_msgs_from_client{user="hello"} 59456
telemt_user_msgs_to_client{user="hello"} 167525
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 9297.9 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3568
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3282
telemt_upstream_connect_success_total 3280
telemt_upstream_connect_attempts_per_request{bucket="1"} 3278
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3278
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 23213914 (22.14 MB)
telemt_user_octets_to_client{user="hello"} 1294658279 (1.21 GB)
telemt_user_msgs_from_client{user="hello"} 47366
telemt_user_msgs_to_client{user="hello"} 335639
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 9299.6 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4016
telemt_connections_bad_total 1670
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2237
telemt_upstream_connect_success_total 2236
telemt_upstream_connect_attempts_per_request{bucket="1"} 2235
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2234
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 45255736 (43.16 MB)
telemt_user_octets_to_client{user="hello"} 6810808048 (6.34 GB)
telemt_user_msgs_from_client{user="hello"} 108417
telemt_user_msgs_to_client{user="hello"} 1238518
telemt_user_unique_ips_current{user="hello"} 1
```