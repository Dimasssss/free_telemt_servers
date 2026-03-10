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

# Server Metrics 2026-03-10 11:25:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 129909.5 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281412
telemt_connections_bad_total 3456
telemt_handshake_timeouts_total 3025
telemt_upstream_connect_attempt_total 263037
telemt_upstream_connect_success_total 262889
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 263037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 242818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 262877
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 6362096927 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 166613722978 (155.17 GB)
telemt_user_msgs_from_client{user="hello"} 6375378
telemt_user_msgs_to_client{user="hello"} 10196796
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 129908.3 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85784
telemt_connections_bad_total 3267
telemt_handshake_timeouts_total 1208
telemt_upstream_connect_attempt_total 76838
telemt_upstream_connect_success_total 76794
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 76838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76780
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2434025829 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 34106337685 (31.76 GB)
telemt_user_msgs_from_client{user="hello"} 2025769
telemt_user_msgs_to_client{user="hello"} 9802260
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 129908.7 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121720
telemt_connections_bad_total 1198
telemt_handshake_timeouts_total 6161
telemt_upstream_connect_attempt_total 88162
telemt_upstream_connect_success_total 88160
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 88162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88148
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 6448127439 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 64845325268 (60.39 GB)
telemt_user_msgs_from_client{user="hello"} 4235184
telemt_user_msgs_to_client{user="hello"} 10681337
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 129903.4 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124320
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 115926
telemt_upstream_connect_success_total 115677
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 115926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115665
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 3129152415 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 81860406316 (76.24 GB)
telemt_user_msgs_from_client{user="hello"} 2923063
telemt_user_msgs_to_client{user="hello"} 18803761
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 129908.9 (36h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188641
telemt_connections_bad_total 28311
telemt_handshake_timeouts_total 4710
telemt_upstream_connect_attempt_total 147667
telemt_upstream_connect_success_total 146706
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 147667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 146692
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 3286172859 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 110985861678 (103.36 GB)
telemt_user_msgs_from_client{user="hello"} 3409788
telemt_user_msgs_to_client{user="hello"} 15089159
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```