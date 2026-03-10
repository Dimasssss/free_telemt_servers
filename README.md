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

# Server Metrics 2026-03-10 03:54:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 102864.1 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187715
telemt_connections_bad_total 2375
telemt_handshake_timeouts_total 1812
telemt_upstream_connect_attempt_total 175993
telemt_upstream_connect_success_total 175937
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 175993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 175927
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 5014402345 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 105553668824 (98.30 GB)
telemt_user_msgs_from_client{user="hello"} 4565811
telemt_user_msgs_to_client{user="hello"} 6665317
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 102863.0 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57814
telemt_connections_bad_total 3115
telemt_handshake_timeouts_total 879
telemt_upstream_connect_attempt_total 50879
telemt_upstream_connect_success_total 50838
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 50879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50828
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 2150685209 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 24390780009 (22.72 GB)
telemt_user_msgs_from_client{user="hello"} 1577522
telemt_user_msgs_to_client{user="hello"} 6989040
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 102863.5 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75924
telemt_connections_bad_total 970
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 55172
telemt_upstream_connect_success_total 55170
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55160
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 6062693238 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 55055821102 (51.27 GB)
telemt_user_msgs_from_client{user="hello"} 3511800
telemt_user_msgs_to_client{user="hello"} 8235395
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 102858.3 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78191
telemt_connections_bad_total 550
telemt_handshake_timeouts_total 1059
telemt_upstream_connect_attempt_total 72409
telemt_upstream_connect_success_total 72243
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 72409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72233
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2322576928 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 49759343631 (46.34 GB)
telemt_user_msgs_from_client{user="hello"} 1942606
telemt_user_msgs_to_client{user="hello"} 11867453
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 102863.7 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129240
telemt_connections_bad_total 22745
telemt_handshake_timeouts_total 3048
telemt_upstream_connect_attempt_total 98175
telemt_upstream_connect_success_total 98158
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 98175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98148
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1628138888 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 90226116220 (84.03 GB)
telemt_user_msgs_from_client{user="hello"} 2225974
telemt_user_msgs_to_client{user="hello"} 12160461
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 7
```