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

# Server Metrics 2026-03-11 03:02:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 45355.4 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118517
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 2572
telemt_upstream_connect_attempt_total 107177
telemt_upstream_connect_success_total 107139
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 107177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107133
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2917808381 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 81983915325 (76.35 GB)
telemt_user_msgs_from_client{user="hello"} 2963404
telemt_user_msgs_to_client{user="hello"} 5667097
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 45354.9 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49448
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2918
telemt_upstream_connect_attempt_total 43497
telemt_upstream_connect_success_total 43488
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43484
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2274093448 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 41647347457 (38.79 GB)
telemt_user_msgs_from_client{user="hello"} 1757504
telemt_user_msgs_to_client{user="hello"} 10127455
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 45354.7 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69877
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 61110
telemt_upstream_connect_success_total 61108
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61102
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 11743541321 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70042465039 (65.23 GB)
telemt_user_msgs_from_client{user="hello"} 5131368
telemt_user_msgs_to_client{user="hello"} 13143981
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 45353.7 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69077
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 546
telemt_upstream_connect_attempt_total 66089
telemt_upstream_connect_success_total 65932
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 66089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65926
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 1764039136 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42682900003 (39.75 GB)
telemt_user_msgs_from_client{user="hello"} 1597884
telemt_user_msgs_to_client{user="hello"} 8378517
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45355.0 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105959
telemt_connections_bad_total 10415
telemt_handshake_timeouts_total 1529
telemt_upstream_connect_attempt_total 90088
telemt_upstream_connect_success_total 89840
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 90088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89836
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2209996255 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 79281446855 (73.84 GB)
telemt_user_msgs_from_client{user="hello"} 2278145
telemt_user_msgs_to_client{user="hello"} 10788605
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24324.5 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```