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

# Server Metrics 2026-03-12 03:44:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21550.9 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44739
telemt_connections_bad_total 1934
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 40441
telemt_upstream_connect_success_total 40431
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 40441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40427
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 368525783 (351.45 MB)
telemt_user_octets_to_client{user="hello"} 11923120162 (11.10 GB)
telemt_user_msgs_from_client{user="hello"} 623264
telemt_user_msgs_to_client{user="hello"} 1501920
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21539.0 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17682
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 16885
telemt_upstream_connect_success_total 16885
telemt_upstream_connect_attempts_per_request{bucket="1"} 16885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16881
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 148736990 (141.85 MB)
telemt_user_octets_to_client{user="hello"} 9382880612 (8.74 GB)
telemt_user_msgs_from_client{user="hello"} 322430
telemt_user_msgs_to_client{user="hello"} 2581470
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21512.6 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30750
telemt_connections_bad_total 384
telemt_handshake_timeouts_total 917
telemt_upstream_connect_attempt_total 27127
telemt_upstream_connect_success_total 27127
telemt_upstream_connect_attempts_per_request{bucket="1"} 27127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27123
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 5251783219 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 17289259290 (16.10 GB)
telemt_user_msgs_from_client{user="hello"} 2317089
telemt_user_msgs_to_client{user="hello"} 3428887
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21538.0 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32233
telemt_connections_bad_total 8600
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 21922
telemt_upstream_connect_success_total 20224
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 21922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3063
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20220
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 183170361 (174.68 MB)
telemt_user_octets_to_client{user="hello"} 15071727599 (14.04 GB)
telemt_user_msgs_from_client{user="hello"} 370870
telemt_user_msgs_to_client{user="hello"} 6215215
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21538.8 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25322
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 23460
telemt_upstream_connect_success_total 23459
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 23460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23457
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 546618095 (521.30 MB)
telemt_user_octets_to_client{user="hello"} 30299333969 (28.22 GB)
telemt_user_msgs_from_client{user="hello"} 744596
telemt_user_msgs_to_client{user="hello"} 3813478
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```