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

# Server Metrics 2026-03-04 11:12:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 10166.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17226
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 15830
telemt_upstream_connect_success_total 15829
telemt_upstream_connect_attempts_per_request{bucket="1"} 15828
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15827
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 472782517 (450.88 MB)
telemt_user_octets_to_client{user="hello"} 8502616018 (7.92 GB)
telemt_user_msgs_from_client{user="hello"} 459722
telemt_user_msgs_to_client{user="hello"} 1409244
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 10177.6 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2400
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 2221
telemt_upstream_connect_success_total 2218
telemt_upstream_connect_attempts_per_request{bucket="1"} 2215
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2216
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 77986841 (74.37 MB)
telemt_user_octets_to_client{user="hello"} 1124681080 (1.05 GB)
telemt_user_msgs_from_client{user="hello"} 72172
telemt_user_msgs_to_client{user="hello"} 346054
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 10162.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1971
telemt_connections_bad_total 79
telemt_upstream_connect_attempt_total 1862
telemt_upstream_connect_success_total 1862
telemt_upstream_connect_attempts_per_request{bucket="1"} 1862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1860
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 44694312 (42.62 MB)
telemt_user_octets_to_client{user="hello"} 3336404044 (3.11 GB)
telemt_user_msgs_from_client{user="hello"} 95970
telemt_user_msgs_to_client{user="hello"} 634652
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 10152.9 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3665
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 3337
telemt_upstream_connect_success_total 3336
telemt_upstream_connect_attempts_per_request{bucket="1"} 3335
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3334
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 23412036 (22.33 MB)
telemt_user_octets_to_client{user="hello"} 1229322336 (1.14 GB)
telemt_user_msgs_from_client{user="hello"} 39994
telemt_user_msgs_to_client{user="hello"} 340552
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 10164.2 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3646
telemt_connections_bad_total 1816
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1758
telemt_upstream_connect_success_total 1758
telemt_upstream_connect_attempts_per_request{bucket="1"} 1758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1756
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 24681233 (23.54 MB)
telemt_user_octets_to_client{user="hello"} 922409455 (879.68 MB)
telemt_user_msgs_from_client{user="hello"} 48639
telemt_user_msgs_to_client{user="hello"} 229896
telemt_user_unique_ips_current{user="hello"} 4
```