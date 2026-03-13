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

# Server Metrics 2026-03-13 05:04:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 77495.9 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294798
telemt_connections_bad_total 3062
telemt_handshake_timeouts_total 5950
telemt_upstream_connect_attempt_total 19579
telemt_upstream_connect_success_total 19487
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 19579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19068
telemt_me_reconnect_success_total 15571
telemt_me_reader_eof_total 16643
telemt_me_idle_close_by_peer_total 16642
telemt_me_route_drop_no_conn_total 91858
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247791
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15847
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15555
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 247727
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 4261405420 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 121405419548 (113.07 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 77388.9 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135200
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 41403
telemt_upstream_connect_success_total 40886
telemt_upstream_connect_fail_total 517
telemt_upstream_connect_attempts_per_request{bucket="1"} 41403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 517
telemt_me_keepalive_timeout_total 567
telemt_me_reconnect_attempts_total 67094
telemt_me_reconnect_success_total 20531
telemt_me_reader_eof_total 22601
telemt_me_idle_close_by_peer_total 22601
telemt_me_route_drop_no_conn_total 50182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111946
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 22148
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20516
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1617
telemt_user_connections_total{user="hello"} 128446
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1332728064 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 38970998635 (36.29 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77352.6 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163309
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 2640
telemt_upstream_connect_attempt_total 21330
telemt_upstream_connect_success_total 21328
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 18600
telemt_me_reconnect_success_total 17436
telemt_me_reader_eof_total 18669
telemt_me_idle_close_by_peer_total 18669
telemt_me_route_drop_no_conn_total 62966
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152772
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17626
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17416
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 152699
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2898626516 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 70808783128 (65.95 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77328.1 (21h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235608
telemt_connections_bad_total 13563
telemt_handshake_timeouts_total 1688
telemt_upstream_connect_attempt_total 33695
telemt_upstream_connect_success_total 23811
telemt_upstream_connect_fail_total 9884
telemt_upstream_connect_attempts_per_request{bucket="1"} 33695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9884
telemt_me_keepalive_timeout_total 3314
telemt_me_reconnect_attempts_total 65876
telemt_me_reconnect_success_total 17098
telemt_me_reader_eof_total 19145
telemt_me_idle_close_by_peer_total 19138
telemt_me_route_drop_no_conn_total 85822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197254
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 543
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 205
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18846
telemt_me_refill_failed_total 1520
telemt_me_writer_restored_same_endpoint_total 17088
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1748
telemt_user_connections_total{user="hello"} 200001
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 3267319102 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 80240302181 (74.73 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27499.7 (7h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28659
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 8883
telemt_upstream_connect_success_total 8797
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 8883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 7438
telemt_me_reconnect_success_total 7409
telemt_me_reader_eof_total 7897
telemt_me_idle_close_by_peer_total 7897
telemt_me_route_drop_no_conn_total 7855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22584
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7478
telemt_me_writer_restored_same_endpoint_total 7391
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 22584
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 154403200 (147.25 MB)
telemt_user_octets_to_client{user="hello"} 9260196228 (8.62 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 77284.6 (21h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396061
telemt_connections_bad_total 7718
telemt_handshake_timeouts_total 2959
telemt_upstream_connect_attempt_total 16448
telemt_upstream_connect_success_total 16356
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1440
telemt_me_reconnect_attempts_total 16153
telemt_me_reconnect_success_total 12523
telemt_me_reader_eof_total 13448
telemt_me_idle_close_by_peer_total 13445
telemt_me_route_drop_no_conn_total 176916
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386000
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 12798
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12516
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 374243
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 6195041124 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 220280618072 (205.15 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 53
```