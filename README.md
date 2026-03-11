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

# Server Metrics 2026-03-11 07:01:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 59722.3 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161920
telemt_connections_bad_total 3504
telemt_handshake_timeouts_total 3952
telemt_upstream_connect_attempt_total 146375
telemt_upstream_connect_success_total 146330
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 146375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 146322
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 3475318723 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 96058944937 (89.46 GB)
telemt_user_msgs_from_client{user="hello"} 3680049
telemt_user_msgs_to_client{user="hello"} 6876670
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 59721.6 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63650
telemt_connections_bad_total 456
telemt_handshake_timeouts_total 3064
telemt_upstream_connect_attempt_total 56984
telemt_upstream_connect_success_total 56972
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 56984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56966
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 4654367111 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 49550254928 (46.15 GB)
telemt_user_msgs_from_client{user="hello"} 2860618
telemt_user_msgs_to_client{user="hello"} 11945503
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 59721.2 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85675
telemt_connections_bad_total 743
telemt_handshake_timeouts_total 4418
telemt_upstream_connect_attempt_total 75746
telemt_upstream_connect_success_total 75743
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 75746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75737
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 11846611675 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 73707394696 (68.65 GB)
telemt_user_msgs_from_client{user="hello"} 5306665
telemt_user_msgs_to_client{user="hello"} 14075311
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 59720.5 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93183
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 644
telemt_upstream_connect_attempt_total 89275
telemt_upstream_connect_success_total 89076
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 89275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89070
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2000720484 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 59636289345 (55.54 GB)
telemt_user_msgs_from_client{user="hello"} 2009515
telemt_user_msgs_to_client{user="hello"} 14675905
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 59721.6 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157874
telemt_connections_bad_total 13214
telemt_handshake_timeouts_total 1825
telemt_upstream_connect_attempt_total 125100
telemt_upstream_connect_success_total 124851
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 125100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124845
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2537043452 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 120604320351 (112.32 GB)
telemt_user_msgs_from_client{user="hello"} 2903612
telemt_user_msgs_to_client{user="hello"} 15503418
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38690.9 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```