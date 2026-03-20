# Server Metrics 2026-03-20 14:31:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 959.5 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73784
telemt_connections_bad_total 2023
telemt_connections_current 1628
telemt_connections_me_current 1628
telemt_handshake_timeouts_total 1262
telemt_upstream_connect_attempt_total 293
telemt_upstream_connect_success_total 290
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 195502
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68196
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 12
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
telemt_me_writers_warm_current 16
telemt_desync_total 129
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 166
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 165
telemt_me_writer_teardown_success_total{mode="normal"} 169
telemt_me_writer_teardown_noop_total 166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.772336
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 68192
telemt_user_connections_current{user="hello"} 1628
telemt_user_octets_from_client{user="hello"} 571866572 (545.37 MB)
telemt_user_octets_to_client{user="hello"} 4997823348 (4.65 GB)
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 968.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143951
telemt_connections_bad_total 11447
telemt_connections_current 5009
telemt_connections_me_current 5009
telemt_handshake_timeouts_total 1278
telemt_upstream_connect_attempt_total 336
telemt_upstream_connect_success_total 335
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 63274
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112973
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 24
telemt_desync_total 287
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 203
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 202
telemt_me_writer_teardown_success_total{mode="normal"} 207
telemt_me_writer_teardown_noop_total 203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.045653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 410
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 112967
telemt_user_connections_current{user="hello"} 5009
telemt_user_octets_from_client{user="hello"} 1187657584 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 26040160648 (24.25 GB)
telemt_user_unique_ips_current{user="hello"} 1632
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 962.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88938
telemt_connections_bad_total 3643
telemt_connections_current 3972
telemt_connections_me_current 3972
telemt_handshake_timeouts_total 851
telemt_upstream_connect_attempt_total 327
telemt_upstream_connect_success_total 314
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 39140
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80115
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 11
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 19
telemt_desync_total 220
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_me_draining_writers_reap_progress_total 197
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 196
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 197
telemt_me_writer_teardown_success_total{mode="normal"} 201
telemt_me_writer_teardown_noop_total 197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.019058
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 398
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 80127
telemt_user_connections_current{user="hello"} 3972
telemt_user_octets_from_client{user="hello"} 1419910200 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 22565891316 (21.02 GB)
telemt_user_unique_ips_current{user="hello"} 1526
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 15021.2 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2592724
telemt_connections_bad_total 270154
telemt_connections_current 6438
telemt_connections_me_current 6438
telemt_handshake_timeouts_total 46767
telemt_upstream_connect_attempt_total 5096
telemt_upstream_connect_success_total 5063
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 490
telemt_me_reconnect_success_total 342
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 1524603
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2052652
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
telemt_desync_total 5172
telemt_desync_full_logged_total 1487
telemt_desync_suppressed_total 3685
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1981
telemt_desync_frames_bucket_total{bucket="gt_10"} 1937
telemt_pool_swap_total 10
telemt_pool_force_close_total 569
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 4320
telemt_me_writer_removed_unexpected_total 343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4000
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 283
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3751
telemt_me_writer_teardown_success_total{mode="normal"} 4616
telemt_me_writer_teardown_noop_total 4330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.332477
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 331
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 2050273
telemt_user_connections_current{user="hello"} 6438
telemt_user_octets_from_client{user="hello"} 22100966036 (20.58 GB)
telemt_user_octets_to_client{user="hello"} 577359501408 (537.71 GB)
telemt_user_unique_ips_current{user="hello"} 1960
telemt_user_unique_ips_recent_window{user="hello"} 1042
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 961.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387393
telemt_connections_bad_total 12852
telemt_connections_current 4838
telemt_connections_me_current 4838
telemt_handshake_timeouts_total 3488
telemt_upstream_connect_attempt_total 6179
telemt_upstream_connect_success_total 5917
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 6147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 82
telemt_me_reconnect_success_total 48
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 730135
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344226
telemt_me_endpoint_quarantine_total 12
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 40
telemt_me_writers_warm_current 8
telemt_desync_total 482
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 165
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 165
telemt_me_writer_teardown_success_total{mode="normal"} 216
telemt_me_writer_teardown_noop_total 165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.276546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 349802
telemt_user_connections_current{user="hello"} 4838
telemt_user_octets_from_client{user="hello"} 1103045960 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 10551729702 (9.83 GB)
telemt_user_msgs_from_client{user="hello"} 4517
telemt_user_msgs_to_client{user="hello"} 3964
telemt_user_unique_ips_current{user="hello"} 1505
telemt_user_unique_ips_recent_window{user="hello"} 1796
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 966.1 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452282
telemt_connections_bad_total 15759
telemt_connections_current 7000
telemt_connections_me_current 7000
telemt_handshake_timeouts_total 3545
telemt_upstream_connect_attempt_total 281
telemt_upstream_connect_success_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 1035096
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402005
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 9
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 27
telemt_desync_total 347
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_me_draining_writers_reap_progress_total 152
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 152
telemt_me_writer_teardown_success_total{mode="normal"} 155
telemt_me_writer_teardown_noop_total 152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 307
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.008328
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 307
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 402058
telemt_user_connections_current{user="hello"} 7000
telemt_user_octets_from_client{user="hello"} 1745972232 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 15726382776 (14.65 GB)
telemt_user_unique_ips_current{user="hello"} 2163
telemt_user_unique_ips_recent_window{user="hello"} 1179
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 389.7 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9229
telemt_connections_bad_total 304
telemt_connections_current 824
telemt_connections_me_current 824
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 186
telemt_upstream_connect_success_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 19646
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9007
telemt_me_endpoint_quarantine_total 4
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
telemt_me_writers_active_current 44
telemt_desync_total 13
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 100
telemt_me_writer_teardown_success_total{mode="normal"} 101
telemt_me_writer_teardown_noop_total 101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.031577
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 202
telemt_user_connections_total{user="hello"} 8511
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 77752800 (74.15 MB)
telemt_user_octets_to_client{user="hello"} 1490926116 (1.39 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 963.9 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171531
telemt_connections_bad_total 6762
telemt_connections_current 6898
telemt_connections_me_current 6898
telemt_handshake_timeouts_total 7297
telemt_upstream_connect_attempt_total 281
telemt_upstream_connect_success_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 71269
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149495
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 10
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 15
telemt_desync_total 454
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 155
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 153
telemt_me_writer_teardown_success_total{mode="normal"} 157
telemt_me_writer_teardown_noop_total 155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 312
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.009945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 312
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 149479
telemt_user_connections_current{user="hello"} 6898
telemt_user_octets_from_client{user="hello"} 1535661272 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 43788000908 (40.78 GB)
telemt_user_unique_ips_current{user="hello"} 2148
telemt_user_unique_ips_recent_window{user="hello"} 986
```