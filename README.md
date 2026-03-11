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

# Server Metrics 2026-03-11 13:45:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83967.0 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273878
telemt_connections_bad_total 3670
telemt_handshake_timeouts_total 4743
telemt_upstream_connect_attempt_total 253226
telemt_upstream_connect_success_total 253150
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 253226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 231780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 253140
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 4910712552 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 130003947074 (121.08 GB)
telemt_user_msgs_from_client{user="hello"} 5631831
telemt_user_msgs_to_client{user="hello"} 10291576
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83966.3 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106835
telemt_connections_bad_total 908
telemt_handshake_timeouts_total 3334
telemt_upstream_connect_attempt_total 97952
telemt_upstream_connect_success_total 97933
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 97952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97925
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 5259668950 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 65300339583 (60.82 GB)
telemt_user_msgs_from_client{user="hello"} 3589165
telemt_user_msgs_to_client{user="hello"} 18489705
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83965.8 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148938
telemt_connections_bad_total 1247
telemt_handshake_timeouts_total 6830
telemt_upstream_connect_attempt_total 132556
telemt_upstream_connect_success_total 132542
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 132556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132534
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 12610041068 (11.74 GB)
telemt_user_octets_to_client{user="hello"} 117171379183 (109.12 GB)
telemt_user_msgs_from_client{user="hello"} 6534942
telemt_user_msgs_to_client{user="hello"} 25464542
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83964.8 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165003
telemt_connections_bad_total 4715
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 151611
telemt_upstream_connect_success_total 151248
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 151611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151238
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 9014869959 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 109364753179 (101.85 GB)
telemt_user_msgs_from_client{user="hello"} 5395192
telemt_user_msgs_to_client{user="hello"} 32307859
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83966.1 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240954
telemt_connections_bad_total 18633
telemt_handshake_timeouts_total 6137
telemt_upstream_connect_attempt_total 194680
telemt_upstream_connect_success_total 194178
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 194680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 167945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 194170
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 4807163680 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 155802903843 (145.10 GB)
telemt_user_msgs_from_client{user="hello"} 4580923
telemt_user_msgs_to_client{user="hello"} 21559120
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 62935.4 (17h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440
telemt_connections_bad_total 418
telemt_handshake_timeouts_total 10
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