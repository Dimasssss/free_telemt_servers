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

# Server Metrics 2026-03-10 11:14:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 129295.4 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279289
telemt_connections_bad_total 3454
telemt_handshake_timeouts_total 3008
telemt_upstream_connect_attempt_total 261021
telemt_upstream_connect_success_total 260873
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 261021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 240901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 260861
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 6333480044 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 165233138283 (153.89 GB)
telemt_user_msgs_from_client{user="hello"} 6332818
telemt_user_msgs_to_client{user="hello"} 10111950
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 129294.1 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84905
telemt_connections_bad_total 3266
telemt_handshake_timeouts_total 1188
telemt_upstream_connect_attempt_total 76008
telemt_upstream_connect_success_total 75965
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 76008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 407
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75951
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 2429304547 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 33981853950 (31.65 GB)
telemt_user_msgs_from_client{user="hello"} 2016587
telemt_user_msgs_to_client{user="hello"} 9758472
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 129294.6 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120502
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 6118
telemt_upstream_connect_attempt_total 87089
telemt_upstream_connect_success_total 87087
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 87089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87075
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 6435168969 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 64640260254 (60.20 GB)
telemt_user_msgs_from_client{user="hello"} 4215466
telemt_user_msgs_to_client{user="hello"} 10606002
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 129289.4 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123189
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 1364
telemt_upstream_connect_attempt_total 114839
telemt_upstream_connect_success_total 114590
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 114839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 275
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114578
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 3120705133 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 81393385424 (75.80 GB)
telemt_user_msgs_from_client{user="hello"} 2903435
telemt_user_msgs_to_client{user="hello"} 18678252
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 129294.8 (35h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187188
telemt_connections_bad_total 28199
telemt_handshake_timeouts_total 4705
telemt_upstream_connect_attempt_total 146392
telemt_upstream_connect_success_total 145432
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 146392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 145418
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 3275602126 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 110787911917 (103.18 GB)
telemt_user_msgs_from_client{user="hello"} 3390891
telemt_user_msgs_to_client{user="hello"} 15045468
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 28
```