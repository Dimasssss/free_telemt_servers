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

# Server Metrics 2026-03-11 09:44:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 69525.1 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203975
telemt_connections_bad_total 3593
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 186722
telemt_upstream_connect_success_total 186663
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 186722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 186655
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 4070747945 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 110968097002 (103.35 GB)
telemt_user_msgs_from_client{user="hello"} 4426779
telemt_user_msgs_to_client{user="hello"} 8258426
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 69524.3 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79410
telemt_connections_bad_total 779
telemt_handshake_timeouts_total 3143
telemt_upstream_connect_attempt_total 71777
telemt_upstream_connect_success_total 71761
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 71777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71753
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 4984424277 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 55401715373 (51.60 GB)
telemt_user_msgs_from_client{user="hello"} 3160825
telemt_user_msgs_to_client{user="hello"} 14227754
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 69524.4 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109779
telemt_connections_bad_total 1038
telemt_handshake_timeouts_total 5223
telemt_upstream_connect_attempt_total 97322
telemt_upstream_connect_success_total 97318
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 97322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97310
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 11998154644 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 80889998428 (75.33 GB)
telemt_user_msgs_from_client{user="hello"} 5654858
telemt_user_msgs_to_client{user="hello"} 15715548
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 69523.3 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121239
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1121
telemt_upstream_connect_attempt_total 115108
telemt_upstream_connect_success_total 114847
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 115108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 114839
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 5505180272 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 82031724128 (76.40 GB)
telemt_user_msgs_from_client{user="hello"} 3609648
telemt_user_msgs_to_client{user="hello"} 21180406
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 69524.5 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191494
telemt_connections_bad_total 15171
telemt_handshake_timeouts_total 3338
telemt_upstream_connect_attempt_total 153067
telemt_upstream_connect_success_total 152665
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 153067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 152659
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 3016190471 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 135912296296 (126.58 GB)
telemt_user_msgs_from_client{user="hello"} 3418728
telemt_user_msgs_to_client{user="hello"} 17736612
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 48493.8 (13h 28m)
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