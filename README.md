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

# Server Metrics 2026-03-07 21:22:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 16629.0 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27664
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 26638
telemt_upstream_connect_success_total 26635
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26633
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 1912033948 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 19180459949 (17.86 GB)
telemt_user_msgs_from_client{user="hello"} 966067
telemt_user_msgs_to_client{user="hello"} 2982393
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 16628.4 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5326
telemt_connections_bad_total 162
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 5058
telemt_upstream_connect_success_total 5052
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 5058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5050
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 89092660 (84.97 MB)
telemt_user_octets_to_client{user="hello"} 3154848201 (2.94 GB)
telemt_user_msgs_from_client{user="hello"} 133082
telemt_user_msgs_to_client{user="hello"} 915824
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 16628.0 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3023
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 2857
telemt_upstream_connect_success_total 2857
telemt_upstream_connect_attempts_per_request{bucket="1"} 2857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2855
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 79109011 (75.44 MB)
telemt_user_octets_to_client{user="hello"} 3834657693 (3.57 GB)
telemt_user_msgs_from_client{user="hello"} 100798
telemt_user_msgs_to_client{user="hello"} 800470
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 16456.5 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7496
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7210
telemt_upstream_connect_success_total 7194
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 7210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7192
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 124730216 (118.95 MB)
telemt_user_octets_to_client{user="hello"} 7285816808 (6.79 GB)
telemt_user_msgs_from_client{user="hello"} 184534
telemt_user_msgs_to_client{user="hello"} 2194707
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 16628.3 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9008
telemt_connections_bad_total 3056
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 5780
telemt_upstream_connect_success_total 5772
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 5780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5770
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 1577565853 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 3753637254 (3.50 GB)
telemt_user_msgs_from_client{user="hello"} 690441
telemt_user_msgs_to_client{user="hello"} 873347
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```