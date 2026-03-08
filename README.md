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

# Server Metrics 2026-03-08 23:38:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 1138.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1109
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 920
telemt_upstream_connect_success_total 920
telemt_upstream_connect_attempts_per_request{bucket="1"} 920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 918
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 12834316 (12.24 MB)
telemt_user_octets_to_client{user="hello"} 1360033961 (1.27 GB)
telemt_user_msgs_from_client{user="hello"} 33583
telemt_user_msgs_to_client{user="hello"} 57702
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 1136.8 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 102
telemt_upstream_connect_success_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 833171 (813.64 KB)
telemt_user_octets_to_client{user="hello"} 27276249 (26.01 MB)
telemt_user_msgs_from_client{user="hello"} 1867
telemt_user_msgs_to_client{user="hello"} 6285
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 1137.6 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 81
telemt_upstream_connect_success_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 323098 (315.53 KB)
telemt_user_octets_to_client{user="hello"} 7356491 (7.02 MB)
telemt_user_msgs_from_client{user="hello"} 792
telemt_user_msgs_to_client{user="hello"} 2479
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 1132.3 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194
telemt_upstream_connect_attempt_total 193
telemt_upstream_connect_success_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 191
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 657506 (642.10 KB)
telemt_user_octets_to_client{user="hello"} 27479713 (26.21 MB)
telemt_user_msgs_from_client{user="hello"} 1976
telemt_user_msgs_to_client{user="hello"} 7496
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 1137.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 117
telemt_upstream_connect_success_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 3594542 (3.43 MB)
telemt_user_octets_to_client{user="hello"} 988717528 (942.91 MB)
telemt_user_msgs_from_client{user="hello"} 10194
telemt_user_msgs_to_client{user="hello"} 106668
telemt_user_unique_ips_current{user="hello"} 5
```