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

# Server Metrics 2026-03-21 23:22:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 8159.5 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134846
telemt_connections_bad_total 10579
telemt_connections_current 704
telemt_connections_me_current 704
telemt_handshake_timeouts_total 6534
telemt_upstream_connect_attempt_total 3222
telemt_upstream_connect_success_total 3221
telemt_upstream_connect_attempts_per_request{bucket="1"} 3221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 83
telemt_me_reconnect_success_total 49
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 28222
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109501
telemt_me_endpoint_quarantine_total 52
telemt_me_single_endpoint_shadow_rotate_total 71
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 25
telemt_desync_total 649
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 8
telemt_pool_force_close_total 211
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 2823
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2670
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2612
telemt_me_writer_teardown_success_total{mode="normal"} 2870
telemt_me_writer_teardown_noop_total 2823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.542573
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 109401
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 1310669308 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 41658492928 (38.80 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 21525.6 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646206
telemt_connections_bad_total 31226
telemt_connections_current 725
telemt_connections_me_current 725
telemt_handshake_timeouts_total 24747
telemt_upstream_connect_attempt_total 8958
telemt_upstream_connect_success_total 8801
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 8941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 772
telemt_me_reconnect_success_total 268
telemt_me_reader_eof_total 229
telemt_me_idle_close_by_peer_total 229
telemt_me_route_drop_no_conn_total 321541
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526319
telemt_me_endpoint_quarantine_total 182
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2332
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 999
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 878
telemt_desync_frames_bucket_total{bucket="gt_10"} 961
telemt_pool_swap_total 23
telemt_pool_force_close_total 654
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 7890
telemt_me_writer_removed_unexpected_total 216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7422
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 647
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7236
telemt_me_writer_teardown_success_total{mode="normal"} 8106
telemt_me_writer_teardown_noop_total 7890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15996
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.341167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15996
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 525608
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 8882986032 (8.27 GB)
telemt_user_octets_to_client{user="hello"} 182274677704 (169.76 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 96385.4 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7366845
telemt_connections_bad_total 568734
telemt_connections_current 2079
telemt_connections_me_current 2079
telemt_handshake_timeouts_total 237747
telemt_upstream_connect_attempt_total 34857
telemt_upstream_connect_success_total 34788
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1475
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 737
telemt_me_idle_close_by_peer_total 737
telemt_me_route_drop_no_conn_total 4487598
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6022952
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 713
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 38
telemt_desync_total 25534
telemt_desync_full_logged_total 8433
telemt_desync_suppressed_total 17101
telemt_desync_frames_bucket_total{bucket="1_2"} 5477
telemt_desync_frames_bucket_total{bucket="3_10"} 9973
telemt_desync_frames_bucket_total{bucket="gt_10"} 10084
telemt_pool_swap_total 103
telemt_pool_force_close_total 3477
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 562
telemt_me_draining_writers_reap_progress_total 31725
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2691
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29320
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28248
telemt_me_writer_teardown_success_total{mode="normal"} 32011
telemt_me_writer_teardown_noop_total 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.491955
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 562
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 650
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 6015540
telemt_user_connections_current{user="hello"} 2079
telemt_user_octets_from_client{user="hello"} 103404284736 (96.30 GB)
telemt_user_octets_to_client{user="hello"} 1966259724504 (1.79 TB)
telemt_user_unique_ips_current{user="hello"} 990
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 96386.7 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6058577
telemt_connections_bad_total 576666
telemt_connections_current 1588
telemt_connections_me_current 1588
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 199749
telemt_upstream_connect_attempt_total 38779
telemt_upstream_connect_success_total 38441
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 38619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1795
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 737
telemt_me_idle_close_by_peer_total 737
telemt_me_route_drop_no_conn_total 2147682
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4538545
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 40
telemt_desync_total 21813
telemt_desync_full_logged_total 7338
telemt_desync_suppressed_total 14475
telemt_desync_frames_bucket_total{bucket="1_2"} 5255
telemt_desync_frames_bucket_total{bucket="3_10"} 8469
telemt_desync_frames_bucket_total{bucket="gt_10"} 8089
telemt_pool_swap_total 105
telemt_pool_force_close_total 3168
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30268
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2587
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27100
telemt_me_writer_teardown_success_total{mode="normal"} 30914
telemt_me_writer_teardown_noop_total 30274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.834582
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 656
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4486340
telemt_user_connections_current{user="hello"} 1588
telemt_user_octets_from_client{user="hello"} 137476808909 (128.04 GB)
telemt_user_octets_to_client{user="hello"} 2096520711083 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 745
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 96350.7 (26h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5978688
telemt_connections_bad_total 538637
telemt_connections_current 1649
telemt_connections_me_current 1649
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 190391
telemt_upstream_connect_attempt_total 45188
telemt_upstream_connect_success_total 44880
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1800
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 2091954
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4465989
telemt_me_endpoint_quarantine_total 646
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 718
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_warm_current 18
telemt_desync_total 21711
telemt_desync_full_logged_total 7204
telemt_desync_suppressed_total 14507
telemt_desync_frames_bucket_total{bucket="1_2"} 5324
telemt_desync_frames_bucket_total{bucket="3_10"} 8297
telemt_desync_frames_bucket_total{bucket="gt_10"} 8090
telemt_pool_swap_total 103
telemt_pool_force_close_total 3047
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 31709
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29782
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2832
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28662
telemt_me_writer_teardown_success_total{mode="normal"} 32445
telemt_me_writer_teardown_noop_total 31720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.303964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4467502
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 130657258183 (121.68 GB)
telemt_user_octets_to_client{user="hello"} 2046768440379 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 801
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 96390.0 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19861362
telemt_connections_bad_total 1437352
telemt_connections_current 2406
telemt_connections_me_current 2406
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 571453
telemt_upstream_connect_attempt_total 188402
telemt_upstream_connect_success_total 170819
telemt_upstream_connect_fail_total 16024
telemt_upstream_connect_attempts_per_request{bucket="1"} 186843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8880
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16024
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64269
telemt_me_reconnect_success_total 2129
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1322
telemt_me_route_drop_no_conn_total 39433910
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16199136
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 751
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 37
telemt_desync_total 31143
telemt_desync_full_logged_total 9243
telemt_desync_suppressed_total 21900
telemt_desync_frames_bucket_total{bucket="1_2"} 6807
telemt_desync_frames_bucket_total{bucket="3_10"} 13793
telemt_desync_frames_bucket_total{bucket="gt_10"} 10543
telemt_pool_swap_total 98
telemt_pool_force_close_total 3261
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 744
telemt_me_draining_writers_reap_progress_total 29857
telemt_me_writer_removed_unexpected_total 1985
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27451
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2745
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26596
telemt_me_writer_teardown_success_total{mode="normal"} 31575
telemt_me_writer_teardown_noop_total 29883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.347674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 744
telemt_me_refill_failed_total 3787
telemt_me_writer_restored_same_endpoint_total 1471
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 16327127
telemt_user_connections_current{user="hello"} 2406
telemt_user_octets_from_client{user="hello"} 180521488780 (168.12 GB)
telemt_user_octets_to_client{user="hello"} 1092470729978 (1017.44 GB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1075
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 96357.4 (26h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5776927
telemt_connections_bad_total 537195
telemt_connections_current 1677
telemt_connections_me_current 1677
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118948
telemt_upstream_connect_attempt_total 53239
telemt_upstream_connect_success_total 52627
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 53148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_reconnect_attempts_total 68047
telemt_me_reconnect_success_total 1675
telemt_me_reader_eof_total 1451
telemt_me_idle_close_by_peer_total 1450
telemt_me_route_drop_no_conn_total 2348450
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4507815
telemt_me_endpoint_quarantine_total 628
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 719
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22801
telemt_desync_full_logged_total 7958
telemt_desync_suppressed_total 14843
telemt_desync_frames_bucket_total{bucket="1_2"} 4327
telemt_desync_frames_bucket_total{bucket="3_10"} 8829
telemt_desync_frames_bucket_total{bucket="gt_10"} 9645
telemt_pool_swap_total 98
telemt_pool_force_close_total 2895
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 33002
telemt_me_writer_removed_unexpected_total 1498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2494
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30107
telemt_me_writer_teardown_success_total{mode="normal"} 34522
telemt_me_writer_teardown_noop_total 33003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.868574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 4116
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 4500941
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 120979751620 (112.67 GB)
telemt_user_octets_to_client{user="hello"} 1834411706026 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 813
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 33193.2 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3650447
telemt_connections_bad_total 129327
telemt_connections_current 1364
telemt_connections_me_current 1364
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1528741
telemt_upstream_connect_attempt_total 21390
telemt_upstream_connect_success_total 21255
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 21383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_reconnect_attempts_total 45557
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 548
telemt_me_idle_close_by_peer_total 548
telemt_me_route_drop_no_conn_total 986907
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1755867
telemt_me_endpoint_quarantine_total 224
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 246
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9781
telemt_desync_full_logged_total 3327
telemt_desync_suppressed_total 6454
telemt_desync_frames_bucket_total{bucket="1_2"} 1727
telemt_desync_frames_bucket_total{bucket="3_10"} 3738
telemt_desync_frames_bucket_total{bucket="gt_10"} 4316
telemt_pool_swap_total 35
telemt_pool_force_close_total 1181
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 10957
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1249
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10356
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 975
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9776
telemt_me_writer_teardown_success_total{mode="normal"} 11605
telemt_me_writer_teardown_noop_total 10959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22564
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.992199
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22564
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 2596
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1759622
telemt_user_connections_current{user="hello"} 1364
telemt_user_octets_from_client{user="hello"} 51607734828 (48.06 GB)
telemt_user_octets_to_client{user="hello"} 755360671454 (703.48 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 14164.4 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149766
telemt_connections_bad_total 1367
telemt_connections_current 321
telemt_connections_me_current 321
telemt_handshake_timeouts_total 3516
telemt_upstream_connect_attempt_total 6362
telemt_upstream_connect_success_total 6345
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 79
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 42581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130911
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_shadow_rotate_total 125
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
telemt_desync_total 947
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 15
telemt_pool_force_close_total 361
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5670
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 377
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 359
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5309
telemt_me_writer_teardown_success_total{mode="normal"} 5750
telemt_me_writer_teardown_noop_total 5670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.727941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 130720
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 2444393604 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 78099498208 (72.74 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 96362.0 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6932680
telemt_connections_bad_total 706080
telemt_connections_current 1812
telemt_connections_me_current 1812
telemt_handshake_timeouts_total 196973
telemt_upstream_connect_attempt_total 36674
telemt_upstream_connect_success_total 36529
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 36637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1481
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 745
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 2086917
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5263331
telemt_me_endpoint_quarantine_total 647
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 23
telemt_desync_total 20258
telemt_desync_full_logged_total 6769
telemt_desync_suppressed_total 13489
telemt_desync_frames_bucket_total{bucket="1_2"} 4930
telemt_desync_frames_bucket_total{bucket="3_10"} 7359
telemt_desync_frames_bucket_total{bucket="gt_10"} 7969
telemt_pool_swap_total 106
telemt_pool_force_close_total 2899
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 32957
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31017
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30058
telemt_me_writer_teardown_success_total{mode="normal"} 33692
telemt_me_writer_teardown_noop_total 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.502187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 5238623
telemt_user_connections_current{user="hello"} 1812
telemt_user_octets_from_client{user="hello"} 105175587644 (97.95 GB)
telemt_user_octets_to_client{user="hello"} 2461403621556 (2.24 TB)
telemt_user_unique_ips_current{user="hello"} 836
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 96358.4 (26h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5945262
telemt_connections_bad_total 578287
telemt_connections_current 1880
telemt_connections_me_current 1880
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 166033
telemt_upstream_connect_attempt_total 52736
telemt_upstream_connect_success_total 52337
telemt_upstream_connect_fail_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 52677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 340
telemt_me_reconnect_attempts_total 5274
telemt_me_reconnect_success_total 1065
telemt_me_reader_eof_total 941
telemt_me_idle_close_by_peer_total 941
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2139264
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4632378
telemt_me_endpoint_quarantine_total 752
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 730
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 18
telemt_desync_total 18971
telemt_desync_full_logged_total 6402
telemt_desync_suppressed_total 12569
telemt_desync_frames_bucket_total{bucket="1_2"} 4719
telemt_desync_frames_bucket_total{bucket="3_10"} 6915
telemt_desync_frames_bucket_total{bucket="gt_10"} 7337
telemt_pool_swap_total 104
telemt_pool_force_close_total 2856
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 31838
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29687
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28982
telemt_me_writer_teardown_success_total{mode="normal"} 32835
telemt_me_writer_teardown_noop_total 31842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.575154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4635744
telemt_user_connections_current{user="hello"} 1880
telemt_user_octets_from_client{user="hello"} 88254711949 (82.19 GB)
telemt_user_octets_to_client{user="hello"} 1994088297320 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 803
telemt_user_unique_ips_recent_window{user="hello"} 159
```