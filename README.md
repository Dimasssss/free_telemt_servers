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

# Server Metrics 2026-03-11 06:10:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56665.2 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150244
telemt_connections_bad_total 3496
telemt_handshake_timeouts_total 3869
telemt_upstream_connect_attempt_total 135396
telemt_upstream_connect_success_total 135352
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 135396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135346
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 3321463666 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 91871059649 (85.56 GB)
telemt_user_msgs_from_client{user="hello"} 3468065
telemt_user_msgs_to_client{user="hello"} 6478226
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 56664.6 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59531
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3022
telemt_upstream_connect_attempt_total 53029
telemt_upstream_connect_success_total 53017
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 53029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53011
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 4579368124 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 47785644120 (44.50 GB)
telemt_user_msgs_from_client{user="hello"} 2772339
telemt_user_msgs_to_client{user="hello"} 11326690
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56664.2 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80900
telemt_connections_bad_total 737
telemt_handshake_timeouts_total 4364
telemt_upstream_connect_attempt_total 71259
telemt_upstream_connect_success_total 71256
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 71259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71250
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 11807996885 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 72236947588 (67.28 GB)
telemt_user_msgs_from_client{user="hello"} 5240644
telemt_user_msgs_to_client{user="hello"} 13635396
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 56663.2 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86266
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 634
telemt_upstream_connect_attempt_total 82554
telemt_upstream_connect_success_total 82374
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 82554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82368
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1887824254 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 54781061285 (51.02 GB)
telemt_user_msgs_from_client{user="hello"} 1860518
telemt_user_msgs_to_client{user="hello"} 12791291
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56664.5 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146850
telemt_connections_bad_total 12611
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 116402
telemt_upstream_connect_success_total 116153
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 116402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116147
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2463540514 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 109745310738 (102.21 GB)
telemt_user_msgs_from_client{user="hello"} 2756687
telemt_user_msgs_to_client{user="hello"} 14579560
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35633.9 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166
telemt_connections_bad_total 146
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