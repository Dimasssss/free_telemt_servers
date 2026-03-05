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

# Server Metrics 2026-03-05 22:34:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 1161.0 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19477
telemt_connections_bad_total 18053
telemt_handshake_timeouts_total 629
telemt_upstream_connect_attempt_total 771
telemt_upstream_connect_success_total 771
telemt_upstream_connect_attempts_per_request{bucket="1"} 771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 769
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 10902507 (10.40 MB)
telemt_user_octets_to_client{user="hello"} 1521044945 (1.42 GB)
telemt_user_msgs_from_client{user="hello"} 25004
telemt_user_msgs_to_client{user="hello"} 209066
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 1158.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 127
telemt_upstream_connect_success_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 899314 (878.24 KB)
telemt_user_octets_to_client{user="hello"} 62389208 (59.50 MB)
telemt_user_msgs_from_client{user="hello"} 2213
telemt_user_msgs_to_client{user="hello"} 16515
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 1159.1 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 208734 (203.84 KB)
telemt_user_octets_to_client{user="hello"} 3846184 (3.67 MB)
telemt_user_msgs_from_client{user="hello"} 489
telemt_user_msgs_to_client{user="hello"} 1390
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 1161.9 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196
telemt_upstream_connect_attempt_total 192
telemt_upstream_connect_success_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 190
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 4271174 (4.07 MB)
telemt_user_octets_to_client{user="hello"} 557832790 (531.99 MB)
telemt_user_msgs_from_client{user="hello"} 12159
telemt_user_msgs_to_client{user="hello"} 104172
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 1161.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399
telemt_connections_bad_total 216
telemt_upstream_connect_attempt_total 185
telemt_upstream_connect_success_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 183
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 5538524 (5.28 MB)
telemt_user_octets_to_client{user="hello"} 1040355036 (992.16 MB)
telemt_user_msgs_from_client{user="hello"} 15040
telemt_user_msgs_to_client{user="hello"} 198976
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```