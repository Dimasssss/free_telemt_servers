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

# Server Metrics 2026-03-11 17:57:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3428.1 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14101
telemt_connections_bad_total 802
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 12517
telemt_upstream_connect_success_total 12514
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 12517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12512
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 405201266 (386.43 MB)
telemt_user_octets_to_client{user="hello"} 8103551544 (7.55 GB)
telemt_user_msgs_from_client{user="hello"} 333160
telemt_user_msgs_to_client{user="hello"} 601993
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3416.4 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7458
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 6775
telemt_upstream_connect_success_total 6774
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6772
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 110347345 (105.24 MB)
telemt_user_octets_to_client{user="hello"} 4518672387 (4.21 GB)
telemt_user_msgs_from_client{user="hello"} 161366
telemt_user_msgs_to_client{user="hello"} 1751674
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3435.7 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8325
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 7728
telemt_upstream_connect_success_total 7727
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7725
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 64914789 (61.91 MB)
telemt_user_octets_to_client{user="hello"} 3438746140 (3.20 GB)
telemt_user_msgs_from_client{user="hello"} 159272
telemt_user_msgs_to_client{user="hello"} 980411
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3431.5 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7665
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 183
telemt_upstream_connect_attempt_total 6985
telemt_upstream_connect_success_total 6970
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6968
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 426730255 (406.96 MB)
telemt_user_octets_to_client{user="hello"} 3226875004 (3.01 GB)
telemt_user_msgs_from_client{user="hello"} 241876
telemt_user_msgs_to_client{user="hello"} 783423
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3439.7 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8676
telemt_connections_bad_total 722
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 7668
telemt_upstream_connect_success_total 7668
telemt_upstream_connect_attempts_per_request{bucket="1"} 7668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7666
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 48029899 (45.80 MB)
telemt_user_octets_to_client{user="hello"} 1094039292 (1.02 GB)
telemt_user_msgs_from_client{user="hello"} 106483
telemt_user_msgs_to_client{user="hello"} 361988
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78046.1 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 14
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