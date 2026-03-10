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

# Server Metrics 2026-03-10 21:41:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26098.0 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90938
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 2175
telemt_upstream_connect_attempt_total 81438
telemt_upstream_connect_success_total 81406
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 81438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81402
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2498680053 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 63921075679 (59.53 GB)
telemt_user_msgs_from_client{user="hello"} 2365630
telemt_user_msgs_to_client{user="hello"} 4245041
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26097.4 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34548
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 651
telemt_upstream_connect_attempt_total 31503
telemt_upstream_connect_success_total 31494
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31490
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 1631147897 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 30654980821 (28.55 GB)
telemt_user_msgs_from_client{user="hello"} 1289348
telemt_user_msgs_to_client{user="hello"} 8122495
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26097.2 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56099
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 48587
telemt_upstream_connect_success_total 48585
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 48587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48581
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 750422807 (715.66 MB)
telemt_user_octets_to_client{user="hello"} 43124075532 (40.16 GB)
telemt_user_msgs_from_client{user="hello"} 1020789
telemt_user_msgs_to_client{user="hello"} 6532506
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26096.0 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50866
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 48831
telemt_upstream_connect_success_total 48693
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 48831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48689
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 801194079 (764.08 MB)
telemt_user_octets_to_client{user="hello"} 36630861786 (34.12 GB)
telemt_user_msgs_from_client{user="hello"} 1075395
telemt_user_msgs_to_client{user="hello"} 6944357
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26097.4 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73752
telemt_connections_bad_total 6592
telemt_handshake_timeouts_total 1405
telemt_upstream_connect_attempt_total 62795
telemt_upstream_connect_success_total 62551
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 62795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62547
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1868297262 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 46816111037 (43.60 GB)
telemt_user_msgs_from_client{user="hello"} 1728975
telemt_user_msgs_to_client{user="hello"} 6624452
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5066.9 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19
telemt_connections_bad_total 19
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```