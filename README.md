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

# Server Metrics 2026-03-15 11:03:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 46148.4 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194096
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 4333
telemt_upstream_connect_attempt_total 11583
telemt_upstream_connect_success_total 11522
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11572
telemt_me_reconnect_success_total 9197
telemt_me_reader_eof_total 9830
telemt_me_idle_close_by_peer_total 9830
telemt_me_route_drop_no_conn_total 415607
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242044
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1448
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9358
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 9166
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 181297
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 3368856832 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 183434159260 (170.84 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 46155.1 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63635
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 3075
telemt_upstream_connect_attempt_total 12420
telemt_upstream_connect_success_total 12420
telemt_upstream_connect_attempts_per_request{bucket="1"} 12420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12403
telemt_me_reconnect_success_total 10078
telemt_me_reader_eof_total 10829
telemt_me_idle_close_by_peer_total 10829
telemt_me_route_drop_no_conn_total 29769
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56181
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10260
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10062
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 56181
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1055908972 (1006.99 MB)
telemt_user_octets_to_client{user="hello"} 23497602104 (21.88 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 46147.8 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72005
telemt_connections_bad_total 999
telemt_handshake_timeouts_total 2513
telemt_upstream_connect_attempt_total 12911
telemt_upstream_connect_success_total 12907
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 11768
telemt_me_reconnect_success_total 10568
telemt_me_reader_eof_total 11349
telemt_me_idle_close_by_peer_total 11349
telemt_me_route_drop_no_conn_total 27166
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65394
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10699
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10564
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 65312
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 9400319068 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 40640139640 (37.85 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 46147.2 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93948
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 10941
telemt_upstream_connect_success_total 10940
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8665
telemt_me_reconnect_success_total 8623
telemt_me_reader_eof_total 9210
telemt_me_idle_close_by_peer_total 9210
telemt_me_route_drop_no_conn_total 38350
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85833
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8713
telemt_me_writer_restored_same_endpoint_total 8612
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 85755
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1652329180 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 51552974384 (48.01 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 21218.8 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37387
telemt_connections_bad_total 4001
telemt_handshake_timeouts_total 582
telemt_upstream_connect_attempt_total 7056
telemt_upstream_connect_success_total 7003
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 7056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 100168
telemt_me_reconnect_success_total 5755
telemt_me_reader_eof_total 5970
telemt_me_idle_close_by_peer_total 5970
telemt_me_route_drop_no_conn_total 15090
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31834
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5734
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5651
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 31973
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 503578077 (480.25 MB)
telemt_user_octets_to_client{user="hello"} 13361330999 (12.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 46146.7 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253060
telemt_connections_bad_total 44836
telemt_handshake_timeouts_total 1801
telemt_upstream_connect_attempt_total 9882
telemt_upstream_connect_success_total 9822
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 9882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 7536
telemt_me_reconnect_success_total 7490
telemt_me_reader_eof_total 7982
telemt_me_idle_close_by_peer_total 7982
telemt_me_route_drop_no_conn_total 111597
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198999
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7547
telemt_me_writer_restored_same_endpoint_total 7463
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 197368
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 4591532952 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 97760141628 (91.05 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 73
```