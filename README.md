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

# Server Metrics 2026-03-08 17:55:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 38783.7 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91911
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1239
telemt_upstream_connect_attempt_total 82553
telemt_upstream_connect_success_total 82524
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 82553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82518
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 2019653948 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 50926601334 (47.43 GB)
telemt_user_msgs_from_client{user="hello"} 1986906
telemt_user_msgs_to_client{user="hello"} 2818567
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 38782.9 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20474
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 19782
telemt_upstream_connect_success_total 19778
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 19782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19774
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 712214669 (679.22 MB)
telemt_user_octets_to_client{user="hello"} 18961056852 (17.66 GB)
telemt_user_msgs_from_client{user="hello"} 811886
telemt_user_msgs_to_client{user="hello"} 5206857
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 38782.6 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12860
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11545
telemt_upstream_connect_success_total 11469
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11465
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 234940391 (224.06 MB)
telemt_user_octets_to_client{user="hello"} 4165545821 (3.88 GB)
telemt_user_msgs_from_client{user="hello"} 200517
telemt_user_msgs_to_client{user="hello"} 737820
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 38782.5 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16197
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15475
telemt_upstream_connect_success_total 15441
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15437
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 1017917358 (970.76 MB)
telemt_user_octets_to_client{user="hello"} 5720254598 (5.33 GB)
telemt_user_msgs_from_client{user="hello"} 527250
telemt_user_msgs_to_client{user="hello"} 1289489
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 38782.8 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22816
telemt_connections_bad_total 7363
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 14871
telemt_upstream_connect_success_total 14866
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14862
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 264787209 (252.52 MB)
telemt_user_octets_to_client{user="hello"} 11425867908 (10.64 GB)
telemt_user_msgs_from_client{user="hello"} 355097
telemt_user_msgs_to_client{user="hello"} 1510320
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```