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

# Server Metrics 2026-03-11 04:59:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52385.0 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132890
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 2824
telemt_upstream_connect_attempt_total 120627
telemt_upstream_connect_success_total 120583
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 120627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120577
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 3056872275 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 86318133808 (80.39 GB)
telemt_user_msgs_from_client{user="hello"} 3171146
telemt_user_msgs_to_client{user="hello"} 5998224
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 52384.5 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54639
telemt_connections_bad_total 421
telemt_handshake_timeouts_total 2957
telemt_upstream_connect_attempt_total 48414
telemt_upstream_connect_success_total 48404
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 48414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48398
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 4463749663 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 44875961136 (41.79 GB)
telemt_user_msgs_from_client{user="hello"} 2616196
telemt_user_msgs_to_client{user="hello"} 10732809
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 52383.9 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75507
telemt_connections_bad_total 682
telemt_handshake_timeouts_total 4312
telemt_upstream_connect_attempt_total 66206
telemt_upstream_connect_success_total 66203
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 66206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66197
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 11778583796 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71151100125 (66.26 GB)
telemt_user_msgs_from_client{user="hello"} 5186019
telemt_user_msgs_to_client{user="hello"} 13367258
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52382.9 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77980
telemt_connections_bad_total 156
telemt_handshake_timeouts_total 577
telemt_upstream_connect_attempt_total 74676
telemt_upstream_connect_success_total 74512
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 74676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74506
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 1816724158 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 48671525628 (45.33 GB)
telemt_user_msgs_from_client{user="hello"} 1720211
telemt_user_msgs_to_client{user="hello"} 10710513
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52384.2 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124168
telemt_connections_bad_total 11805
telemt_handshake_timeouts_total 1691
telemt_upstream_connect_attempt_total 105615
telemt_upstream_connect_success_total 105366
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 105615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105360
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2383409246 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 100021177841 (93.15 GB)
telemt_user_msgs_from_client{user="hello"} 2578344
telemt_user_msgs_to_client{user="hello"} 12893853
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31353.6 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```