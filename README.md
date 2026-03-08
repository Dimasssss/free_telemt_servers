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

# Server Metrics 2026-03-08 23:08:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 57569.4 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119976
telemt_connections_bad_total 5809
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 109015
telemt_upstream_connect_success_total 108977
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 109015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108971
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 2623166679 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 77115620874 (71.82 GB)
telemt_user_msgs_from_client{user="hello"} 2741289
telemt_user_msgs_to_client{user="hello"} 4131174
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 57568.3 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27635
telemt_connections_bad_total 320
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26710
telemt_upstream_connect_success_total 26703
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26697
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 842238803 (803.22 MB)
telemt_user_octets_to_client{user="hello"} 22928643171 (21.35 GB)
telemt_user_msgs_from_client{user="hello"} 988556
telemt_user_msgs_to_client{user="hello"} 6211689
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 57568.2 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15732
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14294
telemt_upstream_connect_success_total 14218
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14212
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1576165297 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 5710188760 (5.32 GB)
telemt_user_msgs_from_client{user="hello"} 706874
telemt_user_msgs_to_client{user="hello"} 984090
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 57568.0 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21661
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20777
telemt_upstream_connect_success_total 20736
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20730
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 1069064004 (1019.54 MB)
telemt_user_octets_to_client{user="hello"} 6662162079 (6.20 GB)
telemt_user_msgs_from_client{user="hello"} 579183
telemt_user_msgs_to_client{user="hello"} 1520530
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 57568.3 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32769
telemt_connections_bad_total 10932
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 21078
telemt_upstream_connect_success_total 21071
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 21078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21065
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 388868118 (370.85 MB)
telemt_user_octets_to_client{user="hello"} 18327480866 (17.07 GB)
telemt_user_msgs_from_client{user="hello"} 561798
telemt_user_msgs_to_client{user="hello"} 2367368
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```