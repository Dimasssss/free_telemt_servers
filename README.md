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

# Server Metrics 2026-03-11 10:30:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 72289.0 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215530
telemt_connections_bad_total 3616
telemt_handshake_timeouts_total 4411
telemt_upstream_connect_attempt_total 197704
telemt_upstream_connect_success_total 197642
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 197704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 197634
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 4288034182 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 114959734627 (107.06 GB)
telemt_user_msgs_from_client{user="hello"} 4683369
telemt_user_msgs_to_client{user="hello"} 8648640
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 72288.3 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84299
telemt_connections_bad_total 783
telemt_handshake_timeouts_total 3166
telemt_upstream_connect_attempt_total 76424
telemt_upstream_connect_success_total 76408
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 76424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76400
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 5023346889 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 56318424913 (52.45 GB)
telemt_user_msgs_from_client{user="hello"} 3230335
telemt_user_msgs_to_client{user="hello"} 14643025
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 72288.0 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116703
telemt_connections_bad_total 1077
telemt_handshake_timeouts_total 5305
telemt_upstream_connect_attempt_total 103691
telemt_upstream_connect_success_total 103687
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 103691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103679
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 12293875815 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 85281529799 (79.42 GB)
telemt_user_msgs_from_client{user="hello"} 5873248
telemt_user_msgs_to_client{user="hello"} 16673603
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 72286.8 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128321
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 1229
telemt_upstream_connect_attempt_total 121619
telemt_upstream_connect_success_total 121342
telemt_upstream_connect_fail_total 277
telemt_upstream_connect_attempts_per_request{bucket="1"} 121619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 277
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 121334
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 5608078676 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 84953524844 (79.12 GB)
telemt_user_msgs_from_client{user="hello"} 3722289
telemt_user_msgs_to_client{user="hello"} 22211958
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72288.2 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200607
telemt_connections_bad_total 15693
telemt_handshake_timeouts_total 3415
telemt_upstream_connect_attempt_total 161053
telemt_upstream_connect_success_total 160651
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 161053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160643
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 3561590318 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 142093139615 (132.33 GB)
telemt_user_msgs_from_client{user="hello"} 3726777
telemt_user_msgs_to_client{user="hello"} 18891960
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 51257.5 (14h 14m)
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