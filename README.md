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

# Server Metrics 2026-03-10 06:12:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 111185.1 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210332
telemt_connections_bad_total 2403
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 197786
telemt_upstream_connect_success_total 197723
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 197786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 182345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 197711
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 5342179931 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 120622102543 (112.34 GB)
telemt_user_msgs_from_client{user="hello"} 5000886
telemt_user_msgs_to_client{user="hello"} 7491109
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 111184.0 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63524
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 910
telemt_upstream_connect_attempt_total 56071
telemt_upstream_connect_success_total 56030
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 56071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56018
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2184236752 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 25670809017 (23.91 GB)
telemt_user_msgs_from_client{user="hello"} 1652378
telemt_user_msgs_to_client{user="hello"} 7393878
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 111185.0 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91640
telemt_connections_bad_total 1040
telemt_handshake_timeouts_total 4164
telemt_upstream_connect_attempt_total 61799
telemt_upstream_connect_success_total 61797
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61785
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 6151265876 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 58443960607 (54.43 GB)
telemt_user_msgs_from_client{user="hello"} 3771830
telemt_user_msgs_to_client{user="hello"} 9160342
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 111179.3 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88992
telemt_connections_bad_total 873
telemt_handshake_timeouts_total 1137
telemt_upstream_connect_attempt_total 82280
telemt_upstream_connect_success_total 82098
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 82280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82086
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 2456682273 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 60551858942 (56.39 GB)
telemt_user_msgs_from_client{user="hello"} 2188230
telemt_user_msgs_to_client{user="hello"} 13912780
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 111184.7 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142710
telemt_connections_bad_total 24173
telemt_handshake_timeouts_total 3611
telemt_upstream_connect_attempt_total 108934
telemt_upstream_connect_success_total 108142
telemt_upstream_connect_fail_total 792
telemt_upstream_connect_attempts_per_request{bucket="1"} 108934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 792
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108130
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 1724303440 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 97516820636 (90.82 GB)
telemt_user_msgs_from_client{user="hello"} 2412625
telemt_user_msgs_to_client{user="hello"} 13033258
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```