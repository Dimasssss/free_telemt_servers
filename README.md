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

# Server Metrics 2026-03-07 01:36:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 26900.6 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33760
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 494
telemt_upstream_connect_attempt_total 31516
telemt_upstream_connect_success_total 31508
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31504
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2083689019 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 33099088301 (30.83 GB)
telemt_user_msgs_from_client{user="hello"} 1385271
telemt_user_msgs_to_client{user="hello"} 5220934
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 26899.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6720
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6288
telemt_upstream_connect_success_total 6285
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6281
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215480520 (205.50 MB)
telemt_user_octets_to_client{user="hello"} 3896934587 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 202308
telemt_user_msgs_to_client{user="hello"} 1090115
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 26899.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3220
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2928
telemt_upstream_connect_success_total 2928
telemt_upstream_connect_attempts_per_request{bucket="1"} 2928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 257
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2924
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 65331792 (62.31 MB)
telemt_user_octets_to_client{user="hello"} 1871354491 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 64731
telemt_user_msgs_to_client{user="hello"} 397339
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 26899.3 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4507
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4305
telemt_upstream_connect_success_total 4298
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4294
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 101003035 (96.32 MB)
telemt_user_octets_to_client{user="hello"} 1374640585 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 86608
telemt_user_msgs_to_client{user="hello"} 355505
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 26899.6 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12790
telemt_connections_bad_total 5789
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6840
telemt_upstream_connect_success_total 6839
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6835
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 229388666 (218.76 MB)
telemt_user_octets_to_client{user="hello"} 7685354335 (7.16 GB)
telemt_user_msgs_from_client{user="hello"} 219057
telemt_user_msgs_to_client{user="hello"} 1576618
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```