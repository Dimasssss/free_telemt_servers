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

# Server Metrics 2026-03-08 16:17:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 32928.9 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80090
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 1068
telemt_upstream_connect_attempt_total 71242
telemt_upstream_connect_success_total 71219
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 71242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71215
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 1767095838 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 38234681369 (35.61 GB)
telemt_user_msgs_from_client{user="hello"} 1659363
telemt_user_msgs_to_client{user="hello"} 2312750
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 32927.7 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17059
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 16490
telemt_upstream_connect_success_total 16488
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16484
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 618467410 (589.82 MB)
telemt_user_octets_to_client{user="hello"} 16838513073 (15.68 GB)
telemt_user_msgs_from_client{user="hello"} 666148
telemt_user_msgs_to_client{user="hello"} 4542764
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 32927.1 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10598
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9963
telemt_upstream_connect_success_total 9887
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9883
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 220511979 (210.30 MB)
telemt_user_octets_to_client{user="hello"} 3384145767 (3.15 GB)
telemt_user_msgs_from_client{user="hello"} 168797
telemt_user_msgs_to_client{user="hello"} 583106
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 32927.1 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14080
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 13420
telemt_upstream_connect_success_total 13390
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13386
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 970262939 (925.31 MB)
telemt_user_octets_to_client{user="hello"} 4946186389 (4.61 GB)
telemt_user_msgs_from_client{user="hello"} 486463
telemt_user_msgs_to_client{user="hello"} 1116582
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 32927.3 (9h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18637
telemt_connections_bad_total 6047
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 12192
telemt_upstream_connect_success_total 12188
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12184
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 245249098 (233.89 MB)
telemt_user_octets_to_client{user="hello"} 10627682085 (9.90 GB)
telemt_user_msgs_from_client{user="hello"} 314024
telemt_user_msgs_to_client{user="hello"} 1374195
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```