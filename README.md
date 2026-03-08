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

# Server Metrics 2026-03-08 16:58:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 35394.5 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85183
telemt_connections_bad_total 5042
telemt_handshake_timeouts_total 1105
telemt_upstream_connect_attempt_total 76183
telemt_upstream_connect_success_total 76157
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 76183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76151
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1920034913 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 43493281000 (40.51 GB)
telemt_user_msgs_from_client{user="hello"} 1807710
telemt_user_msgs_to_client{user="hello"} 2515525
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 35393.3 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18466
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 17873
telemt_upstream_connect_success_total 17869
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 17873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17865
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 646194577 (616.26 MB)
telemt_user_octets_to_client{user="hello"} 18025900584 (16.79 GB)
telemt_user_msgs_from_client{user="hello"} 707023
telemt_user_msgs_to_client{user="hello"} 4902904
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 35393.0 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11269
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 10623
telemt_upstream_connect_success_total 10547
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10543
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 225787473 (215.33 MB)
telemt_user_octets_to_client{user="hello"} 3791439641 (3.53 GB)
telemt_user_msgs_from_client{user="hello"} 183385
telemt_user_msgs_to_client{user="hello"} 661682
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 35392.8 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15067
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 14364
telemt_upstream_connect_success_total 14333
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 14364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14329
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 1005012156 (958.45 MB)
telemt_user_octets_to_client{user="hello"} 5149104071 (4.80 GB)
telemt_user_msgs_from_client{user="hello"} 505195
telemt_user_msgs_to_client{user="hello"} 1162992
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 35393.1 (9h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20232
telemt_connections_bad_total 6531
telemt_handshake_timeouts_total 212
telemt_upstream_connect_attempt_total 13180
telemt_upstream_connect_success_total 13176
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13172
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 255060963 (243.25 MB)
telemt_user_octets_to_client{user="hello"} 11083993806 (10.32 GB)
telemt_user_msgs_from_client{user="hello"} 331629
telemt_user_msgs_to_client{user="hello"} 1443806
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```