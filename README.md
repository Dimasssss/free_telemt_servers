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

# Server Metrics 2026-03-11 17:21:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1277.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5534
telemt_connections_bad_total 324
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 4955
telemt_upstream_connect_success_total 4953
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4951
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 122961930 (117.27 MB)
telemt_user_octets_to_client{user="hello"} 2313433555 (2.15 GB)
telemt_user_msgs_from_client{user="hello"} 113343
telemt_user_msgs_to_client{user="hello"} 185244
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1266.6 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3023
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 2713
telemt_upstream_connect_success_total 2712
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2710
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 18903600 (18.03 MB)
telemt_user_octets_to_client{user="hello"} 1326543663 (1.24 GB)
telemt_user_msgs_from_client{user="hello"} 46002
telemt_user_msgs_to_client{user="hello"} 509099
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1285.8 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3056
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 2934
telemt_upstream_connect_success_total 2934
telemt_upstream_connect_attempts_per_request{bucket="1"} 2934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 309
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2932
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 17698554 (16.88 MB)
telemt_user_octets_to_client{user="hello"} 520190267 (496.09 MB)
telemt_user_msgs_from_client{user="hello"} 47505
telemt_user_msgs_to_client{user="hello"} 215443
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1281.6 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3154
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 157
telemt_upstream_connect_attempt_total 2870
telemt_upstream_connect_success_total 2859
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2857
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 79917225 (76.22 MB)
telemt_user_octets_to_client{user="hello"} 1221374849 (1.14 GB)
telemt_user_msgs_from_client{user="hello"} 67409
telemt_user_msgs_to_client{user="hello"} 310582
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1291.1 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3413
telemt_connections_bad_total 256
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 3018
telemt_upstream_connect_success_total 3018
telemt_upstream_connect_attempts_per_request{bucket="1"} 3018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3016
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 17708427 (16.89 MB)
telemt_user_octets_to_client{user="hello"} 374986398 (357.61 MB)
telemt_user_msgs_from_client{user="hello"} 33133
telemt_user_msgs_to_client{user="hello"} 145208
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 75896.2 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492
telemt_connections_bad_total 468
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```