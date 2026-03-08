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

# Server Metrics 2026-03-08 10:27:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 11947.8 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24782
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 21060
telemt_upstream_connect_success_total 21045
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 21060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21043
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 752852206 (717.98 MB)
telemt_user_octets_to_client{user="hello"} 12769292616 (11.89 GB)
telemt_user_msgs_from_client{user="hello"} 612633
telemt_user_msgs_to_client{user="hello"} 698732
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 11946.9 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5971
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 5641
telemt_upstream_connect_success_total 5641
telemt_upstream_connect_attempts_per_request{bucket="1"} 5641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5639
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 81655267 (77.87 MB)
telemt_user_octets_to_client{user="hello"} 3933244524 (3.66 GB)
telemt_user_msgs_from_client{user="hello"} 147259
telemt_user_msgs_to_client{user="hello"} 1030840
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 11946.5 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4359
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4254
telemt_upstream_connect_success_total 4254
telemt_upstream_connect_attempts_per_request{bucket="1"} 4254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4252
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 37840015 (36.09 MB)
telemt_user_octets_to_client{user="hello"} 1310415214 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 47679
telemt_user_msgs_to_client{user="hello"} 219943
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 11946.5 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5560
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 5298
telemt_upstream_connect_success_total 5289
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5287
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 381799147 (364.11 MB)
telemt_user_octets_to_client{user="hello"} 2417631281 (2.25 GB)
telemt_user_msgs_from_client{user="hello"} 181133
telemt_user_msgs_to_client{user="hello"} 518703
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 11946.7 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7279
telemt_connections_bad_total 2238
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4955
telemt_upstream_connect_success_total 4955
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4953
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 60908435 (58.09 MB)
telemt_user_octets_to_client{user="hello"} 3945247984 (3.67 GB)
telemt_user_msgs_from_client{user="hello"} 117920
telemt_user_msgs_to_client{user="hello"} 526608
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```