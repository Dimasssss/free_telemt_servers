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

# Server Metrics 2026-03-06 10:12:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 7317.9 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14014
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 13519
telemt_upstream_connect_success_total 13518
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13516
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1121061424 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 7969653962 (7.42 GB)
telemt_user_msgs_from_client{user="hello"} 629408
telemt_user_msgs_to_client{user="hello"} 1330188
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 7318.2 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2196
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2084
telemt_upstream_connect_success_total 2084
telemt_upstream_connect_attempts_per_request{bucket="1"} 2084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2082
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 21681952 (20.68 MB)
telemt_user_octets_to_client{user="hello"} 662807761 (632.10 MB)
telemt_user_msgs_from_client{user="hello"} 44897
telemt_user_msgs_to_client{user="hello"} 223718
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 7316.2 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2387
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2248
telemt_upstream_connect_success_total 2248
telemt_upstream_connect_attempts_per_request{bucket="1"} 2248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2246
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 132427492 (126.29 MB)
telemt_user_octets_to_client{user="hello"} 1862964351 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 87998
telemt_user_msgs_to_client{user="hello"} 357495
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 7318.7 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4174
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 3665
telemt_upstream_connect_success_total 3653
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3651
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 37928725 (36.17 MB)
telemt_user_octets_to_client{user="hello"} 1004353455 (957.83 MB)
telemt_user_msgs_from_client{user="hello"} 56831
telemt_user_msgs_to_client{user="hello"} 271913
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 7320.4 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4495
telemt_connections_bad_total 1865
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 2434
telemt_upstream_connect_success_total 2433
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2431
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 121493190 (115.86 MB)
telemt_user_octets_to_client{user="hello"} 3397858660 (3.16 GB)
telemt_user_msgs_from_client{user="hello"} 100842
telemt_user_msgs_to_client{user="hello"} 615171
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```