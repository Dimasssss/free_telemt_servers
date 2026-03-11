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

# Server Metrics 2026-03-11 19:19:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8347.2 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32697
telemt_connections_bad_total 1870
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 29468
telemt_upstream_connect_success_total 29459
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 29468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29457
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 718169108 (684.90 MB)
telemt_user_octets_to_client{user="hello"} 18354075559 (17.09 GB)
telemt_user_msgs_from_client{user="hello"} 739600
telemt_user_msgs_to_client{user="hello"} 1480745
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8335.4 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15504
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 244
telemt_upstream_connect_attempt_total 14114
telemt_upstream_connect_success_total 14113
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14111
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 196455784 (187.35 MB)
telemt_user_octets_to_client{user="hello"} 8413304797 (7.84 GB)
telemt_user_msgs_from_client{user="hello"} 317740
telemt_user_msgs_to_client{user="hello"} 3226345
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8355.7 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18262
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 17043
telemt_upstream_connect_success_total 17041
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17039
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 183895798 (175.38 MB)
telemt_user_octets_to_client{user="hello"} 7426428861 (6.92 GB)
telemt_user_msgs_from_client{user="hello"} 349985
telemt_user_msgs_to_client{user="hello"} 1926436
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8350.8 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19049
telemt_connections_bad_total 1236
telemt_handshake_timeouts_total 368
telemt_upstream_connect_attempt_total 16593
telemt_upstream_connect_success_total 16543
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 16593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16541
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 538931398 (513.97 MB)
telemt_user_octets_to_client{user="hello"} 10133536441 (9.44 GB)
telemt_user_msgs_from_client{user="hello"} 421710
telemt_user_msgs_to_client{user="hello"} 2594265
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8358.8 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20651
telemt_connections_bad_total 1624
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 18126
telemt_upstream_connect_success_total 18124
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18122
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 317308780 (302.61 MB)
telemt_user_octets_to_client{user="hello"} 6656286105 (6.20 GB)
telemt_user_msgs_from_client{user="hello"} 389667
telemt_user_msgs_to_client{user="hello"} 2111724
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 82965.2 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 22
telemt_upstream_connect_success_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 8621 (8.42 KB)
telemt_user_octets_to_client{user="hello"} 3281 (3.20 KB)
telemt_user_msgs_from_client{user="hello"} 26
telemt_user_msgs_to_client{user="hello"} 18
```