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

# Server Metrics 2026-03-05 18:43:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 5290.1 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19931
telemt_connections_bad_total 13656
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 5938
telemt_upstream_connect_success_total 5937
telemt_upstream_connect_attempts_per_request{bucket="1"} 5936
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5935
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 147678053 (140.84 MB)
telemt_user_octets_to_client{user="hello"} 3469303005 (3.23 GB)
telemt_user_msgs_from_client{user="hello"} 197808
telemt_user_msgs_to_client{user="hello"} 601512
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 5294.8 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1969
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1381
telemt_upstream_connect_success_total 1381
telemt_upstream_connect_attempts_per_request{bucket="1"} 1381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1379
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 15810094 (15.08 MB)
telemt_user_octets_to_client{user="hello"} 1006831640 (960.19 MB)
telemt_user_msgs_from_client{user="hello"} 37560
telemt_user_msgs_to_client{user="hello"} 256357
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 5290.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1819
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1633
telemt_upstream_connect_success_total 1633
telemt_upstream_connect_attempts_per_request{bucket="1"} 1633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1631
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 28466951 (27.15 MB)
telemt_user_octets_to_client{user="hello"} 1657660490 (1.54 GB)
telemt_user_msgs_from_client{user="hello"} 42645
telemt_user_msgs_to_client{user="hello"} 328641
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 5288.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1933
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1885
telemt_upstream_connect_success_total 1883
telemt_upstream_connect_attempts_per_request{bucket="1"} 1881
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1881
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 20935857 (19.97 MB)
telemt_user_octets_to_client{user="hello"} 602783174 (574.86 MB)
telemt_user_msgs_from_client{user="hello"} 29474
telemt_user_msgs_to_client{user="hello"} 150238
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 5290.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2782
telemt_connections_bad_total 947
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1772
telemt_upstream_connect_success_total 1772
telemt_upstream_connect_attempts_per_request{bucket="1"} 1772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1770
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 37935846 (36.18 MB)
telemt_user_octets_to_client{user="hello"} 1274225979 (1.19 GB)
telemt_user_msgs_from_client{user="hello"} 58424
telemt_user_msgs_to_client{user="hello"} 277833
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```