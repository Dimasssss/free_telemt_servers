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

# Server Metrics 2026-03-10 13:58:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 139124.8 (38h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318977
telemt_connections_bad_total 3625
telemt_handshake_timeouts_total 3366
telemt_upstream_connect_attempt_total 298641
telemt_upstream_connect_success_total 298482
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 298641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 276011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 298468
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 6847836972 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 196503385059 (183.01 GB)
telemt_user_msgs_from_client{user="hello"} 7134497
telemt_user_msgs_to_client{user="hello"} 11728864
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 139123.7 (38h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98581
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 1307
telemt_upstream_connect_attempt_total 88964
telemt_upstream_connect_success_total 88919
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 88964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88905
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2860554354 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 37882611082 (35.28 GB)
telemt_user_msgs_from_client{user="hello"} 2326666
telemt_user_msgs_to_client{user="hello"} 10973889
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 139124.2 (38h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140776
telemt_connections_bad_total 1238
telemt_handshake_timeouts_total 6599
telemt_upstream_connect_attempt_total 105750
telemt_upstream_connect_success_total 105747
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 105750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105733
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 6679314830 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 69045775977 (64.30 GB)
telemt_user_msgs_from_client{user="hello"} 4557132
telemt_user_msgs_to_client{user="hello"} 11726211
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 139119.1 (38h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144815
telemt_connections_bad_total 1063
telemt_handshake_timeouts_total 3058
telemt_upstream_connect_attempt_total 133792
telemt_upstream_connect_success_total 133492
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 133792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 133478
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 5055582468 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 94070144851 (87.61 GB)
telemt_user_msgs_from_client{user="hello"} 3888752
telemt_user_msgs_to_client{user="hello"} 21301955
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 139124.4 (38h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214738
telemt_connections_bad_total 31122
telemt_handshake_timeouts_total 6079
telemt_upstream_connect_attempt_total 168605
telemt_upstream_connect_success_total 167643
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 168605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 167629
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 3594279882 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 119719286902 (111.50 GB)
telemt_user_msgs_from_client{user="hello"} 3825826
telemt_user_msgs_to_client{user="hello"} 16436348
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 30
```