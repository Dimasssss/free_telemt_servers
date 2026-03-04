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

# Server Metrics 2026-03-04 11:27:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 61.4 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 170
telemt_upstream_connect_success_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 168
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 45184026 (43.09 MB)
telemt_user_octets_to_client{user="hello"} 123415327 (117.70 MB)
telemt_user_msgs_from_client{user="hello"} 18596
telemt_user_msgs_to_client{user="hello"} 19415
telemt_user_unique_ips_current{user="hello"} 17
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 64.2 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62
telemt_upstream_connect_attempt_total 62
telemt_upstream_connect_success_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 404446 (394.97 KB)
telemt_user_octets_to_client{user="hello"} 70432900 (67.17 MB)
telemt_user_msgs_from_client{user="hello"} 834
telemt_user_msgs_to_client{user="hello"} 16133
telemt_user_unique_ips_current{user="hello"} 5
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 63.0 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21
telemt_upstream_connect_attempt_total 23
telemt_upstream_connect_success_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 59699 (58.30 KB)
telemt_user_octets_to_client{user="hello"} 330069 (322.33 KB)
telemt_user_msgs_from_client{user="hello"} 202
telemt_user_msgs_to_client{user="hello"} 308
telemt_user_unique_ips_current{user="hello"} 6
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 60.3 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33
telemt_upstream_connect_attempt_total 35
telemt_upstream_connect_success_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 146137 (142.71 KB)
telemt_user_octets_to_client{user="hello"} 3601672 (3.43 MB)
telemt_user_msgs_from_client{user="hello"} 408
telemt_user_msgs_to_client{user="hello"} 1337
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 62.1 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31
telemt_connections_bad_total 10
telemt_upstream_connect_attempt_total 23
telemt_upstream_connect_success_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 493231 (481.67 KB)
telemt_user_octets_to_client{user="hello"} 24407141 (23.28 MB)
telemt_user_msgs_from_client{user="hello"} 865
telemt_user_msgs_to_client{user="hello"} 4800
```