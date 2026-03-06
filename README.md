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

# Server Metrics 2026-03-06 08:40:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 1774.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3725
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3619
telemt_upstream_connect_success_total 3619
telemt_upstream_connect_attempts_per_request{bucket="1"} 3619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3617
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 37314894 (35.59 MB)
telemt_user_octets_to_client{user="hello"} 2394975675 (2.23 GB)
telemt_user_msgs_from_client{user="hello"} 68883
telemt_user_msgs_to_client{user="hello"} 425303
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 1774.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 494
telemt_upstream_connect_success_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 492
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 4443768 (4.24 MB)
telemt_user_octets_to_client{user="hello"} 229359799 (218.73 MB)
telemt_user_msgs_from_client{user="hello"} 10905
telemt_user_msgs_to_client{user="hello"} 64848
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 1772.5 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 574
telemt_upstream_connect_success_total 574
telemt_upstream_connect_attempts_per_request{bucket="1"} 574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 572
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 7316330 (6.98 MB)
telemt_user_octets_to_client{user="hello"} 153820656 (146.69 MB)
telemt_user_msgs_from_client{user="hello"} 9014
telemt_user_msgs_to_client{user="hello"} 36531
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 1775.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1026
telemt_upstream_connect_success_total 1021
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1019
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 20421204 (19.48 MB)
telemt_user_octets_to_client{user="hello"} 413479033 (394.32 MB)
telemt_user_msgs_from_client{user="hello"} 19086
telemt_user_msgs_to_client{user="hello"} 101807
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 1776.9 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1644
telemt_connections_bad_total 872
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 747
telemt_upstream_connect_success_total 747
telemt_upstream_connect_attempts_per_request{bucket="1"} 747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 745
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 29243979 (27.89 MB)
telemt_user_octets_to_client{user="hello"} 515908688 (492.01 MB)
telemt_user_msgs_from_client{user="hello"} 24238
telemt_user_msgs_to_client{user="hello"} 103919
telemt_user_unique_ips_current{user="hello"} 8
```