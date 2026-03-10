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

# Server Metrics 2026-03-10 10:39:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 127147.9 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269807
telemt_connections_bad_total 3452
telemt_handshake_timeouts_total 2901
telemt_upstream_connect_attempt_total 252480
telemt_upstream_connect_success_total 252336
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 252480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 233055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 252324
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 6185879777 (5.76 GB)
telemt_user_octets_to_client{user="hello"} 153316608439 (142.79 GB)
telemt_user_msgs_from_client{user="hello"} 6081029
telemt_user_msgs_to_client{user="hello"} 9624703
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 127146.7 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81534
telemt_connections_bad_total 3260
telemt_handshake_timeouts_total 1079
telemt_upstream_connect_attempt_total 72961
telemt_upstream_connect_success_total 72918
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 72961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 403
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72904
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2373313724 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 33178150818 (30.90 GB)
telemt_user_msgs_from_client{user="hello"} 1968483
telemt_user_msgs_to_client{user="hello"} 9530696
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 127147.1 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117259
telemt_connections_bad_total 1162
telemt_handshake_timeouts_total 5970
telemt_upstream_connect_attempt_total 84123
telemt_upstream_connect_success_total 84121
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 84123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84109
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 6418263471 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 64207510503 (59.80 GB)
telemt_user_msgs_from_client{user="hello"} 4164073
telemt_user_msgs_to_client{user="hello"} 10459975
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 127142.1 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119563
telemt_connections_bad_total 1026
telemt_handshake_timeouts_total 1354
telemt_upstream_connect_attempt_total 111350
telemt_upstream_connect_success_total 111106
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 111350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111094
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 3059701153 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 80763916211 (75.22 GB)
telemt_user_msgs_from_client{user="hello"} 2839701
telemt_user_msgs_to_client{user="hello"} 18509146
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 127147.3 (35h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181548
telemt_connections_bad_total 27813
telemt_handshake_timeouts_total 4485
telemt_upstream_connect_attempt_total 141586
telemt_upstream_connect_success_total 140626
telemt_upstream_connect_fail_total 958
telemt_upstream_connect_attempts_per_request{bucket="1"} 141584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 958
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 140612
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2109706671 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 108925431012 (101.44 GB)
telemt_user_msgs_from_client{user="hello"} 2923554
telemt_user_msgs_to_client{user="hello"} 14797066
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```