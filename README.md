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

# Server Metrics 2026-03-22 20:30:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 84246.0 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3120267
telemt_connections_bad_total 215830
telemt_connections_current 1120
telemt_connections_me_current 1120
telemt_handshake_timeouts_total 99701
telemt_upstream_connect_attempt_total 30863
telemt_upstream_connect_success_total 30862
telemt_upstream_connect_attempts_per_request{bucket="1"} 30862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 83
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1238
telemt_me_reconnect_success_total 519
telemt_me_reader_eof_total 527
telemt_me_idle_close_by_peer_total 527
telemt_me_route_drop_no_conn_total 2797403
telemt_me_route_drop_channel_closed_total 1113
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2638335
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 652
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 42
telemt_desync_total 11317
telemt_desync_full_logged_total 3570
telemt_desync_suppressed_total 7747
telemt_desync_frames_bucket_total{bucket="1_2"} 3046
telemt_desync_frames_bucket_total{bucket="3_10"} 4168
telemt_desync_frames_bucket_total{bucket="gt_10"} 4103
telemt_pool_swap_total 93
telemt_pool_force_close_total 2907
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 597
telemt_me_draining_writers_reap_progress_total 28229
telemt_me_writer_removed_unexpected_total 511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25322
telemt_me_writer_teardown_success_total{mode="normal"} 28444
telemt_me_writer_teardown_noop_total 28240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 325.551116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 597
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2629665
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 38521358196 (35.88 GB)
telemt_user_octets_to_client{user="hello"} 696428933636 (648.60 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 97612.2 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3857802
telemt_connections_bad_total 341035
telemt_connections_current 472
telemt_connections_me_current 472
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98389
telemt_upstream_connect_attempt_total 59035
telemt_upstream_connect_success_total 58311
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 58951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6844
telemt_me_reconnect_success_total 2671
telemt_me_reader_eof_total 2620
telemt_me_idle_close_by_peer_total 2620
telemt_me_route_drop_no_conn_total 3613210
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3074223
telemt_me_endpoint_quarantine_total 749
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 752
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 12358
telemt_desync_full_logged_total 6911
telemt_desync_suppressed_total 5447
telemt_desync_frames_bucket_total{bucket="1_2"} 2814
telemt_desync_frames_bucket_total{bucket="3_10"} 4841
telemt_desync_frames_bucket_total{bucket="gt_10"} 4703
telemt_pool_swap_total 91
telemt_pool_force_close_total 2772
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 38931
telemt_me_writer_removed_unexpected_total 2563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36729
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36159
telemt_me_writer_teardown_success_total{mode="normal"} 41514
telemt_me_writer_teardown_noop_total 38932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.261419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 3084957
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 40510378811 (37.73 GB)
telemt_user_octets_to_client{user="hello"} 741643722270 (690.71 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 172472.0 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16005451
telemt_connections_bad_total 1551574
telemt_connections_current 1756
telemt_connections_me_current 1756
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393403
telemt_upstream_connect_attempt_total 76538
telemt_upstream_connect_success_total 76440
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2813
telemt_me_reconnect_success_total 1449
telemt_me_reader_eof_total 1392
telemt_me_idle_close_by_peer_total 1390
telemt_me_route_drop_no_conn_total 13990928
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12753939
telemt_me_endpoint_quarantine_total 1092
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1284
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 52658
telemt_desync_full_logged_total 16585
telemt_desync_suppressed_total 36073
telemt_desync_frames_bucket_total{bucket="1_2"} 11732
telemt_desync_frames_bucket_total{bucket="3_10"} 20497
telemt_desync_frames_bucket_total{bucket="gt_10"} 20429
telemt_pool_swap_total 186
telemt_pool_force_close_total 6280
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1019
telemt_me_draining_writers_reap_progress_total 56653
telemt_me_writer_removed_unexpected_total 1344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5810
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50373
telemt_me_writer_teardown_success_total{mode="normal"} 57274
telemt_me_writer_teardown_noop_total 56704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.744007
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1019
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1251
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12754376
telemt_user_connections_current{user="hello"} 1756
telemt_user_octets_from_client{user="hello"} 186829722213 (174.00 GB)
telemt_user_octets_to_client{user="hello"} 3402804995963 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 172473.4 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11584013
telemt_connections_bad_total 1161921
telemt_connections_current 1353
telemt_connections_me_current 1353
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343261
telemt_upstream_connect_attempt_total 89062
telemt_upstream_connect_success_total 87793
telemt_upstream_connect_fail_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 88643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 850
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4164
telemt_me_reconnect_success_total 1744
telemt_me_reader_eof_total 1610
telemt_me_idle_close_by_peer_total 1610
telemt_me_route_drop_no_conn_total 4509940
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8630243
telemt_me_endpoint_quarantine_total 1090
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38282
telemt_desync_full_logged_total 12873
telemt_desync_suppressed_total 25409
telemt_desync_frames_bucket_total{bucket="1_2"} 9442
telemt_desync_frames_bucket_total{bucket="3_10"} 14728
telemt_desync_frames_bucket_total{bucket="gt_10"} 14112
telemt_pool_swap_total 183
telemt_pool_force_close_total 5670
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 55043
telemt_me_writer_removed_unexpected_total 1648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5082
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49373
telemt_me_writer_teardown_success_total{mode="normal"} 56538
telemt_me_writer_teardown_noop_total 55068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.757316
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8568319
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 215519476229 (200.72 GB)
telemt_user_octets_to_client{user="hello"} 3872759031246 (3.52 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 172454.3 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10860936
telemt_connections_bad_total 941088
telemt_connections_current 983
telemt_connections_me_current 983
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344231
telemt_upstream_connect_attempt_total 74253
telemt_upstream_connect_success_total 73063
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 73250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 5105
telemt_me_reconnect_success_total 2051
telemt_me_reader_eof_total 1789
telemt_me_idle_close_by_peer_total 1788
telemt_me_route_drop_no_conn_total 5284236
telemt_me_route_drop_channel_closed_total 378
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8216059
telemt_me_endpoint_quarantine_total 1175
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1263
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_me_writers_active_current 43
telemt_desync_total 37601
telemt_desync_full_logged_total 12447
telemt_desync_suppressed_total 25154
telemt_desync_frames_bucket_total{bucket="1_2"} 9509
telemt_desync_frames_bucket_total{bucket="3_10"} 14370
telemt_desync_frames_bucket_total{bucket="gt_10"} 13722
telemt_pool_swap_total 181
telemt_pool_force_close_total 5609
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 55178
telemt_me_writer_removed_unexpected_total 1932
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51465
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49569
telemt_me_writer_teardown_success_total{mode="normal"} 57030
telemt_me_writer_teardown_noop_total 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112279
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.020028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112279
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1759
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8208175
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 191251740733 (178.12 GB)
telemt_user_octets_to_client{user="hello"} 3415920132861 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 42717.6 (11h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10879809
telemt_connections_bad_total 660226
telemt_connections_current 1714
telemt_connections_me_current 1714
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 237174
telemt_upstream_connect_attempt_total 45925
telemt_upstream_connect_success_total 43635
telemt_upstream_connect_fail_total 1563
telemt_upstream_connect_attempts_per_request{bucket="1"} 45198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1563
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6635
telemt_me_reconnect_success_total 933
telemt_me_reader_eof_total 589
telemt_me_idle_close_by_peer_total 589
telemt_me_route_drop_no_conn_total 25216841
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9037389
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 118
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 118
telemt_me_single_endpoint_shadow_rotate_total 335
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 14824
telemt_desync_full_logged_total 3920
telemt_desync_suppressed_total 10904
telemt_desync_frames_bucket_total{bucket="1_2"} 2784
telemt_desync_frames_bucket_total{bucket="3_10"} 6008
telemt_desync_frames_bucket_total{bucket="gt_10"} 6032
telemt_pool_swap_total 43
telemt_pool_force_close_total 1563
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 12278
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11238
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10715
telemt_me_writer_teardown_success_total{mode="normal"} 13060
telemt_me_writer_teardown_noop_total 12297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25357
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.898563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25357
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 315
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 9059453
telemt_user_connections_current{user="hello"} 1714
telemt_user_octets_from_client{user="hello"} 83416518891 (77.69 GB)
telemt_user_octets_to_client{user="hello"} 512222250771 (477.04 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 172444.2 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10748753
telemt_connections_bad_total 908329
telemt_connections_current 1455
telemt_connections_me_current 1455
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236687
telemt_upstream_connect_attempt_total 103661
telemt_upstream_connect_success_total 102573
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 103502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72414
telemt_me_reconnect_success_total 2837
telemt_me_reader_eof_total 2528
telemt_me_idle_close_by_peer_total 2526
telemt_me_route_drop_no_conn_total 5209227
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8490809
telemt_me_endpoint_quarantine_total 1139
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1290
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45213
telemt_desync_full_logged_total 15408
telemt_desync_suppressed_total 29805
telemt_desync_frames_bucket_total{bucket="1_2"} 9153
telemt_desync_frames_bucket_total{bucket="3_10"} 17330
telemt_desync_frames_bucket_total{bucket="gt_10"} 18730
telemt_pool_swap_total 176
telemt_pool_force_close_total 5255
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 59148
telemt_me_writer_removed_unexpected_total 2566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6270
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55470
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53893
telemt_me_writer_teardown_success_total{mode="normal"} 61740
telemt_me_writer_teardown_noop_total 59149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.063177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 4286
telemt_me_writer_restored_same_endpoint_total 2386
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 8494044
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 192146315465 (178.95 GB)
telemt_user_octets_to_client{user="hello"} 3231561699668 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 590
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 109280.3 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11345002
telemt_connections_bad_total 454920
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4658696
telemt_upstream_connect_attempt_total 51754
telemt_upstream_connect_success_total 51365
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 51744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_reconnect_attempts_total 48589
telemt_me_reconnect_success_total 1681
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1338
telemt_me_route_drop_no_conn_total 4046386
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5468511
telemt_me_endpoint_quarantine_total 707
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 825
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30745
telemt_desync_full_logged_total 10432
telemt_desync_suppressed_total 20313
telemt_desync_frames_bucket_total{bucket="1_2"} 6121
telemt_desync_frames_bucket_total{bucket="3_10"} 12165
telemt_desync_frames_bucket_total{bucket="gt_10"} 12459
telemt_pool_swap_total 115
telemt_pool_force_close_total 3510
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 38090
telemt_me_writer_removed_unexpected_total 1399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36163
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34580
telemt_me_writer_teardown_success_total{mode="normal"} 39523
telemt_me_writer_teardown_noop_total 38097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.529095
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 2726
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5461284
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 117439766076 (109.37 GB)
telemt_user_octets_to_client{user="hello"} 2093902578490 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 90251.0 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1365108
telemt_connections_bad_total 31692
telemt_connections_current 1055
telemt_connections_me_current 1055
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25432
telemt_upstream_connect_attempt_total 42634
telemt_upstream_connect_success_total 42503
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 42607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2018
telemt_me_reconnect_success_total 822
telemt_me_reader_eof_total 801
telemt_me_idle_close_by_peer_total 801
telemt_me_route_drop_no_conn_total 477408
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1211921
telemt_me_endpoint_quarantine_total 746
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 743
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 42
telemt_desync_total 7290
telemt_desync_full_logged_total 2265
telemt_desync_suppressed_total 5025
telemt_desync_frames_bucket_total{bucket="1_2"} 1599
telemt_desync_frames_bucket_total{bucket="3_10"} 2857
telemt_desync_frames_bucket_total{bucket="gt_10"} 2834
telemt_pool_swap_total 97
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 35543
telemt_me_writer_removed_unexpected_total 773
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2809
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33021
telemt_me_writer_teardown_success_total{mode="normal"} 36347
telemt_me_writer_teardown_noop_total 35547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.538294
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 696
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 1207971
telemt_user_connections_current{user="hello"} 1055
telemt_user_octets_from_client{user="hello"} 23216324177 (21.62 GB)
telemt_user_octets_to_client{user="hello"} 511486769943 (476.36 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 172448.6 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13065302
telemt_connections_bad_total 1528540
telemt_connections_current 1454
telemt_connections_me_current 1454
telemt_handshake_timeouts_total 374718
telemt_upstream_connect_attempt_total 65252
telemt_upstream_connect_success_total 64920
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2561
telemt_me_reconnect_success_total 1337
telemt_me_reader_eof_total 1304
telemt_me_idle_close_by_peer_total 1304
telemt_me_route_drop_no_conn_total 4428086
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9886704
telemt_me_endpoint_quarantine_total 1162
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 40976
telemt_desync_full_logged_total 13360
telemt_desync_suppressed_total 27616
telemt_desync_frames_bucket_total{bucket="1_2"} 9786
telemt_desync_frames_bucket_total{bucket="3_10"} 15116
telemt_desync_frames_bucket_total{bucket="gt_10"} 16074
telemt_pool_swap_total 191
telemt_pool_force_close_total 5248
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 58798
telemt_me_writer_removed_unexpected_total 1255
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55302
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5074
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53550
telemt_me_writer_teardown_success_total{mode="normal"} 60092
telemt_me_writer_teardown_noop_total 58800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118892
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.470627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118892
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1170
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9854339
telemt_user_connections_current{user="hello"} 1454
telemt_user_octets_from_client{user="hello"} 192455496228 (179.24 GB)
telemt_user_octets_to_client{user="hello"} 4355773112860 (3.96 TB)
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 172445.3 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11367138
telemt_connections_bad_total 1287755
telemt_connections_current 1261
telemt_connections_me_current 1261
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 299231
telemt_upstream_connect_attempt_total 91723
telemt_upstream_connect_success_total 90894
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 91516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9861
telemt_me_reconnect_success_total 2374
telemt_me_reader_eof_total 2215
telemt_me_idle_close_by_peer_total 2214
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5603841
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8789794
telemt_me_endpoint_quarantine_total 1322
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 46
telemt_desync_total 40221
telemt_desync_full_logged_total 12995
telemt_desync_suppressed_total 27226
telemt_desync_frames_bucket_total{bucket="1_2"} 10039
telemt_desync_frames_bucket_total{bucket="3_10"} 14938
telemt_desync_frames_bucket_total{bucket="gt_10"} 15244
telemt_pool_swap_total 181
telemt_pool_force_close_total 5046
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 58592
telemt_me_writer_removed_unexpected_total 2247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54774
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53546
telemt_me_writer_teardown_success_total{mode="normal"} 60915
telemt_me_writer_teardown_noop_total 58597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.187710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 386
telemt_me_writer_restored_same_endpoint_total 1932
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 8795316
telemt_user_connections_current{user="hello"} 1261
telemt_user_octets_from_client{user="hello"} 155650241225 (144.96 GB)
telemt_user_octets_to_client{user="hello"} 3406675353027 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 157
```