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

# Server Metrics 2026-03-11 13:40:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83658.6 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272676
telemt_connections_bad_total 3659
telemt_handshake_timeouts_total 4731
telemt_upstream_connect_attempt_total 252116
telemt_upstream_connect_success_total 252040
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 252116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 230767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 252030
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 4903338206 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 129756237987 (120.84 GB)
telemt_user_msgs_from_client{user="hello"} 5612859
telemt_user_msgs_to_client{user="hello"} 10262819
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83657.9 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105988
telemt_connections_bad_total 908
telemt_handshake_timeouts_total 3333
telemt_upstream_connect_attempt_total 97143
telemt_upstream_connect_success_total 97124
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 97143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97116
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 5252822540 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 65055444180 (60.59 GB)
telemt_user_msgs_from_client{user="hello"} 3578621
telemt_user_msgs_to_client{user="hello"} 18416640
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83657.6 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148004
telemt_connections_bad_total 1246
telemt_handshake_timeouts_total 6823
telemt_upstream_connect_attempt_total 131663
telemt_upstream_connect_success_total 131649
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 131663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131641
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 12599278124 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 115284682828 (107.37 GB)
telemt_user_msgs_from_client{user="hello"} 6511719
telemt_user_msgs_to_client{user="hello"} 24937773
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83656.8 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163565
telemt_connections_bad_total 4318
telemt_handshake_timeouts_total 1910
telemt_upstream_connect_attempt_total 150652
telemt_upstream_connect_success_total 150294
telemt_upstream_connect_fail_total 358
telemt_upstream_connect_attempts_per_request{bucket="1"} 150652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 402
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 358
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150286
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 8940641847 (8.33 GB)
telemt_user_octets_to_client{user="hello"} 109195941058 (101.70 GB)
telemt_user_msgs_from_client{user="hello"} 5358315
telemt_user_msgs_to_client{user="hello"} 32224784
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83657.8 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239874
telemt_connections_bad_total 18579
telemt_handshake_timeouts_total 6134
telemt_upstream_connect_attempt_total 193682
telemt_upstream_connect_success_total 193180
telemt_upstream_connect_fail_total 502
telemt_upstream_connect_attempts_per_request{bucket="1"} 193682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 167075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 502
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 193172
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 4800894199 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 155340431589 (144.67 GB)
telemt_user_msgs_from_client{user="hello"} 4566739
telemt_user_msgs_to_client{user="hello"} 21493276
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 62627.2 (17h 23m)
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