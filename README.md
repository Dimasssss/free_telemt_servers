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

# Server Metrics 2026-03-08 18:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 41863.9 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97114
telemt_connections_bad_total 5049
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 87625
telemt_upstream_connect_success_total 87596
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 87625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87590
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2143840025 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 54239285067 (50.51 GB)
telemt_user_msgs_from_client{user="hello"} 2123584
telemt_user_msgs_to_client{user="hello"} 2989081
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 41863.3 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22027
telemt_connections_bad_total 189
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21330
telemt_upstream_connect_success_total 21325
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21321
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 733859874 (699.86 MB)
telemt_user_octets_to_client{user="hello"} 19900940419 (18.53 GB)
telemt_user_msgs_from_client{user="hello"} 850705
telemt_user_msgs_to_client{user="hello"} 5457757
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 41862.9 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13579
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12254
telemt_upstream_connect_success_total 12178
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12174
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 241170805 (230.00 MB)
telemt_user_octets_to_client{user="hello"} 4215546300 (3.93 GB)
telemt_user_msgs_from_client{user="hello"} 206483
telemt_user_msgs_to_client{user="hello"} 754033
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 41862.8 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17361
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 16608
telemt_upstream_connect_success_total 16572
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 16608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16568
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 1038063534 (989.97 MB)
telemt_user_octets_to_client{user="hello"} 5896476251 (5.49 GB)
telemt_user_msgs_from_client{user="hello"} 539464
telemt_user_msgs_to_client{user="hello"} 1338432
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 41863.1 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24631
telemt_connections_bad_total 7934
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 16101
telemt_upstream_connect_success_total 16095
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 16101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16089
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 307838096 (293.58 MB)
telemt_user_octets_to_client{user="hello"} 12284059248 (11.44 GB)
telemt_user_msgs_from_client{user="hello"} 395183
telemt_user_msgs_to_client{user="hello"} 1616637
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```