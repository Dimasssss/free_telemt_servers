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

# Server Metrics 2026-03-10 11:40:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 130831.0 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285312
telemt_connections_bad_total 3460
telemt_handshake_timeouts_total 3052
telemt_upstream_connect_attempt_total 266726
telemt_upstream_connect_success_total 266578
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 266726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 246284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 266566
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 6390951432 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 168316220893 (156.76 GB)
telemt_user_msgs_from_client{user="hello"} 6435916
telemt_user_msgs_to_client{user="hello"} 10327760
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 130829.7 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86976
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1231
telemt_upstream_connect_attempt_total 77936
telemt_upstream_connect_success_total 77892
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 77936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77878
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2712513408 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 34314780255 (31.96 GB)
telemt_user_msgs_from_client{user="hello"} 2135462
telemt_user_msgs_to_client{user="hello"} 9877850
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 130830.2 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123335
telemt_connections_bad_total 1199
telemt_handshake_timeouts_total 6248
telemt_upstream_connect_attempt_total 89585
telemt_upstream_connect_success_total 89583
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 89585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89571
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 6458345361 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 65004289600 (60.54 GB)
telemt_user_msgs_from_client{user="hello"} 4257794
telemt_user_msgs_to_client{user="hello"} 10731684
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 130825.0 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127027
telemt_connections_bad_total 1036
telemt_handshake_timeouts_total 1880
telemt_upstream_connect_attempt_total 117822
telemt_upstream_connect_success_total 117570
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 117822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 117558
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 3142335139 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 82144903539 (76.50 GB)
telemt_user_msgs_from_client{user="hello"} 2946595
telemt_user_msgs_to_client{user="hello"} 18881868
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 130830.2 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191463
telemt_connections_bad_total 28479
telemt_handshake_timeouts_total 4968
telemt_upstream_connect_attempt_total 149893
telemt_upstream_connect_success_total 148932
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 149893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148918
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 3340948534 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 111600591303 (103.94 GB)
telemt_user_msgs_from_client{user="hello"} 3457406
telemt_user_msgs_to_client{user="hello"} 15195149
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```