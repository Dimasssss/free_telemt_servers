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

# Server Metrics 2026-03-11 20:41:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13255.2 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47153
telemt_connections_bad_total 2484
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 42473
telemt_upstream_connect_success_total 42463
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 42473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42461
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 1428906499 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 24648611328 (22.96 GB)
telemt_user_msgs_from_client{user="hello"} 1177304
telemt_user_msgs_to_client{user="hello"} 2090274
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13243.3 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21744
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 20066
telemt_upstream_connect_success_total 20027
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 20066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20025
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 233574461 (222.75 MB)
telemt_user_octets_to_client{user="hello"} 10541648854 (9.82 GB)
telemt_user_msgs_from_client{user="hello"} 410730
telemt_user_msgs_to_client{user="hello"} 4267247
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13263.3 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26504
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 24788
telemt_upstream_connect_success_total 24786
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 24788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24784
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 301549972 (287.58 MB)
telemt_user_octets_to_client{user="hello"} 9677379771 (9.01 GB)
telemt_user_msgs_from_client{user="hello"} 480271
telemt_user_msgs_to_client{user="hello"} 2412460
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13258.7 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28769
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 25236
telemt_upstream_connect_success_total 25161
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 25236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25159
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 692996236 (660.89 MB)
telemt_user_octets_to_client{user="hello"} 13740563393 (12.80 GB)
telemt_user_msgs_from_client{user="hello"} 592821
telemt_user_msgs_to_client{user="hello"} 4028848
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13266.9 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31605
telemt_connections_bad_total 2522
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 27951
telemt_upstream_connect_success_total 27950
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 27951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27948
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 497691725 (474.64 MB)
telemt_user_octets_to_client{user="hello"} 10735399884 (10.00 GB)
telemt_user_msgs_from_client{user="hello"} 632547
telemt_user_msgs_to_client{user="hello"} 3930002
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 87873.3 (24h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1161
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 628
telemt_upstream_connect_success_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 620
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 5209030 (4.97 MB)
telemt_user_octets_to_client{user="hello"} 221489150 (211.23 MB)
telemt_user_msgs_from_client{user="hello"} 12080
telemt_user_msgs_to_client{user="hello"} 28874
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```