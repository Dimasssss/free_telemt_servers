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

# Server Metrics 2026-03-11 10:15:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 71367.7 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211216
telemt_connections_bad_total 3615
telemt_handshake_timeouts_total 4394
telemt_upstream_connect_attempt_total 193614
telemt_upstream_connect_success_total 193553
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 193614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 176962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 193545
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 4236031730 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 113774889487 (105.96 GB)
telemt_user_msgs_from_client{user="hello"} 4600405
telemt_user_msgs_to_client{user="hello"} 8532120
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 71367.2 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82636
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3157
telemt_upstream_connect_attempt_total 74814
telemt_upstream_connect_success_total 74798
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 74814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74790
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 5012983145 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 56020249468 (52.17 GB)
telemt_user_msgs_from_client{user="hello"} 3208488
telemt_user_msgs_to_client{user="hello"} 14510673
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 71367.0 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114464
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 5287
telemt_upstream_connect_attempt_total 101599
telemt_upstream_connect_success_total 101595
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 101599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101587
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 12047860371 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 83636913674 (77.89 GB)
telemt_user_msgs_from_client{user="hello"} 5748355
telemt_user_msgs_to_client{user="hello"} 16239212
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 71366.0 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125858
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 1220
telemt_upstream_connect_attempt_total 119268
telemt_upstream_connect_success_total 118995
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 119268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118987
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 5539247598 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 83408335409 (77.68 GB)
telemt_user_msgs_from_client{user="hello"} 3667762
telemt_user_msgs_to_client{user="hello"} 21658651
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71367.2 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197458
telemt_connections_bad_total 15527
telemt_handshake_timeouts_total 3380
telemt_upstream_connect_attempt_total 158209
telemt_upstream_connect_success_total 157807
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 158209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157799
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 3338592450 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 138515264243 (129.00 GB)
telemt_user_msgs_from_client{user="hello"} 3597716
telemt_user_msgs_to_client{user="hello"} 18287974
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 50336.6 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 9
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