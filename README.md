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

# Server Metrics 2026-03-11 07:47:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 62476.3 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172597
telemt_connections_bad_total 3538
telemt_handshake_timeouts_total 4057
telemt_upstream_connect_attempt_total 156553
telemt_upstream_connect_success_total 156505
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 156553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 142868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 156497
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 3617046114 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 100522518796 (93.62 GB)
telemt_user_msgs_from_client{user="hello"} 3865106
telemt_user_msgs_to_client{user="hello"} 7246164
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 62475.8 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67467
telemt_connections_bad_total 581
telemt_handshake_timeouts_total 3078
telemt_upstream_connect_attempt_total 60537
telemt_upstream_connect_success_total 60523
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 60537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60517
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 4769113909 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 51169336303 (47.66 GB)
telemt_user_msgs_from_client{user="hello"} 2947549
telemt_user_msgs_to_client{user="hello"} 12542270
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 62475.4 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93664
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 5151
telemt_upstream_connect_attempt_total 82077
telemt_upstream_connect_success_total 82074
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 82077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82068
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 11900483499 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 74853279047 (69.71 GB)
telemt_user_msgs_from_client{user="hello"} 5392707
telemt_user_msgs_to_client{user="hello"} 14466732
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 62474.4 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100750
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 674
telemt_upstream_connect_attempt_total 96446
telemt_upstream_connect_success_total 96233
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 96445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96225
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 3440970916 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 65452260889 (60.96 GB)
telemt_user_msgs_from_client{user="hello"} 2610305
telemt_user_msgs_to_client{user="hello"} 16189021
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 62475.7 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167666
telemt_connections_bad_total 13867
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 133714
telemt_upstream_connect_success_total 133464
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 133714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 133458
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2598311811 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 127779562848 (119.00 GB)
telemt_user_msgs_from_client{user="hello"} 3037605
telemt_user_msgs_to_client{user="hello"} 16282201
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 41445.0 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 9
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