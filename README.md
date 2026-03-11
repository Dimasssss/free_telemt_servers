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

# Server Metrics 2026-03-11 01:30:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 39854.7 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108401
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2521
telemt_upstream_connect_attempt_total 97749
telemt_upstream_connect_success_total 97714
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 97749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97710
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 2748518745 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 78217563895 (72.85 GB)
telemt_user_msgs_from_client{user="hello"} 2796410
telemt_user_msgs_to_client{user="hello"} 5386651
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 39853.9 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44223
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 1600
telemt_upstream_connect_attempt_total 39736
telemt_upstream_connect_success_total 39727
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 39736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39723
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 2022921001 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38760064812 (36.10 GB)
telemt_user_msgs_from_client{user="hello"} 1617160
telemt_user_msgs_to_client{user="hello"} 9617204
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39853.8 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66197
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 4127
telemt_upstream_connect_attempt_total 57735
telemt_upstream_connect_success_total 57733
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57729
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 9315624131 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 65794262255 (61.28 GB)
telemt_user_msgs_from_client{user="hello"} 4232511
telemt_user_msgs_to_client{user="hello"} 11680845
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 39852.6 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64465
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 531
telemt_upstream_connect_attempt_total 61680
telemt_upstream_connect_success_total 61525
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 61680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61521
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 1743553533 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 42400105592 (39.49 GB)
telemt_user_msgs_from_client{user="hello"} 1557702
telemt_user_msgs_to_client{user="hello"} 8277782
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 39854.0 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93038
telemt_connections_bad_total 9337
telemt_handshake_timeouts_total 1494
telemt_upstream_connect_attempt_total 78802
telemt_upstream_connect_success_total 78554
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 78802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78550
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2131876513 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 62279084115 (58.00 GB)
telemt_user_msgs_from_client{user="hello"} 2098606
telemt_user_msgs_to_client{user="hello"} 9075247
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18823.4 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```