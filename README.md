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

# Server Metrics 2026-03-05 02:22:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 53742.1 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72992
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 1566
telemt_upstream_connect_attempt_total 66269
telemt_upstream_connect_success_total 66254
telemt_upstream_connect_attempts_per_request{bucket="1"} 66239
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66248
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 2399579328 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 53013496663 (49.37 GB)
telemt_user_msgs_from_client{user="hello"} 2127215
telemt_user_msgs_to_client{user="hello"} 8604378
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 53745.0 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16158
telemt_connections_bad_total 258
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11641
telemt_upstream_connect_success_total 11639
telemt_upstream_connect_attempts_per_request{bucket="1"} 11637
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11633
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1057828910 (1008.82 MB)
telemt_user_octets_to_client{user="hello"} 11131650521 (10.37 GB)
telemt_user_msgs_from_client{user="hello"} 653417
telemt_user_msgs_to_client{user="hello"} 3747223
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 53743.2 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11558
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 7642
telemt_upstream_connect_success_total 7642
telemt_upstream_connect_attempts_per_request{bucket="1"} 7642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7636
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 317787514 (303.07 MB)
telemt_user_octets_to_client{user="hello"} 5612105759 (5.23 GB)
telemt_user_msgs_from_client{user="hello"} 283502
telemt_user_msgs_to_client{user="hello"} 1216868
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 53741.1 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17983
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 15653
telemt_upstream_connect_success_total 15648
telemt_upstream_connect_attempts_per_request{bucket="1"} 15643
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15642
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 403562080 (384.87 MB)
telemt_user_octets_to_client{user="hello"} 5856369847 (5.45 GB)
telemt_user_msgs_from_client{user="hello"} 321756
telemt_user_msgs_to_client{user="hello"} 1478882
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 53742.8 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20072
telemt_connections_bad_total 9683
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10011
telemt_upstream_connect_success_total 10007
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10005
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10001
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 521682120 (497.51 MB)
telemt_user_octets_to_client{user="hello"} 22467537608 (20.92 GB)
telemt_user_msgs_from_client{user="hello"} 565021
telemt_user_msgs_to_client{user="hello"} 4267464
```