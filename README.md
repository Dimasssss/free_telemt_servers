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

# Server Metrics 2026-03-10 14:39:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 806.7 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4214
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 3962
telemt_upstream_connect_success_total 3962
telemt_upstream_connect_attempts_per_request{bucket="1"} 3962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3960
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 54665350 (52.13 MB)
telemt_user_octets_to_client{user="hello"} 2338833443 (2.18 GB)
telemt_user_msgs_from_client{user="hello"} 64998
telemt_user_msgs_to_client{user="hello"} 116958
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 805.6 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1236
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 1116
telemt_upstream_connect_success_total 1115
telemt_upstream_connect_attempts_per_request{bucket="1"} 1115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1113
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 19255183 (18.36 MB)
telemt_user_octets_to_client{user="hello"} 826288423 (788.01 MB)
telemt_user_msgs_from_client{user="hello"} 28635
telemt_user_msgs_to_client{user="hello"} 237404
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 805.3 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1854
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 1714
telemt_upstream_connect_success_total 1714
telemt_upstream_connect_attempts_per_request{bucket="1"} 1714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1712
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 15738438 (15.01 MB)
telemt_user_octets_to_client{user="hello"} 127038306 (121.15 MB)
telemt_user_msgs_from_client{user="hello"} 21511
telemt_user_msgs_to_client{user="hello"} 48257
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 804.3 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1864
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 1702
telemt_upstream_connect_success_total 1696
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1694
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 11422821 (10.89 MB)
telemt_user_octets_to_client{user="hello"} 843291549 (804.23 MB)
telemt_user_msgs_from_client{user="hello"} 26346
telemt_user_msgs_to_client{user="hello"} 165611
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 805.4 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2970
telemt_connections_bad_total 387
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 2461
telemt_upstream_connect_success_total 2461
telemt_upstream_connect_attempts_per_request{bucket="1"} 2461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2459
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 18824645 (17.95 MB)
telemt_user_octets_to_client{user="hello"} 1113677062 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 40157
telemt_user_msgs_to_client{user="hello"} 152310
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 33
```