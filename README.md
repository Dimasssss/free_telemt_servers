# Server Metrics 2026-03-20 11:01:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 2642.2 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194305
telemt_connections_bad_total 5973
telemt_connections_current 1772
telemt_connections_me_current 1772
telemt_handshake_timeouts_total 1776
telemt_upstream_connect_attempt_total 891
telemt_upstream_connect_success_total 879
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 110
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 259105
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159541
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 16
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 371
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 713
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 675
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 654
telemt_me_writer_teardown_success_total{mode="normal"} 727
telemt_me_writer_teardown_noop_total 713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.429707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 13
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 159208
telemt_user_connections_current{user="hello"} 1772
telemt_user_octets_from_client{user="hello"} 1332247512 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 19310569336 (17.98 GB)
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 2624.5 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324607
telemt_connections_bad_total 54584
telemt_connections_current 4617
telemt_connections_me_current 4617
telemt_handshake_timeouts_total 7683
telemt_upstream_connect_attempt_total 1098
telemt_upstream_connect_success_total 1092
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 321
telemt_me_reconnect_success_total 252
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 205917
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233988
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 128
telemt_desync_total 797
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 522
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 613
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 284
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 587
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 613
telemt_me_writer_teardown_success_total{mode="normal"} 871
telemt_me_writer_teardown_noop_total 613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1484
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.060369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1484
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 252
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 234028
telemt_user_connections_current{user="hello"} 4617
telemt_user_octets_from_client{user="hello"} 3452724920 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 70117392336 (65.30 GB)
telemt_user_unique_ips_current{user="hello"} 1579
telemt_user_unique_ips_recent_window{user="hello"} 760
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 2612.5 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240486
telemt_connections_bad_total 34789
telemt_connections_current 3758
telemt_connections_me_current 3758
telemt_handshake_timeouts_total 3284
telemt_upstream_connect_attempt_total 983
telemt_upstream_connect_success_total 982
telemt_upstream_connect_attempts_per_request{bucket="1"} 982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 56
telemt_me_idle_close_by_peer_total 56
telemt_me_route_drop_no_conn_total 77699
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182150
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 81
telemt_desync_total 481
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 742
telemt_me_writer_removed_unexpected_total 55
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 702
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 715
telemt_me_writer_teardown_success_total{mode="normal"} 798
telemt_me_writer_teardown_noop_total 742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.095636
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 182201
telemt_user_connections_current{user="hello"} 3758
telemt_user_octets_from_client{user="hello"} 2348119348 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 66258422928 (61.71 GB)
telemt_user_unique_ips_current{user="hello"} 1475
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 2418.9 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355785
telemt_connections_bad_total 39859
telemt_connections_current 5929
telemt_connections_me_current 5929
telemt_handshake_timeouts_total 6135
telemt_upstream_connect_attempt_total 791
telemt_upstream_connect_success_total 790
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 166075
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286015
telemt_me_endpoint_quarantine_total 10
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 84
telemt_desync_total 502
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 590
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 563
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 556
telemt_me_writer_teardown_success_total{mode="normal"} 634
telemt_me_writer_teardown_noop_total 590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.910132
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1224
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 285360
telemt_user_connections_current{user="hello"} 5929
telemt_user_octets_from_client{user="hello"} 3527217392 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 98188240824 (91.44 GB)
telemt_user_unique_ips_current{user="hello"} 1912
telemt_user_unique_ips_recent_window{user="hello"} 953
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 2404.1 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929313
telemt_connections_bad_total 16712
telemt_connections_current 5791
telemt_connections_me_current 5791
telemt_handshake_timeouts_total 6970
telemt_upstream_connect_attempt_total 1050
telemt_upstream_connect_success_total 963
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 376
telemt_me_reconnect_success_total 179
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 1917094
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855720
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 128
telemt_desync_total 754
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 566
telemt_me_writer_removed_unexpected_total 185
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 547
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 566
telemt_me_writer_teardown_success_total{mode="normal"} 751
telemt_me_writer_teardown_noop_total 566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.340179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 177
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 855664
telemt_user_connections_current{user="hello"} 5791
telemt_user_octets_from_client{user="hello"} 3260565440 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 27701929092 (25.80 GB)
telemt_user_unique_ips_current{user="hello"} 1796
telemt_user_unique_ips_recent_window{user="hello"} 1221
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 2396.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690018
telemt_connections_bad_total 19503
telemt_connections_current 7524
telemt_connections_me_current 7524
telemt_handshake_timeouts_total 8579
telemt_upstream_connect_attempt_total 767
telemt_upstream_connect_success_total 755
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 1016523
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613364
telemt_me_endpoint_quarantine_total 10
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 87
telemt_desync_total 1402
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 997
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 552
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 524
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 519
telemt_me_writer_teardown_success_total{mode="normal"} 601
telemt_me_writer_teardown_noop_total 552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1153
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.621525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1153
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_writer_restored_same_endpoint_total 49
telemt_user_connections_total{user="hello"} 613268
telemt_user_connections_current{user="hello"} 7524
telemt_user_octets_from_client{user="hello"} 4926925848 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 51222733768 (47.70 GB)
telemt_user_unique_ips_current{user="hello"} 2262
telemt_user_unique_ips_recent_window{user="hello"} 1231
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 2395.4 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53629
telemt_connections_bad_total 8231
telemt_connections_current 870
telemt_connections_me_current 870
telemt_handshake_timeouts_total 652
telemt_upstream_connect_attempt_total 1365
telemt_upstream_connect_success_total 1365
telemt_upstream_connect_attempts_per_request{bucket="1"} 1365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 377
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 212
telemt_me_idle_close_by_peer_total 212
telemt_me_route_drop_no_conn_total 25571
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40346
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 127
telemt_desync_total 99
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 927
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 897
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 926
telemt_me_writer_teardown_success_total{mode="normal"} 1140
telemt_me_writer_teardown_noop_total 927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.698511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 197
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 40359
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 528210876 (503.74 MB)
telemt_user_octets_to_client{user="hello"} 6416047840 (5.98 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 2386.8 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400402
telemt_connections_bad_total 69910
telemt_connections_current 7099
telemt_connections_me_current 7099
telemt_handshake_timeouts_total 7981
telemt_upstream_connect_attempt_total 1063
telemt_upstream_connect_success_total 1041
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 307
telemt_me_reconnect_success_total 115
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 165817
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309639
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 127
telemt_desync_total 1035
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 702
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 425
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 733
telemt_me_writer_removed_unexpected_total 119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 713
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 733
telemt_me_writer_teardown_success_total{mode="normal"} 852
telemt_me_writer_teardown_noop_total 733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.053073
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 309634
telemt_user_connections_current{user="hello"} 7099
telemt_user_octets_from_client{user="hello"} 8473771864 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 112843738492 (105.09 GB)
telemt_user_unique_ips_current{user="hello"} 2207
telemt_user_unique_ips_recent_window{user="hello"} 1022
```