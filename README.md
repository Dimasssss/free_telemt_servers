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

# Server Metrics 2026-03-11 14:11:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 85505.4 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280865
telemt_connections_bad_total 3677
telemt_handshake_timeouts_total 4772
telemt_upstream_connect_attempt_total 259830
telemt_upstream_connect_success_total 259753
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 259830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 237730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 259743
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 4984887448 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 132842887623 (123.72 GB)
telemt_user_msgs_from_client{user="hello"} 5751829
telemt_user_msgs_to_client{user="hello"} 10510507
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 85504.6 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110575
telemt_connections_bad_total 921
telemt_handshake_timeouts_total 3354
telemt_upstream_connect_attempt_total 101461
telemt_upstream_connect_success_total 101442
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 101461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101434
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 5431818983 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 67243205877 (62.63 GB)
telemt_user_msgs_from_client{user="hello"} 3698972
telemt_user_msgs_to_client{user="hello"} 19139243
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 85504.3 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154266
telemt_connections_bad_total 1250
telemt_handshake_timeouts_total 6894
telemt_upstream_connect_attempt_total 137549
telemt_upstream_connect_success_total 137535
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 137549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137527
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 12655911935 (11.79 GB)
telemt_user_octets_to_client{user="hello"} 126268976239 (117.60 GB)
telemt_user_msgs_from_client{user="hello"} 6650907
telemt_user_msgs_to_client{user="hello"} 28059282
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 85503.1 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171084
telemt_connections_bad_total 6168
telemt_handshake_timeouts_total 1946
telemt_upstream_connect_attempt_total 156033
telemt_upstream_connect_success_total 155657
telemt_upstream_connect_fail_total 376
telemt_upstream_connect_attempts_per_request{bucket="1"} 156033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 376
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 155647
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 9324866703 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 109992941309 (102.44 GB)
telemt_user_msgs_from_client{user="hello"} 5548191
telemt_user_msgs_to_client{user="hello"} 32570069
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 85504.5 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246479
telemt_connections_bad_total 18933
telemt_handshake_timeouts_total 6165
telemt_upstream_connect_attempt_total 199747
telemt_upstream_connect_success_total 199244
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 199747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 172409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 199236
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 4905580745 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 157329271883 (146.52 GB)
telemt_user_msgs_from_client{user="hello"} 4678334
telemt_user_msgs_to_client{user="hello"} 21786589
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 64473.9 (17h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
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