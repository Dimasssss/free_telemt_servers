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

# Server Metrics 2026-03-07 16:34:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.9

telemt_uptime_seconds 433.9 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 981
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 960
telemt_upstream_connect_success_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 958
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 68311186 (65.15 MB)
telemt_user_octets_to_client{user="hello"} 944372945 (900.62 MB)
telemt_user_msgs_from_client{user="hello"} 44876
telemt_user_msgs_to_client{user="hello"} 139389
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.9

telemt_uptime_seconds 433.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187
telemt_connections_bad_total 20
telemt_upstream_connect_attempt_total 169
telemt_upstream_connect_success_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 167
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 1222546 (1.17 MB)
telemt_user_octets_to_client{user="hello"} 40093803 (38.24 MB)
telemt_user_msgs_from_client{user="hello"} 2798
telemt_user_msgs_to_client{user="hello"} 14634
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.9

telemt_uptime_seconds 433.0 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85
telemt_upstream_connect_attempt_total 87
telemt_upstream_connect_success_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 87
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 383340 (374.36 KB)
telemt_user_octets_to_client{user="hello"} 13209571 (12.60 MB)
telemt_user_msgs_from_client{user="hello"} 1140
telemt_user_msgs_to_client{user="hello"} 4789
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.9

telemt_uptime_seconds 432.7 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122
telemt_upstream_connect_attempt_total 122
telemt_upstream_connect_success_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 495553 (483.94 KB)
telemt_user_octets_to_client{user="hello"} 13141239 (12.53 MB)
telemt_user_msgs_from_client{user="hello"} 1182
telemt_user_msgs_to_client{user="hello"} 5003
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.9

telemt_uptime_seconds 433.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328
telemt_connections_bad_total 77
telemt_upstream_connect_attempt_total 250
telemt_upstream_connect_success_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 248
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 19178059 (18.29 MB)
telemt_user_octets_to_client{user="hello"} 55286768 (52.73 MB)
telemt_user_msgs_from_client{user="hello"} 9472
telemt_user_msgs_to_client{user="hello"} 13485
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```