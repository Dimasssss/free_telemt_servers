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

# Server Metrics 2026-03-04 10:52:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 8935.7 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15229
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 13921
telemt_upstream_connect_success_total 13920
telemt_upstream_connect_attempts_per_request{bucket="1"} 13919
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13918
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 176824077 (168.63 MB)
telemt_user_octets_to_client{user="hello"} 6767676823 (6.30 GB)
telemt_user_msgs_from_client{user="hello"} 298282
telemt_user_msgs_to_client{user="hello"} 1132720
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 8947.3 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2016
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1853
telemt_upstream_connect_success_total 1851
telemt_upstream_connect_attempts_per_request{bucket="1"} 1849
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1849
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 74083726 (70.65 MB)
telemt_user_octets_to_client{user="hello"} 826039221 (787.77 MB)
telemt_user_msgs_from_client{user="hello"} 64613
telemt_user_msgs_to_client{user="hello"} 259854
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 8931.9 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1769
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1663
telemt_upstream_connect_success_total 1663
telemt_upstream_connect_attempts_per_request{bucket="1"} 1663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1661
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 43019753 (41.03 MB)
telemt_user_octets_to_client{user="hello"} 3292840545 (3.07 GB)
telemt_user_msgs_from_client{user="hello"} 92854
telemt_user_msgs_to_client{user="hello"} 621657
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 8922.6 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3254
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 2934
telemt_upstream_connect_success_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 2932
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2931
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 21912767 (20.90 MB)
telemt_user_octets_to_client{user="hello"} 1196416909 (1.11 GB)
telemt_user_msgs_from_client{user="hello"} 37216
telemt_user_msgs_to_client{user="hello"} 327296
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 8933.9 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3057
telemt_connections_bad_total 1597
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1393
telemt_upstream_connect_success_total 1393
telemt_upstream_connect_attempts_per_request{bucket="1"} 1393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1391
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 21111369 (20.13 MB)
telemt_user_octets_to_client{user="hello"} 774090419 (738.23 MB)
telemt_user_msgs_from_client{user="hello"} 42403
telemt_user_msgs_to_client{user="hello"} 193552
telemt_user_unique_ips_current{user="hello"} 2
```