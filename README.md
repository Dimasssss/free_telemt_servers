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

# Server Metrics 2026-03-06 07:02:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 31634.0 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86744
telemt_connections_bad_total 51943
telemt_handshake_timeouts_total 2477
telemt_upstream_connect_attempt_total 30453
telemt_upstream_connect_success_total 30449
telemt_upstream_connect_attempts_per_request{bucket="1"} 30445
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30445
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 426243106 (406.50 MB)
telemt_user_octets_to_client{user="hello"} 27891492899 (25.98 GB)
telemt_user_msgs_from_client{user="hello"} 753691
telemt_user_msgs_to_client{user="hello"} 4171420
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 31631.7 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4071
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 3845
telemt_upstream_connect_success_total 3844
telemt_upstream_connect_attempts_per_request{bucket="1"} 3843
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3840
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 78126900 (74.51 MB)
telemt_user_octets_to_client{user="hello"} 1763832901 (1.64 GB)
telemt_user_msgs_from_client{user="hello"} 114357
telemt_user_msgs_to_client{user="hello"} 550938
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 31632.6 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3584
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3292
telemt_upstream_connect_success_total 3292
telemt_upstream_connect_attempts_per_request{bucket="1"} 3292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 290
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3288
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 66096385 (63.03 MB)
telemt_user_octets_to_client{user="hello"} 2960714585 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 100362
telemt_user_msgs_to_client{user="hello"} 638145
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 31634.7 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6378
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 5569
telemt_upstream_connect_success_total 5568
telemt_upstream_connect_attempts_per_request{bucket="1"} 5567
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5564
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 118000801 (112.53 MB)
telemt_user_octets_to_client{user="hello"} 8245538582 (7.68 GB)
telemt_user_msgs_from_client{user="hello"} 188546
telemt_user_msgs_to_client{user="hello"} 1746611
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 31634.5 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11128
telemt_connections_bad_total 5801
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 5008
telemt_upstream_connect_success_total 5008
telemt_upstream_connect_attempts_per_request{bucket="1"} 5008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5004
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 130675182 (124.62 MB)
telemt_user_octets_to_client{user="hello"} 22158731132 (20.64 GB)
telemt_user_msgs_from_client{user="hello"} 282169
telemt_user_msgs_to_client{user="hello"} 4137068
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```