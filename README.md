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

# Server Metrics 2026-03-08 15:56:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 31694.6 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77604
telemt_connections_bad_total 5038
telemt_handshake_timeouts_total 1059
telemt_upstream_connect_attempt_total 68823
telemt_upstream_connect_success_total 68800
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 68823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68796
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1746776288 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 37172063889 (34.62 GB)
telemt_user_msgs_from_client{user="hello"} 1613924
telemt_user_msgs_to_client{user="hello"} 2236062
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 31693.7 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16386
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 15830
telemt_upstream_connect_success_total 15829
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15825
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 598346213 (570.63 MB)
telemt_user_octets_to_client{user="hello"} 15623271505 (14.55 GB)
telemt_user_msgs_from_client{user="hello"} 625943
telemt_user_msgs_to_client{user="hello"} 4190743
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 31693.4 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10393
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9759
telemt_upstream_connect_success_total 9683
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9679
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 218292180 (208.18 MB)
telemt_user_octets_to_client{user="hello"} 3216514611 (3.00 GB)
telemt_user_msgs_from_client{user="hello"} 162881
telemt_user_msgs_to_client{user="hello"} 556533
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 31693.3 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13577
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 12932
telemt_upstream_connect_success_total 12902
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12898
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 960170549 (915.69 MB)
telemt_user_octets_to_client{user="hello"} 4762799440 (4.44 GB)
telemt_user_msgs_from_client{user="hello"} 477053
telemt_user_msgs_to_client{user="hello"} 1074187
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 31693.6 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17931
telemt_connections_bad_total 5827
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 11715
telemt_upstream_connect_success_total 11711
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11707
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 236163009 (225.22 MB)
telemt_user_octets_to_client{user="hello"} 8528762747 (7.94 GB)
telemt_user_msgs_from_client{user="hello"} 290217
telemt_user_msgs_to_client{user="hello"} 1200217
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```