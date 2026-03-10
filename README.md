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

# Server Metrics 2026-03-10 21:20:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24874.8 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89000
telemt_connections_bad_total 3271
telemt_handshake_timeouts_total 2166
telemt_upstream_connect_attempt_total 79596
telemt_upstream_connect_success_total 79564
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 79596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79560
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 2484134391 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 61593925166 (57.36 GB)
telemt_user_msgs_from_client{user="hello"} 2331472
telemt_user_msgs_to_client{user="hello"} 4183325
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24874.2 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33942
telemt_connections_bad_total 318
telemt_handshake_timeouts_total 627
telemt_upstream_connect_attempt_total 30955
telemt_upstream_connect_success_total 30946
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 30955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30942
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 1617676023 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 27320588756 (25.44 GB)
telemt_user_msgs_from_client{user="hello"} 1252204
telemt_user_msgs_to_client{user="hello"} 7718090
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24873.9 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54722
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 3732
telemt_upstream_connect_attempt_total 47485
telemt_upstream_connect_success_total 47483
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 47485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47479
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 739691564 (705.42 MB)
telemt_user_octets_to_client{user="hello"} 42726138579 (39.79 GB)
telemt_user_msgs_from_client{user="hello"} 1003803
telemt_user_msgs_to_client{user="hello"} 6447576
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24872.9 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48994
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 316
telemt_upstream_connect_attempt_total 47003
telemt_upstream_connect_success_total 46868
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 47003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46864
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 784397262 (748.06 MB)
telemt_user_octets_to_client{user="hello"} 35847851583 (33.39 GB)
telemt_user_msgs_from_client{user="hello"} 1044904
telemt_user_msgs_to_client{user="hello"} 6769160
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24874.1 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71421
telemt_connections_bad_total 6365
telemt_handshake_timeouts_total 1397
telemt_upstream_connect_attempt_total 60753
telemt_upstream_connect_success_total 60509
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 60753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60505
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 1847278002 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 45793501554 (42.65 GB)
telemt_user_msgs_from_client{user="hello"} 1683794
telemt_user_msgs_to_client{user="hello"} 6382816
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3843.5 (1h 4m)
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