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

# Server Metrics 2026-03-16 15:13:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 5754.2 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66000
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1644
telemt_upstream_connect_attempt_total 1233
telemt_upstream_connect_success_total 1231
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 643
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 891
telemt_me_reconnect_success_total 883
telemt_me_reader_eof_total 876
telemt_me_idle_close_by_peer_total 876
telemt_me_route_drop_no_conn_total 19077
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61416
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 879
telemt_me_writer_restored_same_endpoint_total 881
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 61348
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 1262189556 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 36354155780 (33.86 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 532.6 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4900
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 101
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 38
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 1976
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4673
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 29
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_user_connections_total{user="hello"} 4671
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 31202172 (29.76 MB)
telemt_user_octets_to_client{user="hello"} 861280296 (821.38 MB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 5867.1 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27318
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 379
telemt_upstream_connect_attempt_total 2423
telemt_upstream_connect_success_total 2388
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 34789
telemt_me_reconnect_success_total 1070
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 7539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24057
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1228
telemt_me_refill_failed_total 1053
telemt_me_writer_restored_same_endpoint_total 1026
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 25008
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 299072814 (285.22 MB)
telemt_user_octets_to_client{user="hello"} 4105175166 (3.82 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 6003.4 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47858
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 808
telemt_upstream_connect_attempt_total 1260
telemt_upstream_connect_success_total 1252
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 5830
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 1012
telemt_me_idle_close_by_peer_total 1012
telemt_me_route_drop_no_conn_total 16451
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45235
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 259
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_me_writer_removed_unexpected_total 1036
telemt_me_refill_failed_total 154
telemt_me_writer_restored_same_endpoint_total 878
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 45216
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 819269116 (781.32 MB)
telemt_user_octets_to_client{user="hello"} 10380440436 (9.67 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 3463.7 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18746
telemt_connections_bad_total 6626
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 902
telemt_upstream_connect_success_total 893
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 697
telemt_me_reconnect_success_total 686
telemt_me_reader_eof_total 673
telemt_me_idle_close_by_peer_total 673
telemt_me_route_drop_no_conn_total 3978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11431
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 690
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 11415
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 270911864 (258.36 MB)
telemt_user_octets_to_client{user="hello"} 2048292556 (1.91 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 5571.2 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67674
telemt_connections_bad_total 1121
telemt_handshake_timeouts_total 1503
telemt_upstream_connect_attempt_total 1141
telemt_upstream_connect_success_total 1141
telemt_upstream_connect_attempts_per_request{bucket="1"} 1141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3170
telemt_me_reconnect_success_total 795
telemt_me_reader_eof_total 862
telemt_me_idle_close_by_peer_total 862
telemt_me_route_drop_no_conn_total 30402
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63177
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 874
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 62932
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 1378193768 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 18124293824 (16.88 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 87
```