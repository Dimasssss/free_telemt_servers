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

# Server Metrics 2026-03-04 16:10:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 17001.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27294
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 593
telemt_upstream_connect_attempt_total 26053
telemt_upstream_connect_success_total 26047
telemt_upstream_connect_attempts_per_request{bucket="1"} 26041
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26045
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 1095949525 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 21851133659 (20.35 GB)
telemt_user_msgs_from_client{user="hello"} 896479
telemt_user_msgs_to_client{user="hello"} 3444132
telemt_user_unique_ips_current{user="hello"} 8
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 17004.0 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6409
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 5914
telemt_upstream_connect_success_total 5913
telemt_upstream_connect_attempts_per_request{bucket="1"} 5912
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5911
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 413861343 (394.69 MB)
telemt_user_octets_to_client{user="hello"} 7355733328 (6.85 GB)
telemt_user_msgs_from_client{user="hello"} 296943
telemt_user_msgs_to_client{user="hello"} 2403433
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 17002.2 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3318
telemt_connections_bad_total 31
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 3205
telemt_upstream_connect_success_total 3205
telemt_upstream_connect_attempts_per_request{bucket="1"} 3205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3203
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 102331220 (97.59 MB)
telemt_user_octets_to_client{user="hello"} 1507694546 (1.40 GB)
telemt_user_msgs_from_client{user="hello"} 96869
telemt_user_msgs_to_client{user="hello"} 364369
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 17000.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6652
telemt_connections_bad_total 341
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 5849
telemt_upstream_connect_success_total 5845
telemt_upstream_connect_attempts_per_request{bucket="1"} 5841
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5843
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 58411792 (55.71 MB)
telemt_user_octets_to_client{user="hello"} 3453012964 (3.22 GB)
telemt_user_msgs_from_client{user="hello"} 96258
telemt_user_msgs_to_client{user="hello"} 792367
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 17001.9 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7148
telemt_connections_bad_total 3040
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 3927
telemt_upstream_connect_success_total 3926
telemt_upstream_connect_attempts_per_request{bucket="1"} 3925
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3924
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 114128229 (108.84 MB)
telemt_user_octets_to_client{user="hello"} 7904736618 (7.36 GB)
telemt_user_msgs_from_client{user="hello"} 177291
telemt_user_msgs_to_client{user="hello"} 1491133
telemt_user_unique_ips_current{user="hello"} 3
```