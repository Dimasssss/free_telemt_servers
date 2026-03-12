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

# Server Metrics 2026-03-12 04:05:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22848.2 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48428
telemt_connections_bad_total 1981
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 43942
telemt_upstream_connect_success_total 43928
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 43942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43924
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 490063395 (467.36 MB)
telemt_user_octets_to_client{user="hello"} 14231558679 (13.25 GB)
telemt_user_msgs_from_client{user="hello"} 715179
telemt_user_msgs_to_client{user="hello"} 1722743
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22836.5 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19077
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 18157
telemt_upstream_connect_success_total 18155
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18151
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 165190175 (157.54 MB)
telemt_user_octets_to_client{user="hello"} 10776300157 (10.04 GB)
telemt_user_msgs_from_client{user="hello"} 347801
telemt_user_msgs_to_client{user="hello"} 2846631
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22810.3 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32740
telemt_connections_bad_total 405
telemt_handshake_timeouts_total 921
telemt_upstream_connect_attempt_total 28980
telemt_upstream_connect_success_total 28980
telemt_upstream_connect_attempts_per_request{bucket="1"} 28980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28976
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 5265000916 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 19000262517 (17.70 GB)
telemt_user_msgs_from_client{user="hello"} 2353647
telemt_user_msgs_to_client{user="hello"} 3589392
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22835.7 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33973
telemt_connections_bad_total 8612
telemt_handshake_timeouts_total 731
telemt_upstream_connect_attempt_total 23582
telemt_upstream_connect_success_total 21884
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 23582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21880
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 202501831 (193.12 MB)
telemt_user_octets_to_client{user="hello"} 18762633753 (17.47 GB)
telemt_user_msgs_from_client{user="hello"} 421022
telemt_user_msgs_to_client{user="hello"} 7907900
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22836.3 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28266
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 159
telemt_upstream_connect_attempt_total 26289
telemt_upstream_connect_success_total 26288
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 26289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26286
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 595957284 (568.35 MB)
telemt_user_octets_to_client{user="hello"} 31129298805 (28.99 GB)
telemt_user_msgs_from_client{user="hello"} 806200
telemt_user_msgs_to_client{user="hello"} 3994071
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 22
```