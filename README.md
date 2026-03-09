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

# Server Metrics 2026-03-09 00:14:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 3278.4 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2848
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 162
telemt_upstream_connect_attempt_total 2368
telemt_upstream_connect_success_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 2368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2366
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 23887930 (22.78 MB)
telemt_user_octets_to_client{user="hello"} 2644267695 (2.46 GB)
telemt_user_msgs_from_client{user="hello"} 59683
telemt_user_msgs_to_client{user="hello"} 102243
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 3276.7 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 224
telemt_upstream_connect_success_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 222
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 1635394 (1.56 MB)
telemt_user_octets_to_client{user="hello"} 45406514 (43.30 MB)
telemt_user_msgs_from_client{user="hello"} 4436
telemt_user_msgs_to_client{user="hello"} 13620
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 3277.1 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271
telemt_connections_bad_total 27
telemt_upstream_connect_attempt_total 241
telemt_upstream_connect_success_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 239
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 15694544 (14.97 MB)
telemt_user_octets_to_client{user="hello"} 23161840 (22.09 MB)
telemt_user_msgs_from_client{user="hello"} 8180
telemt_user_msgs_to_client{user="hello"} 8243
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 3272.0 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 419
telemt_upstream_connect_success_total 419
telemt_upstream_connect_attempts_per_request{bucket="1"} 419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 417
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 2440335 (2.33 MB)
telemt_user_octets_to_client{user="hello"} 118001445 (112.53 MB)
telemt_user_msgs_from_client{user="hello"} 6293
telemt_user_msgs_to_client{user="hello"} 25708
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 3277.5 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918
telemt_connections_bad_total 587
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 325
telemt_upstream_connect_success_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 323
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 4849420 (4.62 MB)
telemt_user_octets_to_client{user="hello"} 1092870619 (1.02 GB)
telemt_user_msgs_from_client{user="hello"} 13702
telemt_user_msgs_to_client{user="hello"} 134693
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```