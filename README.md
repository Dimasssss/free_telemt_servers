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

# Server Metrics 2026-03-05 00:55:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 48509.4 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69434
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 1558
telemt_upstream_connect_attempt_total 62782
telemt_upstream_connect_success_total 62767
telemt_upstream_connect_attempts_per_request{bucket="1"} 62752
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62761
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 2351602455 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 48023397352 (44.73 GB)
telemt_user_msgs_from_client{user="hello"} 2026021
telemt_user_msgs_to_client{user="hello"} 7653707
telemt_user_unique_ips_current{user="hello"} 8
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 48512.3 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15965
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11456
telemt_upstream_connect_success_total 11454
telemt_upstream_connect_attempts_per_request{bucket="1"} 11452
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11448
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1056565546 (1007.62 MB)
telemt_user_octets_to_client{user="hello"} 11093806675 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 650455
telemt_user_msgs_to_client{user="hello"} 3738026
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 48510.7 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11331
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 7432
telemt_upstream_connect_success_total 7432
telemt_upstream_connect_attempts_per_request{bucket="1"} 7432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7426
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308457513 (294.17 MB)
telemt_user_octets_to_client{user="hello"} 5260584296 (4.90 GB)
telemt_user_msgs_from_client{user="hello"} 269541
telemt_user_msgs_to_client{user="hello"} 1137122
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 48509.1 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16226
telemt_connections_bad_total 690
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 14125
telemt_upstream_connect_success_total 14120
telemt_upstream_connect_attempts_per_request{bucket="1"} 14115
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14114
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 396133262 (377.78 MB)
telemt_user_octets_to_client{user="hello"} 5648813745 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 308842
telemt_user_msgs_to_client{user="hello"} 1416211
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 48510.2 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18944
telemt_connections_bad_total 8734
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9839
telemt_upstream_connect_success_total 9835
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9833
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9829
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 519896024 (495.81 MB)
telemt_user_octets_to_client{user="hello"} 22395742965 (20.86 GB)
telemt_user_msgs_from_client{user="hello"} 560967
telemt_user_msgs_to_client{user="hello"} 4250908
```