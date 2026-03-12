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

# Server Metrics 2026-03-12 03:49:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21875.1 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45654
telemt_connections_bad_total 1938
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 41319
telemt_upstream_connect_success_total 41309
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 41319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41305
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 393083147 (374.87 MB)
telemt_user_octets_to_client{user="hello"} 12539283839 (11.68 GB)
telemt_user_msgs_from_client{user="hello"} 642998
telemt_user_msgs_to_client{user="hello"} 1553257
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21863.4 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17965
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 17150
telemt_upstream_connect_success_total 17150
telemt_upstream_connect_attempts_per_request{bucket="1"} 17150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17146
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 150256928 (143.30 MB)
telemt_user_octets_to_client{user="hello"} 9443779245 (8.80 GB)
telemt_user_msgs_from_client{user="hello"} 325963
telemt_user_msgs_to_client{user="hello"} 2603827
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21836.8 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31309
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 917
telemt_upstream_connect_attempt_total 27666
telemt_upstream_connect_success_total 27666
telemt_upstream_connect_attempts_per_request{bucket="1"} 27666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27662
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 5253341622 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 17359846997 (16.17 GB)
telemt_user_msgs_from_client{user="hello"} 2321961
telemt_user_msgs_to_client{user="hello"} 3441258
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21862.3 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32653
telemt_connections_bad_total 8602
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 22326
telemt_upstream_connect_success_total 20628
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 22326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20624
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 186426665 (177.79 MB)
telemt_user_octets_to_client{user="hello"} 15156579614 (14.12 GB)
telemt_user_msgs_from_client{user="hello"} 377646
telemt_user_msgs_to_client{user="hello"} 6255068
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21863.2 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26009
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 24112
telemt_upstream_connect_success_total 24111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 24112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24109
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 550583439 (525.08 MB)
telemt_user_octets_to_client{user="hello"} 30424842740 (28.34 GB)
telemt_user_msgs_from_client{user="hello"} 754968
telemt_user_msgs_to_client{user="hello"} 3841954
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```