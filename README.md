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

# Server Metrics 2026-03-08 10:02:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 10401.3 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21688
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 18160
telemt_upstream_connect_success_total 18146
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 18160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18144
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 621490925 (592.70 MB)
telemt_user_octets_to_client{user="hello"} 11264216437 (10.49 GB)
telemt_user_msgs_from_client{user="hello"} 515888
telemt_user_msgs_to_client{user="hello"} 602126
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 10400.2 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4906
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4672
telemt_upstream_connect_success_total 4672
telemt_upstream_connect_attempts_per_request{bucket="1"} 4672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4670
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 68406310 (65.24 MB)
telemt_user_octets_to_client{user="hello"} 3273668981 (3.05 GB)
telemt_user_msgs_from_client{user="hello"} 119299
telemt_user_msgs_to_client{user="hello"} 856927
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 10400.0 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3937
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3854
telemt_upstream_connect_success_total 3854
telemt_upstream_connect_attempts_per_request{bucket="1"} 3854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3852
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 35252495 (33.62 MB)
telemt_user_octets_to_client{user="hello"} 1180668003 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 40378
telemt_user_msgs_to_client{user="hello"} 192296
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 10399.9 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4630
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 4436
telemt_upstream_connect_success_total 4429
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4427
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 159829878 (152.43 MB)
telemt_user_octets_to_client{user="hello"} 1856500230 (1.73 GB)
telemt_user_msgs_from_client{user="hello"} 91127
telemt_user_msgs_to_client{user="hello"} 424605
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 10400.1 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6237
telemt_connections_bad_total 1962
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 4206
telemt_upstream_connect_success_total 4206
telemt_upstream_connect_attempts_per_request{bucket="1"} 4206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4204
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 52903931 (50.45 MB)
telemt_user_octets_to_client{user="hello"} 3449957840 (3.21 GB)
telemt_user_msgs_from_client{user="hello"} 98970
telemt_user_msgs_to_client{user="hello"} 415960
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```