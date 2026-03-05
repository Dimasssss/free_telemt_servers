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

# Server Metrics 2026-03-05 22:19:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 237.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3884
telemt_connections_bad_total 3544
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 204
telemt_upstream_connect_success_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 202
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 1696709 (1.62 MB)
telemt_user_octets_to_client{user="hello"} 107779409 (102.79 MB)
telemt_user_msgs_from_client{user="hello"} 4917
telemt_user_msgs_to_client{user="hello"} 17859
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 235.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50
telemt_upstream_connect_attempt_total 51
telemt_upstream_connect_success_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 466567 (455.63 KB)
telemt_user_octets_to_client{user="hello"} 59809685 (57.04 MB)
telemt_user_msgs_from_client{user="hello"} 1265
telemt_user_msgs_to_client{user="hello"} 14560
telemt_user_unique_ips_current{user="hello"} 8
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 235.8 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24
telemt_upstream_connect_attempt_total 26
telemt_upstream_connect_success_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 76188 (74.40 KB)
telemt_user_octets_to_client{user="hello"} 2508472 (2.39 MB)
telemt_user_msgs_from_client{user="hello"} 190
telemt_user_msgs_to_client{user="hello"} 811
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 238.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69
telemt_upstream_connect_attempt_total 69
telemt_upstream_connect_success_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 822391 (803.12 KB)
telemt_user_octets_to_client{user="hello"} 93739700 (89.40 MB)
telemt_user_msgs_from_client{user="hello"} 2384
telemt_user_msgs_to_client{user="hello"} 21100
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 238.0 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77
telemt_connections_bad_total 51
telemt_upstream_connect_attempt_total 28
telemt_upstream_connect_success_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 1656989 (1.58 MB)
telemt_user_octets_to_client{user="hello"} 498459587 (475.37 MB)
telemt_user_msgs_from_client{user="hello"} 4683
telemt_user_msgs_to_client{user="hello"} 84312
telemt_user_unique_ips_current{user="hello"} 3
```