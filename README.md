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

# Server Metrics 2026-03-12 03:01:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18957.3 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38002
telemt_connections_bad_total 1923
telemt_handshake_timeouts_total 302
telemt_upstream_connect_attempt_total 34083
telemt_upstream_connect_success_total 34076
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34074
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 319101258 (304.32 MB)
telemt_user_octets_to_client{user="hello"} 10568506400 (9.84 GB)
telemt_user_msgs_from_client{user="hello"} 544851
telemt_user_msgs_to_client{user="hello"} 1332063
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18945.6 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15598
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 14919
telemt_upstream_connect_success_total 14919
telemt_upstream_connect_attempts_per_request{bucket="1"} 14919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14917
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 129324764 (123.33 MB)
telemt_user_octets_to_client{user="hello"} 8720206041 (8.12 GB)
telemt_user_msgs_from_client{user="hello"} 279617
telemt_user_msgs_to_client{user="hello"} 2321384
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18919.1 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26584
telemt_connections_bad_total 365
telemt_handshake_timeouts_total 907
telemt_upstream_connect_attempt_total 23153
telemt_upstream_connect_success_total 23153
telemt_upstream_connect_attempts_per_request{bucket="1"} 23153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23149
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 5218616306 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 12957010082 (12.07 GB)
telemt_user_msgs_from_client{user="hello"} 2214678
telemt_user_msgs_to_client{user="hello"} 2692152
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18944.6 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28961
telemt_connections_bad_total 8512
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 18922
telemt_upstream_connect_success_total 17224
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 18922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17220
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 162654158 (155.12 MB)
telemt_user_octets_to_client{user="hello"} 12122187424 (11.29 GB)
telemt_user_msgs_from_client{user="hello"} 320336
telemt_user_msgs_to_client{user="hello"} 4881448
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18945.5 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21045
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 19397
telemt_upstream_connect_success_total 19397
telemt_upstream_connect_attempts_per_request{bucket="1"} 19397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19395
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 462718751 (441.28 MB)
telemt_user_octets_to_client{user="hello"} 26345210918 (24.54 GB)
telemt_user_msgs_from_client{user="hello"} 620265
telemt_user_msgs_to_client{user="hello"} 3262602
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```