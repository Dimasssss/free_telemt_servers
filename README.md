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

# Server Metrics 2026-03-06 16:37:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 22527.9 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53140
telemt_connections_bad_total 3109
telemt_handshake_timeouts_total 215
telemt_upstream_connect_attempt_total 46203
telemt_upstream_connect_success_total 46191
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 46203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46189
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 2416215120 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 29524609351 (27.50 GB)
telemt_user_msgs_from_client{user="hello"} 1634494
telemt_user_msgs_to_client{user="hello"} 4679824
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 22527.2 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10042
telemt_connections_bad_total 175
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 9520
telemt_upstream_connect_success_total 9502
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9500
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 113396581 (108.14 MB)
telemt_user_octets_to_client{user="hello"} 5478129860 (5.10 GB)
telemt_user_msgs_from_client{user="hello"} 196194
telemt_user_msgs_to_client{user="hello"} 1695204
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 22526.3 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8156
telemt_connections_bad_total 140
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 7852
telemt_upstream_connect_success_total 7850
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7848
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 119359122 (113.83 MB)
telemt_user_octets_to_client{user="hello"} 4862984032 (4.53 GB)
telemt_user_msgs_from_client{user="hello"} 179174
telemt_user_msgs_to_client{user="hello"} 1142565
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 22525.6 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11952
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11046
telemt_upstream_connect_success_total 11009
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 11046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11007
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 154619594 (147.46 MB)
telemt_user_octets_to_client{user="hello"} 3780641274 (3.52 GB)
telemt_user_msgs_from_client{user="hello"} 192079
telemt_user_msgs_to_client{user="hello"} 957606
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 22527.0 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16307
telemt_connections_bad_total 5611
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9852
telemt_upstream_connect_success_total 9852
telemt_upstream_connect_attempts_per_request{bucket="1"} 9852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9850
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 236673358 (225.71 MB)
telemt_user_octets_to_client{user="hello"} 21633325946 (20.15 GB)
telemt_user_msgs_from_client{user="hello"} 392961
telemt_user_msgs_to_client{user="hello"} 3898643
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```