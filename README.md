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

# Server Metrics 2026-03-12 04:59:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26089.7 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61371
telemt_connections_bad_total 2102
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 55061
telemt_upstream_connect_success_total 55045
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 55061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55041
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 580932773 (554.02 MB)
telemt_user_octets_to_client{user="hello"} 18939804995 (17.64 GB)
telemt_user_msgs_from_client{user="hello"} 867787
telemt_user_msgs_to_client{user="hello"} 2126714
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26077.9 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23114
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 21962
telemt_upstream_connect_success_total 21958
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 21962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21954
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 195772980 (186.70 MB)
telemt_user_octets_to_client{user="hello"} 12092530717 (11.26 GB)
telemt_user_msgs_from_client{user="hello"} 415986
telemt_user_msgs_to_client{user="hello"} 3455315
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26051.7 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38376
telemt_connections_bad_total 542
telemt_handshake_timeouts_total 978
telemt_upstream_connect_attempt_total 34173
telemt_upstream_connect_success_total 34172
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 34173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34168
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 5312908472 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 21524525468 (20.05 GB)
telemt_user_msgs_from_client{user="hello"} 2453948
telemt_user_msgs_to_client{user="hello"} 3900940
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26077.0 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40601
telemt_connections_bad_total 9805
telemt_handshake_timeouts_total 765
telemt_upstream_connect_attempt_total 28627
telemt_upstream_connect_success_total 26927
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 28627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26923
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 254749042 (242.95 MB)
telemt_user_octets_to_client{user="hello"} 20937203649 (19.50 GB)
telemt_user_msgs_from_client{user="hello"} 504188
telemt_user_msgs_to_client{user="hello"} 8697884
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26077.8 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36204
telemt_connections_bad_total 753
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 33290
telemt_upstream_connect_success_total 33289
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 33290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33285
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 657931665 (627.45 MB)
telemt_user_octets_to_client{user="hello"} 34253505550 (31.90 GB)
telemt_user_msgs_from_client{user="hello"} 917594
telemt_user_msgs_to_client{user="hello"} 4632374
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```