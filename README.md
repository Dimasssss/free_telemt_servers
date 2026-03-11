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

# Server Metrics 2026-03-11 14:36:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87042.1 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288648
telemt_connections_bad_total 3681
telemt_handshake_timeouts_total 4801
telemt_upstream_connect_attempt_total 267288
telemt_upstream_connect_success_total 267211
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 267288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 267201
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 5060172634 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 134938388583 (125.67 GB)
telemt_user_msgs_from_client{user="hello"} 5863562
telemt_user_msgs_to_client{user="hello"} 10725908
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87041.4 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114117
telemt_connections_bad_total 922
telemt_handshake_timeouts_total 3370
telemt_upstream_connect_attempt_total 104836
telemt_upstream_connect_success_total 104815
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 104836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 460
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104805
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 5961013887 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 68379469910 (63.68 GB)
telemt_user_msgs_from_client{user="hello"} 3931596
telemt_user_msgs_to_client{user="hello"} 19611635
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87041.1 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158925
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 6971
telemt_upstream_connect_attempt_total 141838
telemt_upstream_connect_success_total 141824
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 141838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 141814
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 12689779562 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 128048172853 (119.25 GB)
telemt_user_msgs_from_client{user="hello"} 6724820
telemt_user_msgs_to_client{user="hello"} 28588251
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87040.1 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176291
telemt_connections_bad_total 7453
telemt_handshake_timeouts_total 1967
telemt_upstream_connect_attempt_total 159826
telemt_upstream_connect_success_total 159437
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 159826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159427
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 9600389200 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 111353854640 (103.71 GB)
telemt_user_msgs_from_client{user="hello"} 5695553
telemt_user_msgs_to_client{user="hello"} 33083766
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87041.3 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251765
telemt_connections_bad_total 19231
telemt_handshake_timeouts_total 6303
telemt_upstream_connect_attempt_total 204434
telemt_upstream_connect_success_total 203931
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 204434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 176553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 203923
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 5011154426 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 165242189054 (153.89 GB)
telemt_user_msgs_from_client{user="hello"} 4822762
telemt_user_msgs_to_client{user="hello"} 22744767
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 66010.8 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```