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

# Server Metrics 2026-03-05 17:36:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.0

telemt_uptime_seconds 1275.6 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4859
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1569
telemt_upstream_connect_success_total 1567
telemt_upstream_connect_attempts_per_request{bucket="1"} 1566
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1565
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 17997608 (17.16 MB)
telemt_user_octets_to_client{user="hello"} 633407514 (604.06 MB)
telemt_user_msgs_from_client{user="hello"} 41485
telemt_user_msgs_to_client{user="hello"} 121046
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.0

telemt_uptime_seconds 1278.0 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339
telemt_upstream_connect_attempt_total 341
telemt_upstream_connect_success_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 339
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 2539413 (2.42 MB)
telemt_user_octets_to_client{user="hello"} 136598976 (130.27 MB)
telemt_user_msgs_from_client{user="hello"} 5985
telemt_user_msgs_to_client{user="hello"} 38301
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.0

telemt_uptime_seconds 1275.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 368
telemt_upstream_connect_success_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 366
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1866983 (1.78 MB)
telemt_user_octets_to_client{user="hello"} 117204806 (111.78 MB)
telemt_user_msgs_from_client{user="hello"} 4950
telemt_user_msgs_to_client{user="hello"} 28263
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.0

telemt_uptime_seconds 1273.4 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 349
telemt_upstream_connect_success_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 347
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1983048 (1.89 MB)
telemt_user_octets_to_client{user="hello"} 84535312 (80.62 MB)
telemt_user_msgs_from_client{user="hello"} 4664
telemt_user_msgs_to_client{user="hello"} 23731
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.0

telemt_uptime_seconds 1275.4 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 497
telemt_upstream_connect_success_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 495
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 20914254 (19.95 MB)
telemt_user_octets_to_client{user="hello"} 355962306 (339.47 MB)
telemt_user_msgs_from_client{user="hello"} 20536
telemt_user_msgs_to_client{user="hello"} 76267
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```