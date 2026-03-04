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

# Server Metrics 2026-03-04 15:08:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 13302.7 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21506
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 20422
telemt_upstream_connect_success_total 20419
telemt_upstream_connect_attempts_per_request{bucket="1"} 20416
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20417
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 907313584 (865.28 MB)
telemt_user_octets_to_client{user="hello"} 15906867803 (14.81 GB)
telemt_user_msgs_from_client{user="hello"} 719384
telemt_user_msgs_to_client{user="hello"} 2537345
telemt_user_unique_ips_current{user="hello"} 6
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 13305.7 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5242
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 4779
telemt_upstream_connect_success_total 4778
telemt_upstream_connect_attempts_per_request{bucket="1"} 4777
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4776
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 331122024 (315.78 MB)
telemt_user_octets_to_client{user="hello"} 6416374183 (5.98 GB)
telemt_user_msgs_from_client{user="hello"} 241653
telemt_user_msgs_to_client{user="hello"} 2086893
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 13303.8 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2534
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2446
telemt_upstream_connect_success_total 2446
telemt_upstream_connect_attempts_per_request{bucket="1"} 2446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2444
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 81875996 (78.08 MB)
telemt_user_octets_to_client{user="hello"} 906827118 (864.82 MB)
telemt_user_msgs_from_client{user="hello"} 75047
telemt_user_msgs_to_client{user="hello"} 232539
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 13301.8 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5675
telemt_connections_bad_total 338
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 4893
telemt_upstream_connect_success_total 4890
telemt_upstream_connect_attempts_per_request{bucket="1"} 4888
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4888
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 39185595 (37.37 MB)
telemt_user_octets_to_client{user="hello"} 3274460719 (3.05 GB)
telemt_user_msgs_from_client{user="hello"} 80755
telemt_user_msgs_to_client{user="hello"} 735467
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 13303.4 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5602
telemt_connections_bad_total 2399
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 3040
telemt_upstream_connect_success_total 3039
telemt_upstream_connect_attempts_per_request{bucket="1"} 3038
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3037
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 77326805 (73.74 MB)
telemt_user_octets_to_client{user="hello"} 7226375712 (6.73 GB)
telemt_user_msgs_from_client{user="hello"} 138551
telemt_user_msgs_to_client{user="hello"} 1336142
telemt_user_unique_ips_current{user="hello"} 1
```