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

# Server Metrics 2026-03-12 03:11:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19605.8 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39683
telemt_connections_bad_total 1933
telemt_handshake_timeouts_total 319
telemt_upstream_connect_attempt_total 35647
telemt_upstream_connect_success_total 35640
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35638
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 329030076 (313.79 MB)
telemt_user_octets_to_client{user="hello"} 10809327717 (10.07 GB)
telemt_user_msgs_from_client{user="hello"} 563686
telemt_user_msgs_to_client{user="hello"} 1365728
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19594.0 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16086
telemt_connections_bad_total 105
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 15386
telemt_upstream_connect_success_total 15386
telemt_upstream_connect_attempts_per_request{bucket="1"} 15386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15384
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 134465033 (128.24 MB)
telemt_user_octets_to_client{user="hello"} 8912838841 (8.30 GB)
telemt_user_msgs_from_client{user="hello"} 290156
telemt_user_msgs_to_client{user="hello"} 2374157
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19567.4 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27495
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 24025
telemt_upstream_connect_success_total 24025
telemt_upstream_connect_attempts_per_request{bucket="1"} 24025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24021
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 5228553606 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 14640844343 (13.64 GB)
telemt_user_msgs_from_client{user="hello"} 2245509
telemt_user_msgs_to_client{user="hello"} 2891154
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19593.0 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29659
telemt_connections_bad_total 8512
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 19587
telemt_upstream_connect_success_total 17889
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 19587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17885
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 165034318 (157.39 MB)
telemt_user_octets_to_client{user="hello"} 12187061570 (11.35 GB)
telemt_user_msgs_from_client{user="hello"} 326210
telemt_user_msgs_to_client{user="hello"} 4912285
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19593.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22153
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 20461
telemt_upstream_connect_success_total 20461
telemt_upstream_connect_attempts_per_request{bucket="1"} 20461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20459
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 481314327 (459.02 MB)
telemt_user_octets_to_client{user="hello"} 28766737018 (26.79 GB)
telemt_user_msgs_from_client{user="hello"} 665820
telemt_user_msgs_to_client{user="hello"} 3564555
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```