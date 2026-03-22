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

# Server Metrics 2026-03-22 22:28:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 91308.0 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3315324
telemt_connections_bad_total 255019
telemt_connections_current 778
telemt_connections_me_current 778
telemt_handshake_timeouts_total 104961
telemt_upstream_connect_attempt_total 33604
telemt_upstream_connect_success_total 33603
telemt_upstream_connect_attempts_per_request{bucket="1"} 33603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1342
telemt_me_reconnect_success_total 552
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 2961009
telemt_me_route_drop_channel_closed_total 1227
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2781757
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 713
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 11928
telemt_desync_full_logged_total 3737
telemt_desync_suppressed_total 8191
telemt_desync_frames_bucket_total{bucket="1_2"} 3225
telemt_desync_frames_bucket_total{bucket="3_10"} 4359
telemt_desync_frames_bucket_total{bucket="gt_10"} 4344
telemt_pool_swap_total 101
telemt_pool_force_close_total 3146
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 30749
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28736
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3091
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27603
telemt_me_writer_teardown_success_total{mode="normal"} 30964
telemt_me_writer_teardown_noop_total 30760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61724
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.535369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61724
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 491
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2771106
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 39780418516 (37.05 GB)
telemt_user_octets_to_client{user="hello"} 750353829828 (698.82 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 104674.4 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3943341
telemt_connections_bad_total 356990
telemt_connections_current 316
telemt_connections_me_current 316
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99694
telemt_upstream_connect_attempt_total 63199
telemt_upstream_connect_success_total 62421
telemt_upstream_connect_fail_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 63109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 688
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9429
telemt_me_reconnect_success_total 3451
telemt_me_reader_eof_total 3468
telemt_me_idle_close_by_peer_total 3468
telemt_me_route_drop_no_conn_total 3634265
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3137946
telemt_me_endpoint_quarantine_total 780
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 808
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 12784
telemt_desync_full_logged_total 7161
telemt_desync_suppressed_total 5623
telemt_desync_frames_bucket_total{bucket="1_2"} 2887
telemt_desync_frames_bucket_total{bucket="3_10"} 5015
telemt_desync_frames_bucket_total{bucket="gt_10"} 4882
telemt_pool_swap_total 96
telemt_pool_force_close_total 2936
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 42025
telemt_me_writer_removed_unexpected_total 3404
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39668
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2478
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39089
telemt_me_writer_teardown_success_total{mode="normal"} 45456
telemt_me_writer_teardown_noop_total 42026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.500228
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 226
telemt_me_writer_restored_same_endpoint_total 3121
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 3148602
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 42604199167 (39.68 GB)
telemt_user_octets_to_client{user="hello"} 776302337506 (722.99 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 179534.4 (49h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16193960
telemt_connections_bad_total 1604782
telemt_connections_current 1026
telemt_connections_me_current 1026
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395997
telemt_upstream_connect_attempt_total 79719
telemt_upstream_connect_success_total 79618
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2893
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1451
telemt_me_idle_close_by_peer_total 1449
telemt_me_route_drop_no_conn_total 14028220
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12881856
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1344
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
telemt_desync_total 53245
telemt_desync_full_logged_total 16870
telemt_desync_suppressed_total 36375
telemt_desync_frames_bucket_total{bucket="1_2"} 11829
telemt_desync_frames_bucket_total{bucket="3_10"} 20733
telemt_desync_frames_bucket_total{bucket="gt_10"} 20683
telemt_pool_swap_total 194
telemt_pool_force_close_total 6489
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1044
telemt_me_draining_writers_reap_progress_total 59534
telemt_me_writer_removed_unexpected_total 1400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5185
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55019
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53045
telemt_me_writer_teardown_success_total{mode="normal"} 60204
telemt_me_writer_teardown_noop_total 59587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119791
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.920057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119791
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1044
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1302
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 12882089
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 189860845241 (176.82 GB)
telemt_user_octets_to_client{user="hello"} 3460037315147 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 179535.8 (49h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11750508
telemt_connections_bad_total 1204917
telemt_connections_current 805
telemt_connections_me_current 805
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343731
telemt_upstream_connect_attempt_total 94198
telemt_upstream_connect_success_total 92888
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 93751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4320
telemt_me_reconnect_success_total 1810
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 4541890
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8739574
telemt_me_endpoint_quarantine_total 1158
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 38589
telemt_desync_full_logged_total 12980
telemt_desync_suppressed_total 25609
telemt_desync_frames_bucket_total{bucket="1_2"} 9532
telemt_desync_frames_bucket_total{bucket="3_10"} 14834
telemt_desync_frames_bucket_total{bucket="gt_10"} 14223
telemt_pool_swap_total 191
telemt_pool_force_close_total 5857
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57894
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5345
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52037
telemt_me_writer_teardown_success_total{mode="normal"} 59451
telemt_me_writer_teardown_noop_total 57919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.253739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1542
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8677406
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 217192445460 (202.28 GB)
telemt_user_octets_to_client{user="hello"} 3931671574379 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 179499.8 (49h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10958448
telemt_connections_bad_total 953979
telemt_connections_current 572
telemt_connections_me_current 572
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344930
telemt_upstream_connect_attempt_total 78275
telemt_upstream_connect_success_total 76753
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 76957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5591
telemt_me_reconnect_success_total 2289
telemt_me_reader_eof_total 2026
telemt_me_idle_close_by_peer_total 2025
telemt_me_route_drop_no_conn_total 5323945
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8294032
telemt_me_endpoint_quarantine_total 1239
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1319
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37868
telemt_desync_full_logged_total 12553
telemt_desync_suppressed_total 25315
telemt_desync_frames_bucket_total{bucket="1_2"} 9567
telemt_desync_frames_bucket_total{bucket="3_10"} 14483
telemt_desync_frames_bucket_total{bucket="gt_10"} 13818
telemt_pool_swap_total 187
telemt_pool_force_close_total 5770
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 730
telemt_me_draining_writers_reap_progress_total 58175
telemt_me_writer_removed_unexpected_total 2181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6027
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54256
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52405
telemt_me_writer_teardown_success_total{mode="normal"} 60283
telemt_me_writer_teardown_noop_total 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.604085
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 730
telemt_me_refill_failed_total 175
telemt_me_writer_restored_same_endpoint_total 1981
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 8286022
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 192037274385 (178.85 GB)
telemt_user_octets_to_client{user="hello"} 3445557832201 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 49779.1 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11080962
telemt_connections_bad_total 667022
telemt_connections_current 1095
telemt_connections_me_current 1095
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 252455
telemt_upstream_connect_attempt_total 51712
telemt_upstream_connect_success_total 49133
telemt_upstream_connect_fail_total 1741
telemt_upstream_connect_attempts_per_request{bucket="1"} 50874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5988
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1741
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7062
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 662
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 25264174
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9204567
telemt_me_endpoint_quarantine_total 345
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 394
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
telemt_me_writers_active_current 44
telemt_desync_total 15801
telemt_desync_full_logged_total 4202
telemt_desync_suppressed_total 11599
telemt_desync_frames_bucket_total{bucket="1_2"} 3023
telemt_desync_frames_bucket_total{bucket="3_10"} 6383
telemt_desync_frames_bucket_total{bucket="gt_10"} 6395
telemt_pool_swap_total 51
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 14761
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12992
telemt_me_writer_teardown_success_total{mode="normal"} 15650
telemt_me_writer_teardown_noop_total 14780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.634681
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 689
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9229245
telemt_user_connections_current{user="hello"} 1095
telemt_user_octets_from_client{user="hello"} 85851704588 (79.96 GB)
telemt_user_octets_to_client{user="hello"} 570225541618 (531.06 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 179505.8 (49h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10887680
telemt_connections_bad_total 927361
telemt_connections_current 847
telemt_connections_me_current 847
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239448
telemt_upstream_connect_attempt_total 107076
telemt_upstream_connect_success_total 105960
telemt_upstream_connect_fail_total 946
telemt_upstream_connect_attempts_per_request{bucket="1"} 106906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 946
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72712
telemt_me_reconnect_success_total 2964
telemt_me_reader_eof_total 2660
telemt_me_idle_close_by_peer_total 2658
telemt_me_route_drop_no_conn_total 5243424
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8597773
telemt_me_endpoint_quarantine_total 1181
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1349
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 45876
telemt_desync_full_logged_total 15688
telemt_desync_suppressed_total 30188
telemt_desync_frames_bucket_total{bucket="1_2"} 9302
telemt_desync_frames_bucket_total{bucket="3_10"} 17562
telemt_desync_frames_bucket_total{bucket="gt_10"} 19012
telemt_pool_swap_total 183
telemt_pool_force_close_total 5460
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 62184
telemt_me_writer_removed_unexpected_total 2692
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6539
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56724
telemt_me_writer_teardown_success_total{mode="normal"} 64908
telemt_me_writer_teardown_noop_total 62185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.182468
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 4295
telemt_me_writer_restored_same_endpoint_total 2502
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 8600850
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 193847078641 (180.53 GB)
telemt_user_octets_to_client{user="hello"} 3283607659740 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 116341.9 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11548424
telemt_connections_bad_total 460542
telemt_connections_current 688
telemt_connections_me_current 688
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4735747
telemt_upstream_connect_attempt_total 55121
telemt_upstream_connect_success_total 54714
telemt_upstream_connect_fail_total 396
telemt_upstream_connect_attempts_per_request{bucket="1"} 55110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 396
telemt_me_reconnect_attempts_total 48691
telemt_me_reconnect_success_total 1729
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1392
telemt_me_route_drop_no_conn_total 4073380
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5556142
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 884
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31220
telemt_desync_full_logged_total 10640
telemt_desync_suppressed_total 20580
telemt_desync_frames_bucket_total{bucket="1_2"} 6196
telemt_desync_frames_bucket_total{bucket="3_10"} 12320
telemt_desync_frames_bucket_total{bucket="gt_10"} 12704
telemt_pool_swap_total 123
telemt_pool_force_close_total 3707
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 41140
telemt_me_writer_removed_unexpected_total 1447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3531
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39096
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37433
telemt_me_writer_teardown_success_total{mode="normal"} 42627
telemt_me_writer_teardown_noop_total 41147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.634066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1534
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5548755
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 118496010236 (110.36 GB)
telemt_user_octets_to_client{user="hello"} 2137139565986 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 97312.8 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1459127
telemt_connections_bad_total 36392
telemt_connections_current 610
telemt_connections_me_current 610
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29035
telemt_upstream_connect_attempt_total 45538
telemt_upstream_connect_success_total 45395
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 45510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 766
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2091
telemt_me_reconnect_success_total 859
telemt_me_reader_eof_total 837
telemt_me_idle_close_by_peer_total 837
telemt_me_route_drop_no_conn_total 503852
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1294691
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 798
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
telemt_me_writers_active_current 43
telemt_desync_total 8158
telemt_desync_full_logged_total 2466
telemt_desync_suppressed_total 5692
telemt_desync_frames_bucket_total{bucket="1_2"} 2029
telemt_desync_frames_bucket_total{bucket="3_10"} 3152
telemt_desync_frames_bucket_total{bucket="gt_10"} 2977
telemt_pool_swap_total 105
telemt_pool_force_close_total 2714
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 38139
telemt_me_writer_removed_unexpected_total 810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2997
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35986
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35425
telemt_me_writer_teardown_success_total{mode="normal"} 38983
telemt_me_writer_teardown_noop_total 38143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77126
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.972670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77126
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 729
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1290606
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 25308424405 (23.57 GB)
telemt_user_octets_to_client{user="hello"} 550419169211 (512.62 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 179510.7 (49h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13210248
telemt_connections_bad_total 1566630
telemt_connections_current 952
telemt_connections_me_current 952
telemt_handshake_timeouts_total 379343
telemt_upstream_connect_attempt_total 68749
telemt_upstream_connect_success_total 68411
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 68613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2692
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 4471016
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9986030
telemt_me_endpoint_quarantine_total 1230
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1349
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
telemt_me_writers_active_current 42
telemt_desync_total 41745
telemt_desync_full_logged_total 13622
telemt_desync_suppressed_total 28123
telemt_desync_frames_bucket_total{bucket="1_2"} 10033
telemt_desync_frames_bucket_total{bucket="3_10"} 15364
telemt_desync_frames_bucket_total{bucket="gt_10"} 16348
telemt_pool_swap_total 199
telemt_pool_force_close_total 5422
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 62014
telemt_me_writer_removed_unexpected_total 1315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5004
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58367
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5248
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56592
telemt_me_writer_teardown_success_total{mode="normal"} 63371
telemt_me_writer_teardown_noop_total 62016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.591021
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1223
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 9952816
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 194135589860 (180.80 GB)
telemt_user_octets_to_client{user="hello"} 4411201360304 (4.01 TB)
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 179507.1 (49h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11504532
telemt_connections_bad_total 1312717
telemt_connections_current 607
telemt_connections_me_current 607
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 305329
telemt_upstream_connect_attempt_total 95258
telemt_upstream_connect_success_total 94409
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 95051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10097
telemt_me_reconnect_success_total 2448
telemt_me_reader_eof_total 2285
telemt_me_idle_close_by_peer_total 2284
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5630969
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8886772
telemt_me_endpoint_quarantine_total 1395
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1352
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
telemt_me_writers_active_current 44
telemt_desync_total 41336
telemt_desync_full_logged_total 13269
telemt_desync_suppressed_total 28067
telemt_desync_frames_bucket_total{bucket="1_2"} 10608
telemt_desync_frames_bucket_total{bucket="3_10"} 15213
telemt_desync_frames_bucket_total{bucket="gt_10"} 15515
telemt_pool_swap_total 189
telemt_pool_force_close_total 5213
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 61817
telemt_me_writer_removed_unexpected_total 2319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6341
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56604
telemt_me_writer_teardown_success_total{mode="normal"} 64216
telemt_me_writer_teardown_noop_total 61822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.321017
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1986
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8892181
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 156802682793 (146.03 GB)
telemt_user_octets_to_client{user="hello"} 3461508645787 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 56
```