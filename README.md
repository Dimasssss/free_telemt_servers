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

# Server Metrics 2026-03-12 04:38:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24793.7 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55524
telemt_connections_bad_total 2084
telemt_handshake_timeouts_total 861
telemt_upstream_connect_attempt_total 50100
telemt_upstream_connect_success_total 50086
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 50100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50082
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 542844235 (517.70 MB)
telemt_user_octets_to_client{user="hello"} 15917861990 (14.82 GB)
telemt_user_msgs_from_client{user="hello"} 793991
telemt_user_msgs_to_client{user="hello"} 1928900
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24781.8 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21470
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 20379
telemt_upstream_connect_success_total 20376
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20372
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 185222253 (176.64 MB)
telemt_user_octets_to_client{user="hello"} 11718026499 (10.91 GB)
telemt_user_msgs_from_client{user="hello"} 393156
telemt_user_msgs_to_client{user="hello"} 3251291
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24755.3 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36228
telemt_connections_bad_total 521
telemt_handshake_timeouts_total 970
telemt_upstream_connect_attempt_total 32147
telemt_upstream_connect_success_total 32147
telemt_upstream_connect_attempts_per_request{bucket="1"} 32147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32143
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 5287980529 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 20824104886 (19.39 GB)
telemt_user_msgs_from_client{user="hello"} 2415266
telemt_user_msgs_to_client{user="hello"} 3793635
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24781.0 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36971
telemt_connections_bad_total 8656
telemt_handshake_timeouts_total 750
telemt_upstream_connect_attempt_total 26395
telemt_upstream_connect_success_total 24695
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 26395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24691
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 237689280 (226.68 MB)
telemt_user_octets_to_client{user="hello"} 19869501312 (18.50 GB)
telemt_user_msgs_from_client{user="hello"} 470038
telemt_user_msgs_to_client{user="hello"} 8294915
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24781.6 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32745
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 30565
telemt_upstream_connect_success_total 30564
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 30565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30562
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 640305188 (610.64 MB)
telemt_user_octets_to_client{user="hello"} 33119320226 (30.84 GB)
telemt_user_msgs_from_client{user="hello"} 877536
telemt_user_msgs_to_client{user="hello"} 4370176
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```