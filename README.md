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

# Server Metrics 2026-03-09 06:26:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 25600.6 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25728
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 565
telemt_upstream_connect_attempt_total 23661
telemt_upstream_connect_success_total 23653
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23649
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 218938876 (208.80 MB)
telemt_user_octets_to_client{user="hello"} 13317110920 (12.40 GB)
telemt_user_msgs_from_client{user="hello"} 444204
telemt_user_msgs_to_client{user="hello"} 671718
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 25598.7 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3460
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 70
telemt_upstream_connect_attempt_total 3263
telemt_upstream_connect_success_total 3263
telemt_upstream_connect_attempts_per_request{bucket="1"} 3263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3259
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 49696542 (47.39 MB)
telemt_user_octets_to_client{user="hello"} 3071500103 (2.86 GB)
telemt_user_msgs_from_client{user="hello"} 108486
telemt_user_msgs_to_client{user="hello"} 593132
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 25599.3 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1954
telemt_connections_bad_total 106
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1823
telemt_upstream_connect_success_total 1823
telemt_upstream_connect_attempts_per_request{bucket="1"} 1823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1819
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 908010849 (865.95 MB)
telemt_user_octets_to_client{user="hello"} 1146036142 (1.07 GB)
telemt_user_msgs_from_client{user="hello"} 350240
telemt_user_msgs_to_client{user="hello"} 228901
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 25594.2 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4469
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 3556
telemt_upstream_connect_success_total 3554
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3550
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 128759528 (122.79 MB)
telemt_user_octets_to_client{user="hello"} 2768609818 (2.58 GB)
telemt_user_msgs_from_client{user="hello"} 79169
telemt_user_msgs_to_client{user="hello"} 596832
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 25599.6 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9105
telemt_connections_bad_total 5084
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 3806
telemt_upstream_connect_success_total 3806
telemt_upstream_connect_attempts_per_request{bucket="1"} 3806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3802
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 55827148 (53.24 MB)
telemt_user_octets_to_client{user="hello"} 2787414186 (2.60 GB)
telemt_user_msgs_from_client{user="hello"} 81115
telemt_user_msgs_to_client{user="hello"} 377671
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 5
```