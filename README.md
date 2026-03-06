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

# Server Metrics 2026-03-06 19:11:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 3805.8 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6543
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 6003
telemt_upstream_connect_success_total 5999
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 6003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5997
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 853495843 (813.96 MB)
telemt_user_octets_to_client{user="hello"} 10738030787 (10.00 GB)
telemt_user_msgs_from_client{user="hello"} 485280
telemt_user_msgs_to_client{user="hello"} 1678452
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 3804.3 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2041
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1921
telemt_upstream_connect_success_total 1921
telemt_upstream_connect_attempts_per_request{bucket="1"} 1921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1919
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 21674155 (20.67 MB)
telemt_user_octets_to_client{user="hello"} 1550551824 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 42256
telemt_user_msgs_to_client{user="hello"} 430708
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 3804.2 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 981
telemt_connections_bad_total 11
telemt_upstream_connect_attempt_total 963
telemt_upstream_connect_success_total 963
telemt_upstream_connect_attempts_per_request{bucket="1"} 963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 961
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 12341312 (11.77 MB)
telemt_user_octets_to_client{user="hello"} 574435755 (547.82 MB)
telemt_user_msgs_from_client{user="hello"} 19910
telemt_user_msgs_to_client{user="hello"} 131645
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 3804.2 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 920
telemt_upstream_connect_success_total 917
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 915
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 24165893 (23.05 MB)
telemt_user_octets_to_client{user="hello"} 429409791 (409.52 MB)
telemt_user_msgs_from_client{user="hello"} 23263
telemt_user_msgs_to_client{user="hello"} 108905
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 3804.7 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3163
telemt_connections_bad_total 691
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2451
telemt_upstream_connect_success_total 2451
telemt_upstream_connect_attempts_per_request{bucket="1"} 2451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2449
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 25760128 (24.57 MB)
telemt_user_octets_to_client{user="hello"} 1941962311 (1.81 GB)
telemt_user_msgs_from_client{user="hello"} 55858
telemt_user_msgs_to_client{user="hello"} 410356
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```