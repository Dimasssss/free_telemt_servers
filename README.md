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

# Server Metrics 2026-03-21 23:12:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 7548.3 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127536
telemt_connections_bad_total 9993
telemt_connections_current 615
telemt_connections_me_current 615
telemt_handshake_timeouts_total 6126
telemt_upstream_connect_attempt_total 2976
telemt_upstream_connect_success_total 2975
telemt_upstream_connect_attempts_per_request{bucket="1"} 2975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 41
telemt_me_idle_close_by_peer_total 41
telemt_me_route_drop_no_conn_total 26371
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103433
telemt_me_endpoint_quarantine_total 52
telemt_me_single_endpoint_shadow_rotate_total 68
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
telemt_me_writers_active_current 44
telemt_desync_total 627
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 300
telemt_pool_swap_total 8
telemt_pool_force_close_total 211
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 2637
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2426
telemt_me_writer_teardown_success_total{mode="normal"} 2677
telemt_me_writer_teardown_noop_total 2637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.535361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 103329
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 1272526284 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 38123416724 (35.51 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 20914.2 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638416
telemt_connections_bad_total 29760
telemt_connections_current 262
telemt_connections_me_current 262
telemt_handshake_timeouts_total 24359
telemt_upstream_connect_attempt_total 8711
telemt_upstream_connect_success_total 8556
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 8696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 766
telemt_me_reconnect_success_total 263
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 320399
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520554
telemt_me_endpoint_quarantine_total 182
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2311
telemt_desync_full_logged_total 1321
telemt_desync_suppressed_total 990
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 956
telemt_pool_swap_total 23
telemt_pool_force_close_total 654
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 7677
telemt_me_writer_removed_unexpected_total 212
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7214
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 647
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7023
telemt_me_writer_teardown_success_total{mode="normal"} 7889
telemt_me_writer_teardown_noop_total 7677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.338665
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 182
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 519843
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 8839412164 (8.23 GB)
telemt_user_octets_to_client{user="hello"} 179166468172 (166.86 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 95774.1 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7346454
telemt_connections_bad_total 566478
telemt_connections_current 1781
telemt_connections_me_current 1781
telemt_handshake_timeouts_total 235512
telemt_upstream_connect_attempt_total 34603
telemt_upstream_connect_success_total 34534
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 4483241
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6007496
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 712
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 25485
telemt_desync_full_logged_total 8408
telemt_desync_suppressed_total 17077
telemt_desync_frames_bucket_total{bucket="1_2"} 5464
telemt_desync_frames_bucket_total{bucket="3_10"} 9957
telemt_desync_frames_bucket_total{bucket="gt_10"} 10064
telemt_pool_swap_total 103
telemt_pool_force_close_total 3477
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 562
telemt_me_draining_writers_reap_progress_total 31543
telemt_me_writer_removed_unexpected_total 702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2680
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28066
telemt_me_writer_teardown_success_total{mode="normal"} 31822
telemt_me_writer_teardown_noop_total 31587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63409
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.486689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63409
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 562
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 644
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 6000084
telemt_user_connections_current{user="hello"} 1781
telemt_user_octets_from_client{user="hello"} 103160954952 (96.08 GB)
telemt_user_octets_to_client{user="hello"} 1956422551508 (1.78 TB)
telemt_user_unique_ips_current{user="hello"} 802
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 95775.6 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6040843
telemt_connections_bad_total 576427
telemt_connections_current 1670
telemt_connections_me_current 1670
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 198703
telemt_upstream_connect_attempt_total 38537
telemt_upstream_connect_success_total 38199
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 38377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1791
telemt_me_reconnect_success_total 756
telemt_me_reader_eof_total 733
telemt_me_idle_close_by_peer_total 733
telemt_me_route_drop_no_conn_total 2136929
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4523322
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 734
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
telemt_me_writers_active_current 45
telemt_desync_total 21712
telemt_desync_full_logged_total 7291
telemt_desync_suppressed_total 14421
telemt_desync_frames_bucket_total{bucket="1_2"} 5243
telemt_desync_frames_bucket_total{bucket="3_10"} 8418
telemt_desync_frames_bucket_total{bucket="gt_10"} 8051
telemt_pool_swap_total 105
telemt_pool_force_close_total 3168
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30093
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28153
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26925
telemt_me_writer_teardown_success_total{mode="normal"} 30735
telemt_me_writer_teardown_noop_total 30099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.831800
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4475019
telemt_user_connections_current{user="hello"} 1670
telemt_user_octets_from_client{user="hello"} 137340620573 (127.91 GB)
telemt_user_octets_to_client{user="hello"} 2089257405255 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 95739.8 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5961969
telemt_connections_bad_total 538191
telemt_connections_current 1617
telemt_connections_me_current 1617
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 189570
telemt_upstream_connect_attempt_total 44948
telemt_upstream_connect_success_total 44641
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1800
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 2088545
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4454308
telemt_me_endpoint_quarantine_total 646
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 716
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21640
telemt_desync_full_logged_total 7171
telemt_desync_suppressed_total 14469
telemt_desync_frames_bucket_total{bucket="1_2"} 5314
telemt_desync_frames_bucket_total{bucket="3_10"} 8261
telemt_desync_frames_bucket_total{bucket="gt_10"} 8065
telemt_pool_swap_total 103
telemt_pool_force_close_total 3047
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 31492
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2658
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29570
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2832
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28445
telemt_me_writer_teardown_success_total{mode="normal"} 32228
telemt_me_writer_teardown_noop_total 31503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63731
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.301703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63731
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4455822
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 130446733779 (121.49 GB)
telemt_user_octets_to_client{user="hello"} 2040178308083 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 762
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 95779.0 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19829178
telemt_connections_bad_total 1427021
telemt_connections_current 2304
telemt_connections_me_current 2304
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 569000
telemt_upstream_connect_attempt_total 188185
telemt_upstream_connect_success_total 170610
telemt_upstream_connect_fail_total 16023
telemt_upstream_connect_attempts_per_request{bucket="1"} 186633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16023
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64265
telemt_me_reconnect_success_total 2125
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1318
telemt_me_route_drop_no_conn_total 39429341
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16180820
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 31092
telemt_desync_full_logged_total 9225
telemt_desync_suppressed_total 21867
telemt_desync_frames_bucket_total{bucket="1_2"} 6800
telemt_desync_frames_bucket_total{bucket="3_10"} 13766
telemt_desync_frames_bucket_total{bucket="gt_10"} 10526
telemt_pool_swap_total 98
telemt_pool_force_close_total 3261
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 744
telemt_me_draining_writers_reap_progress_total 29712
telemt_me_writer_removed_unexpected_total 1981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27310
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2745
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26451
telemt_me_writer_teardown_success_total{mode="normal"} 31426
telemt_me_writer_teardown_noop_total 29738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.342885
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 744
telemt_me_refill_failed_total 3787
telemt_me_writer_restored_same_endpoint_total 1467
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 16308786
telemt_user_connections_current{user="hello"} 2304
telemt_user_octets_from_client{user="hello"} 179072808384 (166.77 GB)
telemt_user_octets_to_client{user="hello"} 1085693341598 (1011.13 GB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 95746.4 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5763868
telemt_connections_bad_total 536611
telemt_connections_current 1702
telemt_connections_me_current 1702
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118668
telemt_upstream_connect_attempt_total 52989
telemt_upstream_connect_success_total 52378
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 52899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_reconnect_attempts_total 68041
telemt_me_reconnect_success_total 1670
telemt_me_reader_eof_total 1446
telemt_me_idle_close_by_peer_total 1446
telemt_me_route_drop_no_conn_total 2345897
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4496791
telemt_me_endpoint_quarantine_total 628
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 718
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 44
telemt_desync_total 22759
telemt_desync_full_logged_total 7938
telemt_desync_suppressed_total 14821
telemt_desync_frames_bucket_total{bucket="1_2"} 4318
telemt_desync_frames_bucket_total{bucket="3_10"} 8817
telemt_desync_frames_bucket_total{bucket="gt_10"} 9624
telemt_pool_swap_total 98
telemt_pool_force_close_total 2895
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 32794
telemt_me_writer_removed_unexpected_total 1493
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2494
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29899
telemt_me_writer_teardown_success_total{mode="normal"} 34309
telemt_me_writer_teardown_noop_total 32795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67104
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.866926
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67104
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 4116
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 4489906
telemt_user_connections_current{user="hello"} 1702
telemt_user_octets_from_client{user="hello"} 120536990872 (112.26 GB)
telemt_user_octets_to_client{user="hello"} 1827951127890 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 32582.2 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3637427
telemt_connections_bad_total 128212
telemt_connections_current 1281
telemt_connections_me_current 1281
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1526058
telemt_upstream_connect_attempt_total 21175
telemt_upstream_connect_success_total 21040
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 21168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_reconnect_attempts_total 45551
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 984615
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1746996
telemt_me_endpoint_quarantine_total 224
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 244
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9708
telemt_desync_full_logged_total 3290
telemt_desync_suppressed_total 6418
telemt_desync_frames_bucket_total{bucket="1_2"} 1718
telemt_desync_frames_bucket_total{bucket="3_10"} 3712
telemt_desync_frames_bucket_total{bucket="gt_10"} 4278
telemt_pool_swap_total 35
telemt_pool_force_close_total 1161
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 10749
telemt_me_writer_removed_unexpected_total 625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10153
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9588
telemt_me_writer_teardown_success_total{mode="normal"} 11392
telemt_me_writer_teardown_noop_total 10751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.991258
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 2596
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1750752
telemt_user_connections_current{user="hello"} 1281
telemt_user_octets_from_client{user="hello"} 51505703668 (47.97 GB)
telemt_user_octets_to_client{user="hello"} 750900368314 (699.33 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 13553.2 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147051
telemt_connections_bad_total 1365
telemt_connections_current 360
telemt_connections_me_current 360
telemt_handshake_timeouts_total 3500
telemt_upstream_connect_attempt_total 6065
telemt_upstream_connect_success_total 6048
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 79
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 41657
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128283
telemt_me_endpoint_quarantine_total 107
telemt_me_single_endpoint_shadow_rotate_total 120
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
telemt_me_writers_warm_current 18
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 14
telemt_pool_force_close_total 341
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5371
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5095
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 339
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5030
telemt_me_writer_teardown_success_total{mode="normal"} 5451
telemt_me_writer_teardown_noop_total 5371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10822
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.654855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10822
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 128097
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 2428082000 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 77443677672 (72.13 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 95750.7 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6905484
telemt_connections_bad_total 702590
telemt_connections_current 1969
telemt_connections_me_current 1969
telemt_handshake_timeouts_total 196044
telemt_upstream_connect_attempt_total 36419
telemt_upstream_connect_success_total 36274
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 36382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1476
telemt_me_reconnect_success_total 762
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 2082894
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5250162
telemt_me_endpoint_quarantine_total 647
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 734
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
telemt_me_writers_active_current 45
telemt_desync_total 20216
telemt_desync_full_logged_total 6753
telemt_desync_suppressed_total 13463
telemt_desync_frames_bucket_total{bucket="1_2"} 4919
telemt_desync_frames_bucket_total{bucket="3_10"} 7345
telemt_desync_frames_bucket_total{bucket="gt_10"} 7952
telemt_pool_swap_total 106
telemt_pool_force_close_total 2899
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 32750
telemt_me_writer_removed_unexpected_total 717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2666
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30815
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29851
telemt_me_writer_teardown_success_total{mode="normal"} 33481
telemt_me_writer_teardown_noop_total 32752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.500574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 5225455
telemt_user_connections_current{user="hello"} 1969
telemt_user_octets_from_client{user="hello"} 104929063432 (97.72 GB)
telemt_user_octets_to_client{user="hello"} 2455617850780 (2.23 TB)
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 95747.4 (26h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5925274
telemt_connections_bad_total 573576
telemt_connections_current 1772
telemt_connections_me_current 1772
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 165682
telemt_upstream_connect_attempt_total 52526
telemt_upstream_connect_success_total 52128
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 52467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_reconnect_attempts_total 5270
telemt_me_reconnect_success_total 1061
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 937
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2135427
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4619391
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 727
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 18933
telemt_desync_full_logged_total 6384
telemt_desync_suppressed_total 12549
telemt_desync_frames_bucket_total{bucket="1_2"} 4710
telemt_desync_frames_bucket_total{bucket="3_10"} 6899
telemt_desync_frames_bucket_total{bucket="gt_10"} 7324
telemt_pool_swap_total 104
telemt_pool_force_close_total 2856
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 31676
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29526
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28820
telemt_me_writer_teardown_success_total{mode="normal"} 32669
telemt_me_writer_teardown_noop_total 31680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64349
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.573494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64349
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4622760
telemt_user_connections_current{user="hello"} 1772
telemt_user_octets_from_client{user="hello"} 88093470345 (82.04 GB)
telemt_user_octets_to_client{user="hello"} 1989060059788 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 752
telemt_user_unique_ips_recent_window{user="hello"} 171
```