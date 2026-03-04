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

# Server Metrics 2026-03-04 11:07:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 9858.6 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16782
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 202
telemt_upstream_connect_attempt_total 15400
telemt_upstream_connect_success_total 15399
telemt_upstream_connect_attempts_per_request{bucket="1"} 15398
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15397
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 439827779 (419.45 MB)
telemt_user_octets_to_client{user="hello"} 8133099855 (7.57 GB)
telemt_user_msgs_from_client{user="hello"} 436974
telemt_user_msgs_to_client{user="hello"} 1352895
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 9870.2 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2242
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 2073
telemt_upstream_connect_success_total 2071
telemt_upstream_connect_attempts_per_request{bucket="1"} 2069
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2069
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 76899270 (73.34 MB)
telemt_user_octets_to_client{user="hello"} 1076313562 (1.00 GB)
telemt_user_msgs_from_client{user="hello"} 69338
telemt_user_msgs_to_client{user="hello"} 329766
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 9854.8 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1907
telemt_connections_bad_total 79
telemt_upstream_connect_attempt_total 1799
telemt_upstream_connect_success_total 1799
telemt_upstream_connect_attempts_per_request{bucket="1"} 1799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1797
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 44493654 (42.43 MB)
telemt_user_octets_to_client{user="hello"} 3321547263 (3.09 GB)
telemt_user_msgs_from_client{user="hello"} 95321
telemt_user_msgs_to_client{user="hello"} 630493
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 9845.4 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3582
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 3257
telemt_upstream_connect_success_total 3256
telemt_upstream_connect_attempts_per_request{bucket="1"} 3255
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3254
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 23206378 (22.13 MB)
telemt_user_octets_to_client{user="hello"} 1225918557 (1.14 GB)
telemt_user_msgs_from_client{user="hello"} 39553
telemt_user_msgs_to_client{user="hello"} 338992
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 9856.7 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3487
telemt_connections_bad_total 1761
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1654
telemt_upstream_connect_success_total 1654
telemt_upstream_connect_attempts_per_request{bucket="1"} 1654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1652
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 24081168 (22.97 MB)
telemt_user_octets_to_client{user="hello"} 860095389 (820.25 MB)
telemt_user_msgs_from_client{user="hello"} 47350
telemt_user_msgs_to_client{user="hello"} 216609
telemt_user_unique_ips_current{user="hello"} 3
```