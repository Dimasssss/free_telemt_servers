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

# Server Metrics 2026-03-09 01:46:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 8781.4 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7424
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 6763
telemt_upstream_connect_success_total 6761
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6759
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 74966435 (71.49 MB)
telemt_user_octets_to_client{user="hello"} 7345740938 (6.84 GB)
telemt_user_msgs_from_client{user="hello"} 168001
telemt_user_msgs_to_client{user="hello"} 277792
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 8780.0 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 498
telemt_upstream_connect_success_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 496
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 6882051 (6.56 MB)
telemt_user_octets_to_client{user="hello"} 430707911 (410.76 MB)
telemt_user_msgs_from_client{user="hello"} 19457
telemt_user_msgs_to_client{user="hello"} 84835
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 8780.4 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 525
telemt_upstream_connect_success_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 523
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 29859377 (28.48 MB)
telemt_user_octets_to_client{user="hello"} 81328659 (77.56 MB)
telemt_user_msgs_from_client{user="hello"} 16645
telemt_user_msgs_to_client{user="hello"} 26009
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 8775.3 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1154
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 988
telemt_upstream_connect_success_total 988
telemt_upstream_connect_attempts_per_request{bucket="1"} 988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 986
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 7759450 (7.40 MB)
telemt_user_octets_to_client{user="hello"} 558450891 (532.58 MB)
telemt_user_msgs_from_client{user="hello"} 20111
telemt_user_msgs_to_client{user="hello"} 155235
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 8780.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2486
telemt_connections_bad_total 1576
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 890
telemt_upstream_connect_success_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 888
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 7018346 (6.69 MB)
telemt_user_octets_to_client{user="hello"} 1289029038 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 19501
telemt_user_msgs_to_client{user="hello"} 159736
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```