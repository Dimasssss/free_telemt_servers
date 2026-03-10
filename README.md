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

# Server Metrics 2026-03-10 05:26:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 108423.4 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202847
telemt_connections_bad_total 2397
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 190677
telemt_upstream_connect_success_total 190617
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 190677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 190607
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 5214322979 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 116893077933 (108.87 GB)
telemt_user_msgs_from_client{user="hello"} 4865665
telemt_user_msgs_to_client{user="hello"} 7292846
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 108422.5 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61280
telemt_connections_bad_total 3177
telemt_handshake_timeouts_total 905
telemt_upstream_connect_attempt_total 53940
telemt_upstream_connect_success_total 53899
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 53940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53887
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 2170094355 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 25156758438 (23.43 GB)
telemt_user_msgs_from_client{user="hello"} 1619596
telemt_user_msgs_to_client{user="hello"} 7206677
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 108423.0 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88603
telemt_connections_bad_total 1000
telemt_handshake_timeouts_total 4010
telemt_upstream_connect_attempt_total 59180
telemt_upstream_connect_success_total 59178
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 59180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59168
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 6108444034 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 56737662091 (52.84 GB)
telemt_user_msgs_from_client{user="hello"} 3693997
telemt_user_msgs_to_client{user="hello"} 8727353
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 108417.8 (30h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84400
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 1104
telemt_upstream_connect_attempt_total 78115
telemt_upstream_connect_success_total 77941
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 78115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77929
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2403564191 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 55758322278 (51.93 GB)
telemt_user_msgs_from_client{user="hello"} 2091824
telemt_user_msgs_to_client{user="hello"} 12879195
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 108423.2 (30h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137344
telemt_connections_bad_total 23672
telemt_handshake_timeouts_total 3104
telemt_upstream_connect_attempt_total 105078
telemt_upstream_connect_success_total 104287
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 105078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104275
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 1694558741 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 93411395701 (87.00 GB)
telemt_user_msgs_from_client{user="hello"} 2338472
telemt_user_msgs_to_client{user="hello"} 12630082
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 8
```