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

# Server Metrics 2026-03-10 22:21:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28546.8 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94106
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 2197
telemt_upstream_connect_attempt_total 84436
telemt_upstream_connect_success_total 84404
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 84436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84400
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2541453997 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 66896277858 (62.30 GB)
telemt_user_msgs_from_client{user="hello"} 2438373
telemt_user_msgs_to_client{user="hello"} 4393802
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28546.2 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35827
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 722
telemt_upstream_connect_attempt_total 32634
telemt_upstream_connect_success_total 32625
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32621
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 1672468396 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 33922835532 (31.59 GB)
telemt_user_msgs_from_client{user="hello"} 1347043
telemt_user_msgs_to_client{user="hello"} 8563118
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28546.2 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58320
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 3979
telemt_upstream_connect_attempt_total 50597
telemt_upstream_connect_success_total 50595
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50591
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 769211132 (733.58 MB)
telemt_user_octets_to_client{user="hello"} 46937237117 (43.71 GB)
telemt_user_msgs_from_client{user="hello"} 1072888
telemt_user_msgs_to_client{user="hello"} 7075945
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28544.9 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53428
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 51299
telemt_upstream_connect_success_total 51156
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 51299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51152
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 820075265 (782.08 MB)
telemt_user_octets_to_client{user="hello"} 37093622048 (34.55 GB)
telemt_user_msgs_from_client{user="hello"} 1109085
telemt_user_msgs_to_client{user="hello"} 7081302
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28546.3 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77846
telemt_connections_bad_total 7099
telemt_handshake_timeouts_total 1453
telemt_upstream_connect_attempt_total 66232
telemt_upstream_connect_success_total 65988
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 66232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65984
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 2034770790 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 51011872208 (47.51 GB)
telemt_user_msgs_from_client{user="hello"} 1865270
telemt_user_msgs_to_client{user="hello"} 7484039
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7515.7 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```