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

# Server Metrics 2026-03-10 11:04:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 128681.7 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276158
telemt_connections_bad_total 3454
telemt_handshake_timeouts_total 2982
telemt_upstream_connect_attempt_total 258193
telemt_upstream_connect_success_total 258047
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 258193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 238276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 258035
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 6290877907 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 160302765476 (149.29 GB)
telemt_user_msgs_from_client{user="hello"} 6247262
telemt_user_msgs_to_client{user="hello"} 9950905
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 128680.6 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84185
telemt_connections_bad_total 3264
telemt_handshake_timeouts_total 1181
telemt_upstream_connect_attempt_total 75329
telemt_upstream_connect_success_total 75286
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 75329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 407
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75272
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 2425985241 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 33863405075 (31.54 GB)
telemt_user_msgs_from_client{user="hello"} 2008590
telemt_user_msgs_to_client{user="hello"} 9715566
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 128680.9 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119530
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 6077
telemt_upstream_connect_attempt_total 86204
telemt_upstream_connect_success_total 86202
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 86204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86190
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 6431006512 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 64555785314 (60.12 GB)
telemt_user_msgs_from_client{user="hello"} 4202191
telemt_user_msgs_to_client{user="hello"} 10565013
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 128675.6 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122045
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 1363
telemt_upstream_connect_attempt_total 113730
telemt_upstream_connect_success_total 113482
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 113730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 113470
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 3088569470 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 81174928305 (75.60 GB)
telemt_user_msgs_from_client{user="hello"} 2878431
telemt_user_msgs_to_client{user="hello"} 18621758
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 128681.2 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185450
telemt_connections_bad_total 28089
telemt_handshake_timeouts_total 4691
telemt_upstream_connect_attempt_total 144828
telemt_upstream_connect_success_total 143868
telemt_upstream_connect_fail_total 960
telemt_upstream_connect_attempts_per_request{bucket="1"} 144828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 960
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 143854
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 3266681430 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 110265807824 (102.69 GB)
telemt_user_msgs_from_client{user="hello"} 3370191
telemt_user_msgs_to_client{user="hello"} 14968738
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```