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

# Server Metrics 2026-03-08 19:42:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 45253.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103808
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 1272
telemt_upstream_connect_attempt_total 94139
telemt_upstream_connect_success_total 94107
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 94139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94101
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 2260584877 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 58782418612 (54.75 GB)
telemt_user_msgs_from_client{user="hello"} 2279166
telemt_user_msgs_to_client{user="hello"} 3195956
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 45252.1 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24092
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 23310
telemt_upstream_connect_success_total 23305
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23301
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 754148089 (719.21 MB)
telemt_user_octets_to_client{user="hello"} 21277220570 (19.82 GB)
telemt_user_msgs_from_client{user="hello"} 897743
telemt_user_msgs_to_client{user="hello"} 5781264
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 45251.7 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14251
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12913
telemt_upstream_connect_success_total 12837
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12833
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 268751321 (256.30 MB)
telemt_user_octets_to_client{user="hello"} 5429137784 (5.06 GB)
telemt_user_msgs_from_client{user="hello"} 234902
telemt_user_msgs_to_client{user="hello"} 902582
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 45251.5 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18469
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17672
telemt_upstream_connect_success_total 17635
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17631
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 1044195075 (995.82 MB)
telemt_user_octets_to_client{user="hello"} 6257909729 (5.83 GB)
telemt_user_msgs_from_client{user="hello"} 549962
telemt_user_msgs_to_client{user="hello"} 1405213
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 45251.8 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26736
telemt_connections_bad_total 8548
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 17535
telemt_upstream_connect_success_total 17528
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17522
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 328410155 (313.20 MB)
telemt_user_octets_to_client{user="hello"} 14485610891 (13.49 GB)
telemt_user_msgs_from_client{user="hello"} 445493
telemt_user_msgs_to_client{user="hello"} 1904142
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```