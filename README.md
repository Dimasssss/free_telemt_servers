# Server Metrics 2026-03-20 14:26:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 651.9 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56196
telemt_connections_bad_total 1419
telemt_connections_current 1906
telemt_connections_me_current 1906
telemt_handshake_timeouts_total 959
telemt_upstream_connect_attempt_total 209
telemt_upstream_connect_success_total 207
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 135303
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52166
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
telemt_desync_total 105
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 108
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 106
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 107
telemt_me_writer_teardown_success_total{mode="normal"} 108
telemt_me_writer_teardown_noop_total 108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.003154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_user_connections_total{user="hello"} 52172
telemt_user_connections_current{user="hello"} 1906
telemt_user_octets_from_client{user="hello"} 421144560 (401.63 MB)
telemt_user_octets_to_client{user="hello"} 3135704104 (2.92 GB)
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 661.6 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103693
telemt_connections_bad_total 9963
telemt_connections_current 4860
telemt_connections_me_current 4860
telemt_handshake_timeouts_total 804
telemt_upstream_connect_attempt_total 242
telemt_upstream_connect_success_total 241
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 42339
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80992
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
telemt_desync_total 189
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 135
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 134
telemt_me_writer_teardown_success_total{mode="normal"} 138
telemt_me_writer_teardown_noop_total 135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.043408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 273
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 80987
telemt_user_connections_current{user="hello"} 4860
telemt_user_octets_from_client{user="hello"} 847313764 (808.06 MB)
telemt_user_octets_to_client{user="hello"} 17438308640 (16.24 GB)
telemt_user_unique_ips_current{user="hello"} 1583
telemt_user_unique_ips_recent_window{user="hello"} 670
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 656.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62252
telemt_connections_bad_total 2718
telemt_connections_current 3914
telemt_connections_me_current 3914
telemt_handshake_timeouts_total 489
telemt_upstream_connect_attempt_total 249
telemt_upstream_connect_success_total 237
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 25612
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56142
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
telemt_desync_total 135
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_me_draining_writers_reap_progress_total 141
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 141
telemt_me_writer_teardown_success_total{mode="normal"} 144
telemt_me_writer_teardown_noop_total 141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.014867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 285
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 56151
telemt_user_connections_current{user="hello"} 3914
telemt_user_octets_from_client{user="hello"} 1110247812 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 14599003844 (13.60 GB)
telemt_user_unique_ips_current{user="hello"} 1482
telemt_user_unique_ips_recent_window{user="hello"} 630
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 14713.5 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2524970
telemt_connections_bad_total 268630
telemt_connections_current 5843
telemt_connections_me_current 5843
telemt_handshake_timeouts_total 45608
telemt_upstream_connect_attempt_total 5046
telemt_upstream_connect_success_total 5013
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 1462900
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1995524
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 67
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 93
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
telemt_me_writers_active_current 42
telemt_desync_total 4988
telemt_desync_full_logged_total 1439
telemt_desync_suppressed_total 3549
telemt_desync_frames_bucket_total{bucket="1_2"} 1218
telemt_desync_frames_bucket_total{bucket="3_10"} 1894
telemt_desync_frames_bucket_total{bucket="gt_10"} 1876
telemt_pool_swap_total 10
telemt_pool_force_close_total 569
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 4283
telemt_me_writer_removed_unexpected_total 341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3963
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 283
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3714
telemt_me_writer_teardown_success_total{mode="normal"} 4576
telemt_me_writer_teardown_noop_total 4293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.260853
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 329
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 1993170
telemt_user_connections_current{user="hello"} 5843
telemt_user_octets_from_client{user="hello"} 21609126096 (20.13 GB)
telemt_user_octets_to_client{user="hello"} 566793743776 (527.87 GB)
telemt_user_unique_ips_current{user="hello"} 1866
telemt_user_unique_ips_recent_window{user="hello"} 747
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 653.8 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256709
telemt_connections_bad_total 9528
telemt_connections_current 6037
telemt_connections_me_current 6037
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 231
telemt_upstream_connect_success_total 221
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 40
telemt_me_route_drop_no_conn_total 438495
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230891
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
telemt_desync_total 346
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_me_draining_writers_reap_progress_total 128
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 127
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 128
telemt_me_writer_teardown_success_total{mode="normal"} 128
telemt_me_writer_teardown_noop_total 128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.189501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 256
telemt_user_connections_total{user="hello"} 230864
telemt_user_connections_current{user="hello"} 6037
telemt_user_octets_from_client{user="hello"} 813848040 (776.15 MB)
telemt_user_octets_to_client{user="hello"} 7504521832 (6.99 GB)
telemt_user_unique_ips_current{user="hello"} 1788
telemt_user_unique_ips_recent_window{user="hello"} 1174
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 658.1 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283378
telemt_connections_bad_total 7387
telemt_connections_current 6809
telemt_connections_me_current 6809
telemt_handshake_timeouts_total 2429
telemt_upstream_connect_attempt_total 199
telemt_upstream_connect_success_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 616500
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248707
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
telemt_desync_total 213
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_me_draining_writers_reap_progress_total 103
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 103
telemt_me_writer_teardown_success_total{mode="normal"} 104
telemt_me_writer_teardown_noop_total 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.003752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 207
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 248735
telemt_user_connections_current{user="hello"} 6809
telemt_user_octets_from_client{user="hello"} 1268130404 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 11873379408 (11.06 GB)
telemt_user_unique_ips_current{user="hello"} 2092
telemt_user_unique_ips_recent_window{user="hello"} 1231
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 83.5 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2626
telemt_connections_bad_total 75
telemt_connections_current 640
telemt_connections_me_current 640
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 107
telemt_upstream_connect_success_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 5258
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2619
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_draining_writers_reap_progress_total 21
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21
telemt_me_writer_teardown_success_total{mode="normal"} 21
telemt_me_writer_teardown_noop_total 21
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.006059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42
telemt_user_connections_total{user="hello"} 2389
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 17309796 (16.51 MB)
telemt_user_octets_to_client{user="hello"} 149481092 (142.56 MB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 657.0 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123143
telemt_connections_bad_total 4531
telemt_connections_current 6827
telemt_connections_me_current 6827
telemt_handshake_timeouts_total 4885
telemt_upstream_connect_attempt_total 207
telemt_upstream_connect_success_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 49854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107650
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
telemt_desync_total 339
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 103
telemt_me_writer_teardown_success_total{mode="normal"} 105
telemt_me_writer_teardown_noop_total 105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 210
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.007139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 210
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_user_connections_total{user="hello"} 107616
telemt_user_connections_current{user="hello"} 6827
telemt_user_octets_from_client{user="hello"} 944770408 (901.00 MB)
telemt_user_octets_to_client{user="hello"} 28436772248 (26.48 GB)
telemt_user_unique_ips_current{user="hello"} 2143
telemt_user_unique_ips_recent_window{user="hello"} 852
```