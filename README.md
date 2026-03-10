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

# Server Metrics 2026-03-10 15:25:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3571.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17157
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 15955
telemt_upstream_connect_success_total 15952
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 15955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15950
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 242883344 (231.63 MB)
telemt_user_octets_to_client{user="hello"} 9075699352 (8.45 GB)
telemt_user_msgs_from_client{user="hello"} 338030
telemt_user_msgs_to_client{user="hello"} 618570
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3570.6 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5030
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 114
telemt_upstream_connect_attempt_total 4603
telemt_upstream_connect_success_total 4603
telemt_upstream_connect_attempts_per_request{bucket="1"} 4603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4601
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 97150954 (92.65 MB)
telemt_user_octets_to_client{user="hello"} 4068261341 (3.79 GB)
telemt_user_msgs_from_client{user="hello"} 132767
telemt_user_msgs_to_client{user="hello"} 1212091
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3570.3 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8364
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 268
telemt_upstream_connect_attempt_total 7737
telemt_upstream_connect_success_total 7737
telemt_upstream_connect_attempts_per_request{bucket="1"} 7737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 898
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7735
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 56780761 (54.15 MB)
telemt_user_octets_to_client{user="hello"} 1965431596 (1.83 GB)
telemt_user_msgs_from_client{user="hello"} 118713
telemt_user_msgs_to_client{user="hello"} 498415
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3569.3 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8212
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 7821
telemt_upstream_connect_success_total 7799
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 7821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7797
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 148834227 (141.94 MB)
telemt_user_octets_to_client{user="hello"} 6871813821 (6.40 GB)
telemt_user_msgs_from_client{user="hello"} 163306
telemt_user_msgs_to_client{user="hello"} 1077156
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3570.6 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11648
telemt_connections_bad_total 886
telemt_handshake_timeouts_total 216
telemt_upstream_connect_attempt_total 10085
telemt_upstream_connect_success_total 10083
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 10085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10081
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 725897028 (692.27 MB)
telemt_user_octets_to_client{user="hello"} 6666946538 (6.21 GB)
telemt_user_msgs_from_client{user="hello"} 400638
telemt_user_msgs_to_client{user="hello"} 724094
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 31
```