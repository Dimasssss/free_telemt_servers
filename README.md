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

# Server Metrics 2026-03-06 09:36:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 5161.0 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10355
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 9989
telemt_upstream_connect_success_total 9988
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9986
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 122906119 (117.21 MB)
telemt_user_octets_to_client{user="hello"} 6280909815 (5.85 GB)
telemt_user_msgs_from_client{user="hello"} 204686
telemt_user_msgs_to_client{user="hello"} 1034028
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 5161.3 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1636
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1601
telemt_upstream_connect_success_total 1601
telemt_upstream_connect_attempts_per_request{bucket="1"} 1601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1599
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 17203020 (16.41 MB)
telemt_user_octets_to_client{user="hello"} 511237066 (487.55 MB)
telemt_user_msgs_from_client{user="hello"} 34136
telemt_user_msgs_to_client{user="hello"} 169556
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 5159.7 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1697
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1583
telemt_upstream_connect_success_total 1583
telemt_upstream_connect_attempts_per_request{bucket="1"} 1583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1581
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 121412372 (115.79 MB)
telemt_user_octets_to_client{user="hello"} 539638711 (514.64 MB)
telemt_user_msgs_from_client{user="hello"} 66168
telemt_user_msgs_to_client{user="hello"} 125201
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 5161.8 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2756
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 2423
telemt_upstream_connect_success_total 2418
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2416
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 26292821 (25.07 MB)
telemt_user_octets_to_client{user="hello"} 623295354 (594.42 MB)
telemt_user_msgs_from_client{user="hello"} 33281
telemt_user_msgs_to_client{user="hello"} 163068
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 5163.5 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3182
telemt_connections_bad_total 1474
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1641
telemt_upstream_connect_success_total 1640
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1638
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 82757845 (78.92 MB)
telemt_user_octets_to_client{user="hello"} 1094664781 (1.02 GB)
telemt_user_msgs_from_client{user="hello"} 58644
telemt_user_msgs_to_client{user="hello"} 216238
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```