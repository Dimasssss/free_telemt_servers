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

# Server Metrics 2026-03-08 07:22:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 852.8 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1380
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1357
telemt_upstream_connect_success_total 1356
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1354
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 29912029 (28.53 MB)
telemt_user_octets_to_client{user="hello"} 492380285 (469.57 MB)
telemt_user_msgs_from_client{user="hello"} 36908
telemt_user_msgs_to_client{user="hello"} 41282
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 851.6 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 229
telemt_upstream_connect_success_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 227
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 2910169 (2.78 MB)
telemt_user_octets_to_client{user="hello"} 174774405 (166.68 MB)
telemt_user_msgs_from_client{user="hello"} 6343
telemt_user_msgs_to_client{user="hello"} 40741
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 851.4 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 267
telemt_upstream_connect_success_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 265
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1188298 (1.13 MB)
telemt_user_octets_to_client{user="hello"} 159251619 (151.87 MB)
telemt_user_msgs_from_client{user="hello"} 3160
telemt_user_msgs_to_client{user="hello"} 19604
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 851.2 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 330
telemt_upstream_connect_success_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 328
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 21467991 (20.47 MB)
telemt_user_octets_to_client{user="hello"} 57903163 (55.22 MB)
telemt_user_msgs_from_client{user="hello"} 4985
telemt_user_msgs_to_client{user="hello"} 17541
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 851.5 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647
telemt_connections_bad_total 153
telemt_upstream_connect_attempt_total 492
telemt_upstream_connect_success_total 492
telemt_upstream_connect_attempts_per_request{bucket="1"} 492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 490
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 2990269 (2.85 MB)
telemt_user_octets_to_client{user="hello"} 158654307 (151.30 MB)
telemt_user_msgs_from_client{user="hello"} 7054
telemt_user_msgs_to_client{user="hello"} 23611
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```