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

# Server Metrics 2026-03-11 12:23:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 79050.4 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247523
telemt_connections_bad_total 3635
telemt_handshake_timeouts_total 4610
telemt_upstream_connect_attempt_total 228191
telemt_upstream_connect_success_total 228119
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 228191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 208752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 228111
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 4628481716 (4.31 GB)
telemt_user_octets_to_client{user="hello"} 124313461753 (115.78 GB)
telemt_user_msgs_from_client{user="hello"} 5219785
telemt_user_msgs_to_client{user="hello"} 9630853
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 79049.8 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96574
telemt_connections_bad_total 896
telemt_handshake_timeouts_total 3312
telemt_upstream_connect_attempt_total 88063
telemt_upstream_connect_success_total 88046
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 278
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88038
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 5168760662 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 59131879568 (55.07 GB)
telemt_user_msgs_from_client{user="hello"} 3418145
telemt_user_msgs_to_client{user="hello"} 16050143
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 79049.5 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134538
telemt_connections_bad_total 1099
telemt_handshake_timeouts_total 6697
telemt_upstream_connect_attempt_total 119208
telemt_upstream_connect_success_total 119194
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 119208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119186
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 12430916099 (11.58 GB)
telemt_user_octets_to_client{user="hello"} 89258296163 (83.13 GB)
telemt_user_msgs_from_client{user="hello"} 6152974
telemt_user_msgs_to_client{user="hello"} 17899509
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 79048.5 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146588
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 1877
telemt_upstream_connect_attempt_total 138328
telemt_upstream_connect_success_total 138005
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 138328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137997
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 7039405411 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 103521736171 (96.41 GB)
telemt_user_msgs_from_client{user="hello"} 4511786
telemt_user_msgs_to_client{user="hello"} 29983267
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 79049.7 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222347
telemt_connections_bad_total 17406
telemt_handshake_timeouts_total 3866
telemt_upstream_connect_attempt_total 180025
telemt_upstream_connect_success_total 179621
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 180025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 179613
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 4674779189 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 149271448018 (139.02 GB)
telemt_user_msgs_from_client{user="hello"} 4348258
telemt_user_msgs_to_client{user="hello"} 20483552
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 58019.1 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428
telemt_connections_bad_total 406
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```