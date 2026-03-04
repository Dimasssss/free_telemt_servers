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

# Server Metrics 2026-03-04 09:40:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 4626.4 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8566
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 7529
telemt_upstream_connect_success_total 7529
telemt_upstream_connect_attempts_per_request{bucket="1"} 7529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7527
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 100548484 (95.89 MB)
telemt_user_octets_to_client{user="hello"} 3603757324 (3.36 GB)
telemt_user_msgs_from_client{user="hello"} 159691
telemt_user_msgs_to_client{user="hello"} 618613
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 4637.8 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 715
telemt_upstream_connect_success_total 715
telemt_upstream_connect_attempts_per_request{bucket="1"} 715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 713
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 28233298 (26.93 MB)
telemt_user_octets_to_client{user="hello"} 268832813 (256.38 MB)
telemt_user_msgs_from_client{user="hello"} 26018
telemt_user_msgs_to_client{user="hello"} 85695
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 4622.7 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782
telemt_connections_bad_total 59
telemt_upstream_connect_attempt_total 701
telemt_upstream_connect_success_total 701
telemt_upstream_connect_attempts_per_request{bucket="1"} 701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 699
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 12379922 (11.81 MB)
telemt_user_octets_to_client{user="hello"} 1472773999 (1.37 GB)
telemt_user_msgs_from_client{user="hello"} 34987
telemt_user_msgs_to_client{user="hello"} 253662
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 4612.9 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1531
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1384
telemt_upstream_connect_success_total 1383
telemt_upstream_connect_attempts_per_request{bucket="1"} 1382
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1381
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 6221392 (5.93 MB)
telemt_user_octets_to_client{user="hello"} 228420752 (217.84 MB)
telemt_user_msgs_from_client{user="hello"} 13135
telemt_user_msgs_to_client{user="hello"} 71839
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 4624.3 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1708
telemt_connections_bad_total 811
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 846
telemt_upstream_connect_success_total 846
telemt_upstream_connect_attempts_per_request{bucket="1"} 846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 844
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 11724801 (11.18 MB)
telemt_user_octets_to_client{user="hello"} 421662009 (402.13 MB)
telemt_user_msgs_from_client{user="hello"} 26182
telemt_user_msgs_to_client{user="hello"} 109792
telemt_user_unique_ips_current{user="hello"} 1
```