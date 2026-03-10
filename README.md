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

# Server Metrics 2026-03-10 12:11:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 132674.0 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292175
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 3076
telemt_upstream_connect_attempt_total 273351
telemt_upstream_connect_success_total 273201
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 273351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 252500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 273189
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 6488477738 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 179590457364 (167.26 GB)
telemt_user_msgs_from_client{user="hello"} 6619393
telemt_user_msgs_to_client{user="hello"} 10717408
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 132673.2 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89332
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1255
telemt_upstream_connect_attempt_total 80166
telemt_upstream_connect_success_total 80122
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 80166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80108
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 2764437633 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 34710745808 (32.33 GB)
telemt_user_msgs_from_client{user="hello"} 2176413
telemt_user_msgs_to_client{user="hello"} 10015269
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 132673.5 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127086
telemt_connections_bad_total 1215
telemt_handshake_timeouts_total 6281
telemt_upstream_connect_attempt_total 93119
telemt_upstream_connect_success_total 93117
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 93119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93105
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 6596095872 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 66597507873 (62.02 GB)
telemt_user_msgs_from_client{user="hello"} 4353931
telemt_user_msgs_to_client{user="hello"} 11057478
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 132672.8 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132300
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 2903
telemt_upstream_connect_attempt_total 121816
telemt_upstream_connect_success_total 121556
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 121816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 308
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 121542
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 3718044757 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 84617395326 (78.81 GB)
telemt_user_msgs_from_client{user="hello"} 3202090
telemt_user_msgs_to_client{user="hello"} 19287729
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 132673.5 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196547
telemt_connections_bad_total 28808
telemt_handshake_timeouts_total 5289
telemt_upstream_connect_attempt_total 154145
telemt_upstream_connect_success_total 153184
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 154145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153170
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 3402620165 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 114333454632 (106.48 GB)
telemt_user_msgs_from_client{user="hello"} 3553830
telemt_user_msgs_to_client{user="hello"} 15548410
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```