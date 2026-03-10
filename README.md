# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

# Server Metrics 2026-03-10 19:26:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18011.1 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69736
telemt_connections_bad_total 2276
telemt_handshake_timeouts_total 1929
telemt_upstream_connect_attempt_total 62205
telemt_upstream_connect_success_total 62193
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 62205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62191
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 1961062681 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 44898173703 (41.81 GB)
telemt_user_msgs_from_client{user="hello"} 1801675
telemt_user_msgs_to_client{user="hello"} 3381831
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18010.2 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26657
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 446
telemt_upstream_connect_attempt_total 24378
telemt_upstream_connect_success_total 24371
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 24378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24369
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 808963927 (771.49 MB)
telemt_user_octets_to_client{user="hello"} 16487173825 (15.35 GB)
telemt_user_msgs_from_client{user="hello"} 786073
telemt_user_msgs_to_client{user="hello"} 5096516
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18009.8 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41103
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 3584
telemt_upstream_connect_attempt_total 34880
telemt_upstream_connect_success_total 34880
telemt_upstream_connect_attempts_per_request{bucket="1"} 34880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34878
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 561256397 (535.26 MB)
telemt_user_octets_to_client{user="hello"} 33931029099 (31.60 GB)
telemt_user_msgs_from_client{user="hello"} 764548
telemt_user_msgs_to_client{user="hello"} 5029352
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18008.7 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38017
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 274
telemt_upstream_connect_attempt_total 36422
telemt_upstream_connect_success_total 36317
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 36422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36315
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 608372102 (580.19 MB)
telemt_user_octets_to_client{user="hello"} 29591262708 (27.56 GB)
telemt_user_msgs_from_client{user="hello"} 778829
telemt_user_msgs_to_client{user="hello"} 5485917
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18010.1 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56652
telemt_connections_bad_total 4984
telemt_handshake_timeouts_total 1212
telemt_upstream_connect_attempt_total 48128
telemt_upstream_connect_success_total 47886
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 48128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47884
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1488657760 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 35382673290 (32.95 GB)
telemt_user_msgs_from_client{user="hello"} 1327113
telemt_user_msgs_to_client{user="hello"} 5126778
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```