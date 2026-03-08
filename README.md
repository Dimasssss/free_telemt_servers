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

# Server Metrics 2026-03-08 16:02:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 32002.2 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78336
telemt_connections_bad_total 5038
telemt_handshake_timeouts_total 1063
telemt_upstream_connect_attempt_total 69527
telemt_upstream_connect_success_total 69504
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 69527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69500
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1753392696 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 37454257807 (34.88 GB)
telemt_user_msgs_from_client{user="hello"} 1627755
telemt_user_msgs_to_client{user="hello"} 2258170
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 32001.6 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16558
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 15997
telemt_upstream_connect_success_total 15996
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15992
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 602442892 (574.53 MB)
telemt_user_octets_to_client{user="hello"} 15992347413 (14.89 GB)
telemt_user_msgs_from_client{user="hello"} 636459
telemt_user_msgs_to_client{user="hello"} 4294169
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 32001.3 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10426
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9792
telemt_upstream_connect_success_total 9716
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9712
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 218386210 (208.27 MB)
telemt_user_octets_to_client{user="hello"} 3218703509 (3.00 GB)
telemt_user_msgs_from_client{user="hello"} 163110
telemt_user_msgs_to_client{user="hello"} 557308
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 32001.2 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13750
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 13101
telemt_upstream_connect_success_total 13071
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13067
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 960898345 (916.38 MB)
telemt_user_octets_to_client{user="hello"} 4783622529 (4.46 GB)
telemt_user_msgs_from_client{user="hello"} 478663
telemt_user_msgs_to_client{user="hello"} 1081199
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 32001.4 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18113
telemt_connections_bad_total 5882
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 11838
telemt_upstream_connect_success_total 11834
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11830
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 236866711 (225.89 MB)
telemt_user_octets_to_client{user="hello"} 8561151129 (7.97 GB)
telemt_user_msgs_from_client{user="hello"} 291757
telemt_user_msgs_to_client{user="hello"} 1205538
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```