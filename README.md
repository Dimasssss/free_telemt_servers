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

# Server Metrics 2026-03-22 22:38:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 91918.7 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3328265
telemt_connections_bad_total 259426
telemt_connections_current 919
telemt_connections_me_current 919
telemt_handshake_timeouts_total 105028
telemt_upstream_connect_attempt_total 33844
telemt_upstream_connect_success_total 33843
telemt_upstream_connect_attempts_per_request{bucket="1"} 33843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1345
telemt_me_reconnect_success_total 555
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 2962570
telemt_me_route_drop_channel_closed_total 1227
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2789585
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 631
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 715
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
telemt_me_writers_active_current 44
telemt_desync_total 11945
telemt_desync_full_logged_total 3741
telemt_desync_suppressed_total 8204
telemt_desync_frames_bucket_total{bucket="1_2"} 3226
telemt_desync_frames_bucket_total{bucket="3_10"} 4367
telemt_desync_frames_bucket_total{bucket="gt_10"} 4352
telemt_pool_swap_total 102
telemt_pool_force_close_total 3146
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 630
telemt_me_draining_writers_reap_progress_total 30950
telemt_me_writer_removed_unexpected_total 551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2238
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28931
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3091
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27804
telemt_me_writer_teardown_success_total{mode="normal"} 31169
telemt_me_writer_teardown_noop_total 30961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62130
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.560243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62130
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 630
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 494
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2778929
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 39859209256 (37.12 GB)
telemt_user_octets_to_client{user="hello"} 753401103248 (701.66 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 105284.2 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3949787
telemt_connections_bad_total 359674
telemt_connections_current 542
telemt_connections_me_current 542
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99755
telemt_upstream_connect_attempt_total 63442
telemt_upstream_connect_success_total 62664
telemt_upstream_connect_fail_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 63352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 688
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9432
telemt_me_reconnect_success_total 3453
telemt_me_reader_eof_total 3470
telemt_me_idle_close_by_peer_total 3470
telemt_me_route_drop_no_conn_total 3635164
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3141480
telemt_me_endpoint_quarantine_total 780
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 812
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 12797
telemt_desync_full_logged_total 7170
telemt_desync_suppressed_total 5627
telemt_desync_frames_bucket_total{bucket="1_2"} 2892
telemt_desync_frames_bucket_total{bucket="3_10"} 5020
telemt_desync_frames_bucket_total{bucket="gt_10"} 4885
telemt_pool_swap_total 96
telemt_pool_force_close_total 2936
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 42242
telemt_me_writer_removed_unexpected_total 3406
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5793
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39882
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2478
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39306
telemt_me_writer_teardown_success_total{mode="normal"} 45675
telemt_me_writer_teardown_noop_total 42243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.502561
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 226
telemt_me_writer_restored_same_endpoint_total 3123
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 3152136
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 42661124295 (39.73 GB)
telemt_user_octets_to_client{user="hello"} 777911160078 (724.49 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 180144.2 (50h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16203667
telemt_connections_bad_total 1607410
telemt_connections_current 1120
telemt_connections_me_current 1120
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396073
telemt_upstream_connect_attempt_total 80016
telemt_upstream_connect_success_total 79916
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2909
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1452
telemt_me_idle_close_by_peer_total 1450
telemt_me_route_drop_no_conn_total 14029894
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12888537
telemt_me_endpoint_quarantine_total 1167
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1346
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 53301
telemt_desync_full_logged_total 16892
telemt_desync_suppressed_total 36409
telemt_desync_frames_bucket_total{bucket="1_2"} 11844
telemt_desync_frames_bucket_total{bucket="3_10"} 20750
telemt_desync_frames_bucket_total{bucket="gt_10"} 20707
telemt_pool_swap_total 195
telemt_pool_force_close_total 6489
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1044
telemt_me_draining_writers_reap_progress_total 59808
telemt_me_writer_removed_unexpected_total 1401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5202
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55277
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53319
telemt_me_writer_teardown_success_total{mode="normal"} 60479
telemt_me_writer_teardown_noop_total 59861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.925411
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1044
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1302
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12888771
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 189955752809 (176.91 GB)
telemt_user_octets_to_client{user="hello"} 3462826458655 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 180145.5 (50h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11761739
telemt_connections_bad_total 1207715
telemt_connections_current 801
telemt_connections_me_current 801
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343988
telemt_upstream_connect_attempt_total 94508
telemt_upstream_connect_success_total 93197
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 94061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4320
telemt_me_reconnect_success_total 1810
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 4543361
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8746274
telemt_me_endpoint_quarantine_total 1171
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1366
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38602
telemt_desync_full_logged_total 12984
telemt_desync_suppressed_total 25618
telemt_desync_frames_bucket_total{bucket="1_2"} 9535
telemt_desync_frames_bucket_total{bucket="3_10"} 14838
telemt_desync_frames_bucket_total{bucket="gt_10"} 14229
telemt_pool_swap_total 192
telemt_pool_force_close_total 5857
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58176
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5345
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52319
telemt_me_writer_teardown_success_total{mode="normal"} 59733
telemt_me_writer_teardown_noop_total 58201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.258106
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1542
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8684102
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 217285356144 (202.36 GB)
telemt_user_octets_to_client{user="hello"} 3934074613223 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 180110.0 (50h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10964469
telemt_connections_bad_total 955182
telemt_connections_current 634
telemt_connections_me_current 634
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344964
telemt_upstream_connect_attempt_total 78551
telemt_upstream_connect_success_total 77015
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 77220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5594
telemt_me_reconnect_success_total 2292
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2028
telemt_me_route_drop_no_conn_total 5325670
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8298368
telemt_me_endpoint_quarantine_total 1239
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1322
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_warm_current 33
telemt_desync_total 37877
telemt_desync_full_logged_total 12560
telemt_desync_suppressed_total 25317
telemt_desync_frames_bucket_total{bucket="1_2"} 9568
telemt_desync_frames_bucket_total{bucket="3_10"} 14489
telemt_desync_frames_bucket_total{bucket="gt_10"} 13820
telemt_pool_swap_total 187
telemt_pool_force_close_total 5770
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 730
telemt_me_draining_writers_reap_progress_total 58365
telemt_me_writer_removed_unexpected_total 2184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54440
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52595
telemt_me_writer_teardown_success_total{mode="normal"} 60476
telemt_me_writer_teardown_noop_total 58436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.606094
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 730
telemt_me_refill_failed_total 175
telemt_me_writer_restored_same_endpoint_total 1984
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 8290357
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 192111489533 (178.92 GB)
telemt_user_octets_to_client{user="hello"} 3448879292421 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 50389.5 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11094082
telemt_connections_bad_total 667046
telemt_connections_current 1074
telemt_connections_me_current 1074
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 253679
telemt_upstream_connect_attempt_total 51954
telemt_upstream_connect_success_total 49368
telemt_upstream_connect_fail_total 1741
telemt_upstream_connect_attempts_per_request{bucket="1"} 51109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5988
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1741
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7067
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 25266392
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9216102
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 396
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
telemt_desync_total 15832
telemt_desync_full_logged_total 4215
telemt_desync_suppressed_total 11617
telemt_desync_frames_bucket_total{bucket="1_2"} 3026
telemt_desync_frames_bucket_total{bucket="3_10"} 6398
telemt_desync_frames_bucket_total{bucket="gt_10"} 6408
telemt_pool_swap_total 51
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 14967
telemt_me_writer_removed_unexpected_total 943
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2107
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13754
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13198
telemt_me_writer_teardown_success_total{mode="normal"} 15861
telemt_me_writer_teardown_noop_total 14986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30847
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.638562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30847
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 694
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9240784
telemt_user_connections_current{user="hello"} 1074
telemt_user_octets_from_client{user="hello"} 85968924692 (80.06 GB)
telemt_user_octets_to_client{user="hello"} 572701575582 (533.37 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 180116.0 (50h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10894172
telemt_connections_bad_total 927789
telemt_connections_current 802
telemt_connections_me_current 802
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239505
telemt_upstream_connect_attempt_total 107357
telemt_upstream_connect_success_total 106238
telemt_upstream_connect_fail_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 107187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 949
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72718
telemt_me_reconnect_success_total 2969
telemt_me_reader_eof_total 2665
telemt_me_idle_close_by_peer_total 2663
telemt_me_route_drop_no_conn_total 5245391
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8603416
telemt_me_endpoint_quarantine_total 1190
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
telemt_desync_total 45891
telemt_desync_full_logged_total 15698
telemt_desync_suppressed_total 30193
telemt_desync_frames_bucket_total{bucket="1_2"} 9304
telemt_desync_frames_bucket_total{bucket="3_10"} 17566
telemt_desync_frames_bucket_total{bucket="gt_10"} 19021
telemt_pool_swap_total 184
telemt_pool_force_close_total 5460
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 62410
telemt_me_writer_removed_unexpected_total 2697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56950
telemt_me_writer_teardown_success_total{mode="normal"} 65139
telemt_me_writer_teardown_noop_total 62411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.183652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 4295
telemt_me_writer_restored_same_endpoint_total 2507
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 8606493
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 193892580569 (180.58 GB)
telemt_user_octets_to_client{user="hello"} 3286105216836 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 116952.2 (32h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11557738
telemt_connections_bad_total 461447
telemt_connections_current 655
telemt_connections_me_current 655
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4736834
telemt_upstream_connect_attempt_total 55395
telemt_upstream_connect_success_total 54988
telemt_upstream_connect_fail_total 396
telemt_upstream_connect_attempts_per_request{bucket="1"} 55384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 396
telemt_me_reconnect_attempts_total 48698
telemt_me_reconnect_success_total 1734
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1397
telemt_me_route_drop_no_conn_total 4074520
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5560729
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 887
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31270
telemt_desync_full_logged_total 10650
telemt_desync_suppressed_total 20620
telemt_desync_frames_bucket_total{bucket="1_2"} 6201
telemt_desync_frames_bucket_total{bucket="3_10"} 12342
telemt_desync_frames_bucket_total{bucket="gt_10"} 12727
telemt_pool_swap_total 123
telemt_pool_force_close_total 3707
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 41384
telemt_me_writer_removed_unexpected_total 1452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37677
telemt_me_writer_teardown_success_total{mode="normal"} 42876
telemt_me_writer_teardown_noop_total 41391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84267
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.635049
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84267
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5553341
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 118540309864 (110.40 GB)
telemt_user_octets_to_client{user="hello"} 2144377607650 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 97923.1 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1464390
telemt_connections_bad_total 36400
telemt_connections_current 597
telemt_connections_me_current 597
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29116
telemt_upstream_connect_attempt_total 45789
telemt_upstream_connect_success_total 45646
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 45761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 767
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2095
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 840
telemt_me_idle_close_by_peer_total 840
telemt_me_route_drop_no_conn_total 505352
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299624
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 805
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
telemt_me_writers_active_current 46
telemt_desync_total 8193
telemt_desync_full_logged_total 2476
telemt_desync_suppressed_total 5717
telemt_desync_frames_bucket_total{bucket="1_2"} 2043
telemt_desync_frames_bucket_total{bucket="3_10"} 3168
telemt_desync_frames_bucket_total{bucket="gt_10"} 2982
telemt_pool_swap_total 105
telemt_pool_force_close_total 2736
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 38382
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3010
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36219
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35646
telemt_me_writer_teardown_success_total{mode="normal"} 39229
telemt_me_writer_teardown_noop_total 38386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.981177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 732
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1295528
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 25375068497 (23.63 GB)
telemt_user_octets_to_client{user="hello"} 553078764407 (515.09 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 180120.7 (50h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13217176
telemt_connections_bad_total 1567399
telemt_connections_current 947
telemt_connections_me_current 947
telemt_handshake_timeouts_total 380159
telemt_upstream_connect_attempt_total 69059
telemt_upstream_connect_success_total 68719
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 68923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2693
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1369
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 4472079
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9991031
telemt_me_endpoint_quarantine_total 1237
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1352
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
telemt_me_writers_active_current 43
telemt_desync_total 41754
telemt_desync_full_logged_total 13626
telemt_desync_suppressed_total 28128
telemt_desync_frames_bucket_total{bucket="1_2"} 10037
telemt_desync_frames_bucket_total{bucket="3_10"} 15365
telemt_desync_frames_bucket_total{bucket="gt_10"} 16352
telemt_pool_swap_total 200
telemt_pool_force_close_total 5422
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 62295
telemt_me_writer_removed_unexpected_total 1316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58643
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5248
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56873
telemt_me_writer_teardown_success_total{mode="normal"} 63654
telemt_me_writer_teardown_noop_total 62297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125951
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.593362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125951
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1224
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 9957817
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 194178902040 (180.84 GB)
telemt_user_octets_to_client{user="hello"} 4414899301604 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 180117.1 (50h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11513133
telemt_connections_bad_total 1315875
telemt_connections_current 596
telemt_connections_me_current 596
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 305422
telemt_upstream_connect_attempt_total 95596
telemt_upstream_connect_success_total 94744
telemt_upstream_connect_fail_total 645
telemt_upstream_connect_attempts_per_request{bucket="1"} 95389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 645
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10100
telemt_me_reconnect_success_total 2452
telemt_me_reader_eof_total 2287
telemt_me_idle_close_by_peer_total 2286
telemt_me_seq_mismatch_total 86
telemt_me_route_drop_no_conn_total 5632207
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8891956
telemt_me_endpoint_quarantine_total 1404
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1353
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
telemt_desync_total 41385
telemt_desync_full_logged_total 13281
telemt_desync_suppressed_total 28104
telemt_desync_frames_bucket_total{bucket="1_2"} 10628
telemt_desync_frames_bucket_total{bucket="3_10"} 15227
telemt_desync_frames_bucket_total{bucket="gt_10"} 15530
telemt_pool_swap_total 190
telemt_pool_force_close_total 5213
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 62111
telemt_me_writer_removed_unexpected_total 2322
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6352
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58161
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56898
telemt_me_writer_teardown_success_total{mode="normal"} 64513
telemt_me_writer_teardown_noop_total 62116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126629
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.324071
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126629
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1988
telemt_me_writer_restored_fallback_total 118
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8897365
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 156848606617 (146.08 GB)
telemt_user_octets_to_client{user="hello"} 3463604390871 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 73
```