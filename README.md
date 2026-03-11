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

# Server Metrics 2026-03-11 04:33:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 50856.0 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129848
telemt_connections_bad_total 3385
telemt_handshake_timeouts_total 2786
telemt_upstream_connect_attempt_total 117724
telemt_upstream_connect_success_total 117681
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 117724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117675
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 3026298509 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 85077272109 (79.23 GB)
telemt_user_msgs_from_client{user="hello"} 3116231
telemt_user_msgs_to_client{user="hello"} 5917935
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 50855.6 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53066
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 2947
telemt_upstream_connect_attempt_total 46922
telemt_upstream_connect_success_total 46912
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 46922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46906
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 4259125989 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 44437886340 (41.39 GB)
telemt_user_msgs_from_client{user="hello"} 2518942
telemt_user_msgs_to_client{user="hello"} 10602429
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 50855.2 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74028
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 4299
telemt_upstream_connect_attempt_total 64923
telemt_upstream_connect_success_total 64920
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 64923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64914
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 11770209524 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 70942625452 (66.07 GB)
telemt_user_msgs_from_client{user="hello"} 5172503
telemt_user_msgs_to_client{user="hello"} 13322201
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 50854.2 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76147
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 570
telemt_upstream_connect_attempt_total 72917
telemt_upstream_connect_success_total 72754
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 72917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72748
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 1806530492 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 47737621165 (44.46 GB)
telemt_user_msgs_from_client{user="hello"} 1695124
telemt_user_msgs_to_client{user="hello"} 10518031
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 50855.5 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121003
telemt_connections_bad_total 11505
telemt_handshake_timeouts_total 1666
telemt_upstream_connect_attempt_total 102962
telemt_upstream_connect_success_total 102713
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 102962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102707
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2345305997 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 96379261388 (89.76 GB)
telemt_user_msgs_from_client{user="hello"} 2520307
telemt_user_msgs_to_client{user="hello"} 12438990
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29824.8 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```