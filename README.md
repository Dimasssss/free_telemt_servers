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

# Server Metrics 2026-03-04 23:23:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 42968.2 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66133
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 59613
telemt_upstream_connect_success_total 59598
telemt_upstream_connect_attempts_per_request{bucket="1"} 59583
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59594
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2321663326 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 46770839698 (43.56 GB)
telemt_user_msgs_from_client{user="hello"} 1970477
telemt_user_msgs_to_client{user="hello"} 7444189
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 42971.1 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12121
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 11353
telemt_upstream_connect_success_total 11351
telemt_upstream_connect_attempts_per_request{bucket="1"} 11349
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11347
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1055231116 (1006.35 MB)
telemt_user_octets_to_client{user="hello"} 11042254212 (10.28 GB)
telemt_user_msgs_from_client{user="hello"} 647159
telemt_user_msgs_to_client{user="hello"} 3724060
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 42969.3 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11162
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 7273
telemt_upstream_connect_success_total 7273
telemt_upstream_connect_attempts_per_request{bucket="1"} 7273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7269
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 307884153 (293.62 MB)
telemt_user_octets_to_client{user="hello"} 5245729661 (4.89 GB)
telemt_user_msgs_from_client{user="hello"} 267998
telemt_user_msgs_to_client{user="hello"} 1129377
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 42967.3 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14838
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 12949
telemt_upstream_connect_success_total 12944
telemt_upstream_connect_attempts_per_request{bucket="1"} 12939
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12940
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 389355535 (371.32 MB)
telemt_user_octets_to_client{user="hello"} 5503963057 (5.13 GB)
telemt_user_msgs_from_client{user="hello"} 300154
telemt_user_msgs_to_client{user="hello"} 1374739
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 42969.1 (11h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17189
telemt_connections_bad_total 7724
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9109
telemt_upstream_connect_success_total 9105
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9103
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9099
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 509780478 (486.16 MB)
telemt_user_octets_to_client{user="hello"} 20789047562 (19.36 GB)
telemt_user_msgs_from_client{user="hello"} 538623
telemt_user_msgs_to_client{user="hello"} 3940597
telemt_user_unique_ips_current{user="hello"} 3
```