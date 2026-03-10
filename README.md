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

# Server Metrics 2026-03-10 21:15:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24568.6 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88408
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 2161
telemt_upstream_connect_attempt_total 79025
telemt_upstream_connect_success_total 78993
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 79025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78989
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 2480196522 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 61223383444 (57.02 GB)
telemt_user_msgs_from_client{user="hello"} 2321775
telemt_user_msgs_to_client{user="hello"} 4166653
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24568.1 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33792
telemt_connections_bad_total 318
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 30820
telemt_upstream_connect_success_total 30811
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 30820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30807
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 1573572919 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 26675729490 (24.84 GB)
telemt_user_msgs_from_client{user="hello"} 1227474
telemt_user_msgs_to_client{user="hello"} 7619510
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24567.8 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54281
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 3732
telemt_upstream_connect_attempt_total 47057
telemt_upstream_connect_success_total 47055
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 47057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47051
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 736890802 (702.75 MB)
telemt_user_octets_to_client{user="hello"} 42655674595 (39.73 GB)
telemt_user_msgs_from_client{user="hello"} 999628
telemt_user_msgs_to_client{user="hello"} 6426771
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24566.8 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48456
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 316
telemt_upstream_connect_attempt_total 46480
telemt_upstream_connect_success_total 46346
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 46480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46342
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 779050892 (742.96 MB)
telemt_user_octets_to_client{user="hello"} 35672841633 (33.22 GB)
telemt_user_msgs_from_client{user="hello"} 1035107
telemt_user_msgs_to_client{user="hello"} 6730973
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24568.1 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70488
telemt_connections_bad_total 6311
telemt_handshake_timeouts_total 1397
telemt_upstream_connect_attempt_total 59895
telemt_upstream_connect_success_total 59651
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 59895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59647
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 1843172474 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 45531386475 (42.40 GB)
telemt_user_msgs_from_client{user="hello"} 1672583
telemt_user_msgs_to_client{user="hello"} 6298624
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3537.5 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17
telemt_connections_bad_total 17
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```