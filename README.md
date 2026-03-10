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

# Server Metrics 2026-03-10 23:43:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33441.0 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99634
telemt_connections_bad_total 3322
telemt_handshake_timeouts_total 2224
telemt_upstream_connect_attempt_total 89683
telemt_upstream_connect_success_total 89651
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 89683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89647
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2622652289 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 73309404616 (68.27 GB)
telemt_user_msgs_from_client{user="hello"} 2607800
telemt_user_msgs_to_client{user="hello"} 5009008
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33440.3 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38964
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 911
telemt_upstream_connect_attempt_total 35419
telemt_upstream_connect_success_total 35410
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35406
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 1985265907 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 37380067972 (34.81 GB)
telemt_user_msgs_from_client{user="hello"} 1544943
telemt_user_msgs_to_client{user="hello"} 9267206
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33440.2 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61782
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 53697
telemt_upstream_connect_success_total 53695
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53691
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1081530105 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 55277946583 (51.48 GB)
telemt_user_msgs_from_client{user="hello"} 1255994
telemt_user_msgs_to_client{user="hello"} 8155515
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33438.9 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58018
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 510
telemt_upstream_connect_attempt_total 55541
telemt_upstream_connect_success_total 55389
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 55541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55385
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 836236585 (797.50 MB)
telemt_user_octets_to_client{user="hello"} 37651606775 (35.07 GB)
telemt_user_msgs_from_client{user="hello"} 1150312
telemt_user_msgs_to_client{user="hello"} 7237174
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33440.2 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84409
telemt_connections_bad_total 8047
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 71688
telemt_upstream_connect_success_total 71440
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 71688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71436
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 2085981182 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 57387886029 (53.45 GB)
telemt_user_msgs_from_client{user="hello"} 1987276
telemt_user_msgs_to_client{user="hello"} 8339508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12409.6 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```