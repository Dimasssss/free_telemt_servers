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

# Server Metrics 2026-03-08 06:26:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 49277.8 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72513
telemt_connections_bad_total 6647
telemt_handshake_timeouts_total 693
telemt_upstream_connect_attempt_total 61707
telemt_upstream_connect_success_total 61588
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 61707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61582
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 2573755682 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 39619590219 (36.90 GB)
telemt_user_msgs_from_client{user="hello"} 1809015
telemt_user_msgs_to_client{user="hello"} 6225608
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 49277.0 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10748
telemt_connections_bad_total 371
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10185
telemt_upstream_connect_success_total 10176
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10170
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 283163166 (270.05 MB)
telemt_user_octets_to_client{user="hello"} 15584339218 (14.51 GB)
telemt_user_msgs_from_client{user="hello"} 509915
telemt_user_msgs_to_client{user="hello"} 3609968
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 49276.7 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6815
telemt_connections_bad_total 306
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 6119
telemt_upstream_connect_success_total 6119
telemt_upstream_connect_attempts_per_request{bucket="1"} 6119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6113
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 135668333 (129.38 MB)
telemt_user_octets_to_client{user="hello"} 14742110727 (13.73 GB)
telemt_user_msgs_from_client{user="hello"} 245606
telemt_user_msgs_to_client{user="hello"} 3154890
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 49105.0 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15512
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 14876
telemt_upstream_connect_success_total 14850
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14844
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 478774841 (456.60 MB)
telemt_user_octets_to_client{user="hello"} 13480816708 (12.55 GB)
telemt_user_msgs_from_client{user="hello"} 460333
telemt_user_msgs_to_client{user="hello"} 3771006
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 49276.9 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20366
telemt_connections_bad_total 9116
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 10963
telemt_upstream_connect_success_total 10955
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 10963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10949
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 1655900797 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 10713153867 (9.98 GB)
telemt_user_msgs_from_client{user="hello"} 883786
telemt_user_msgs_to_client{user="hello"} 2325302
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```