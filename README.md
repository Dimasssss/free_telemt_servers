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

# Server Metrics 2026-03-22 19:03:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 79025.3 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2924787
telemt_connections_bad_total 185885
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_handshake_timeouts_total 97382
telemt_upstream_connect_attempt_total 28859
telemt_upstream_connect_success_total 28858
telemt_upstream_connect_attempts_per_request{bucket="1"} 28858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1173
telemt_me_reconnect_success_total 489
telemt_me_reader_eof_total 492
telemt_me_idle_close_by_peer_total 492
telemt_me_route_drop_no_conn_total 2542451
telemt_me_route_drop_channel_closed_total 1026
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2480150
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 529
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 613
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 10910
telemt_desync_full_logged_total 3464
telemt_desync_suppressed_total 7446
telemt_desync_frames_bucket_total{bucket="1_2"} 2927
telemt_desync_frames_bucket_total{bucket="3_10"} 4050
telemt_desync_frames_bucket_total{bucket="gt_10"} 3933
telemt_pool_swap_total 87
telemt_pool_force_close_total 2709
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 26391
telemt_me_writer_removed_unexpected_total 478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24695
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2656
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23682
telemt_me_writer_teardown_success_total{mode="normal"} 26611
telemt_me_writer_teardown_noop_total 26401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 283.894017
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2475431
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 35785888692 (33.33 GB)
telemt_user_octets_to_client{user="hello"} 650323399956 (605.66 GB)
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 92391.1 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3782323
telemt_connections_bad_total 338736
telemt_connections_current 882
telemt_connections_me_current 882
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 96686
telemt_upstream_connect_attempt_total 56272
telemt_upstream_connect_success_total 55583
telemt_upstream_connect_fail_total 607
telemt_upstream_connect_attempts_per_request{bucket="1"} 56190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 607
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6386
telemt_me_reconnect_success_total 2343
telemt_me_reader_eof_total 2277
telemt_me_idle_close_by_peer_total 2277
telemt_me_route_drop_no_conn_total 3589573
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3006571
telemt_me_endpoint_quarantine_total 720
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 714
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 11969
telemt_desync_full_logged_total 6696
telemt_desync_suppressed_total 5273
telemt_desync_frames_bucket_total{bucket="1_2"} 2756
telemt_desync_frames_bucket_total{bucket="3_10"} 4681
telemt_desync_frames_bucket_total{bucket="gt_10"} 4532
telemt_pool_swap_total 87
telemt_pool_force_close_total 2630
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 36694
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34600
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2241
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34064
telemt_me_writer_teardown_success_total{mode="normal"} 38933
telemt_me_writer_teardown_noop_total 36694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.854871
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3017381
telemt_user_connections_current{user="hello"} 882
telemt_user_octets_from_client{user="hello"} 39110900991 (36.42 GB)
telemt_user_octets_to_client{user="hello"} 706322058150 (657.81 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 167251.1 (46h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15806729
telemt_connections_bad_total 1523493
telemt_connections_current 2232
telemt_connections_me_current 2232
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 390258
telemt_upstream_connect_attempt_total 74605
telemt_upstream_connect_success_total 74508
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2768
telemt_me_reconnect_success_total 1423
telemt_me_reader_eof_total 1364
telemt_me_idle_close_by_peer_total 1362
telemt_me_route_drop_no_conn_total 13933491
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12594906
telemt_me_endpoint_quarantine_total 1055
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1246
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 51993
telemt_desync_full_logged_total 16340
telemt_desync_suppressed_total 35653
telemt_desync_frames_bucket_total{bucket="1_2"} 11602
telemt_desync_frames_bucket_total{bucket="3_10"} 20250
telemt_desync_frames_bucket_total{bucket="gt_10"} 20141
telemt_pool_swap_total 180
telemt_pool_force_close_total 6089
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 988
telemt_me_draining_writers_reap_progress_total 54886
telemt_me_writer_removed_unexpected_total 1316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4810
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50685
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5621
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48797
telemt_me_writer_teardown_success_total{mode="normal"} 55495
telemt_me_writer_teardown_noop_total 54936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 308.065032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 988
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1227
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12595524
telemt_user_connections_current{user="hello"} 2232
telemt_user_octets_from_client{user="hello"} 183534343237 (170.93 GB)
telemt_user_octets_to_client{user="hello"} 3316168399943 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 167252.6 (46h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11410272
telemt_connections_bad_total 1128267
telemt_connections_current 1624
telemt_connections_me_current 1624
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 340051
telemt_upstream_connect_attempt_total 87107
telemt_upstream_connect_success_total 85890
telemt_upstream_connect_fail_total 842
telemt_upstream_connect_attempts_per_request{bucket="1"} 86732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3706
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 842
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4100
telemt_me_reconnect_success_total 1695
telemt_me_reader_eof_total 1563
telemt_me_idle_close_by_peer_total 1563
telemt_me_route_drop_no_conn_total 4461872
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8502975
telemt_me_endpoint_quarantine_total 1057
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1266
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
telemt_me_writers_active_current 44
telemt_desync_total 37703
telemt_desync_full_logged_total 12709
telemt_desync_suppressed_total 24994
telemt_desync_frames_bucket_total{bucket="1_2"} 9296
telemt_desync_frames_bucket_total{bucket="3_10"} 14525
telemt_desync_frames_bucket_total{bucket="gt_10"} 13882
telemt_pool_swap_total 177
telemt_pool_force_close_total 5498
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 696
telemt_me_draining_writers_reap_progress_total 53364
telemt_me_writer_removed_unexpected_total 1602
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4925
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49885
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47866
telemt_me_writer_teardown_success_total{mode="normal"} 54810
telemt_me_writer_teardown_noop_total 53387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.194692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 696
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1451
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8441335
telemt_user_connections_current{user="hello"} 1624
telemt_user_octets_from_client{user="hello"} 210987399337 (196.50 GB)
telemt_user_octets_to_client{user="hello"} 3806623491362 (3.46 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 167216.4 (46h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10732723
telemt_connections_bad_total 924410
telemt_connections_current 1320
telemt_connections_me_current 1320
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342768
telemt_upstream_connect_attempt_total 72178
telemt_upstream_connect_success_total 71117
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4905
telemt_me_reconnect_success_total 1983
telemt_me_reader_eof_total 1732
telemt_me_idle_close_by_peer_total 1731
telemt_me_route_drop_no_conn_total 5231778
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8111592
telemt_me_endpoint_quarantine_total 1140
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1228
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 59
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
telemt_desync_total 37263
telemt_desync_full_logged_total 12323
telemt_desync_suppressed_total 24940
telemt_desync_frames_bucket_total{bucket="1_2"} 9427
telemt_desync_frames_bucket_total{bucket="3_10"} 14268
telemt_desync_frames_bucket_total{bucket="gt_10"} 13568
telemt_pool_swap_total 175
telemt_pool_force_close_total 5436
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 703
telemt_me_draining_writers_reap_progress_total 53510
telemt_me_writer_removed_unexpected_total 1873
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5371
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49929
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 546
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48074
telemt_me_writer_teardown_success_total{mode="normal"} 55300
telemt_me_writer_teardown_noop_total 53581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.643428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 703
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8104034
telemt_user_connections_current{user="hello"} 1320
telemt_user_octets_from_client{user="hello"} 187881377277 (174.98 GB)
telemt_user_octets_to_client{user="hello"} 3374156862897 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37511.4 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10662064
telemt_connections_bad_total 651356
telemt_connections_current 2142
telemt_connections_me_current 2142
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 223030
telemt_upstream_connect_attempt_total 44017
telemt_upstream_connect_success_total 41797
telemt_upstream_connect_fail_total 1538
telemt_upstream_connect_attempts_per_request{bucket="1"} 43335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5951
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1538
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6392
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 25143128
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8854601
telemt_me_endpoint_quarantine_total 235
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 295
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 14250
telemt_desync_full_logged_total 3724
telemt_desync_suppressed_total 10526
telemt_desync_frames_bucket_total{bucket="1_2"} 2636
telemt_desync_frames_bucket_total{bucket="3_10"} 5772
telemt_desync_frames_bucket_total{bucket="gt_10"} 5842
telemt_pool_swap_total 37
telemt_pool_force_close_total 1372
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 10625
telemt_me_writer_removed_unexpected_total 775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9740
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1083
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9253
telemt_me_writer_teardown_success_total{mode="normal"} 11359
telemt_me_writer_teardown_noop_total 10644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.864649
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 306
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8876869
telemt_user_connections_current{user="hello"} 2142
telemt_user_octets_from_client{user="hello"} 80825826679 (75.27 GB)
telemt_user_octets_to_client{user="hello"} 440558353011 (410.30 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 167222.9 (46h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10591037
telemt_connections_bad_total 892678
telemt_connections_current 1788
telemt_connections_me_current 1788
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233424
telemt_upstream_connect_attempt_total 101219
telemt_upstream_connect_success_total 100151
telemt_upstream_connect_fail_total 909
telemt_upstream_connect_attempts_per_request{bucket="1"} 101060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1329
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 909
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72235
telemt_me_reconnect_success_total 2747
telemt_me_reader_eof_total 2436
telemt_me_idle_close_by_peer_total 2434
telemt_me_route_drop_no_conn_total 5163608
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8362296
telemt_me_endpoint_quarantine_total 1110
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1248
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
telemt_me_writers_active_current 45
telemt_desync_total 44445
telemt_desync_full_logged_total 15131
telemt_desync_suppressed_total 29314
telemt_desync_frames_bucket_total{bucket="1_2"} 9009
telemt_desync_frames_bucket_total{bucket="3_10"} 17062
telemt_desync_frames_bucket_total{bucket="gt_10"} 18374
telemt_pool_swap_total 171
telemt_pool_force_close_total 5090
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 56965
telemt_me_writer_removed_unexpected_total 2474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6060
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51875
telemt_me_writer_teardown_success_total{mode="normal"} 59465
telemt_me_writer_teardown_noop_total 56966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.918981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2300
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8365763
telemt_user_connections_current{user="hello"} 1788
telemt_user_octets_from_client{user="hello"} 189919539965 (176.88 GB)
telemt_user_octets_to_client{user="hello"} 3174631848172 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 104059.1 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11134382
telemt_connections_bad_total 433680
telemt_connections_current 1646
telemt_connections_me_current 1646
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4607645
telemt_upstream_connect_attempt_total 49513
telemt_upstream_connect_success_total 49147
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 49504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 48306
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1296
telemt_me_idle_close_by_peer_total 1295
telemt_me_route_drop_no_conn_total 4008816
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5356981
telemt_me_endpoint_quarantine_total 674
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 785
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29997
telemt_desync_full_logged_total 10141
telemt_desync_suppressed_total 19856
telemt_desync_frames_bucket_total{bucket="1_2"} 6019
telemt_desync_frames_bucket_total{bucket="3_10"} 11855
telemt_desync_frames_bucket_total{bucket="gt_10"} 12123
telemt_pool_swap_total 109
telemt_pool_force_close_total 3348
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 36071
telemt_me_writer_removed_unexpected_total 1357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3225
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34236
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32723
telemt_me_writer_teardown_success_total{mode="normal"} 37461
telemt_me_writer_teardown_noop_total 36078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.325263
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1461
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5349958
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 115474691404 (107.54 GB)
telemt_user_octets_to_client{user="hello"} 2044441006554 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 85030.1 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1255987
telemt_connections_bad_total 27787
telemt_connections_current 1129
telemt_connections_me_current 1129
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24138
telemt_upstream_connect_attempt_total 40633
telemt_upstream_connect_success_total 40512
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 40606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 671
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1846
telemt_me_reconnect_success_total 785
telemt_me_reader_eof_total 758
telemt_me_idle_close_by_peer_total 758
telemt_me_route_drop_no_conn_total 438327
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1112720
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 702
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 6465
telemt_desync_full_logged_total 1997
telemt_desync_suppressed_total 4468
telemt_desync_frames_bucket_total{bucket="1_2"} 1467
telemt_desync_frames_bucket_total{bucket="3_10"} 2548
telemt_desync_frames_bucket_total{bucket="gt_10"} 2450
telemt_pool_swap_total 91
telemt_pool_force_close_total 2351
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 33783
telemt_me_writer_removed_unexpected_total 732
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2652
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31892
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31432
telemt_me_writer_teardown_success_total{mode="normal"} 34544
telemt_me_writer_teardown_noop_total 33787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68331
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.190896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68331
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 664
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1108929
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 21213399757 (19.76 GB)
telemt_user_octets_to_client{user="hello"} 471433234223 (439.06 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 167227.6 (46h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12905075
telemt_connections_bad_total 1507650
telemt_connections_current 1838
telemt_connections_me_current 1838
telemt_handshake_timeouts_total 366381
telemt_upstream_connect_attempt_total 62964
telemt_upstream_connect_success_total 62635
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 62829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2454
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1261
telemt_me_route_drop_no_conn_total 4388882
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9762071
telemt_me_endpoint_quarantine_total 1116
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1249
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
telemt_desync_total 40149
telemt_desync_full_logged_total 13089
telemt_desync_suppressed_total 27060
telemt_desync_frames_bucket_total{bucket="1_2"} 9588
telemt_desync_frames_bucket_total{bucket="3_10"} 14820
telemt_desync_frames_bucket_total{bucket="gt_10"} 15741
telemt_pool_swap_total 185
telemt_pool_force_close_total 5098
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 56708
telemt_me_writer_removed_unexpected_total 1213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4650
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53309
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4924
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51610
telemt_me_writer_teardown_success_total{mode="normal"} 57959
telemt_me_writer_teardown_noop_total 56710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114669
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.108795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114669
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 1135
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 9729975
telemt_user_connections_current{user="hello"} 1838
telemt_user_octets_from_client{user="hello"} 190632604124 (177.54 GB)
telemt_user_octets_to_client{user="hello"} 4293957169000 (3.91 TB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 167224.0 (46h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11211701
telemt_connections_bad_total 1269201
telemt_connections_current 1654
telemt_connections_me_current 1654
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 294039
telemt_upstream_connect_attempt_total 89331
telemt_upstream_connect_success_total 88519
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9650
telemt_me_reconnect_success_total 2307
telemt_me_reader_eof_total 2152
telemt_me_idle_close_by_peer_total 2151
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5566892
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8664305
telemt_me_endpoint_quarantine_total 1282
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1248
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39554
telemt_desync_full_logged_total 12782
telemt_desync_suppressed_total 26772
telemt_desync_frames_bucket_total{bucket="1_2"} 9871
telemt_desync_frames_bucket_total{bucket="3_10"} 14708
telemt_desync_frames_bucket_total{bucket="gt_10"} 14975
telemt_pool_swap_total 175
telemt_pool_force_close_total 4899
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 56445
telemt_me_writer_removed_unexpected_total 2186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52726
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51546
telemt_me_writer_teardown_success_total{mode="normal"} 58704
telemt_me_writer_teardown_noop_total 56450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115154
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.094402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115154
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 379
telemt_me_writer_restored_same_endpoint_total 1882
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8669994
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 152880681221 (142.38 GB)
telemt_user_octets_to_client{user="hello"} 3334986460411 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 234
```