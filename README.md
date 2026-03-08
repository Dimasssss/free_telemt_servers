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

# Server Metrics 2026-03-08 14:34:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 26763.1 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63609
telemt_connections_bad_total 4773
telemt_handshake_timeouts_total 347
telemt_upstream_connect_attempt_total 56097
telemt_upstream_connect_success_total 56075
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 56097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56071
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 1586789080 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 29397172861 (27.38 GB)
telemt_user_msgs_from_client{user="hello"} 1362818
telemt_user_msgs_to_client{user="hello"} 1789017
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 26761.8 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13847
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 13370
telemt_upstream_connect_success_total 13369
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13365
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 505362602 (481.95 MB)
telemt_user_octets_to_client{user="hello"} 8684011314 (8.09 GB)
telemt_user_msgs_from_client{user="hello"} 456287
telemt_user_msgs_to_client{user="hello"} 2223356
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 26761.5 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9074
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 8469
telemt_upstream_connect_success_total 8393
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8389
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 202657757 (193.27 MB)
telemt_user_octets_to_client{user="hello"} 2770992492 (2.58 GB)
telemt_user_msgs_from_client{user="hello"} 144236
telemt_user_msgs_to_client{user="hello"} 474912
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 26761.4 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11588
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 11106
telemt_upstream_connect_success_total 11084
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 11106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11080
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 938218098 (894.75 MB)
telemt_user_octets_to_client{user="hello"} 4334791836 (4.04 GB)
telemt_user_msgs_from_client{user="hello"} 446449
telemt_user_msgs_to_client{user="hello"} 969334
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 26761.6 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15232
telemt_connections_bad_total 4936
telemt_handshake_timeouts_total 112
telemt_upstream_connect_attempt_total 9957
telemt_upstream_connect_success_total 9953
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9949
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 223105193 (212.77 MB)
telemt_user_octets_to_client{user="hello"} 7997575769 (7.45 GB)
telemt_user_msgs_from_client{user="hello"} 260766
telemt_user_msgs_to_client{user="hello"} 1108776
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```