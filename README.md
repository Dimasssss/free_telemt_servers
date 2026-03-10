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

# Server Metrics 2026-03-10 13:27:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 137281.5 (38h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311871
telemt_connections_bad_total 3472
telemt_handshake_timeouts_total 3243
telemt_upstream_connect_attempt_total 292078
telemt_upstream_connect_success_total 291921
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 292078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 270005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 291907
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 6766157615 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 193074313385 (179.81 GB)
telemt_user_msgs_from_client{user="hello"} 7020620
telemt_user_msgs_to_client{user="hello"} 11430110
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 137279.8 (38h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96141
telemt_connections_bad_total 3273
telemt_handshake_timeouts_total 1285
telemt_upstream_connect_attempt_total 86658
telemt_upstream_connect_success_total 86614
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 86658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86600
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2813160775 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 36947234781 (34.41 GB)
telemt_user_msgs_from_client{user="hello"} 2284432
telemt_user_msgs_to_client{user="hello"} 10677999
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 137280.3 (38h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136537
telemt_connections_bad_total 1229
telemt_handshake_timeouts_total 6451
telemt_upstream_connect_attempt_total 101897
telemt_upstream_connect_success_total 101894
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 101897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101880
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 6658317528 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 68605243492 (63.89 GB)
telemt_user_msgs_from_client{user="hello"} 4502360
telemt_user_msgs_to_client{user="hello"} 11562198
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 137275.0 (38h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141498
telemt_connections_bad_total 1060
telemt_handshake_timeouts_total 2931
telemt_upstream_connect_attempt_total 130704
telemt_upstream_connect_success_total 130411
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 130704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 331
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130397
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 5001953930 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 91405627190 (85.13 GB)
telemt_user_msgs_from_client{user="hello"} 3819914
telemt_user_msgs_to_client{user="hello"} 20624008
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 137280.4 (38h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208633
telemt_connections_bad_total 30628
telemt_handshake_timeouts_total 5712
telemt_upstream_connect_attempt_total 163531
telemt_upstream_connect_success_total 162569
telemt_upstream_connect_fail_total 962
telemt_upstream_connect_attempts_per_request{bucket="1"} 163531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 962
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 162555
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 3493015466 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 117852498971 (109.76 GB)
telemt_user_msgs_from_client{user="hello"} 3725383
telemt_user_msgs_to_client{user="hello"} 16124014
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 31
```