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

# Server Metrics 2026-03-09 15:12:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 57159.9 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102175
telemt_connections_bad_total 1651
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 95208
telemt_upstream_connect_success_total 95170
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 95208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95164
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 2492963895 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 50324939075 (46.87 GB)
telemt_user_msgs_from_client{user="hello"} 2334675
telemt_user_msgs_to_client{user="hello"} 3308835
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 57158.4 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25528
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 23973
telemt_upstream_connect_success_total 23956
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 23973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23950
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 816491135 (778.67 MB)
telemt_user_octets_to_client{user="hello"} 13567555964 (12.64 GB)
telemt_user_msgs_from_client{user="hello"} 708749
telemt_user_msgs_to_client{user="hello"} 3710960
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 57159.5 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31965
telemt_connections_bad_total 643
telemt_handshake_timeouts_total 1548
telemt_upstream_connect_attempt_total 23173
telemt_upstream_connect_success_total 23173
telemt_upstream_connect_attempts_per_request{bucket="1"} 23173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23167
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 4355712315 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 14410045075 (13.42 GB)
telemt_user_msgs_from_client{user="hello"} 1858971
telemt_user_msgs_to_client{user="hello"} 1983379
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 57153.7 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34822
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 813
telemt_upstream_connect_attempt_total 31930
telemt_upstream_connect_success_total 31847
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 31930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31841
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1848873723 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 25504356733 (23.75 GB)
telemt_user_msgs_from_client{user="hello"} 1120584
telemt_user_msgs_to_client{user="hello"} 6464747
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 57159.2 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62512
telemt_connections_bad_total 13794
telemt_handshake_timeouts_total 1541
telemt_upstream_connect_attempt_total 44226
telemt_upstream_connect_success_total 44224
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 44226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44218
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 740908748 (706.59 MB)
telemt_user_octets_to_client{user="hello"} 44989256150 (41.90 GB)
telemt_user_msgs_from_client{user="hello"} 986525
telemt_user_msgs_to_client{user="hello"} 5488983
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```