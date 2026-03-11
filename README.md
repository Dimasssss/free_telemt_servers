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

# Server Metrics 2026-03-11 02:21:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 42911.0 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113535
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2557
telemt_upstream_connect_attempt_total 102472
telemt_upstream_connect_success_total 102436
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 102472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102432
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2875617722 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 80557689293 (75.03 GB)
telemt_user_msgs_from_client{user="hello"} 2906964
telemt_user_msgs_to_client{user="hello"} 5581744
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 42910.5 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46924
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2314
telemt_upstream_connect_attempt_total 41646
telemt_upstream_connect_success_total 41637
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 41646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41633
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2216538941 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 40811568556 (38.01 GB)
telemt_user_msgs_from_client{user="hello"} 1716802
telemt_user_msgs_to_client{user="hello"} 9955693
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 42910.1 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68116
telemt_connections_bad_total 649
telemt_handshake_timeouts_total 4149
telemt_upstream_connect_attempt_total 59487
telemt_upstream_connect_success_total 59485
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 59487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59479
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 11735527241 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69915941732 (65.11 GB)
telemt_user_msgs_from_client{user="hello"} 5117716
telemt_user_msgs_to_client{user="hello"} 13101414
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 42909.1 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66880
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 63982
telemt_upstream_connect_success_total 63826
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 63982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63820
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 1754758703 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42581281108 (39.66 GB)
telemt_user_msgs_from_client{user="hello"} 1581095
telemt_user_msgs_to_client{user="hello"} 8337299
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 42910.5 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98846
telemt_connections_bad_total 9948
telemt_handshake_timeouts_total 1522
telemt_upstream_connect_attempt_total 83686
telemt_upstream_connect_success_total 83438
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 83686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83434
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 2170812594 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 70446475561 (65.61 GB)
telemt_user_msgs_from_client{user="hello"} 2183147
telemt_user_msgs_to_client{user="hello"} 10039241
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21879.9 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```