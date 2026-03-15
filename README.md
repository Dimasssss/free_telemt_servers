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

# Server Metrics 2026-03-15 05:17:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 25376.6 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62788
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 1124
telemt_upstream_connect_attempt_total 6344
telemt_upstream_connect_success_total 6306
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5032
telemt_me_reconnect_success_total 5013
telemt_me_reader_eof_total 5365
telemt_me_idle_close_by_peer_total 5365
telemt_me_route_drop_no_conn_total 19141
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59039
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 449
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5049
telemt_me_writer_restored_same_endpoint_total 4982
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 59035
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 586271648 (559.11 MB)
telemt_user_octets_to_client{user="hello"} 19073460888 (17.76 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 25382.9 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22417
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 6966
telemt_upstream_connect_success_total 6965
telemt_upstream_connect_attempts_per_request{bucket="1"} 6965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5687
telemt_me_reconnect_success_total 5660
telemt_me_reader_eof_total 6091
telemt_me_idle_close_by_peer_total 6091
telemt_me_route_drop_no_conn_total 11206
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21270
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5715
telemt_me_writer_restored_same_endpoint_total 5644
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 21273
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 678787764 (647.34 MB)
telemt_user_octets_to_client{user="hello"} 7264390504 (6.77 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 25375.5 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28533
telemt_connections_bad_total 429
telemt_handshake_timeouts_total 1692
telemt_upstream_connect_attempt_total 6811
telemt_upstream_connect_success_total 6810
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5537
telemt_me_reconnect_success_total 5510
telemt_me_reader_eof_total 5959
telemt_me_idle_close_by_peer_total 5959
telemt_me_route_drop_no_conn_total 9505
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25583
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5560
telemt_me_writer_restored_same_endpoint_total 5506
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 25534
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 8725637184 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 16369302584 (15.25 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 25375.3 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29304
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 6006
telemt_upstream_connect_success_total 6005
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4736
telemt_me_reconnect_success_total 4719
telemt_me_reader_eof_total 5055
telemt_me_idle_close_by_peer_total 5055
telemt_me_route_drop_no_conn_total 13561
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4769
telemt_me_writer_restored_same_endpoint_total 4708
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 27245
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 523831140 (499.56 MB)
telemt_user_octets_to_client{user="hello"} 16807842416 (15.65 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 446.7 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 615
telemt_upstream_connect_success_total 592
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 94767
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 276
telemt_me_idle_close_by_peer_total 276
telemt_me_route_drop_no_conn_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 296
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 277
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 636
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 4330029 (4.13 MB)
telemt_user_octets_to_client{user="hello"} 197011159 (187.88 MB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 25374.5 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78062
telemt_connections_bad_total 1546
telemt_handshake_timeouts_total 323
telemt_upstream_connect_attempt_total 5661
telemt_upstream_connect_success_total 5630
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 4354
telemt_me_reconnect_success_total 4334
telemt_me_reader_eof_total 4611
telemt_me_idle_close_by_peer_total 4611
telemt_me_route_drop_no_conn_total 42967
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75483
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4351
telemt_me_writer_restored_same_endpoint_total 4307
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 74045
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 2008169108 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 45144789572 (42.04 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 40
```