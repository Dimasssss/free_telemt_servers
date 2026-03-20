# Server Metrics 2026-03-20 14:21:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 344.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32830
telemt_connections_bad_total 727
telemt_connections_current 1688
telemt_connections_me_current 1688
telemt_handshake_timeouts_total 800
telemt_upstream_connect_attempt_total 151
telemt_upstream_connect_success_total 149
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 96580
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30266
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 44
telemt_desync_total 64
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 64
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63
telemt_me_writer_teardown_success_total{mode="normal"} 64
telemt_me_writer_teardown_noop_total 64
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.607693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_user_connections_total{user="hello"} 30277
telemt_user_connections_current{user="hello"} 1688
telemt_user_octets_from_client{user="hello"} 155317112 (148.12 MB)
telemt_user_octets_to_client{user="hello"} 1576038392 (1.47 GB)
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 353.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64802
telemt_connections_bad_total 8019
telemt_connections_current 5050
telemt_connections_me_current 5050
telemt_handshake_timeouts_total 306
telemt_upstream_connect_attempt_total 166
telemt_upstream_connect_success_total 165
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 24797
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50257
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 43
telemt_desync_total 88
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 80
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 79
telemt_me_writer_teardown_success_total{mode="normal"} 81
telemt_me_writer_teardown_noop_total 80
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 161
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.041576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 161
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 50251
telemt_user_connections_current{user="hello"} 5050
telemt_user_octets_from_client{user="hello"} 461579044 (440.20 MB)
telemt_user_octets_to_client{user="hello"} 8562644244 (7.97 GB)
telemt_user_unique_ips_current{user="hello"} 1603
telemt_user_unique_ips_recent_window{user="hello"} 728
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 347.1 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34762
telemt_connections_bad_total 1480
telemt_connections_current 3429
telemt_connections_me_current 3429
telemt_handshake_timeouts_total 312
telemt_upstream_connect_attempt_total 168
telemt_upstream_connect_success_total 157
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 13384
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31288
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 45
telemt_desync_total 70
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_draining_writers_reap_progress_total 80
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 80
telemt_me_writer_teardown_success_total{mode="normal"} 80
telemt_me_writer_teardown_noop_total 80
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.009675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 160
telemt_user_connections_total{user="hello"} 31290
telemt_user_connections_current{user="hello"} 3429
telemt_user_octets_from_client{user="hello"} 798324392 (761.34 MB)
telemt_user_octets_to_client{user="hello"} 7225162932 (6.73 GB)
telemt_user_unique_ips_current{user="hello"} 1448
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 14406.2 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2472777
telemt_connections_bad_total 266878
telemt_connections_current 5855
telemt_connections_me_current 5855
telemt_handshake_timeouts_total 44661
telemt_upstream_connect_attempt_total 4915
telemt_upstream_connect_success_total 4884
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 455
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 340
telemt_me_idle_close_by_peer_total 340
telemt_me_route_drop_no_conn_total 1437183
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1952762
telemt_me_endpoint_quarantine_total 60
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 90
telemt_desync_total 4818
telemt_desync_full_logged_total 1394
telemt_desync_suppressed_total 3424
telemt_desync_frames_bucket_total{bucket="1_2"} 1179
telemt_desync_frames_bucket_total{bucket="3_10"} 1837
telemt_desync_frames_bucket_total{bucket="gt_10"} 1802
telemt_pool_swap_total 9
telemt_pool_force_close_total 501
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 4109
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3817
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 259
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 242
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3608
telemt_me_writer_teardown_success_total{mode="normal"} 4403
telemt_me_writer_teardown_noop_total 4119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.893878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 328
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1950676
telemt_user_connections_current{user="hello"} 5855
telemt_user_octets_from_client{user="hello"} 21048930996 (19.60 GB)
telemt_user_octets_to_client{user="hello"} 555585564980 (517.43 GB)
telemt_user_unique_ips_current{user="hello"} 1894
telemt_user_unique_ips_recent_window{user="hello"} 785
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 345.8 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131969
telemt_connections_bad_total 3350
telemt_connections_current 5742
telemt_connections_me_current 5742
telemt_handshake_timeouts_total 990
telemt_upstream_connect_attempt_total 166
telemt_upstream_connect_success_total 160
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 4
telemt_me_route_drop_no_conn_total 197886
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119866
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 43
telemt_desync_total 144
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_me_draining_writers_reap_progress_total 81
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 81
telemt_me_writer_teardown_success_total{mode="normal"} 81
telemt_me_writer_teardown_noop_total 81
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.132615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 162
telemt_user_connections_total{user="hello"} 119855
telemt_user_connections_current{user="hello"} 5742
telemt_user_octets_from_client{user="hello"} 425912708 (406.18 MB)
telemt_user_octets_to_client{user="hello"} 3886239652 (3.62 GB)
telemt_user_unique_ips_current{user="hello"} 1776
telemt_user_unique_ips_recent_window{user="hello"} 1192
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 350.8 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147651
telemt_connections_bad_total 3614
telemt_connections_current 6577
telemt_connections_me_current 6577
telemt_handshake_timeouts_total 1218
telemt_upstream_connect_attempt_total 144
telemt_upstream_connect_success_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 69
telemt_me_route_drop_no_conn_total 267185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127817
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 5
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
telemt_me_writers_active_current 43
telemt_desync_total 94
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_draining_writers_reap_progress_total 62
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62
telemt_me_writer_teardown_success_total{mode="normal"} 62
telemt_me_writer_teardown_noop_total 62
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.002837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124
telemt_user_connections_total{user="hello"} 127824
telemt_user_connections_current{user="hello"} 6577
telemt_user_octets_from_client{user="hello"} 621589548 (592.79 MB)
telemt_user_octets_to_client{user="hello"} 6655819580 (6.20 GB)
telemt_user_unique_ips_current{user="hello"} 2087
telemt_user_unique_ips_recent_window{user="hello"} 1240
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 342.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8503
telemt_connections_bad_total 459
telemt_connections_current 767
telemt_connections_me_current 767
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 173
telemt_upstream_connect_success_total 170
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 3752
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7654
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_active_current 48
telemt_desync_total 25
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 80
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 79
telemt_me_writer_teardown_success_total{mode="normal"} 80
telemt_me_writer_teardown_noop_total 80
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.092023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 160
telemt_user_connections_total{user="hello"} 7605
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 35696864 (34.04 MB)
telemt_user_octets_to_client{user="hello"} 1595140228 (1.49 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 348.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72381
telemt_connections_bad_total 2602
telemt_connections_current 7054
telemt_connections_me_current 7054
telemt_handshake_timeouts_total 1509
telemt_upstream_connect_attempt_total 148
telemt_upstream_connect_success_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 31534
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64039
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_me_writers_active_current 48
telemt_desync_total 187
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 59
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57
telemt_me_writer_teardown_success_total{mode="normal"} 59
telemt_me_writer_teardown_noop_total 59
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.004419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_user_connections_total{user="hello"} 63988
telemt_user_connections_current{user="hello"} 7054
telemt_user_octets_from_client{user="hello"} 471793012 (449.94 MB)
telemt_user_octets_to_client{user="hello"} 13280424664 (12.37 GB)
telemt_user_unique_ips_current{user="hello"} 2145
telemt_user_unique_ips_recent_window{user="hello"} 993
```