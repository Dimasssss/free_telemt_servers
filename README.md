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

# Server Metrics 2026-03-10 14:19:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 140353.3 (38h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324091
telemt_connections_bad_total 3720
telemt_handshake_timeouts_total 3405
telemt_upstream_connect_attempt_total 303371
telemt_upstream_connect_success_total 303209
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 303371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 280282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 303195
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 6905300737 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 199365998091 (185.67 GB)
telemt_user_msgs_from_client{user="hello"} 7224317
telemt_user_msgs_to_client{user="hello"} 11890931
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 140352.2 (38h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100658
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1378
telemt_upstream_connect_attempt_total 90780
telemt_upstream_connect_success_total 90734
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 90780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90720
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2902745698 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 38590595322 (35.94 GB)
telemt_user_msgs_from_client{user="hello"} 2372868
telemt_user_msgs_to_client{user="hello"} 11177225
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 140352.8 (38h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144370
telemt_connections_bad_total 1242
telemt_handshake_timeouts_total 7068
telemt_upstream_connect_attempt_total 108594
telemt_upstream_connect_success_total 108591
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 108594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108577
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 6726281298 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 69760884362 (64.97 GB)
telemt_user_msgs_from_client{user="hello"} 4617220
telemt_user_msgs_to_client{user="hello"} 11884824
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 140347.7 (38h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147943
telemt_connections_bad_total 1089
telemt_handshake_timeouts_total 3070
telemt_upstream_connect_attempt_total 136775
telemt_upstream_connect_success_total 136465
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 136775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136451
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 5085130508 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 95795994977 (89.22 GB)
telemt_user_msgs_from_client{user="hello"} 3940891
telemt_user_msgs_to_client{user="hello"} 21688760
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 140352.8 (38h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218683
telemt_connections_bad_total 31350
telemt_handshake_timeouts_total 6275
telemt_upstream_connect_attempt_total 171997
telemt_upstream_connect_success_total 171035
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 171997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 171021
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 3664044276 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 121030063084 (112.72 GB)
telemt_user_msgs_from_client{user="hello"} 3902449
telemt_user_msgs_to_client{user="hello"} 16718470
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 28
```