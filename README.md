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

# Server Metrics 2026-03-06 17:54:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 27149.7 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63733
telemt_connections_bad_total 3310
telemt_handshake_timeouts_total 296
telemt_upstream_connect_attempt_total 55941
telemt_upstream_connect_success_total 55928
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 55941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55924
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2806314700 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 36916481494 (34.38 GB)
telemt_user_msgs_from_client{user="hello"} 1936923
telemt_user_msgs_to_client{user="hello"} 5831170
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 27149.6 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12508
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 11926
telemt_upstream_connect_success_total 11907
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 11926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11903
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 151188585 (144.18 MB)
telemt_user_octets_to_client{user="hello"} 6402303539 (5.96 GB)
telemt_user_msgs_from_client{user="hello"} 247551
telemt_user_msgs_to_client{user="hello"} 1968353
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 27148.8 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9620
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 9281
telemt_upstream_connect_success_total 9279
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9277
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 133918127 (127.71 MB)
telemt_user_octets_to_client{user="hello"} 5540038749 (5.16 GB)
telemt_user_msgs_from_client{user="hello"} 212703
telemt_user_msgs_to_client{user="hello"} 1307037
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 27148.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13663
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 12732
telemt_upstream_connect_success_total 12688
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 12732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12684
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 189238751 (180.47 MB)
telemt_user_octets_to_client{user="hello"} 5710230056 (5.32 GB)
telemt_user_msgs_from_client{user="hello"} 237033
telemt_user_msgs_to_client{user="hello"} 1349907
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 27149.4 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19186
telemt_connections_bad_total 6441
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 11843
telemt_upstream_connect_success_total 11843
telemt_upstream_connect_attempts_per_request{bucket="1"} 11843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11839
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 264206495 (251.97 MB)
telemt_user_octets_to_client{user="hello"} 24478455506 (22.80 GB)
telemt_user_msgs_from_client{user="hello"} 455810
telemt_user_msgs_to_client{user="hello"} 4451729
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```