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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 23:24:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6005.4 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9923
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 9526
telemt_upstream_connect_success_total 9522
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9520
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 142397876 (135.80 MB)
telemt_user_octets_to_client{user="hello"} 4698759091 (4.38 GB)
telemt_user_msgs_from_client{user="hello"} 235174
telemt_user_msgs_to_client{user="hello"} 643017
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5993.5 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4225
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 4057
telemt_upstream_connect_success_total 4057
telemt_upstream_connect_attempts_per_request{bucket="1"} 4057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 536
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4055
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 18317971 (17.47 MB)
telemt_user_octets_to_client{user="hello"} 499339673 (476.21 MB)
telemt_user_msgs_from_client{user="hello"} 45505
telemt_user_msgs_to_client{user="hello"} 217462
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5967.2 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7406
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 5972
telemt_upstream_connect_success_total 5972
telemt_upstream_connect_attempts_per_request{bucket="1"} 5972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 754
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5970
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 39433988 (37.61 MB)
telemt_user_octets_to_client{user="hello"} 3685405655 (3.43 GB)
telemt_user_msgs_from_client{user="hello"} 122316
telemt_user_msgs_to_client{user="hello"} 904729
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5992.4 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5647
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 5419
telemt_upstream_connect_success_total 5412
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5410
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 42930810 (40.94 MB)
telemt_user_octets_to_client{user="hello"} 2019179344 (1.88 GB)
telemt_user_msgs_from_client{user="hello"} 84120
telemt_user_msgs_to_client{user="hello"} 752159
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5993.7 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6201
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 4618
telemt_upstream_connect_success_total 4615
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4613
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 49407275 (47.12 MB)
telemt_user_octets_to_client{user="hello"} 1837188434 (1.71 GB)
telemt_user_msgs_from_client{user="hello"} 70197
telemt_user_msgs_to_client{user="hello"} 339663
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5993.3 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5855
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 5050
telemt_upstream_connect_success_total 5050
telemt_upstream_connect_attempts_per_request{bucket="1"} 5050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 817
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5048
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 87848148 (83.78 MB)
telemt_user_octets_to_client{user="hello"} 11681405700 (10.88 GB)
telemt_user_msgs_from_client{user="hello"} 162637
telemt_user_msgs_to_client{user="hello"} 879932
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 7
```