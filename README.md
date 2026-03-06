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

# Server Metrics 2026-03-06 06:57:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 31326.0 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86112
telemt_connections_bad_total 51943
telemt_handshake_timeouts_total 2476
telemt_upstream_connect_attempt_total 29826
telemt_upstream_connect_success_total 29822
telemt_upstream_connect_attempts_per_request{bucket="1"} 29818
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29818
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 418450905 (399.07 MB)
telemt_user_octets_to_client{user="hello"} 26770997572 (24.93 GB)
telemt_user_msgs_from_client{user="hello"} 738855
telemt_user_msgs_to_client{user="hello"} 4017365
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 31323.6 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3984
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 3758
telemt_upstream_connect_success_total 3757
telemt_upstream_connect_attempts_per_request{bucket="1"} 3756
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3753
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 74854721 (71.39 MB)
telemt_user_octets_to_client{user="hello"} 1564052330 (1.46 GB)
telemt_user_msgs_from_client{user="hello"} 106646
telemt_user_msgs_to_client{user="hello"} 499957
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 31324.3 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3447
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 3161
telemt_upstream_connect_success_total 3161
telemt_upstream_connect_attempts_per_request{bucket="1"} 3161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3157
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 63005103 (60.09 MB)
telemt_user_octets_to_client{user="hello"} 2881020059 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 96198
telemt_user_msgs_to_client{user="hello"} 621124
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 31326.7 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6175
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 5386
telemt_upstream_connect_success_total 5385
telemt_upstream_connect_attempts_per_request{bucket="1"} 5384
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5381
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 116868274 (111.45 MB)
telemt_user_octets_to_client{user="hello"} 8194974196 (7.63 GB)
telemt_user_msgs_from_client{user="hello"} 185934
telemt_user_msgs_to_client{user="hello"} 1733313
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 31326.5 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10831
telemt_connections_bad_total 5744
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 4779
telemt_upstream_connect_success_total 4779
telemt_upstream_connect_attempts_per_request{bucket="1"} 4779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4775
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 128865579 (122.90 MB)
telemt_user_octets_to_client{user="hello"} 22059969436 (20.54 GB)
telemt_user_msgs_from_client{user="hello"} 279043
telemt_user_msgs_to_client{user="hello"} 4114784
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```