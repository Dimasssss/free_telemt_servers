# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 03:42:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 23757.9 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362590
telemt_connections_bad_total 23713
telemt_connections_current 1029
telemt_connections_me_current 1029
telemt_handshake_timeouts_total 20235
telemt_upstream_connect_attempt_total 9955
telemt_upstream_connect_success_total 9954
telemt_upstream_connect_attempts_per_request{bucket="1"} 9954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 278
telemt_me_reconnect_success_total 151
telemt_me_reader_eof_total 148
telemt_me_idle_close_by_peer_total 148
telemt_me_route_drop_no_conn_total 69654
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299723
telemt_me_endpoint_quarantine_total 192
telemt_me_single_endpoint_shadow_rotate_total 202
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
telemt_desync_total 2730
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1991
telemt_desync_frames_bucket_total{bucket="1_2"} 930
telemt_desync_frames_bucket_total{bucket="3_10"} 1027
telemt_desync_frames_bucket_total{bucket="gt_10"} 773
telemt_pool_swap_total 26
telemt_pool_force_close_total 682
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 9003
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 677
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8321
telemt_me_writer_teardown_success_total{mode="normal"} 9141
telemt_me_writer_teardown_noop_total 9004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.338586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 299033
telemt_user_connections_current{user="hello"} 1029
telemt_user_octets_from_client{user="hello"} 3936086144 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 103410400092 (96.31 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 37124.0 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835988
telemt_connections_bad_total 54083
telemt_connections_current 412
telemt_connections_me_current 412
telemt_handshake_timeouts_total 30417
telemt_upstream_connect_attempt_total 17418
telemt_upstream_connect_success_total 17149
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 17395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_reconnect_attempts_total 1488
telemt_me_reconnect_success_total 535
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 348973
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661811
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_active_current 41
telemt_desync_total 2824
telemt_desync_full_logged_total 1624
telemt_desync_suppressed_total 1200
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 1074
telemt_desync_frames_bucket_total{bucket="gt_10"} 1152
telemt_pool_swap_total 40
telemt_pool_force_close_total 1076
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 15454
telemt_me_writer_removed_unexpected_total 452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1284
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14632
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1054
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14378
telemt_me_writer_teardown_success_total{mode="normal"} 15916
telemt_me_writer_teardown_noop_total 15454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.794494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 660844
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 10788679344 (10.05 GB)
telemt_user_octets_to_client{user="hello"} 236157055512 (219.94 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 111983.8 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7875001
telemt_connections_bad_total 652385
telemt_connections_current 1933
telemt_connections_me_current 1933
telemt_handshake_timeouts_total 259079
telemt_upstream_connect_attempt_total 41779
telemt_upstream_connect_success_total 41703
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1622
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 4555737
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6361564
telemt_me_endpoint_quarantine_total 724
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 838
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 26715
telemt_desync_full_logged_total 8865
telemt_desync_suppressed_total 17850
telemt_desync_frames_bucket_total{bucket="1_2"} 5771
telemt_desync_frames_bucket_total{bucket="3_10"} 10431
telemt_desync_frames_bucket_total{bucket="gt_10"} 10513
telemt_pool_swap_total 121
telemt_pool_force_close_total 3991
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 611
telemt_me_draining_writers_reap_progress_total 38109
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3179
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35283
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34118
telemt_me_writer_teardown_success_total{mode="normal"} 38462
telemt_me_writer_teardown_noop_total 38153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.387656
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 611
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6353575
telemt_user_connections_current{user="hello"} 1933
telemt_user_octets_from_client{user="hello"} 107787559920 (100.38 GB)
telemt_user_octets_to_client{user="hello"} 2126948597636 (1.93 TB)
telemt_user_unique_ips_current{user="hello"} 938
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 111985.3 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6514090
telemt_connections_bad_total 591167
telemt_connections_current 1793
telemt_connections_me_current 1793
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 216194
telemt_upstream_connect_attempt_total 45742
telemt_upstream_connect_success_total 45349
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 45545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1967
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 2274635
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4856574
telemt_me_endpoint_quarantine_total 705
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 864
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 47
telemt_desync_total 22852
telemt_desync_full_logged_total 7795
telemt_desync_suppressed_total 15057
telemt_desync_frames_bucket_total{bucket="1_2"} 5493
telemt_desync_frames_bucket_total{bucket="3_10"} 8883
telemt_desync_frames_bucket_total{bucket="gt_10"} 8476
telemt_pool_swap_total 122
telemt_pool_force_close_total 3619
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 36585
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34338
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32966
telemt_me_writer_teardown_success_total{mode="normal"} 37377
telemt_me_writer_teardown_noop_total 36591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.470545
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4778621
telemt_user_connections_current{user="hello"} 1793
telemt_user_octets_from_client{user="hello"} 141829936089 (132.09 GB)
telemt_user_octets_to_client{user="hello"} 2261918631355 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 835
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 111949.4 (31h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6383193
telemt_connections_bad_total 550528
telemt_connections_current 1694
telemt_connections_me_current 1694
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 208088
telemt_upstream_connect_attempt_total 51878
telemt_upstream_connect_success_total 51482
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 51619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1092
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2181
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 2172264
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4740765
telemt_me_endpoint_quarantine_total 794
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 22764
telemt_desync_full_logged_total 7675
telemt_desync_suppressed_total 15089
telemt_desync_frames_bucket_total{bucket="1_2"} 5557
telemt_desync_frames_bucket_total{bucket="3_10"} 8723
telemt_desync_frames_bucket_total{bucket="gt_10"} 8484
telemt_pool_swap_total 121
telemt_pool_force_close_total 3507
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 37691
telemt_me_writer_removed_unexpected_total 857
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35434
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34184
telemt_me_writer_teardown_success_total{mode="normal"} 38565
telemt_me_writer_teardown_noop_total 37703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76268
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.167664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76268
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 4736050
telemt_user_connections_current{user="hello"} 1694
telemt_user_octets_from_client{user="hello"} 134843091323 (125.58 GB)
telemt_user_octets_to_client{user="hello"} 2174873882379 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 790
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 111988.7 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20611037
telemt_connections_bad_total 1680578
telemt_connections_current 2628
telemt_connections_me_current 2628
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 619481
telemt_upstream_connect_attempt_total 202644
telemt_upstream_connect_success_total 184369
telemt_upstream_connect_fail_total 16465
telemt_upstream_connect_attempts_per_request{bucket="1"} 200834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8948
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16465
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65127
telemt_me_reconnect_success_total 2399
telemt_me_reader_eof_total 1486
telemt_me_idle_close_by_peer_total 1485
telemt_me_route_drop_no_conn_total 39542587
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16617605
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 875
telemt_me_single_endpoint_outage_enter_total 143
telemt_me_single_endpoint_outage_exit_total 143
telemt_me_single_endpoint_outage_reconnect_attempt_total 296
telemt_me_single_endpoint_outage_reconnect_success_total 75
telemt_me_single_endpoint_quarantine_bypass_total 296
telemt_me_single_endpoint_shadow_rotate_total 880
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_desync_total 32210
telemt_desync_full_logged_total 9689
telemt_desync_suppressed_total 22521
telemt_desync_frames_bucket_total{bucket="1_2"} 6985
telemt_desync_frames_bucket_total{bucket="3_10"} 14291
telemt_desync_frames_bucket_total{bucket="gt_10"} 10934
telemt_pool_swap_total 116
telemt_pool_force_close_total 3741
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 827
telemt_me_draining_writers_reap_progress_total 35172
telemt_me_writer_removed_unexpected_total 2229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32380
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3216
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31431
telemt_me_writer_teardown_success_total{mode="normal"} 37142
telemt_me_writer_teardown_noop_total 35199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.520535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 827
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1629
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16752462
telemt_user_connections_current{user="hello"} 2628
telemt_user_octets_from_client{user="hello"} 230235717016 (214.42 GB)
telemt_user_octets_to_client{user="hello"} 1242312459023 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1191
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 111956.1 (31h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6145045
telemt_connections_bad_total 594757
telemt_connections_current 1553
telemt_connections_me_current 1553
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 129213
telemt_upstream_connect_attempt_total 60586
telemt_upstream_connect_success_total 59892
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 60485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24734
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_reconnect_attempts_total 69754
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 2405429
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4772834
telemt_me_endpoint_quarantine_total 762
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 851
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 47
telemt_desync_total 23791
telemt_desync_full_logged_total 8367
telemt_desync_suppressed_total 15424
telemt_desync_frames_bucket_total{bucket="1_2"} 4582
telemt_desync_frames_bucket_total{bucket="3_10"} 9214
telemt_desync_frames_bucket_total{bucket="gt_10"} 9995
telemt_pool_swap_total 116
telemt_pool_force_close_total 3320
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 39629
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4035
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36309
telemt_me_writer_teardown_success_total{mode="normal"} 41298
telemt_me_writer_teardown_noop_total 39630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80928
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.225835
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80928
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1525
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4765524
telemt_user_connections_current{user="hello"} 1553
telemt_user_octets_from_client{user="hello"} 125920197968 (117.27 GB)
telemt_user_octets_to_client{user="hello"} 1950221610946 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48792.0 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4070020
telemt_connections_bad_total 170483
telemt_connections_current 1965
telemt_connections_me_current 1965
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1638375
telemt_upstream_connect_attempt_total 29334
telemt_upstream_connect_success_total 29143
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 29327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 45957
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 680
telemt_me_idle_close_by_peer_total 680
telemt_me_route_drop_no_conn_total 1036240
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1992098
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 377
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10678
telemt_desync_full_logged_total 3696
telemt_desync_suppressed_total 6982
telemt_desync_frames_bucket_total{bucket="1_2"} 1945
telemt_desync_frames_bucket_total{bucket="3_10"} 4091
telemt_desync_frames_bucket_total{bucket="gt_10"} 4642
telemt_pool_swap_total 53
telemt_pool_force_close_total 1548
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 18189
telemt_me_writer_removed_unexpected_total 753
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1608
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1342
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16641
telemt_me_writer_teardown_success_total{mode="normal"} 18969
telemt_me_writer_teardown_noop_total 18191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.499531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 888
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1995620
telemt_user_connections_current{user="hello"} 1965
telemt_user_octets_from_client{user="hello"} 55148816784 (51.36 GB)
telemt_user_octets_to_client{user="hello"} 846174846326 (788.06 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 29762.8 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213332
telemt_connections_bad_total 1776
telemt_connections_current 395
telemt_connections_me_current 395
telemt_handshake_timeouts_total 5790
telemt_upstream_connect_attempt_total 14356
telemt_upstream_connect_success_total 14321
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 14354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 332
telemt_me_reconnect_success_total 189
telemt_me_reader_eof_total 194
telemt_me_idle_close_by_peer_total 194
telemt_me_route_drop_no_conn_total 59196
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188498
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 25
telemt_desync_total 1092
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 810
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 32
telemt_pool_force_close_total 716
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 12941
telemt_me_writer_removed_unexpected_total 187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 829
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12306
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 714
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12225
telemt_me_writer_teardown_success_total{mode="normal"} 13135
telemt_me_writer_teardown_noop_total 12941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.060363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 171
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 188168
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 3310966536 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 115659432300 (107.72 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 111960.5 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7459496
telemt_connections_bad_total 750919
telemt_connections_current 2007
telemt_connections_me_current 2007
telemt_handshake_timeouts_total 212713
telemt_upstream_connect_attempt_total 44074
telemt_upstream_connect_success_total 43914
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 44037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_reconnect_attempts_total 1637
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 856
telemt_me_idle_close_by_peer_total 856
telemt_me_route_drop_no_conn_total 2144259
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5562437
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 864
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21812
telemt_desync_full_logged_total 7158
telemt_desync_suppressed_total 14654
telemt_desync_frames_bucket_total{bucket="1_2"} 5479
telemt_desync_frames_bucket_total{bucket="3_10"} 7904
telemt_desync_frames_bucket_total{bucket="gt_10"} 8429
telemt_pool_swap_total 124
telemt_pool_force_close_total 3311
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 39759
telemt_me_writer_removed_unexpected_total 825
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36448
telemt_me_writer_teardown_success_total{mode="normal"} 40605
telemt_me_writer_teardown_noop_total 39761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.694881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5537321
telemt_user_connections_current{user="hello"} 2007
telemt_user_octets_from_client{user="hello"} 110551215888 (102.96 GB)
telemt_user_octets_to_client{user="hello"} 2580214203772 (2.35 TB)
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 111957.1 (31h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6462842
telemt_connections_bad_total 635754
telemt_connections_current 1804
telemt_connections_me_current 1804
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174998
telemt_upstream_connect_attempt_total 59898
telemt_upstream_connect_success_total 59450
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 59839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_reconnect_attempts_total 5608
telemt_me_reconnect_success_total 1207
telemt_me_reader_eof_total 1090
telemt_me_idle_close_by_peer_total 1090
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2197065
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4928461
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 857
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20431
telemt_desync_full_logged_total 6814
telemt_desync_suppressed_total 13617
telemt_desync_frames_bucket_total{bucket="1_2"} 5220
telemt_desync_frames_bucket_total{bucket="3_10"} 7458
telemt_desync_frames_bucket_total{bucket="gt_10"} 7753
telemt_pool_swap_total 122
telemt_pool_force_close_total 3265
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 38346
telemt_me_writer_removed_unexpected_total 1102
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35855
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35081
telemt_me_writer_teardown_success_total{mode="normal"} 39503
telemt_me_writer_teardown_noop_total 38350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.162770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4931353
telemt_user_connections_current{user="hello"} 1804
telemt_user_octets_from_client{user="hello"} 92989946385 (86.60 GB)
telemt_user_octets_to_client{user="hello"} 2110814401628 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 817
telemt_user_unique_ips_recent_window{user="hello"} 220
```