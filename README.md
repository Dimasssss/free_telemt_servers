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

# Server Metrics 2026-03-10 09:42:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 123771.9 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257172
telemt_connections_bad_total 3444
telemt_handshake_timeouts_total 2619
telemt_upstream_connect_attempt_total 240846
telemt_upstream_connect_success_total 240764
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 240846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 240752
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 6018899589 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 145291135293 (135.31 GB)
telemt_user_msgs_from_client{user="hello"} 5856571
telemt_user_msgs_to_client{user="hello"} 9195424
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 123770.9 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77496
telemt_connections_bad_total 3249
telemt_handshake_timeouts_total 1032
telemt_upstream_connect_attempt_total 69237
telemt_upstream_connect_success_total 69195
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 69237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69183
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 2322507495 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 32314341157 (30.10 GB)
telemt_user_msgs_from_client{user="hello"} 1903117
telemt_user_msgs_to_client{user="hello"} 9230972
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 123771.4 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111369
telemt_connections_bad_total 1145
telemt_handshake_timeouts_total 5498
telemt_upstream_connect_attempt_total 78999
telemt_upstream_connect_success_total 78997
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 78999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78985
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 6364841412 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 62123498000 (57.86 GB)
telemt_user_msgs_from_client{user="hello"} 4062513
telemt_user_msgs_to_client{user="hello"} 9969873
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 123766.1 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112781
telemt_connections_bad_total 958
telemt_handshake_timeouts_total 1311
telemt_upstream_connect_attempt_total 104922
telemt_upstream_connect_success_total 104690
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 104922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104678
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2946149801 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 78276742358 (72.90 GB)
telemt_user_msgs_from_client{user="hello"} 2714311
telemt_user_msgs_to_client{user="hello"} 17856348
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 123771.5 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172287
telemt_connections_bad_total 27157
telemt_handshake_timeouts_total 4420
telemt_upstream_connect_attempt_total 133466
telemt_upstream_connect_success_total 132660
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 133466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 132648
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 2024132661 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 105322856797 (98.09 GB)
telemt_user_msgs_from_client{user="hello"} 2797682
telemt_user_msgs_to_client{user="hello"} 14291822
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 24
```