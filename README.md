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

# Server Metrics 2026-03-12 05:53:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29332.0 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75196
telemt_connections_bad_total 2109
telemt_handshake_timeouts_total 2216
telemt_upstream_connect_attempt_total 67383
telemt_upstream_connect_success_total 67364
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 67382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67360
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 687618979 (655.76 MB)
telemt_user_octets_to_client{user="hello"} 20998135176 (19.56 GB)
telemt_user_msgs_from_client{user="hello"} 1009109
telemt_user_msgs_to_client{user="hello"} 2403516
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29320.1 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29835
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 28426
telemt_upstream_connect_success_total 28419
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 28426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28415
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 270877058 (258.33 MB)
telemt_user_octets_to_client{user="hello"} 14997917914 (13.97 GB)
telemt_user_msgs_from_client{user="hello"} 536829
telemt_user_msgs_to_client{user="hello"} 4629275
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29293.9 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46182
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 1046
telemt_upstream_connect_attempt_total 41519
telemt_upstream_connect_success_total 41518
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 41519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41514
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 5361578800 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 26163356607 (24.37 GB)
telemt_user_msgs_from_client{user="hello"} 2585016
telemt_user_msgs_to_client{user="hello"} 4724651
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29319.2 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50788
telemt_connections_bad_total 12306
telemt_handshake_timeouts_total 835
telemt_upstream_connect_attempt_total 35758
telemt_upstream_connect_success_total 34057
telemt_upstream_connect_fail_total 1701
telemt_upstream_connect_attempts_per_request{bucket="1"} 35758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1701
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34053
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1147637844 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 22703315267 (21.14 GB)
telemt_user_msgs_from_client{user="hello"} 894479
telemt_user_msgs_to_client{user="hello"} 9383841
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29319.9 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45140
telemt_connections_bad_total 765
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 41925
telemt_upstream_connect_success_total 41920
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 41921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41916
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 788864312 (752.32 MB)
telemt_user_octets_to_client{user="hello"} 39401740161 (36.70 GB)
telemt_user_msgs_from_client{user="hello"} 1119667
telemt_user_msgs_to_client{user="hello"} 5292729
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```