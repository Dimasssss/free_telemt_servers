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

# Server Metrics 2026-03-08 07:17:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 544.5 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 935
telemt_upstream_connect_success_total 934
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 932
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 24493542 (23.36 MB)
telemt_user_octets_to_client{user="hello"} 296167034 (282.45 MB)
telemt_user_msgs_from_client{user="hello"} 26732
telemt_user_msgs_to_client{user="hello"} 27347
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 543.8 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 132
telemt_upstream_connect_success_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1285014 (1.23 MB)
telemt_user_octets_to_client{user="hello"} 74048513 (70.62 MB)
telemt_user_msgs_from_client{user="hello"} 2688
telemt_user_msgs_to_client{user="hello"} 19238
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 543.5 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 162
telemt_upstream_connect_success_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 396535 (387.24 KB)
telemt_user_octets_to_client{user="hello"} 33059485 (31.53 MB)
telemt_user_msgs_from_client{user="hello"} 1072
telemt_user_msgs_to_client{user="hello"} 5518
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 543.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 165
telemt_upstream_connect_success_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 911820 (890.45 KB)
telemt_user_octets_to_client{user="hello"} 32113818 (30.63 MB)
telemt_user_msgs_from_client{user="hello"} 2012
telemt_user_msgs_to_client{user="hello"} 8581
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 543.6 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404
telemt_connections_bad_total 99
telemt_upstream_connect_attempt_total 305
telemt_upstream_connect_success_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 303
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 2317023 (2.21 MB)
telemt_user_octets_to_client{user="hello"} 116213161 (110.83 MB)
telemt_user_msgs_from_client{user="hello"} 5356
telemt_user_msgs_to_client{user="hello"} 17198
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```