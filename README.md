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

# Server Metrics 2026-03-12 01:02:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11824.0 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22370
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 19718
telemt_upstream_connect_success_total 19712
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19710
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 218181744 (208.07 MB)
telemt_user_octets_to_client{user="hello"} 7013503051 (6.53 GB)
telemt_user_msgs_from_client{user="hello"} 370846
telemt_user_msgs_to_client{user="hello"} 948250
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11812.3 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9075
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 8698
telemt_upstream_connect_success_total 8698
telemt_upstream_connect_attempts_per_request{bucket="1"} 8698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8696
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 60412835 (57.61 MB)
telemt_user_octets_to_client{user="hello"} 3190093153 (2.97 GB)
telemt_user_msgs_from_client{user="hello"} 151431
telemt_user_msgs_to_client{user="hello"} 1009677
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11785.9 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15682
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 854
telemt_upstream_connect_attempt_total 12916
telemt_upstream_connect_success_total 12916
telemt_upstream_connect_attempts_per_request{bucket="1"} 12916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12914
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 243593396 (232.31 MB)
telemt_user_octets_to_client{user="hello"} 7172252897 (6.68 GB)
telemt_user_msgs_from_client{user="hello"} 308259
telemt_user_msgs_to_client{user="hello"} 1623349
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11811.3 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15307
telemt_connections_bad_total 3060
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 10994
telemt_upstream_connect_success_total 10983
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 10994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10981
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 85835632 (81.86 MB)
telemt_user_octets_to_client{user="hello"} 5077364848 (4.73 GB)
telemt_user_msgs_from_client{user="hello"} 171446
telemt_user_msgs_to_client{user="hello"} 1899172
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11812.1 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12062
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 10854
telemt_upstream_connect_success_total 10854
telemt_upstream_connect_attempts_per_request{bucket="1"} 10854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10852
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 162172134 (154.66 MB)
telemt_user_octets_to_client{user="hello"} 17417770004 (16.22 GB)
telemt_user_msgs_from_client{user="hello"} 296476
telemt_user_msgs_to_client{user="hello"} 1585400
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```