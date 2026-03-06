# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-06 16:57:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 23759.3 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56051
telemt_connections_bad_total 3112
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 48991
telemt_upstream_connect_success_total 48979
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 48991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48975
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 2559182999 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 32121450845 (29.92 GB)
telemt_user_msgs_from_client{user="hello"} 1736348
telemt_user_msgs_to_client{user="hello"} 5081101
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 23758.7 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10509
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 9981
telemt_upstream_connect_success_total 9962
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9960
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 130280954 (124.25 MB)
telemt_user_octets_to_client{user="hello"} 5746541684 (5.35 GB)
telemt_user_msgs_from_client{user="hello"} 212921
telemt_user_msgs_to_client{user="hello"} 1774638
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 23758.0 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8746
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 8425
telemt_upstream_connect_success_total 8423
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8421
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 124654491 (118.88 MB)
telemt_user_octets_to_client{user="hello"} 5015136903 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 189880
telemt_user_msgs_to_client{user="hello"} 1186051
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 23757.3 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12358
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11448
telemt_upstream_connect_success_total 11410
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 11448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11408
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 156094243 (148.86 MB)
telemt_user_octets_to_client{user="hello"} 3826513662 (3.56 GB)
telemt_user_msgs_from_client{user="hello"} 195886
telemt_user_msgs_to_client{user="hello"} 973814
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 23758.6 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17048
telemt_connections_bad_total 5832
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 10364
telemt_upstream_connect_success_total 10364
telemt_upstream_connect_attempts_per_request{bucket="1"} 10364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10362
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 242100041 (230.88 MB)
telemt_user_octets_to_client{user="hello"} 21825190134 (20.33 GB)
telemt_user_msgs_from_client{user="hello"} 403648
telemt_user_msgs_to_client{user="hello"} 3942970
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```