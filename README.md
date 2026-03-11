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

# Server Metrics 2026-03-11 11:32:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 75976.3 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231913
telemt_connections_bad_total 3628
telemt_handshake_timeouts_total 4492
telemt_upstream_connect_attempt_total 213394
telemt_upstream_connect_success_total 213327
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 213394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 213319
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 4488849250 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 120600730074 (112.32 GB)
telemt_user_msgs_from_client{user="hello"} 5001289
telemt_user_msgs_to_client{user="hello"} 9226428
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 75975.6 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90729
telemt_connections_bad_total 845
telemt_handshake_timeouts_total 3258
telemt_upstream_connect_attempt_total 82515
telemt_upstream_connect_success_total 82499
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 82515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82491
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 5125392185 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 57660494651 (53.70 GB)
telemt_user_msgs_from_client{user="hello"} 3340107
telemt_user_msgs_to_client{user="hello"} 15330548
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 75975.3 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127051
telemt_connections_bad_total 1092
telemt_handshake_timeouts_total 6369
telemt_upstream_connect_attempt_total 112198
telemt_upstream_connect_success_total 112185
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 112198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112177
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 12350568343 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 87929611737 (81.89 GB)
telemt_user_msgs_from_client{user="hello"} 6019403
telemt_user_msgs_to_client{user="hello"} 17477792
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 75974.4 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137435
telemt_connections_bad_total 334
telemt_handshake_timeouts_total 1260
telemt_upstream_connect_attempt_total 130389
telemt_upstream_connect_success_total 130084
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 130389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130076
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5725504089 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 99945127441 (93.08 GB)
telemt_user_msgs_from_client{user="hello"} 3947859
telemt_user_msgs_to_client{user="hello"} 28578524
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 75975.4 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211382
telemt_connections_bad_total 16429
telemt_handshake_timeouts_total 3747
telemt_upstream_connect_attempt_total 170473
telemt_upstream_connect_success_total 170071
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 170473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 170063
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 3738024748 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 144860770128 (134.91 GB)
telemt_user_msgs_from_client{user="hello"} 3896540
telemt_user_msgs_to_client{user="hello"} 19543578
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 54944.9 (15h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425
telemt_connections_bad_total 403
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