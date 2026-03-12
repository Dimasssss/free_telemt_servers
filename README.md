# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 07:21:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34575.3 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101861
telemt_connections_bad_total 2192
telemt_handshake_timeouts_total 2577
telemt_upstream_connect_attempt_total 92399
telemt_upstream_connect_success_total 91981
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 92398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91977
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 993481242 (947.46 MB)
telemt_user_octets_to_client{user="hello"} 26751388747 (24.91 GB)
telemt_user_msgs_from_client{user="hello"} 1397297
telemt_user_msgs_to_client{user="hello"} 3085155
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34563.5 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41387
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 39215
telemt_upstream_connect_success_total 39059
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 39213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39055
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 333064967 (317.64 MB)
telemt_user_octets_to_client{user="hello"} 16817657883 (15.66 GB)
telemt_user_msgs_from_client{user="hello"} 662024
telemt_user_msgs_to_client{user="hello"} 5415646
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34537.0 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60864
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 1145
telemt_upstream_connect_attempt_total 55158
telemt_upstream_connect_success_total 55026
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 55158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55022
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 5502143118 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 31684581126 (29.51 GB)
telemt_user_msgs_from_client{user="hello"} 2804348
telemt_user_msgs_to_client{user="hello"} 5664700
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34562.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66903
telemt_connections_bad_total 13898
telemt_handshake_timeouts_total 935
telemt_upstream_connect_attempt_total 49228
telemt_upstream_connect_success_total 47384
telemt_upstream_connect_fail_total 1843
telemt_upstream_connect_attempts_per_request{bucket="1"} 49227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1843
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47380
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 1503229006 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 37915844286 (35.31 GB)
telemt_user_msgs_from_client{user="hello"} 1267333
telemt_user_msgs_to_client{user="hello"} 15086307
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4754.8 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8044
telemt_connections_bad_total 887
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 6784
telemt_upstream_connect_success_total 6676
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 6784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6674
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 182616255 (174.16 MB)
telemt_user_octets_to_client{user="hello"} 5113157608 (4.76 GB)
telemt_user_msgs_from_client{user="hello"} 178203
telemt_user_msgs_to_client{user="hello"} 785760
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34563.1 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65283
telemt_connections_bad_total 1117
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 61071
telemt_upstream_connect_success_total 60848
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 61071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60844
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1044959013 (996.55 MB)
telemt_user_octets_to_client{user="hello"} 51902720192 (48.34 GB)
telemt_user_msgs_from_client{user="hello"} 1497989
telemt_user_msgs_to_client{user="hello"} 6709060
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 29
```