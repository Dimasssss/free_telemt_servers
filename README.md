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

# Server Metrics 2026-03-11 10:25:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 71981.7 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214052
telemt_connections_bad_total 3616
telemt_handshake_timeouts_total 4405
telemt_upstream_connect_attempt_total 196278
telemt_upstream_connect_success_total 196217
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 196278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 179469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 196209
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 4268405690 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 114458568590 (106.60 GB)
telemt_user_msgs_from_client{user="hello"} 4651567
telemt_user_msgs_to_client{user="hello"} 8605030
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 71981.0 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83792
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3166
telemt_upstream_connect_attempt_total 75934
telemt_upstream_connect_success_total 75917
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 75933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75909
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 5021124358 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 56288215093 (52.42 GB)
telemt_user_msgs_from_client{user="hello"} 3226136
telemt_user_msgs_to_client{user="hello"} 14626285
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 71980.8 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116010
telemt_connections_bad_total 1077
telemt_handshake_timeouts_total 5302
telemt_upstream_connect_attempt_total 103036
telemt_upstream_connect_success_total 103032
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 103036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103024
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 12252083213 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 84019220288 (78.25 GB)
telemt_user_msgs_from_client{user="hello"} 5841802
telemt_user_msgs_to_client{user="hello"} 16358731
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 71979.7 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127439
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 1227
telemt_upstream_connect_attempt_total 120784
telemt_upstream_connect_success_total 120508
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 120784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 327
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120500
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 5600712673 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 83817412969 (78.06 GB)
telemt_user_msgs_from_client{user="hello"} 3703455
telemt_user_msgs_to_client{user="hello"} 21826407
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71981.1 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199430
telemt_connections_bad_total 15639
telemt_handshake_timeouts_total 3395
telemt_upstream_connect_attempt_total 159993
telemt_upstream_connect_success_total 159591
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 159993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 159583
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 3553168930 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 141418302214 (131.71 GB)
telemt_user_msgs_from_client{user="hello"} 3710939
telemt_user_msgs_to_client{user="hello"} 18774650
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 50950.3 (14h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
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