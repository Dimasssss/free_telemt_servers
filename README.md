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

# Server Metrics 2026-03-10 12:06:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 132367.7 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291058
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 3075
telemt_upstream_connect_attempt_total 272274
telemt_upstream_connect_success_total 272124
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 272274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 272112
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 6472903544 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 177615917432 (165.42 GB)
telemt_user_msgs_from_client{user="hello"} 6589390
telemt_user_msgs_to_client{user="hello"} 10664010
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 132366.6 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88976
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1252
telemt_upstream_connect_attempt_total 79832
telemt_upstream_connect_success_total 79788
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 79832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79774
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 2763117091 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 34651336178 (32.27 GB)
telemt_user_msgs_from_client{user="hello"} 2172932
telemt_user_msgs_to_client{user="hello"} 9994839
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 132367.0 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126454
telemt_connections_bad_total 1213
telemt_handshake_timeouts_total 6280
telemt_upstream_connect_attempt_total 92510
telemt_upstream_connect_success_total 92508
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 92510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92496
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 6590940672 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 66513664755 (61.95 GB)
telemt_user_msgs_from_client{user="hello"} 4345358
telemt_user_msgs_to_client{user="hello"} 11034216
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 132362.0 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131623
telemt_connections_bad_total 1040
telemt_handshake_timeouts_total 2898
telemt_upstream_connect_attempt_total 121233
telemt_upstream_connect_success_total 120975
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 121233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120961
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 3714980922 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 84480811848 (78.68 GB)
telemt_user_msgs_from_client{user="hello"} 3194095
telemt_user_msgs_to_client{user="hello"} 19252715
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 132367.2 (36h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195852
telemt_connections_bad_total 28753
telemt_handshake_timeouts_total 5289
telemt_upstream_connect_attempt_total 153532
telemt_upstream_connect_success_total 152571
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 153532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 152557
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 3397893429 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 114069531229 (106.24 GB)
telemt_user_msgs_from_client{user="hello"} 3542717
telemt_user_msgs_to_client{user="hello"} 15509248
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```