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

# Server Metrics 2026-03-11 02:26:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 43216.8 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114181
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2558
telemt_upstream_connect_attempt_total 103062
telemt_upstream_connect_success_total 103026
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 103062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103022
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 2880620319 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 80647354218 (75.11 GB)
telemt_user_msgs_from_client{user="hello"} 2913493
telemt_user_msgs_to_client{user="hello"} 5590658
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 43215.9 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47162
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2314
telemt_upstream_connect_attempt_total 41878
telemt_upstream_connect_success_total 41869
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 41878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41865
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2265351851 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 41065940780 (38.25 GB)
telemt_user_msgs_from_client{user="hello"} 1738734
telemt_user_msgs_to_client{user="hello"} 10001293
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 43215.8 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68262
telemt_connections_bad_total 652
telemt_handshake_timeouts_total 4154
telemt_upstream_connect_attempt_total 59620
telemt_upstream_connect_success_total 59618
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 59620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59612
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 11736073199 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69918767711 (65.12 GB)
telemt_user_msgs_from_client{user="hello"} 5119006
telemt_user_msgs_to_client{user="hello"} 13103287
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 43214.7 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67050
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 64146
telemt_upstream_connect_success_total 63990
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 64146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63984
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1755038183 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42582998525 (39.66 GB)
telemt_user_msgs_from_client{user="hello"} 1581924
telemt_user_msgs_to_client{user="hello"} 8338632
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 43216.0 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99680
telemt_connections_bad_total 10003
telemt_handshake_timeouts_total 1523
telemt_upstream_connect_attempt_total 84432
telemt_upstream_connect_success_total 84184
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 84432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84180
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 2175543906 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 71475432817 (66.57 GB)
telemt_user_msgs_from_client{user="hello"} 2193455
telemt_user_msgs_to_client{user="hello"} 10121198
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22185.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```