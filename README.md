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

# Server Metrics 2026-03-10 13:02:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 135745.2 (37h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305341
telemt_connections_bad_total 3469
telemt_handshake_timeouts_total 3115
telemt_upstream_connect_attempt_total 286031
telemt_upstream_connect_success_total 285877
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 286031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 264391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 285863
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 6663449175 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 189739548961 (176.71 GB)
telemt_user_msgs_from_client{user="hello"} 6888602
telemt_user_msgs_to_client{user="hello"} 11208509
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 135743.9 (37h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94031
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 1277
telemt_upstream_connect_attempt_total 84638
telemt_upstream_connect_success_total 84594
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 84638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84580
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2793667660 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 35682470460 (33.23 GB)
telemt_user_msgs_from_client{user="hello"} 2245934
telemt_user_msgs_to_client{user="hello"} 10344432
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 135744.4 (37h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133405
telemt_connections_bad_total 1227
telemt_handshake_timeouts_total 6353
telemt_upstream_connect_attempt_total 99024
telemt_upstream_connect_success_total 99021
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 99024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99009
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 6636830552 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 67476976286 (62.84 GB)
telemt_user_msgs_from_client{user="hello"} 4438546
telemt_user_msgs_to_client{user="hello"} 11304908
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 135739.3 (37h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138293
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 2917
telemt_upstream_connect_attempt_total 127602
telemt_upstream_connect_success_total 127322
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 127602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 81
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 323
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 127308
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 4636370149 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 88328709349 (82.26 GB)
telemt_user_msgs_from_client{user="hello"} 3625435
telemt_user_msgs_to_client{user="hello"} 20128346
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 135744.6 (37h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204395
telemt_connections_bad_total 30352
telemt_handshake_timeouts_total 5567
telemt_upstream_connect_attempt_total 159915
telemt_upstream_connect_success_total 158953
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 159915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 158939
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 3467819985 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 116851857918 (108.83 GB)
telemt_user_msgs_from_client{user="hello"} 3670906
telemt_user_msgs_to_client{user="hello"} 15916910
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```