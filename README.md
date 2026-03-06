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

# Server Metrics 2026-03-06 08:19:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 543.5 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1220
telemt_upstream_connect_success_total 1220
telemt_upstream_connect_attempts_per_request{bucket="1"} 1220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1218
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 11779979 (11.23 MB)
telemt_user_octets_to_client{user="hello"} 888216780 (847.07 MB)
telemt_user_msgs_from_client{user="hello"} 19649
telemt_user_msgs_to_client{user="hello"} 126152
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 543.6 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 161
telemt_upstream_connect_success_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 1593795 (1.52 MB)
telemt_user_octets_to_client{user="hello"} 102393400 (97.65 MB)
telemt_user_msgs_from_client{user="hello"} 4010
telemt_user_msgs_to_client{user="hello"} 26780
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 541.7 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 74
telemt_upstream_connect_success_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 331392 (323.62 KB)
telemt_user_octets_to_client{user="hello"} 8185848 (7.81 MB)
telemt_user_msgs_from_client{user="hello"} 875
telemt_user_msgs_to_client{user="hello"} 2607
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 544.2 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135
telemt_connections_bad_total 8
telemt_upstream_connect_attempt_total 127
telemt_upstream_connect_success_total 126
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 962074 (939.53 KB)
telemt_user_octets_to_client{user="hello"} 33218632 (31.68 MB)
telemt_user_msgs_from_client{user="hello"} 2184
telemt_user_msgs_to_client{user="hello"} 10397
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 545.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419
telemt_connections_bad_total 244
telemt_upstream_connect_attempt_total 176
telemt_upstream_connect_success_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 174
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 12493458 (11.91 MB)
telemt_user_octets_to_client{user="hello"} 159304724 (151.92 MB)
telemt_user_msgs_from_client{user="hello"} 9475
telemt_user_msgs_to_client{user="hello"} 32682
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```