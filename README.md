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

# Server Metrics 2026-03-08 17:29:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 37242.9 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88940
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1131
telemt_upstream_connect_attempt_total 79759
telemt_upstream_connect_success_total 79731
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 79759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79725
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 1985225072 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 47739526453 (44.46 GB)
telemt_user_msgs_from_client{user="hello"} 1908545
telemt_user_msgs_to_client{user="hello"} 2683141
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 37242.2 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19480
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 18869
telemt_upstream_connect_success_total 18865
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18861
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 683415181 (651.76 MB)
telemt_user_octets_to_client{user="hello"} 18567959178 (17.29 GB)
telemt_user_msgs_from_client{user="hello"} 738050
telemt_user_msgs_to_client{user="hello"} 5045846
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 37241.9 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11937
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 11170
telemt_upstream_connect_success_total 11094
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11090
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 229649912 (219.01 MB)
telemt_user_octets_to_client{user="hello"} 3994310904 (3.72 GB)
telemt_user_msgs_from_client{user="hello"} 192493
telemt_user_msgs_to_client{user="hello"} 703656
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 37241.7 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15709
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 14996
telemt_upstream_connect_success_total 14964
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 14996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14960
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1014918009 (967.90 MB)
telemt_user_octets_to_client{user="hello"} 5293148277 (4.93 GB)
telemt_user_msgs_from_client{user="hello"} 519080
telemt_user_msgs_to_client{user="hello"} 1200256
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 37242.0 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21300
telemt_connections_bad_total 6880
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 13876
telemt_upstream_connect_success_total 13872
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13868
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 260325801 (248.27 MB)
telemt_user_octets_to_client{user="hello"} 11286824638 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 344603
telemt_user_msgs_to_client{user="hello"} 1480930
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 1
```