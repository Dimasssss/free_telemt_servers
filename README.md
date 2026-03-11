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

# Server Metrics 2026-03-11 03:07:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 45661.2 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119085
telemt_connections_bad_total 3363
telemt_handshake_timeouts_total 2577
telemt_upstream_connect_attempt_total 107700
telemt_upstream_connect_success_total 107661
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 107700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107655
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2925850996 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 82039050637 (76.40 GB)
telemt_user_msgs_from_client{user="hello"} 2969410
telemt_user_msgs_to_client{user="hello"} 5675321
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 45660.2 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49684
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 2919
telemt_upstream_connect_attempt_total 43723
telemt_upstream_connect_success_total 43714
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43710
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2286796973 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 41894294988 (39.02 GB)
telemt_user_msgs_from_client{user="hello"} 1766391
telemt_user_msgs_to_client{user="hello"} 10167865
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 45660.0 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70030
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 61256
telemt_upstream_connect_success_total 61254
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61248
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 11743866751 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70046206635 (65.24 GB)
telemt_user_msgs_from_client{user="hello"} 5132063
telemt_user_msgs_to_client{user="hello"} 13145812
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 45659.1 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69486
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 549
telemt_upstream_connect_attempt_total 66480
telemt_upstream_connect_success_total 66323
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 66480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66317
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 1765227730 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42698916794 (39.77 GB)
telemt_user_msgs_from_client{user="hello"} 1600452
telemt_user_msgs_to_client{user="hello"} 8386246
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45660.2 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106754
telemt_connections_bad_total 10469
telemt_handshake_timeouts_total 1531
telemt_upstream_connect_attempt_total 90803
telemt_upstream_connect_success_total 90555
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 90803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90551
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2216474656 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 80811100866 (75.26 GB)
telemt_user_msgs_from_client{user="hello"} 2295116
telemt_user_msgs_to_client{user="hello"} 10950191
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24629.7 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```