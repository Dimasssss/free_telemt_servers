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

# Server Metrics 2026-03-12 03:06:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19281.3 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38798
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 306
telemt_upstream_connect_attempt_total 34826
telemt_upstream_connect_success_total 34819
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34817
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 322540757 (307.60 MB)
telemt_user_octets_to_client{user="hello"} 10677018065 (9.94 GB)
telemt_user_msgs_from_client{user="hello"} 552213
telemt_user_msgs_to_client{user="hello"} 1346603
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19269.6 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15891
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 15203
telemt_upstream_connect_success_total 15203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15201
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 133003045 (126.84 MB)
telemt_user_octets_to_client{user="hello"} 8859519484 (8.25 GB)
telemt_user_msgs_from_client{user="hello"} 286983
telemt_user_msgs_to_client{user="hello"} 2358153
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19243.1 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27056
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 909
telemt_upstream_connect_attempt_total 23603
telemt_upstream_connect_success_total 23603
telemt_upstream_connect_attempts_per_request{bucket="1"} 23603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23599
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 5222958502 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 13637746834 (12.70 GB)
telemt_user_msgs_from_client{user="hello"} 2228636
telemt_user_msgs_to_client{user="hello"} 2755150
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19268.7 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29303
telemt_connections_bad_total 8512
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 19244
telemt_upstream_connect_success_total 17546
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 19244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17542
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 164129622 (156.53 MB)
telemt_user_octets_to_client{user="hello"} 12181944778 (11.35 GB)
telemt_user_msgs_from_client{user="hello"} 324097
telemt_user_msgs_to_client{user="hello"} 4909205
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19269.5 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21588
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 19915
telemt_upstream_connect_success_total 19915
telemt_upstream_connect_attempts_per_request{bucket="1"} 19915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19913
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 474522331 (452.54 MB)
telemt_user_octets_to_client{user="hello"} 28130061244 (26.20 GB)
telemt_user_msgs_from_client{user="hello"} 648740
telemt_user_msgs_to_client{user="hello"} 3468979
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```