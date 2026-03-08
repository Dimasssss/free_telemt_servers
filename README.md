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

# Server Metrics 2026-03-08 21:30:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 51722.4 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113149
telemt_connections_bad_total 5494
telemt_handshake_timeouts_total 1279
telemt_upstream_connect_attempt_total 102597
telemt_upstream_connect_success_total 102559
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 102597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102553
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 2480726678 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 64531111230 (60.10 GB)
telemt_user_msgs_from_client{user="hello"} 2531242
telemt_user_msgs_to_client{user="hello"} 3484760
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 51721.3 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26944
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 26050
telemt_upstream_connect_success_total 26043
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26037
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 837827745 (799.01 MB)
telemt_user_octets_to_client{user="hello"} 22648441082 (21.09 GB)
telemt_user_msgs_from_client{user="hello"} 975208
telemt_user_msgs_to_client{user="hello"} 6145492
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 51720.9 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15178
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 13773
telemt_upstream_connect_success_total 13697
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13691
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 1554012566 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 5660147698 (5.27 GB)
telemt_user_msgs_from_client{user="hello"} 696043
telemt_user_msgs_to_client{user="hello"} 969328
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 51720.9 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20539
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 19688
telemt_upstream_connect_success_total 19648
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 19688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19642
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 1066053491 (1016.67 MB)
telemt_user_octets_to_client{user="hello"} 6508553082 (6.06 GB)
telemt_user_msgs_from_client{user="hello"} 571579
telemt_user_msgs_to_client{user="hello"} 1474032
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 51721.2 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30308
telemt_connections_bad_total 9833
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 19748
telemt_upstream_connect_success_total 19741
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19735
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 367405639 (350.39 MB)
telemt_user_octets_to_client{user="hello"} 17196469462 (16.02 GB)
telemt_user_msgs_from_client{user="hello"} 522046
telemt_user_msgs_to_client{user="hello"} 2215199
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```