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

# Server Metrics 2026-03-10 23:58:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34357.2 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101079
telemt_connections_bad_total 3324
telemt_handshake_timeouts_total 2476
telemt_upstream_connect_attempt_total 90792
telemt_upstream_connect_success_total 90760
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 90792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90756
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 2651368212 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 74100176602 (69.01 GB)
telemt_user_msgs_from_client{user="hello"} 2640747
telemt_user_msgs_to_client{user="hello"} 5077610
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34356.8 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39479
telemt_connections_bad_total 338
telemt_handshake_timeouts_total 945
telemt_upstream_connect_attempt_total 35870
telemt_upstream_connect_success_total 35861
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35857
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 2001738600 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 38191176832 (35.57 GB)
telemt_user_msgs_from_client{user="hello"} 1565160
telemt_user_msgs_to_client{user="hello"} 9405229
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34356.5 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62397
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4085
telemt_upstream_connect_attempt_total 54286
telemt_upstream_connect_success_total 54284
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5440
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54280
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1102592897 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 56615487092 (52.73 GB)
telemt_user_msgs_from_client{user="hello"} 1274924
telemt_user_msgs_to_client{user="hello"} 8333280
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34355.6 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58974
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 518
telemt_upstream_connect_attempt_total 56440
telemt_upstream_connect_success_total 56287
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 56440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56283
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 839949560 (801.04 MB)
telemt_user_octets_to_client{user="hello"} 37851335958 (35.25 GB)
telemt_user_msgs_from_client{user="hello"} 1159523
telemt_user_msgs_to_client{user="hello"} 7300480
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34356.8 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85485
telemt_connections_bad_total 8216
telemt_handshake_timeouts_total 1470
telemt_upstream_connect_attempt_total 72556
telemt_upstream_connect_success_total 72308
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 72556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72304
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 2089989815 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 57764808547 (53.80 GB)
telemt_user_msgs_from_client{user="hello"} 1997393
telemt_user_msgs_to_client{user="hello"} 8379188
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13326.2 (3h 42m)
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