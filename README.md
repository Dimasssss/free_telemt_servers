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

# Server Metrics 2026-03-11 16:14:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 92880.1 (25h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319474
telemt_connections_bad_total 5945
telemt_handshake_timeouts_total 5818
telemt_upstream_connect_attempt_total 293580
telemt_upstream_connect_success_total 293499
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 293580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 293489
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 5497285612 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 141762721945 (132.03 GB)
telemt_user_msgs_from_client{user="hello"} 6317418
telemt_user_msgs_to_client{user="hello"} 11494496
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 92879.7 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126628
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 3428
telemt_upstream_connect_attempt_total 116861
telemt_upstream_connect_success_total 116838
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 116861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 571
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116828
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 6100602925 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 72366612319 (67.40 GB)
telemt_user_msgs_from_client{user="hello"} 4147482
telemt_user_msgs_to_client{user="hello"} 21234655
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 92879.7 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172456
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7834
telemt_upstream_connect_attempt_total 153783
telemt_upstream_connect_success_total 153769
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 153783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153759
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 12772136871 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 133096223376 (123.96 GB)
telemt_user_msgs_from_client{user="hello"} 6951055
telemt_user_msgs_to_client{user="hello"} 30123567
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92878.4 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194672
telemt_connections_bad_total 9408
telemt_handshake_timeouts_total 3027
telemt_upstream_connect_attempt_total 174417
telemt_upstream_connect_success_total 173996
telemt_upstream_connect_fail_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 174417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 474
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 421
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 173986
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 10111023462 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 120470074695 (112.20 GB)
telemt_user_msgs_from_client{user="hello"} 6081239
telemt_user_msgs_to_client{user="hello"} 36004753
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 71849.6 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 12
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