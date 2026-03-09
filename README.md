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

# Server Metrics 2026-03-09 04:39:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 19179.1 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17046
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 455
telemt_upstream_connect_attempt_total 15338
telemt_upstream_connect_success_total 15333
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15331
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 149707270 (142.77 MB)
telemt_user_octets_to_client{user="hello"} 9439851897 (8.79 GB)
telemt_user_msgs_from_client{user="hello"} 288617
telemt_user_msgs_to_client{user="hello"} 437057
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 19177.6 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1847
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 1700
telemt_upstream_connect_success_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 1700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1698
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 30716442 (29.29 MB)
telemt_user_octets_to_client{user="hello"} 1417914780 (1.32 GB)
telemt_user_msgs_from_client{user="hello"} 62082
telemt_user_msgs_to_client{user="hello"} 277617
telemt_user_unique_ips_current{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 19178.1 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1287
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1186
telemt_upstream_connect_success_total 1186
telemt_upstream_connect_attempts_per_request{bucket="1"} 1186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1184
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 463307075 (441.84 MB)
telemt_user_octets_to_client{user="hello"} 992674170 (946.69 MB)
telemt_user_msgs_from_client{user="hello"} 186687
telemt_user_msgs_to_client{user="hello"} 189652
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 19173.0 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2544
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 2054
telemt_upstream_connect_success_total 2054
telemt_upstream_connect_attempts_per_request{bucket="1"} 2054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2052
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 16492527 (15.73 MB)
telemt_user_octets_to_client{user="hello"} 1306605361 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 42498
telemt_user_msgs_to_client{user="hello"} 322321
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 19178.5 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5323
telemt_connections_bad_total 3487
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1796
telemt_upstream_connect_success_total 1796
telemt_upstream_connect_attempts_per_request{bucket="1"} 1796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1794
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 13075694 (12.47 MB)
telemt_user_octets_to_client{user="hello"} 1666736242 (1.55 GB)
telemt_user_msgs_from_client{user="hello"} 33778
telemt_user_msgs_to_client{user="hello"} 209660
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```