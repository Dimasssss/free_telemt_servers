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

# Server Metrics 2026-03-10 08:31:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 119473.9 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239065
telemt_connections_bad_total 2461
telemt_handshake_timeouts_total 2083
telemt_upstream_connect_attempt_total 225118
telemt_upstream_connect_success_total 225050
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 225118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 207524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 225038
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 5676135662 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 133918059230 (124.72 GB)
telemt_user_msgs_from_client{user="hello"} 5492850
telemt_user_msgs_to_client{user="hello"} 8423134
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 119472.7 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71838
telemt_connections_bad_total 3221
telemt_handshake_timeouts_total 1013
telemt_upstream_connect_attempt_total 63872
telemt_upstream_connect_success_total 63830
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 63872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63818
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 2286323525 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 30255181962 (28.18 GB)
telemt_user_msgs_from_client{user="hello"} 1818719
telemt_user_msgs_to_client{user="hello"} 8675317
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 119473.7 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104966
telemt_connections_bad_total 1127
telemt_handshake_timeouts_total 5054
telemt_upstream_connect_attempt_total 73278
telemt_upstream_connect_success_total 73276
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 73278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73264
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 6310475139 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 60120280088 (55.99 GB)
telemt_user_msgs_from_client{user="hello"} 3942637
telemt_user_msgs_to_client{user="hello"} 9531172
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 119468.0 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104023
telemt_connections_bad_total 908
telemt_handshake_timeouts_total 1255
telemt_upstream_connect_attempt_total 96596
telemt_upstream_connect_success_total 96392
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 96596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96380
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 2687888766 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 69869134895 (65.07 GB)
telemt_user_msgs_from_client{user="hello"} 2475197
telemt_user_msgs_to_client{user="hello"} 15810252
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 119473.5 (33h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161169
telemt_connections_bad_total 25933
telemt_handshake_timeouts_total 4153
telemt_upstream_connect_attempt_total 124279
telemt_upstream_connect_success_total 123482
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 124279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123470
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 1932280360 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 103398545080 (96.30 GB)
telemt_user_msgs_from_client{user="hello"} 2665298
telemt_user_msgs_to_client{user="hello"} 13961891
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```