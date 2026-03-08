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

# Server Metrics 2026-03-08 09:20:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 7936.4 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17310
telemt_connections_bad_total 2452
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 14078
telemt_upstream_connect_success_total 14067
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 14078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14065
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 460859240 (439.51 MB)
telemt_user_octets_to_client{user="hello"} 8826440812 (8.22 GB)
telemt_user_msgs_from_client{user="hello"} 381878
telemt_user_msgs_to_client{user="hello"} 457413
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 7935.5 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3736
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3544
telemt_upstream_connect_success_total 3544
telemt_upstream_connect_attempts_per_request{bucket="1"} 3544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3542
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 45322751 (43.22 MB)
telemt_user_octets_to_client{user="hello"} 2535677767 (2.36 GB)
telemt_user_msgs_from_client{user="hello"} 86508
telemt_user_msgs_to_client{user="hello"} 642141
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 7935.4 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3117
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3040
telemt_upstream_connect_success_total 3040
telemt_upstream_connect_attempts_per_request{bucket="1"} 3040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3038
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 30725805 (29.30 MB)
telemt_user_octets_to_client{user="hello"} 569578287 (543.19 MB)
telemt_user_msgs_from_client{user="hello"} 27323
telemt_user_msgs_to_client{user="hello"} 106994
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 7935.1 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3451
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3285
telemt_upstream_connect_success_total 3280
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 3285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3278
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 78659005 (75.02 MB)
telemt_user_octets_to_client{user="hello"} 1178913478 (1.10 GB)
telemt_user_msgs_from_client{user="hello"} 59758
telemt_user_msgs_to_client{user="hello"} 290782
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 7935.5 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4942
telemt_connections_bad_total 1486
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 3409
telemt_upstream_connect_success_total 3409
telemt_upstream_connect_attempts_per_request{bucket="1"} 3409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3407
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 43272905 (41.27 MB)
telemt_user_octets_to_client{user="hello"} 3002031155 (2.80 GB)
telemt_user_msgs_from_client{user="hello"} 75011
telemt_user_msgs_to_client{user="hello"} 337754
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```