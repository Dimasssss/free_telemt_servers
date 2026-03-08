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

# Server Metrics 2026-03-08 09:51:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 9784.8 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20568
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 17084
telemt_upstream_connect_success_total 17071
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 17084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17069
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 571816631 (545.33 MB)
telemt_user_octets_to_client{user="hello"} 10805681132 (10.06 GB)
telemt_user_msgs_from_client{user="hello"} 482360
telemt_user_msgs_to_client{user="hello"} 575256
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 9783.9 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4562
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 4336
telemt_upstream_connect_success_total 4336
telemt_upstream_connect_attempts_per_request{bucket="1"} 4336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4334
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 55621246 (53.04 MB)
telemt_user_octets_to_client{user="hello"} 3048331148 (2.84 GB)
telemt_user_msgs_from_client{user="hello"} 107447
telemt_user_msgs_to_client{user="hello"} 798477
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 9783.5 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3676
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3594
telemt_upstream_connect_success_total 3594
telemt_upstream_connect_attempts_per_request{bucket="1"} 3594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3592
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 34376394 (32.78 MB)
telemt_user_octets_to_client{user="hello"} 1158255582 (1.08 GB)
telemt_user_msgs_from_client{user="hello"} 37752
telemt_user_msgs_to_client{user="hello"} 184965
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 9783.4 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4274
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 4080
telemt_upstream_connect_success_total 4073
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4071
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 128204555 (122.27 MB)
telemt_user_octets_to_client{user="hello"} 1683681016 (1.57 GB)
telemt_user_msgs_from_client{user="hello"} 79911
telemt_user_msgs_to_client{user="hello"} 394485
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 9783.7 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5947
telemt_connections_bad_total 1852
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 4036
telemt_upstream_connect_success_total 4036
telemt_upstream_connect_attempts_per_request{bucket="1"} 4036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4034
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 51359376 (48.98 MB)
telemt_user_octets_to_client{user="hello"} 3404380875 (3.17 GB)
telemt_user_msgs_from_client{user="hello"} 94885
telemt_user_msgs_to_client{user="hello"} 407179
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```