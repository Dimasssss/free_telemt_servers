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

# Server Metrics 2026-03-11 02:46:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 44438.9 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116978
telemt_connections_bad_total 3356
telemt_handshake_timeouts_total 2567
telemt_upstream_connect_attempt_total 105742
telemt_upstream_connect_success_total 105704
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 105742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105698
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2899745389 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 81668881154 (76.06 GB)
telemt_user_msgs_from_client{user="hello"} 2943822
telemt_user_msgs_to_client{user="hello"} 5639250
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 44438.3 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48646
telemt_connections_bad_total 367
telemt_handshake_timeouts_total 2910
telemt_upstream_connect_attempt_total 42736
telemt_upstream_connect_success_total 42727
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42723
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 2270675701 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 41549856764 (38.70 GB)
telemt_user_msgs_from_client{user="hello"} 1750363
telemt_user_msgs_to_client{user="hello"} 10086402
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 44438.0 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69270
telemt_connections_bad_total 656
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 60524
telemt_upstream_connect_success_total 60522
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 60524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60516
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 11741948640 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70018861647 (65.21 GB)
telemt_user_msgs_from_client{user="hello"} 5127681
telemt_user_msgs_to_client{user="hello"} 13133834
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 44437.0 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68122
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 544
telemt_upstream_connect_attempt_total 65162
telemt_upstream_connect_success_total 65005
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 65162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64999
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1761004577 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42653953634 (39.72 GB)
telemt_user_msgs_from_client{user="hello"} 1590745
telemt_user_msgs_to_client{user="hello"} 8363526
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 44438.3 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102921
telemt_connections_bad_total 10242
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 87321
telemt_upstream_connect_success_total 87073
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 87321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87069
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2193555506 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 75628263980 (70.43 GB)
telemt_user_msgs_from_client{user="hello"} 2237542
telemt_user_msgs_to_client{user="hello"} 10417819
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23407.7 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```