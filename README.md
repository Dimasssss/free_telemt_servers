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

# Server Metrics 2026-03-10 04:46:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 105968.4 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196235
telemt_connections_bad_total 2379
telemt_handshake_timeouts_total 1861
telemt_upstream_connect_attempt_total 184235
telemt_upstream_connect_success_total 184178
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 184235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 169664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 184168
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 5103498944 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 113633149245 (105.83 GB)
telemt_user_msgs_from_client{user="hello"} 4734788
telemt_user_msgs_to_client{user="hello"} 7057390
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 105967.2 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59804
telemt_connections_bad_total 3145
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 52579
telemt_upstream_connect_success_total 52538
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 52579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52526
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 2159132901 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 24772045066 (23.07 GB)
telemt_user_msgs_from_client{user="hello"} 1597669
telemt_user_msgs_to_client{user="hello"} 7105422
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 105967.7 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86696
telemt_connections_bad_total 993
telemt_handshake_timeouts_total 3996
telemt_upstream_connect_attempt_total 57379
telemt_upstream_connect_success_total 57377
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57367
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 6090448274 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 56531867269 (52.65 GB)
telemt_user_msgs_from_client{user="hello"} 3620423
telemt_user_msgs_to_client{user="hello"} 8616176
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 105962.5 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81353
telemt_connections_bad_total 582
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 75413
telemt_upstream_connect_success_total 75244
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 75413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75232
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2354448157 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 52078472482 (48.50 GB)
telemt_user_msgs_from_client{user="hello"} 2016327
telemt_user_msgs_to_client{user="hello"} 12373598
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 105967.9 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133757
telemt_connections_bad_total 23227
telemt_handshake_timeouts_total 3087
telemt_upstream_connect_attempt_total 102029
telemt_upstream_connect_success_total 101238
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 102029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101228
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 1652953894 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 91709151692 (85.41 GB)
telemt_user_msgs_from_client{user="hello"} 2276909
telemt_user_msgs_to_client{user="hello"} 12379199
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```