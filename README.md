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

# Server Metrics 2026-03-12 01:34:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13768.1 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26120
telemt_connections_bad_total 1845
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 23246
telemt_upstream_connect_success_total 23240
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 23246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23238
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 252463954 (240.77 MB)
telemt_user_octets_to_client{user="hello"} 8200557484 (7.64 GB)
telemt_user_msgs_from_client{user="hello"} 428498
telemt_user_msgs_to_client{user="hello"} 1052694
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13756.2 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11147
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 10706
telemt_upstream_connect_success_total 10706
telemt_upstream_connect_attempts_per_request{bucket="1"} 10706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10704
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 70903884 (67.62 MB)
telemt_user_octets_to_client{user="hello"} 3665571650 (3.41 GB)
telemt_user_msgs_from_client{user="hello"} 175200
telemt_user_msgs_to_client{user="hello"} 1200988
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13729.8 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18226
telemt_connections_bad_total 287
telemt_handshake_timeouts_total 867
telemt_upstream_connect_attempt_total 15244
telemt_upstream_connect_success_total 15244
telemt_upstream_connect_attempts_per_request{bucket="1"} 15244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15242
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 2273672081 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 7955573725 (7.41 GB)
telemt_user_msgs_from_client{user="hello"} 1057192
telemt_user_msgs_to_client{user="hello"} 1736639
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13755.2 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19989
telemt_connections_bad_total 5930
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 12751
telemt_upstream_connect_success_total 12740
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 12751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12738
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 100470407 (95.82 MB)
telemt_user_octets_to_client{user="hello"} 5977464102 (5.57 GB)
telemt_user_msgs_from_client{user="hello"} 201688
telemt_user_msgs_to_client{user="hello"} 2262353
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13755.9 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15002
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 13592
telemt_upstream_connect_success_total 13592
telemt_upstream_connect_attempts_per_request{bucket="1"} 13592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13590
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 206307315 (196.75 MB)
telemt_user_octets_to_client{user="hello"} 20238132898 (18.85 GB)
telemt_user_msgs_from_client{user="hello"} 385790
telemt_user_msgs_to_client{user="hello"} 1903019
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```