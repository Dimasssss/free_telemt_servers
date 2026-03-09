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

# Server Metrics 2026-03-09 01:05:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 6335.6 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5288
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 4763
telemt_upstream_connect_success_total 4761
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4759
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 55966623 (53.37 MB)
telemt_user_octets_to_client{user="hello"} 6474700142 (6.03 GB)
telemt_user_msgs_from_client{user="hello"} 132704
telemt_user_msgs_to_client{user="hello"} 224614
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 6333.8 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 369
telemt_upstream_connect_success_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 367
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 3438010 (3.28 MB)
telemt_user_octets_to_client{user="hello"} 161724961 (154.23 MB)
telemt_user_msgs_from_client{user="hello"} 9650
telemt_user_msgs_to_client{user="hello"} 36063
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 6334.4 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 408
telemt_upstream_connect_success_total 408
telemt_upstream_connect_attempts_per_request{bucket="1"} 408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 406
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16388275 (15.63 MB)
telemt_user_octets_to_client{user="hello"} 58279152 (55.58 MB)
telemt_user_msgs_from_client{user="hello"} 10071
telemt_user_msgs_to_client{user="hello"} 16588
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 6329.3 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 762
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 750
telemt_upstream_connect_success_total 750
telemt_upstream_connect_attempts_per_request{bucket="1"} 750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 748
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 5749049 (5.48 MB)
telemt_user_octets_to_client{user="hello"} 221385893 (211.13 MB)
telemt_user_msgs_from_client{user="hello"} 14510
telemt_user_msgs_to_client{user="hello"} 51452
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 6334.7 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1901
telemt_connections_bad_total 1138
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 749
telemt_upstream_connect_success_total 749
telemt_upstream_connect_attempts_per_request{bucket="1"} 749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 747
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 6765541 (6.45 MB)
telemt_user_octets_to_client{user="hello"} 1281995343 (1.19 GB)
telemt_user_msgs_from_client{user="hello"} 18880
telemt_user_msgs_to_client{user="hello"} 158099
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```