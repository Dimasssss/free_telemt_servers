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

# Server Metrics 2026-03-11 06:05:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56359.8 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148930
telemt_connections_bad_total 3496
telemt_handshake_timeouts_total 3868
telemt_upstream_connect_attempt_total 134271
telemt_upstream_connect_success_total 134227
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 134271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 134221
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 3310270368 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 91377026584 (85.10 GB)
telemt_user_msgs_from_client{user="hello"} 3449014
telemt_user_msgs_to_client{user="hello"} 6439160
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 56359.3 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59170
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 3013
telemt_upstream_connect_attempt_total 52676
telemt_upstream_connect_success_total 52664
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 52676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52658
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 4566201211 (4.25 GB)
telemt_user_octets_to_client{user="hello"} 47672916976 (44.40 GB)
telemt_user_msgs_from_client{user="hello"} 2761538
telemt_user_msgs_to_client{user="hello"} 11297333
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56359.1 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80493
telemt_connections_bad_total 726
telemt_handshake_timeouts_total 4356
telemt_upstream_connect_attempt_total 70915
telemt_upstream_connect_success_total 70912
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 70915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70906
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 11806437358 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 72005461017 (67.06 GB)
telemt_user_msgs_from_client{user="hello"} 5236775
telemt_user_msgs_to_client{user="hello"} 13587112
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 56358.0 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85619
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 633
telemt_upstream_connect_attempt_total 81936
telemt_upstream_connect_success_total 81757
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 81936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81751
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1883200471 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 54266115714 (50.54 GB)
telemt_user_msgs_from_client{user="hello"} 1848719
telemt_user_msgs_to_client{user="hello"} 12580322
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56359.3 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144234
telemt_connections_bad_total 12557
telemt_handshake_timeouts_total 1772
telemt_upstream_connect_attempt_total 115792
telemt_upstream_connect_success_total 115543
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 115792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115537
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2460325150 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 109638668872 (102.11 GB)
telemt_user_msgs_from_client{user="hello"} 2749954
telemt_user_msgs_to_client{user="hello"} 14561566
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35328.7 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165
telemt_connections_bad_total 145
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