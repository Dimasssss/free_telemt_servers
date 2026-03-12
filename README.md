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

# Server Metrics 2026-03-12 01:12:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12471.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23821
telemt_connections_bad_total 1839
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 21028
telemt_upstream_connect_success_total 21022
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21020
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 231254271 (220.54 MB)
telemt_user_octets_to_client{user="hello"} 7275178745 (6.78 GB)
telemt_user_msgs_from_client{user="hello"} 389016
telemt_user_msgs_to_client{user="hello"} 976588
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12460.1 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9899
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9496
telemt_upstream_connect_success_total 9496
telemt_upstream_connect_attempts_per_request{bucket="1"} 9496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9494
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 65083114 (62.07 MB)
telemt_user_octets_to_client{user="hello"} 3342823841 (3.11 GB)
telemt_user_msgs_from_client{user="hello"} 162140
telemt_user_msgs_to_client{user="hello"} 1081982
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12433.7 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16577
telemt_connections_bad_total 282
telemt_handshake_timeouts_total 864
telemt_upstream_connect_attempt_total 13655
telemt_upstream_connect_success_total 13655
telemt_upstream_connect_attempts_per_request{bucket="1"} 13655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13653
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 1070132029 (1020.56 MB)
telemt_user_octets_to_client{user="hello"} 7303482927 (6.80 GB)
telemt_user_msgs_from_client{user="hello"} 607593
telemt_user_msgs_to_client{user="hello"} 1649026
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12459.0 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16727
telemt_connections_bad_total 3860
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 11597
telemt_upstream_connect_success_total 11586
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 11597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11584
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 89059449 (84.93 MB)
telemt_user_octets_to_client{user="hello"} 5244189380 (4.88 GB)
telemt_user_msgs_from_client{user="hello"} 178742
telemt_user_msgs_to_client{user="hello"} 1968652
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12459.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13122
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 121
telemt_upstream_connect_attempt_total 11850
telemt_upstream_connect_success_total 11850
telemt_upstream_connect_attempts_per_request{bucket="1"} 11850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11848
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 182431032 (173.98 MB)
telemt_user_octets_to_client{user="hello"} 18222520327 (16.97 GB)
telemt_user_msgs_from_client{user="hello"} 326042
telemt_user_msgs_to_client{user="hello"} 1670348
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 18
```