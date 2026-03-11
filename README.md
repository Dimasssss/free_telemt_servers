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

# Server Metrics 2026-03-11 09:24:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 68298.7 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198575
telemt_connections_bad_total 3564
telemt_handshake_timeouts_total 4235
telemt_upstream_connect_attempt_total 181549
telemt_upstream_connect_success_total 181492
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 181549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 181484
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 3991323512 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 109023606834 (101.54 GB)
telemt_user_msgs_from_client{user="hello"} 4318023
telemt_user_msgs_to_client{user="hello"} 8078863
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 68298.1 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77000
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 3140
telemt_upstream_connect_attempt_total 69515
telemt_upstream_connect_success_total 69500
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 69515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69492
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 4936215677 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 54534531264 (50.79 GB)
telemt_user_msgs_from_client{user="hello"} 3119550
telemt_user_msgs_to_client{user="hello"} 13978450
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 68298.9 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106852
telemt_connections_bad_total 938
telemt_handshake_timeouts_total 5212
telemt_upstream_connect_attempt_total 94598
telemt_upstream_connect_success_total 94594
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 94598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94586
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 11979272635 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 79614614932 (74.15 GB)
telemt_user_msgs_from_client{user="hello"} 5601063
telemt_user_msgs_to_client{user="hello"} 15465566
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 68296.6 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118198
telemt_connections_bad_total 247
telemt_handshake_timeouts_total 1065
telemt_upstream_connect_attempt_total 112277
telemt_upstream_connect_success_total 112020
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 112276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 308
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112012
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 4807786884 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 80989577381 (75.43 GB)
telemt_user_msgs_from_client{user="hello"} 3328189
telemt_user_msgs_to_client{user="hello"} 20771268
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 68297.9 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187215
telemt_connections_bad_total 14930
telemt_handshake_timeouts_total 3106
telemt_upstream_connect_attempt_total 149704
telemt_upstream_connect_success_total 149302
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 149704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149296
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 2907060125 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 134281149242 (125.06 GB)
telemt_user_msgs_from_client{user="hello"} 3334466
telemt_user_msgs_to_client{user="hello"} 17522419
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 47267.2 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
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