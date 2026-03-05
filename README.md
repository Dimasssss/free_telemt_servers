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

# Server Metrics 2026-03-05 01:15:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 49740.7 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70564
telemt_connections_bad_total 162
telemt_handshake_timeouts_total 1562
telemt_upstream_connect_attempt_total 63880
telemt_upstream_connect_success_total 63865
telemt_upstream_connect_attempts_per_request{bucket="1"} 63850
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63859
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2358130865 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 48777122418 (45.43 GB)
telemt_user_msgs_from_client{user="hello"} 2042738
telemt_user_msgs_to_client{user="hello"} 7765050
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 49743.8 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15972
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11463
telemt_upstream_connect_success_total 11461
telemt_upstream_connect_attempts_per_request{bucket="1"} 11459
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11455
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1056631406 (1007.68 MB)
telemt_user_octets_to_client{user="hello"} 11094311537 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 650713
telemt_user_msgs_to_client{user="hello"} 3738434
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 49741.9 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11379
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 7477
telemt_upstream_connect_success_total 7477
telemt_upstream_connect_attempts_per_request{bucket="1"} 7477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7471
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 308646989 (294.35 MB)
telemt_user_octets_to_client{user="hello"} 5269771759 (4.91 GB)
telemt_user_msgs_from_client{user="hello"} 270054
telemt_user_msgs_to_client{user="hello"} 1140371
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 49739.9 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16792
telemt_connections_bad_total 690
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 14633
telemt_upstream_connect_success_total 14628
telemt_upstream_connect_attempts_per_request{bucket="1"} 14623
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14622
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 398965214 (380.48 MB)
telemt_user_octets_to_client{user="hello"} 5671733356 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 312878
telemt_user_msgs_to_client{user="hello"} 1428571
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 49741.6 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19201
telemt_connections_bad_total 8955
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9873
telemt_upstream_connect_success_total 9869
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9867
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9863
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 520023019 (495.93 MB)
telemt_user_octets_to_client{user="hello"} 22396912689 (20.86 GB)
telemt_user_msgs_from_client{user="hello"} 561378
telemt_user_msgs_to_client{user="hello"} 4251572
```