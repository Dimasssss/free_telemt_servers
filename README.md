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

# Server Metrics 2026-03-06 04:28:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 22398.4 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73180
telemt_connections_bad_total 51934
telemt_handshake_timeouts_total 2431
telemt_upstream_connect_attempt_total 17378
telemt_upstream_connect_success_total 17376
telemt_upstream_connect_attempts_per_request{bucket="1"} 17374
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17374
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 217460693 (207.39 MB)
telemt_user_octets_to_client{user="hello"} 15503880370 (14.44 GB)
telemt_user_msgs_from_client{user="hello"} 399201
telemt_user_msgs_to_client{user="hello"} 2288732
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 22396.3 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2229
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2057
telemt_upstream_connect_success_total 2056
telemt_upstream_connect_attempts_per_request{bucket="1"} 2055
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2054
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 52484518 (50.05 MB)
telemt_user_octets_to_client{user="hello"} 974677148 (929.52 MB)
telemt_user_msgs_from_client{user="hello"} 70530
telemt_user_msgs_to_client{user="hello"} 308420
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 22396.8 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1454
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1250
telemt_upstream_connect_success_total 1250
telemt_upstream_connect_attempts_per_request{bucket="1"} 1250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1246
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 36804618 (35.10 MB)
telemt_user_octets_to_client{user="hello"} 1733091996 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46827
telemt_user_msgs_to_client{user="hello"} 348185
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 22399.8 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3003
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2499
telemt_upstream_connect_success_total 2499
telemt_upstream_connect_attempts_per_request{bucket="1"} 2499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2495
telemt_user_octets_from_client{user="hello"} 95436159 (91.02 MB)
telemt_user_octets_to_client{user="hello"} 5665029943 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 134571
telemt_user_msgs_to_client{user="hello"} 1189351
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 22399.6 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7416
telemt_connections_bad_total 4079
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 3101
telemt_upstream_connect_success_total 3101
telemt_upstream_connect_attempts_per_request{bucket="1"} 3101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3099
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 54383178 (51.86 MB)
telemt_user_octets_to_client{user="hello"} 11578298887 (10.78 GB)
telemt_user_msgs_from_client{user="hello"} 141693
telemt_user_msgs_to_client{user="hello"} 2109546
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```