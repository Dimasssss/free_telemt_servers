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

# Server Metrics 2026-03-12 05:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29656.5 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76223
telemt_connections_bad_total 2109
telemt_handshake_timeouts_total 2240
telemt_upstream_connect_attempt_total 68357
telemt_upstream_connect_success_total 68338
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 68357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68334
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 695964631 (663.72 MB)
telemt_user_octets_to_client{user="hello"} 21073968321 (19.63 GB)
telemt_user_msgs_from_client{user="hello"} 1020533
telemt_user_msgs_to_client{user="hello"} 2420919
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29644.5 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30529
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 152
telemt_upstream_connect_attempt_total 29091
telemt_upstream_connect_success_total 29084
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29080
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 274851662 (262.12 MB)
telemt_user_octets_to_client{user="hello"} 15114809389 (14.08 GB)
telemt_user_msgs_from_client{user="hello"} 546998
telemt_user_msgs_to_client{user="hello"} 4685406
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29618.3 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47112
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 1057
telemt_upstream_connect_attempt_total 42406
telemt_upstream_connect_success_total 42405
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 42406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42401
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 5367007008 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 26872498345 (25.03 GB)
telemt_user_msgs_from_client{user="hello"} 2601318
telemt_user_msgs_to_client{user="hello"} 4816197
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29643.5 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51867
telemt_connections_bad_total 12670
telemt_handshake_timeouts_total 838
telemt_upstream_connect_attempt_total 36438
telemt_upstream_connect_success_total 34737
telemt_upstream_connect_fail_total 1701
telemt_upstream_connect_attempts_per_request{bucket="1"} 36438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1701
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34733
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1212176225 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 23035618917 (21.45 GB)
telemt_user_msgs_from_client{user="hello"} 926631
telemt_user_msgs_to_client{user="hello"} 9527334
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29644.3 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46166
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 42927
telemt_upstream_connect_success_total 42924
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 42925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42920
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 806796486 (769.42 MB)
telemt_user_octets_to_client{user="hello"} 40968443874 (38.15 GB)
telemt_user_msgs_from_client{user="hello"} 1151379
telemt_user_msgs_to_client{user="hello"} 5444815
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 20
```