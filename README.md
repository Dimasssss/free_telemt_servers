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

# Server Metrics 2026-03-10 09:32:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 123158.3 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254983
telemt_connections_bad_total 3432
telemt_handshake_timeouts_total 2616
telemt_upstream_connect_attempt_total 238790
telemt_upstream_connect_success_total 238710
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 238790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 220361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 238698
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 5975088389 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 144643498142 (134.71 GB)
telemt_user_msgs_from_client{user="hello"} 5812277
telemt_user_msgs_to_client{user="hello"} 9116188
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 123157.0 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76740
telemt_connections_bad_total 3249
telemt_handshake_timeouts_total 1029
telemt_upstream_connect_attempt_total 68503
telemt_upstream_connect_success_total 68461
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 68503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68449
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2317517757 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 32074629369 (29.87 GB)
telemt_user_msgs_from_client{user="hello"} 1891320
telemt_user_msgs_to_client{user="hello"} 9150217
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 123157.5 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110308
telemt_connections_bad_total 1143
telemt_handshake_timeouts_total 5397
telemt_upstream_connect_attempt_total 78071
telemt_upstream_connect_success_total 78069
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 78071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78057
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 6348130327 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 61092171350 (56.90 GB)
telemt_user_msgs_from_client{user="hello"} 4035154
telemt_user_msgs_to_client{user="hello"} 9800809
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 123152.2 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111603
telemt_connections_bad_total 953
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 103793
telemt_upstream_connect_success_total 103564
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 103793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103552
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2934591614 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 77164135849 (71.86 GB)
telemt_user_msgs_from_client{user="hello"} 2686708
telemt_user_msgs_to_client{user="hello"} 17618148
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 123157.6 (34h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170523
telemt_connections_bad_total 27047
telemt_handshake_timeouts_total 4316
telemt_upstream_connect_attempt_total 131970
telemt_upstream_connect_success_total 131164
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 131970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131152
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2015790823 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 105082272907 (97.87 GB)
telemt_user_msgs_from_client{user="hello"} 2777761
telemt_user_msgs_to_client{user="hello"} 14241319
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```