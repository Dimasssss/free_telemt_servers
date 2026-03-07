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

# Server Metrics 2026-03-07 04:15:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 36449.7 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39963
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 37372
telemt_upstream_connect_success_total 37364
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37360
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 2312318063 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 43274331834 (40.30 GB)
telemt_user_msgs_from_client{user="hello"} 1605909
telemt_user_msgs_to_client{user="hello"} 6626600
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 36448.4 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7512
telemt_connections_bad_total 268
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 6975
telemt_upstream_connect_success_total 6972
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6968
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 232490972 (221.72 MB)
telemt_user_octets_to_client{user="hello"} 4469747622 (4.16 GB)
telemt_user_msgs_from_client{user="hello"} 239431
telemt_user_msgs_to_client{user="hello"} 1270131
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 36448.4 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3860
telemt_connections_bad_total 193
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 3514
telemt_upstream_connect_success_total 3514
telemt_upstream_connect_attempts_per_request{bucket="1"} 3514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 366
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3510
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 72941541 (69.56 MB)
telemt_user_octets_to_client{user="hello"} 2080526062 (1.94 GB)
telemt_user_msgs_from_client{user="hello"} 75645
telemt_user_msgs_to_client{user="hello"} 448821
telemt_user_unique_ips_current{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 36448.5 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5179
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 4912
telemt_upstream_connect_success_total 4905
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4901
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 104615200 (99.77 MB)
telemt_user_octets_to_client{user="hello"} 1611692102 (1.50 GB)
telemt_user_msgs_from_client{user="hello"} 95811
telemt_user_msgs_to_client{user="hello"} 445977
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 36448.8 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15657
telemt_connections_bad_total 7509
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 7875
telemt_upstream_connect_success_total 7874
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7870
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 251702431 (240.04 MB)
telemt_user_octets_to_client{user="hello"} 12413412790 (11.56 GB)
telemt_user_msgs_from_client{user="hello"} 273947
telemt_user_msgs_to_client{user="hello"} 2397642
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```