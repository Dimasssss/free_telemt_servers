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

# Server Metrics 2026-03-12 00:45:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10851.4 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20830
telemt_connections_bad_total 1805
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 18222
telemt_upstream_connect_success_total 18216
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 18222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18214
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 202162420 (192.80 MB)
telemt_user_octets_to_client{user="hello"} 6835692410 (6.37 GB)
telemt_user_msgs_from_client{user="hello"} 353561
telemt_user_msgs_to_client{user="hello"} 921893
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10839.7 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8352
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 8011
telemt_upstream_connect_success_total 8011
telemt_upstream_connect_attempts_per_request{bucket="1"} 8011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8009
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 54861563 (52.32 MB)
telemt_user_octets_to_client{user="hello"} 2904744122 (2.71 GB)
telemt_user_msgs_from_client{user="hello"} 137134
telemt_user_msgs_to_client{user="hello"} 933383
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10817.1 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14181
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 799
telemt_upstream_connect_attempt_total 11587
telemt_upstream_connect_success_total 11587
telemt_upstream_connect_attempts_per_request{bucket="1"} 11587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11585
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 72911534 (69.53 MB)
telemt_user_octets_to_client{user="hello"} 6697210339 (6.24 GB)
telemt_user_msgs_from_client{user="hello"} 227533
telemt_user_msgs_to_client{user="hello"} 1524273
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10838.5 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12959
telemt_connections_bad_total 2213
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 10090
telemt_upstream_connect_success_total 10079
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 10090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10077
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 72729095 (69.36 MB)
telemt_user_octets_to_client{user="hello"} 4437251544 (4.13 GB)
telemt_user_msgs_from_client{user="hello"} 156755
telemt_user_msgs_to_client{user="hello"} 1629282
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10839.5 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10962
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 9784
telemt_upstream_connect_success_total 9784
telemt_upstream_connect_attempts_per_request{bucket="1"} 9784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9782
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 130924346 (124.86 MB)
telemt_user_octets_to_client{user="hello"} 17004981166 (15.84 GB)
telemt_user_msgs_from_client{user="hello"} 268536
telemt_user_msgs_to_client{user="hello"} 1536626
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```