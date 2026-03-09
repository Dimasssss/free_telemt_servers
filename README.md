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

# Server Metrics 2026-03-09 17:40:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 66053.1 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123860
telemt_connections_bad_total 1663
telemt_handshake_timeouts_total 1047
telemt_upstream_connect_attempt_total 116087
telemt_upstream_connect_success_total 116045
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 116087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116037
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 3191434584 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 63023029889 (58.69 GB)
telemt_user_msgs_from_client{user="hello"} 2922505
telemt_user_msgs_to_client{user="hello"} 4054962
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 66051.7 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34445
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 412
telemt_upstream_connect_attempt_total 32392
telemt_upstream_connect_success_total 32373
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 32392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32367
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1042541491 (994.25 MB)
telemt_user_octets_to_client{user="hello"} 16730303153 (15.58 GB)
telemt_user_msgs_from_client{user="hello"} 903630
telemt_user_msgs_to_client{user="hello"} 4706589
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 66052.3 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43936
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 2025
telemt_upstream_connect_attempt_total 33995
telemt_upstream_connect_success_total 33995
telemt_upstream_connect_attempts_per_request{bucket="1"} 33995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33987
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 4557537502 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 24118619404 (22.46 GB)
telemt_user_msgs_from_client{user="hello"} 2095355
telemt_user_msgs_to_client{user="hello"} 3194628
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 66047.1 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49597
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 906
telemt_upstream_connect_attempt_total 45209
telemt_upstream_connect_success_total 45098
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 45209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45090
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2067977869 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 33722957182 (31.41 GB)
telemt_user_msgs_from_client{user="hello"} 1396680
telemt_user_msgs_to_client{user="hello"} 8450009
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 66052.6 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80186
telemt_connections_bad_total 15801
telemt_handshake_timeouts_total 2081
telemt_upstream_connect_attempt_total 58670
telemt_upstream_connect_success_total 58668
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58660
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 961797944 (917.24 MB)
telemt_user_octets_to_client{user="hello"} 57561351653 (53.61 GB)
telemt_user_msgs_from_client{user="hello"} 1345850
telemt_user_msgs_to_client{user="hello"} 7284798
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```