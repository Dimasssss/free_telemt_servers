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

# Server Metrics 2026-03-09 02:21:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 10921.6 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9064
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 8330
telemt_upstream_connect_success_total 8327
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8325
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 103226524 (98.44 MB)
telemt_user_octets_to_client{user="hello"} 8362263073 (7.79 GB)
telemt_user_msgs_from_client{user="hello"} 202491
telemt_user_msgs_to_client{user="hello"} 331091
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 10919.7 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 624
telemt_upstream_connect_success_total 624
telemt_upstream_connect_attempts_per_request{bucket="1"} 624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 622
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 8189847 (7.81 MB)
telemt_user_octets_to_client{user="hello"} 464766799 (443.24 MB)
telemt_user_msgs_from_client{user="hello"} 22886
telemt_user_msgs_to_client{user="hello"} 92761
telemt_user_unique_ips_current{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 10920.2 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 663
telemt_upstream_connect_success_total 663
telemt_upstream_connect_attempts_per_request{bucket="1"} 663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 661
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 313806669 (299.27 MB)
telemt_user_octets_to_client{user="hello"} 113942421 (108.66 MB)
telemt_user_msgs_from_client{user="hello"} 117697
telemt_user_msgs_to_client{user="hello"} 39309
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 10915.1 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1469
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 1236
telemt_upstream_connect_success_total 1236
telemt_upstream_connect_attempts_per_request{bucket="1"} 1236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1234
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 10125691 (9.66 MB)
telemt_user_octets_to_client{user="hello"} 646040316 (616.11 MB)
telemt_user_msgs_from_client{user="hello"} 26055
telemt_user_msgs_to_client{user="hello"} 186546
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 10920.6 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3013
telemt_connections_bad_total 1962
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1023
telemt_upstream_connect_success_total 1023
telemt_upstream_connect_attempts_per_request{bucket="1"} 1023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1021
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 7544056 (7.19 MB)
telemt_user_octets_to_client{user="hello"} 1313037865 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 20829
telemt_user_msgs_to_client{user="hello"} 164399
telemt_user_unique_ips_current{user="hello"} 5
```