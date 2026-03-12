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

# Server Metrics 2026-03-12 18:05:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 37936.0 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195712
telemt_connections_bad_total 2415
telemt_handshake_timeouts_total 4945
telemt_upstream_connect_attempt_total 9620
telemt_upstream_connect_success_total 9577
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1381
telemt_me_reconnect_attempts_total 11057
telemt_me_reconnect_success_total 7601
telemt_me_reader_eof_total 8054
telemt_me_idle_close_by_peer_total 8053
telemt_me_route_drop_no_conn_total 58319
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165476
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 630
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7798
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7585
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 165436
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 2953502732 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 70399358616 (65.56 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 37829.0 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83886
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 664
telemt_upstream_connect_attempt_total 15334
telemt_upstream_connect_success_total 15087
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 15334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 38823
telemt_me_reconnect_success_total 9026
telemt_me_reader_eof_total 10129
telemt_me_idle_close_by_peer_total 10129
telemt_me_route_drop_no_conn_total 35178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10029
telemt_me_refill_failed_total 930
telemt_me_writer_restored_same_endpoint_total 9011
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1003
telemt_user_connections_total{user="hello"} 79748
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 871708797 (831.33 MB)
telemt_user_octets_to_client{user="hello"} 21751203482 (20.26 GB)
telemt_user_msgs_from_client{user="hello"} 64805
telemt_user_msgs_to_client{user="hello"} 359657
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 37792.4 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110846
telemt_connections_bad_total 1509
telemt_handshake_timeouts_total 2103
telemt_upstream_connect_attempt_total 10400
telemt_upstream_connect_success_total 10400
telemt_upstream_connect_attempts_per_request{bucket="1"} 10400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 8522
telemt_me_reconnect_success_total 8448
telemt_me_reader_eof_total 8941
telemt_me_idle_close_by_peer_total 8941
telemt_me_route_drop_no_conn_total 41482
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102691
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8528
telemt_me_writer_restored_same_endpoint_total 8428
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 102663
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 2381263692 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 52909292208 (49.28 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 37768.2 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151243
telemt_connections_bad_total 13097
telemt_handshake_timeouts_total 1150
telemt_upstream_connect_attempt_total 8587
telemt_upstream_connect_success_total 8321
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 8586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 374
telemt_me_reconnect_attempts_total 35655
telemt_me_reconnect_success_total 6410
telemt_me_reader_eof_total 7465
telemt_me_idle_close_by_peer_total 7465
telemt_me_route_drop_no_conn_total 55357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129575
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7394
telemt_me_refill_failed_total 912
telemt_me_writer_restored_same_endpoint_total 6402
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 984
telemt_user_connections_total{user="hello"} 129457
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2281186220 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 53517117632 (49.84 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37737.5 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95752
telemt_connections_bad_total 9764
telemt_handshake_timeouts_total 1165
telemt_upstream_connect_attempt_total 51174
telemt_upstream_connect_success_total 50726
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 51174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 52019
telemt_me_reconnect_success_total 3741
telemt_me_reader_eof_total 5247
telemt_me_idle_close_by_peer_total 5247
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13728
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35811
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5275
telemt_me_refill_failed_total 1511
telemt_me_writer_restored_same_endpoint_total 3724
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1534
telemt_user_connections_total{user="hello"} 80888
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 728440575 (694.70 MB)
telemt_user_octets_to_client{user="hello"} 23595570939 (21.98 GB)
telemt_user_msgs_from_client{user="hello"} 690714
telemt_user_msgs_to_client{user="hello"} 2627014
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 37725.3 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241174
telemt_connections_bad_total 1273
telemt_handshake_timeouts_total 2064
telemt_upstream_connect_attempt_total 8027
telemt_upstream_connect_success_total 7989
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 457
telemt_me_reconnect_attempts_total 9684
telemt_me_reconnect_success_total 6082
telemt_me_reader_eof_total 6480
telemt_me_idle_close_by_peer_total 6479
telemt_me_route_drop_no_conn_total 110496
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240102
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6273
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6075
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 230031
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 4083255764 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 106722294200 (99.39 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 59
```