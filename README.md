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

# Server Metrics 2026-03-04 08:33:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 624.1 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1089
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1020
telemt_upstream_connect_success_total 1020
telemt_upstream_connect_attempts_per_request{bucket="1"} 1020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1018
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 11827927 (11.28 MB)
telemt_user_octets_to_client{user="hello"} 1281012384 (1.19 GB)
telemt_user_msgs_from_client{user="hello"} 30348
telemt_user_msgs_to_client{user="hello"} 213544
telemt_user_unique_ips_current{user="hello"} 8
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 635.4 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93
telemt_upstream_connect_attempt_total 92
telemt_upstream_connect_success_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 92
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 430071 (419.99 KB)
telemt_user_octets_to_client{user="hello"} 3022835 (2.88 MB)
telemt_user_msgs_from_client{user="hello"} 1045
telemt_user_msgs_to_client{user="hello"} 3189
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 620.5 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 69
telemt_upstream_connect_success_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 401046 (391.65 KB)
telemt_user_octets_to_client{user="hello"} 35443447 (33.80 MB)
telemt_user_msgs_from_client{user="hello"} 899
telemt_user_msgs_to_client{user="hello"} 6591
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 610.8 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 113
telemt_upstream_connect_success_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 601959 (587.85 KB)
telemt_user_octets_to_client{user="hello"} 16505850 (15.74 MB)
telemt_user_msgs_from_client{user="hello"} 1224
telemt_user_msgs_to_client{user="hello"} 5923
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 622.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 298
telemt_upstream_connect_success_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 296
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 3216359 (3.07 MB)
telemt_user_octets_to_client{user="hello"} 128856117 (122.89 MB)
telemt_user_msgs_from_client{user="hello"} 7034
telemt_user_msgs_to_client{user="hello"} 34607
telemt_user_unique_ips_current{user="hello"} 2
```