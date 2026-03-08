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

# Server Metrics 2026-03-08 23:33:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 832.8 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 738
telemt_upstream_connect_success_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 736
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 10436708 (9.95 MB)
telemt_user_octets_to_client{user="hello"} 1134427289 (1.06 GB)
telemt_user_msgs_from_client{user="hello"} 27924
telemt_user_msgs_to_client{user="hello"} 48202
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 830.9 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56
telemt_upstream_connect_attempt_total 57
telemt_upstream_connect_success_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 223963 (218.71 KB)
telemt_user_octets_to_client{user="hello"} 2172644 (2.07 MB)
telemt_user_msgs_from_client{user="hello"} 717
telemt_user_msgs_to_client{user="hello"} 1708
telemt_user_unique_ips_current{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 831.5 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71
telemt_upstream_connect_attempt_total 73
telemt_upstream_connect_success_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 308963 (301.72 KB)
telemt_user_octets_to_client{user="hello"} 7149232 (6.82 MB)
telemt_user_msgs_from_client{user="hello"} 750
telemt_user_msgs_to_client{user="hello"} 2353
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 826.2 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161
telemt_upstream_connect_attempt_total 162
telemt_upstream_connect_success_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 415773 (406.03 KB)
telemt_user_octets_to_client{user="hello"} 26677744 (25.44 MB)
telemt_user_msgs_from_client{user="hello"} 1162
telemt_user_msgs_to_client{user="hello"} 6817
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 831.8 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 87
telemt_upstream_connect_success_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 87
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 3487550 (3.33 MB)
telemt_user_octets_to_client{user="hello"} 983698904 (938.13 MB)
telemt_user_msgs_from_client{user="hello"} 9936
telemt_user_msgs_to_client{user="hello"} 105857
telemt_user_unique_ips_current{user="hello"} 5
```