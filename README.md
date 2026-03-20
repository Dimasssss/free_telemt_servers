# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-20 16:24:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 739.1 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44044
telemt_connections_bad_total 1674
telemt_connections_current 1781
telemt_connections_direct_current 1781
telemt_relay_adaptive_promotions_total 32
telemt_relay_adaptive_demotions_total 1672
telemt_relay_adaptive_hard_promotions_total 31
telemt_handshake_timeouts_total 437
telemt_upstream_connect_attempt_total 38296
telemt_upstream_connect_success_total 38284
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 38296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38282
telemt_user_connections_current{user="hello"} 1781
telemt_user_octets_from_client{user="hello"} 870574624 (830.24 MB)
telemt_user_octets_to_client{user="hello"} 8070047604 (7.52 GB)
telemt_user_msgs_from_client{user="hello"} 560056
telemt_user_msgs_to_client{user="hello"} 521292
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 7762.0 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966759
telemt_connections_bad_total 49700
telemt_connections_current 4630
telemt_connections_me_current 4630
telemt_handshake_timeouts_total 15387
telemt_upstream_connect_attempt_total 2507
telemt_upstream_connect_success_total 2483
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 156
telemt_me_reconnect_success_total 93
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 396317
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727374
telemt_me_endpoint_quarantine_total 33
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 59
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
telemt_me_writers_active_current 44
telemt_desync_total 2574
telemt_desync_full_logged_total 868
telemt_desync_suppressed_total 1706
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 7
telemt_pool_force_close_total 297
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 2155
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1858
telemt_me_writer_teardown_success_total{mode="normal"} 2205
telemt_me_writer_teardown_noop_total 2161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.063394
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 726621
telemt_user_connections_current{user="hello"} 4630
telemt_user_octets_from_client{user="hello"} 9175851408 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 217316466636 (202.39 GB)
telemt_user_unique_ips_current{user="hello"} 1574
telemt_user_unique_ips_recent_window{user="hello"} 641
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 7756.4 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691883
telemt_connections_bad_total 43934
telemt_connections_current 3940
telemt_connections_me_current 3940
telemt_handshake_timeouts_total 10073
telemt_upstream_connect_attempt_total 3285
telemt_upstream_connect_success_total 3214
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 3282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 366
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 286124
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583907
telemt_me_endpoint_quarantine_total 48
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 2083
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 847
telemt_desync_frames_bucket_total{bucket="gt_10"} 835
telemt_pool_swap_total 5
telemt_pool_force_close_total 324
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 2795
telemt_me_writer_removed_unexpected_total 198
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2548
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2471
telemt_me_writer_teardown_success_total{mode="normal"} 2941
telemt_me_writer_teardown_noop_total 2795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5736
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.672717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5736
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 583360
telemt_user_connections_current{user="hello"} 3940
telemt_user_octets_from_client{user="hello"} 9944310280 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 207474110016 (193.23 GB)
telemt_user_unique_ips_current{user="hello"} 1434
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 21813.7 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3802516
telemt_connections_bad_total 389760
telemt_connections_current 5717
telemt_connections_me_current 5717
telemt_handshake_timeouts_total 69611
telemt_upstream_connect_attempt_total 7045
telemt_upstream_connect_success_total 7005
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 663
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 429
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 2421356
telemt_me_route_drop_channel_closed_total 157
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3015915
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 92
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 8290
telemt_desync_full_logged_total 2362
telemt_desync_suppressed_total 5928
telemt_desync_frames_bucket_total{bucket="1_2"} 2105
telemt_desync_frames_bucket_total{bucket="3_10"} 3221
telemt_desync_frames_bucket_total{bucket="gt_10"} 2964
telemt_pool_swap_total 17
telemt_pool_force_close_total 868
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 6046
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 342
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5178
telemt_me_writer_teardown_success_total{mode="normal"} 6394
telemt_me_writer_teardown_noop_total 6056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12450
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.333809
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12450
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3012522
telemt_user_connections_current{user="hello"} 5717
telemt_user_octets_from_client{user="hello"} 33799118828 (31.48 GB)
telemt_user_octets_to_client{user="hello"} 819556735376 (763.27 GB)
telemt_user_unique_ips_current{user="hello"} 1805
telemt_user_unique_ips_recent_window{user="hello"} 1203
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7754.7 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2881873
telemt_connections_bad_total 69437
telemt_connections_current 5372
telemt_connections_me_current 5372
telemt_handshake_timeouts_total 32017
telemt_upstream_connect_attempt_total 11405
telemt_upstream_connect_success_total 10795
telemt_upstream_connect_fail_total 459
telemt_upstream_connect_attempts_per_request{bucket="1"} 11254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 459
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 650
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 5892474
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2603500
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 58
telemt_desync_total 3286
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 2343
telemt_desync_frames_bucket_total{bucket="1_2"} 674
telemt_desync_frames_bucket_total{bucket="3_10"} 1456
telemt_desync_frames_bucket_total{bucket="gt_10"} 1156
telemt_pool_swap_total 5
telemt_pool_force_close_total 218
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 2184
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 526
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1966
telemt_me_writer_teardown_success_total{mode="normal"} 2556
telemt_me_writer_teardown_noop_total 2185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4741
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.852240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4741
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 2610760
telemt_user_connections_current{user="hello"} 5372
telemt_user_octets_from_client{user="hello"} 10982035199 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 83030230440 (77.33 GB)
telemt_user_msgs_from_client{user="hello"} 8736
telemt_user_msgs_to_client{user="hello"} 7574
telemt_user_unique_ips_current{user="hello"} 1750
telemt_user_unique_ips_recent_window{user="hello"} 1036
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 7759.7 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2518238
telemt_connections_bad_total 174462
telemt_connections_current 6034
telemt_connections_me_current 6034
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 23389
telemt_upstream_connect_attempt_total 19337
telemt_upstream_connect_success_total 19330
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 724
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 220
telemt_me_reconnect_success_total 68
telemt_me_reader_eof_total 69
telemt_me_idle_close_by_peer_total 69
telemt_me_route_drop_no_conn_total 4259537
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2136463
telemt_me_endpoint_quarantine_total 47
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 41
telemt_desync_total 3626
telemt_desync_full_logged_total 1059
telemt_desync_suppressed_total 2567
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 1558
telemt_desync_frames_bucket_total{bucket="gt_10"} 1137
telemt_pool_swap_total 8
telemt_pool_force_close_total 246
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 1751
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1577
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1505
telemt_me_writer_teardown_success_total{mode="normal"} 1787
telemt_me_writer_teardown_noop_total 1755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3542
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 114.254929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3542
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 2149969
telemt_user_connections_current{user="hello"} 6034
telemt_user_octets_from_client{user="hello"} 16849964760 (15.69 GB)
telemt_user_octets_to_client{user="hello"} 159588947219 (148.63 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1950
telemt_user_unique_ips_recent_window{user="hello"} 790
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 7182.8 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148471
telemt_connections_bad_total 1325
telemt_connections_current 732
telemt_connections_me_current 732
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 2607
telemt_upstream_connect_attempt_total 4261
telemt_upstream_connect_success_total 4258
telemt_upstream_connect_attempts_per_request{bucket="1"} 4258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 219
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 56
telemt_me_idle_close_by_peer_total 56
telemt_me_route_drop_no_conn_total 125103
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129796
telemt_me_endpoint_quarantine_total 48
telemt_me_single_endpoint_shadow_rotate_total 55
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
telemt_me_writers_active_current 43
telemt_desync_total 439
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 7
telemt_pool_force_close_total 194
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 2227
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2032
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2033
telemt_me_writer_teardown_success_total{mode="normal"} 2268
telemt_me_writer_teardown_noop_total 2228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.463228
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 45
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 130783
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 1591426326 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 24446563769 (22.77 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 7757.4 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1367043
telemt_connections_bad_total 82631
telemt_connections_current 7390
telemt_connections_me_current 7390
telemt_handshake_timeouts_total 45516
telemt_upstream_connect_attempt_total 2306
telemt_upstream_connect_success_total 2304
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 150
telemt_me_reconnect_success_total 76
telemt_me_reader_eof_total 81
telemt_me_idle_close_by_peer_total 81
telemt_me_route_drop_no_conn_total 672742
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1162618
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 4247
telemt_desync_full_logged_total 1214
telemt_desync_suppressed_total 3033
telemt_desync_frames_bucket_total{bucket="1_2"} 1050
telemt_desync_frames_bucket_total{bucket="3_10"} 1597
telemt_desync_frames_bucket_total{bucket="gt_10"} 1600
telemt_pool_swap_total 7
telemt_pool_force_close_total 263
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 1946
telemt_me_writer_removed_unexpected_total 79
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 221
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1683
telemt_me_writer_teardown_success_total{mode="normal"} 2029
telemt_me_writer_teardown_noop_total 1947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3976
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.362245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3976
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 69
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1161348
telemt_user_connections_current{user="hello"} 7390
telemt_user_octets_from_client{user="hello"} 15083756660 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 356903847284 (332.39 GB)
telemt_user_unique_ips_current{user="hello"} 2229
telemt_user_unique_ips_recent_window{user="hello"} 938
```