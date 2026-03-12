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

# Server Metrics 2026-03-12 04:43:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25117.7 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57335
telemt_connections_bad_total 2084
telemt_handshake_timeouts_total 1007
telemt_upstream_connect_attempt_total 51663
telemt_upstream_connect_success_total 51648
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 51663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51644
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 559464055 (533.55 MB)
telemt_user_octets_to_client{user="hello"} 18032605704 (16.79 GB)
telemt_user_msgs_from_client{user="hello"} 827280
telemt_user_msgs_to_client{user="hello"} 2035704
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25105.6 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21874
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 20766
telemt_upstream_connect_success_total 20762
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20758
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 188103010 (179.39 MB)
telemt_user_octets_to_client{user="hello"} 11909539562 (11.09 GB)
telemt_user_msgs_from_client{user="hello"} 400519
telemt_user_msgs_to_client{user="hello"} 3353005
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25079.4 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36790
telemt_connections_bad_total 522
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 32658
telemt_upstream_connect_success_total 32657
telemt_upstream_connect_attempts_per_request{bucket="1"} 32657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32653
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 5290402630 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 20854918325 (19.42 GB)
telemt_user_msgs_from_client{user="hello"} 2422473
telemt_user_msgs_to_client{user="hello"} 3808784
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25104.8 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37525
telemt_connections_bad_total 8656
telemt_handshake_timeouts_total 752
telemt_upstream_connect_attempt_total 26916
telemt_upstream_connect_success_total 25216
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 26916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25212
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 241871599 (230.67 MB)
telemt_user_octets_to_client{user="hello"} 20044259733 (18.67 GB)
telemt_user_msgs_from_client{user="hello"} 477617
telemt_user_msgs_to_client{user="hello"} 8358801
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25105.5 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33500
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 31285
telemt_upstream_connect_success_total 31284
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 31285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31280
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 646908927 (616.94 MB)
telemt_user_octets_to_client{user="hello"} 33485537843 (31.19 GB)
telemt_user_msgs_from_client{user="hello"} 889002
telemt_user_msgs_to_client{user="hello"} 4441567
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```