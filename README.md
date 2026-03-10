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

# Server Metrics 2026-03-10 03:03:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 99796.0 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180797
telemt_connections_bad_total 2365
telemt_handshake_timeouts_total 1760
telemt_upstream_connect_attempt_total 169551
telemt_upstream_connect_success_total 169496
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 169551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 169486
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 4965497736 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 103162653174 (96.08 GB)
telemt_user_msgs_from_client{user="hello"} 4484690
telemt_user_msgs_to_client{user="hello"} 6532285
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 99795.0 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56524
telemt_connections_bad_total 3069
telemt_handshake_timeouts_total 841
telemt_upstream_connect_attempt_total 49724
telemt_upstream_connect_success_total 49683
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 49724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49673
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 2143757965 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 23941062400 (22.30 GB)
telemt_user_msgs_from_client{user="hello"} 1562870
telemt_user_msgs_to_client{user="hello"} 6894963
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 99795.5 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70003
telemt_connections_bad_total 898
telemt_handshake_timeouts_total 3882
telemt_upstream_connect_attempt_total 53534
telemt_upstream_connect_success_total 53532
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53522
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 6045313815 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 54911918365 (51.14 GB)
telemt_user_msgs_from_client{user="hello"} 3431374
telemt_user_msgs_to_client{user="hello"} 8109700
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 99790.2 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75836
telemt_connections_bad_total 528
telemt_handshake_timeouts_total 1055
telemt_upstream_connect_attempt_total 70149
telemt_upstream_connect_success_total 69983
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 70149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69973
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 2304453382 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 48663793649 (45.32 GB)
telemt_user_msgs_from_client{user="hello"} 1895826
telemt_user_msgs_to_client{user="hello"} 11646678
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 99795.7 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125344
telemt_connections_bad_total 22180
telemt_handshake_timeouts_total 3013
telemt_upstream_connect_attempt_total 94984
telemt_upstream_connect_success_total 94972
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 94984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94962
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1590862457 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 87037623837 (81.06 GB)
telemt_user_msgs_from_client{user="hello"} 2148337
telemt_user_msgs_to_client{user="hello"} 11402226
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```