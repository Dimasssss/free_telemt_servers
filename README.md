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

# Server Metrics 2026-03-12 04:22:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23820.9 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51397
telemt_connections_bad_total 1983
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 46735
telemt_upstream_connect_success_total 46720
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 46734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46716
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 506327783 (482.87 MB)
telemt_user_octets_to_client{user="hello"} 14996916450 (13.97 GB)
telemt_user_msgs_from_client{user="hello"} 749769
telemt_user_msgs_to_client{user="hello"} 1799489
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23809.3 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20143
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 19161
telemt_upstream_connect_success_total 19158
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19154
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 172056446 (164.09 MB)
telemt_user_octets_to_client{user="hello"} 11227682926 (10.46 GB)
telemt_user_msgs_from_client{user="hello"} 363126
telemt_user_msgs_to_client{user="hello"} 3056409
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23782.7 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34539
telemt_connections_bad_total 434
telemt_handshake_timeouts_total 932
telemt_upstream_connect_attempt_total 30665
telemt_upstream_connect_success_total 30665
telemt_upstream_connect_attempts_per_request{bucket="1"} 30665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30661
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 5280622201 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 20610414569 (19.19 GB)
telemt_user_msgs_from_client{user="hello"} 2390910
telemt_user_msgs_to_client{user="hello"} 3730339
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23808.3 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35399
telemt_connections_bad_total 8655
telemt_handshake_timeouts_total 742
telemt_upstream_connect_attempt_total 24909
telemt_upstream_connect_success_total 23210
telemt_upstream_connect_fail_total 1699
telemt_upstream_connect_attempts_per_request{bucket="1"} 24909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1699
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23206
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 224618901 (214.21 MB)
telemt_user_octets_to_client{user="hello"} 19270356107 (17.95 GB)
telemt_user_msgs_from_client{user="hello"} 445379
telemt_user_msgs_to_client{user="hello"} 8071279
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23808.9 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30236
telemt_connections_bad_total 169
telemt_handshake_timeouts_total 166
telemt_upstream_connect_attempt_total 28117
telemt_upstream_connect_success_total 28116
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 28117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28114
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 624921206 (595.97 MB)
telemt_user_octets_to_client{user="hello"} 32384081097 (30.16 GB)
telemt_user_msgs_from_client{user="hello"} 841292
telemt_user_msgs_to_client{user="hello"} 4204776
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```