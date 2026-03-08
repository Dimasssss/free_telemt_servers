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

# Server Metrics 2026-03-08 15:00:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 28306.5 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68709
telemt_connections_bad_total 5023
telemt_handshake_timeouts_total 1028
telemt_upstream_connect_attempt_total 60176
telemt_upstream_connect_success_total 60154
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 60176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60150
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 1649162531 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 31906699564 (29.72 GB)
telemt_user_msgs_from_client{user="hello"} 1445034
telemt_user_msgs_to_client{user="hello"} 1911205
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 28305.6 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14820
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 14313
telemt_upstream_connect_success_total 14312
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14308
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 546004685 (520.71 MB)
telemt_user_octets_to_client{user="hello"} 12164697560 (11.33 GB)
telemt_user_msgs_from_client{user="hello"} 544481
telemt_user_msgs_to_client{user="hello"} 3141013
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 28305.2 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9504
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8879
telemt_upstream_connect_success_total 8803
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8799
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 204876789 (195.39 MB)
telemt_user_octets_to_client{user="hello"} 2988094635 (2.78 GB)
telemt_user_msgs_from_client{user="hello"} 149653
telemt_user_msgs_to_client{user="hello"} 512739
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 28305.1 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12242
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 11682
telemt_upstream_connect_success_total 11656
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11652
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 942466842 (898.81 MB)
telemt_user_octets_to_client{user="hello"} 4439627170 (4.13 GB)
telemt_user_msgs_from_client{user="hello"} 456904
telemt_user_msgs_to_client{user="hello"} 998702
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 28305.3 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16039
telemt_connections_bad_total 5215
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 10474
telemt_upstream_connect_success_total 10468
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10464
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 229545029 (218.91 MB)
telemt_user_octets_to_client{user="hello"} 8270475906 (7.70 GB)
telemt_user_msgs_from_client{user="hello"} 273660
telemt_user_msgs_to_client{user="hello"} 1155340
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```