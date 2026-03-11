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

# Server Metrics 2026-03-11 00:49:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 37411.4 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105028
telemt_connections_bad_total 3344
telemt_handshake_timeouts_total 2494
telemt_upstream_connect_attempt_total 94559
telemt_upstream_connect_success_total 94525
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 94559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94521
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2709056136 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 77113500933 (71.82 GB)
telemt_user_msgs_from_client{user="hello"} 2738427
telemt_user_msgs_to_client{user="hello"} 5238544
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 37410.8 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41804
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 38057
telemt_upstream_connect_success_total 38048
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 38057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38044
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2014313456 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38535840360 (35.89 GB)
telemt_user_msgs_from_client{user="hello"} 1596865
telemt_user_msgs_to_client{user="hello"} 9543303
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 37410.5 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64683
telemt_connections_bad_total 559
telemt_handshake_timeouts_total 4112
telemt_upstream_connect_attempt_total 56372
telemt_upstream_connect_success_total 56370
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 56372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56366
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 8179156267 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 60106100717 (55.98 GB)
telemt_user_msgs_from_client{user="hello"} 3785266
telemt_user_msgs_to_client{user="hello"} 9292324
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 37409.5 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61874
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 59212
telemt_upstream_connect_success_total 59058
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 59212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59054
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 852746034 (813.24 MB)
telemt_user_octets_to_client{user="hello"} 38402783511 (35.77 GB)
telemt_user_msgs_from_client{user="hello"} 1191083
telemt_user_msgs_to_client{user="hello"} 7488388
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37410.7 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89816
telemt_connections_bad_total 8835
telemt_handshake_timeouts_total 1486
telemt_upstream_connect_attempt_total 76167
telemt_upstream_connect_success_total 75919
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 76167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75915
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2118891554 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 61825814822 (57.58 GB)
telemt_user_msgs_from_client{user="hello"} 2066389
telemt_user_msgs_to_client{user="hello"} 8969535
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16380.1 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```