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

# Server Metrics 2026-03-05 11:26:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 86389.3 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125526
telemt_connections_bad_total 485
telemt_handshake_timeouts_total 4184
telemt_upstream_connect_attempt_total 110475
telemt_upstream_connect_success_total 110450
telemt_upstream_connect_attempts_per_request{bucket="1"} 110425
telemt_upstream_connect_attempts_per_request{bucket="2"} 25
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110440
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 3250503349 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 76035983108 (70.81 GB)
telemt_user_msgs_from_client{user="hello"} 3177912
telemt_user_msgs_to_client{user="hello"} 12414521
telemt_user_unique_ips_current{user="hello"} 15
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 86392.2 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23059
telemt_connections_bad_total 477
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 18184
telemt_upstream_connect_success_total 18181
telemt_upstream_connect_attempts_per_request{bucket="1"} 18178
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18171
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 1176377902 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 15000354324 (13.97 GB)
telemt_user_msgs_from_client{user="hello"} 831120
telemt_user_msgs_to_client{user="hello"} 4791262
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 86390.4 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19373
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 15090
telemt_upstream_connect_success_total 15090
telemt_upstream_connect_attempts_per_request{bucket="1"} 15090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15080
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 447523265 (426.79 MB)
telemt_user_octets_to_client{user="hello"} 9674654647 (9.01 GB)
telemt_user_msgs_from_client{user="hello"} 453642
telemt_user_msgs_to_client{user="hello"} 2056361
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 86388.1 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32754
telemt_connections_bad_total 999
telemt_handshake_timeouts_total 635
telemt_upstream_connect_attempt_total 28733
telemt_upstream_connect_success_total 28723
telemt_upstream_connect_attempts_per_request{bucket="1"} 28713
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28713
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 513990129 (490.18 MB)
telemt_user_octets_to_client{user="hello"} 17619983413 (16.41 GB)
telemt_user_msgs_from_client{user="hello"} 550233
telemt_user_msgs_to_client{user="hello"} 3937587
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 86389.9 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33389
telemt_connections_bad_total 15615
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 17218
telemt_upstream_connect_success_total 17214
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17212
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17204
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 653478509 (623.21 MB)
telemt_user_octets_to_client{user="hello"} 28156374037 (26.22 GB)
telemt_user_msgs_from_client{user="hello"} 750375
telemt_user_msgs_to_client{user="hello"} 5386933
telemt_user_unique_ips_current{user="hello"} 2
```