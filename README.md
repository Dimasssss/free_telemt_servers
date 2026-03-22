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

# Server Metrics 2026-03-22 19:49:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 81792.2 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3039142
telemt_connections_bad_total 206461
telemt_connections_current 1060
telemt_connections_me_current 1060
telemt_handshake_timeouts_total 98161
telemt_upstream_connect_attempt_total 29974
telemt_upstream_connect_success_total 29973
telemt_upstream_connect_attempts_per_request{bucket="1"} 29973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1191
telemt_me_reconnect_success_total 505
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 2706100
telemt_me_route_drop_channel_closed_total 1078
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2572318
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 552
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 634
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
telemt_me_writers_active_current 50
telemt_desync_total 11045
telemt_desync_full_logged_total 3506
telemt_desync_suppressed_total 7539
telemt_desync_frames_bucket_total{bucket="1_2"} 2954
telemt_desync_frames_bucket_total{bucket="3_10"} 4102
telemt_desync_frames_bucket_total{bucket="gt_10"} 3989
telemt_pool_swap_total 90
telemt_pool_force_close_total 2788
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 583
telemt_me_draining_writers_reap_progress_total 27388
telemt_me_writer_removed_unexpected_total 494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25618
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24600
telemt_me_writer_teardown_success_total{mode="normal"} 27614
telemt_me_writer_teardown_noop_total 27398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.590127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 583
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2564329
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 37582653528 (35.00 GB)
telemt_user_octets_to_client{user="hello"} 674046895552 (627.76 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 95158.1 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3825926
telemt_connections_bad_total 340071
telemt_connections_current 1292
telemt_connections_me_current 1292
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97550
telemt_upstream_connect_attempt_total 57771
telemt_upstream_connect_success_total 57059
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 57688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6741
telemt_me_reconnect_success_total 2583
telemt_me_reader_eof_total 2527
telemt_me_idle_close_by_peer_total 2527
telemt_me_route_drop_no_conn_total 3603357
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3045660
telemt_me_endpoint_quarantine_total 729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 732
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
telemt_me_writers_active_current 128
telemt_desync_total 12187
telemt_desync_full_logged_total 6812
telemt_desync_suppressed_total 5375
telemt_desync_frames_bucket_total{bucket="1_2"} 2790
telemt_desync_frames_bucket_total{bucket="3_10"} 4777
telemt_desync_frames_bucket_total{bucket="gt_10"} 4620
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37755
telemt_me_writer_removed_unexpected_total 2476
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35618
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35098
telemt_me_writer_teardown_success_total{mode="normal"} 40245
telemt_me_writer_teardown_noop_total 37755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78000
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.978034
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78000
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2270
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 3056461
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 39722069535 (36.99 GB)
telemt_user_octets_to_client{user="hello"} 726707404198 (676.80 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 170018.0 (47h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15920472
telemt_connections_bad_total 1538728
telemt_connections_current 1962
telemt_connections_me_current 1962
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392463
telemt_upstream_connect_attempt_total 75625
telemt_upstream_connect_success_total 75528
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2806
telemt_me_reconnect_success_total 1444
telemt_me_reader_eof_total 1386
telemt_me_idle_close_by_peer_total 1384
telemt_me_route_drop_no_conn_total 13967240
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12686688
telemt_me_endpoint_quarantine_total 1071
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1264
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 52307
telemt_desync_full_logged_total 16464
telemt_desync_suppressed_total 35843
telemt_desync_frames_bucket_total{bucket="1_2"} 11659
telemt_desync_frames_bucket_total{bucket="3_10"} 20377
telemt_desync_frames_bucket_total{bucket="gt_10"} 20271
telemt_pool_swap_total 183
telemt_pool_force_close_total 6191
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1005
telemt_me_draining_writers_reap_progress_total 55820
telemt_me_writer_removed_unexpected_total 1338
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4894
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51541
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49629
telemt_me_writer_teardown_success_total{mode="normal"} 56435
telemt_me_writer_teardown_noop_total 55871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 312.727663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1005
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 12687208
telemt_user_connections_current{user="hello"} 1962
telemt_user_octets_from_client{user="hello"} 185492637057 (172.75 GB)
telemt_user_octets_to_client{user="hello"} 3369208889831 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 812
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 170019.3 (47h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11510939
telemt_connections_bad_total 1147567
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342734
telemt_upstream_connect_attempt_total 88085
telemt_upstream_connect_success_total 86855
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 87700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4140
telemt_me_reconnect_success_total 1721
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1590
telemt_me_route_drop_no_conn_total 4486825
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8576053
telemt_me_endpoint_quarantine_total 1071
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1286
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
telemt_desync_total 37982
telemt_desync_full_logged_total 12796
telemt_desync_suppressed_total 25186
telemt_desync_frames_bucket_total{bucket="1_2"} 9364
telemt_desync_frames_bucket_total{bucket="3_10"} 14627
telemt_desync_frames_bucket_total{bucket="gt_10"} 13991
telemt_pool_swap_total 180
telemt_pool_force_close_total 5580
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54228
telemt_me_writer_removed_unexpected_total 1627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50691
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5077
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48648
telemt_me_writer_teardown_success_total{mode="normal"} 55702
telemt_me_writer_teardown_noop_total 54253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.651187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1471
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8514265
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 213771691621 (199.09 GB)
telemt_user_octets_to_client{user="hello"} 3845351594178 (3.50 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 169984.7 (47h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10802547
telemt_connections_bad_total 933977
telemt_connections_current 1148
telemt_connections_me_current 1148
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343736
telemt_upstream_connect_attempt_total 73229
telemt_upstream_connect_success_total 72114
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4966
telemt_me_reconnect_success_total 2008
telemt_me_reader_eof_total 1754
telemt_me_idle_close_by_peer_total 1753
telemt_me_route_drop_no_conn_total 5256840
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8167726
telemt_me_endpoint_quarantine_total 1157
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1247
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 37473
telemt_desync_full_logged_total 12404
telemt_desync_suppressed_total 25069
telemt_desync_frames_bucket_total{bucket="1_2"} 9475
telemt_desync_frames_bucket_total{bucket="3_10"} 14333
telemt_desync_frames_bucket_total{bucket="gt_10"} 13665
telemt_pool_swap_total 178
telemt_pool_force_close_total 5526
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 710
telemt_me_draining_writers_reap_progress_total 54370
telemt_me_writer_removed_unexpected_total 1895
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4975
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48844
telemt_me_writer_teardown_success_total{mode="normal"} 56184
telemt_me_writer_teardown_noop_total 54441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110625
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.783944
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110625
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 710
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 1728
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 8160029
telemt_user_connections_current{user="hello"} 1148
telemt_user_octets_from_client{user="hello"} 189665320517 (176.64 GB)
telemt_user_octets_to_client{user="hello"} 3395759960425 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 40263.5 (11h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10787504
telemt_connections_bad_total 657231
telemt_connections_current 1988
telemt_connections_me_current 1988
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 231876
telemt_upstream_connect_attempt_total 44940
telemt_upstream_connect_success_total 42690
telemt_upstream_connect_fail_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 44235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5961
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1545
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6488
telemt_me_reconnect_success_total 892
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_route_drop_no_conn_total 25186224
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8958607
telemt_me_endpoint_quarantine_total 248
telemt_me_single_endpoint_outage_enter_total 64
telemt_me_single_endpoint_outage_exit_total 64
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_me_writers_active_current 53
telemt_desync_total 14547
telemt_desync_full_logged_total 3836
telemt_desync_suppressed_total 10711
telemt_desync_frames_bucket_total{bucket="1_2"} 2693
telemt_desync_frames_bucket_total{bucket="3_10"} 5911
telemt_desync_frames_bucket_total{bucket="gt_10"} 5943
telemt_pool_swap_total 40
telemt_pool_force_close_total 1475
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 11431
telemt_me_writer_removed_unexpected_total 798
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1713
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10469
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9956
telemt_me_writer_teardown_success_total{mode="normal"} 12182
telemt_me_writer_teardown_noop_total 11450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23632
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.841709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23632
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8980767
telemt_user_connections_current{user="hello"} 1988
telemt_user_octets_from_client{user="hello"} 82053972539 (76.42 GB)
telemt_user_octets_to_client{user="hello"} 480889285203 (447.86 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 720
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 169990.0 (47h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10678704
telemt_connections_bad_total 899487
telemt_connections_current 1578
telemt_connections_me_current 1578
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 234767
telemt_upstream_connect_attempt_total 102595
telemt_upstream_connect_success_total 101513
telemt_upstream_connect_fail_total 923
telemt_upstream_connect_attempts_per_request{bucket="1"} 102436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 923
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72369
telemt_me_reconnect_success_total 2811
telemt_me_reader_eof_total 2501
telemt_me_idle_close_by_peer_total 2499
telemt_me_route_drop_no_conn_total 5190257
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8436296
telemt_me_endpoint_quarantine_total 1121
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1267
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
telemt_me_writers_active_current 49
telemt_desync_total 44890
telemt_desync_full_logged_total 15275
telemt_desync_suppressed_total 29615
telemt_desync_frames_bucket_total{bucket="1_2"} 9111
telemt_desync_frames_bucket_total{bucket="3_10"} 17190
telemt_desync_frames_bucket_total{bucket="gt_10"} 18589
telemt_pool_swap_total 173
telemt_pool_force_close_total 5167
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 58190
telemt_me_writer_removed_unexpected_total 2539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54563
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 725
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53023
telemt_me_writer_teardown_success_total{mode="normal"} 60755
telemt_me_writer_teardown_noop_total 58191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.990486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2360
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8439634
telemt_user_connections_current{user="hello"} 1578
telemt_user_octets_from_client{user="hello"} 191476646197 (178.33 GB)
telemt_user_octets_to_client{user="hello"} 3205745598784 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 106826.2 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11260487
telemt_connections_bad_total 449974
telemt_connections_current 1361
telemt_connections_me_current 1361
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4640741
telemt_upstream_connect_attempt_total 50725
telemt_upstream_connect_success_total 50347
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 50716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_reconnect_attempts_total 48471
telemt_me_reconnect_success_total 1670
telemt_me_reader_eof_total 1326
telemt_me_idle_close_by_peer_total 1325
telemt_me_route_drop_no_conn_total 4030526
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5418222
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 806
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30408
telemt_desync_full_logged_total 10286
telemt_desync_suppressed_total 20122
telemt_desync_frames_bucket_total{bucket="1_2"} 6075
telemt_desync_frames_bucket_total{bucket="3_10"} 12016
telemt_desync_frames_bucket_total{bucket="gt_10"} 12317
telemt_pool_swap_total 112
telemt_pool_force_close_total 3429
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 37156
telemt_me_writer_removed_unexpected_total 1386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3304
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35272
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2989
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33727
telemt_me_writer_teardown_success_total{mode="normal"} 38576
telemt_me_writer_teardown_noop_total 37163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.467299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5411125
telemt_user_connections_current{user="hello"} 1361
telemt_user_octets_from_client{user="hello"} 116838171964 (108.81 GB)
telemt_user_octets_to_client{user="hello"} 2071948747850 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 87797.1 (24h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1316579
telemt_connections_bad_total 29237
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24830
telemt_upstream_connect_attempt_total 41689
telemt_upstream_connect_success_total 41563
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 41662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 705
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1916
telemt_me_reconnect_success_total 803
telemt_me_reader_eof_total 779
telemt_me_idle_close_by_peer_total 779
telemt_me_route_drop_no_conn_total 459840
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1168382
telemt_me_endpoint_quarantine_total 732
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 724
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
telemt_me_writers_active_current 46
telemt_desync_total 6925
telemt_desync_full_logged_total 2139
telemt_desync_suppressed_total 4786
telemt_desync_frames_bucket_total{bucket="1_2"} 1544
telemt_desync_frames_bucket_total{bucket="3_10"} 2739
telemt_desync_frames_bucket_total{bucket="gt_10"} 2642
telemt_pool_swap_total 94
telemt_pool_force_close_total 2432
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 34704
telemt_me_writer_removed_unexpected_total 752
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2737
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32749
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32272
telemt_me_writer_teardown_success_total{mode="normal"} 35486
telemt_me_writer_teardown_noop_total 34708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.348595
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 1164505
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 22346019569 (20.81 GB)
telemt_user_octets_to_client{user="hello"} 493704209595 (459.80 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 169994.6 (47h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12993350
telemt_connections_bad_total 1514808
telemt_connections_current 1666
telemt_connections_me_current 1666
telemt_handshake_timeouts_total 372532
telemt_upstream_connect_attempt_total 64102
telemt_upstream_connect_success_total 63770
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 63967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2521
telemt_me_reconnect_success_total 1314
telemt_me_reader_eof_total 1278
telemt_me_idle_close_by_peer_total 1278
telemt_me_route_drop_no_conn_total 4413138
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9834105
telemt_me_endpoint_quarantine_total 1136
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1270
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
telemt_me_writers_active_current 44
telemt_desync_total 40655
telemt_desync_full_logged_total 13255
telemt_desync_suppressed_total 27400
telemt_desync_frames_bucket_total{bucket="1_2"} 9713
telemt_desync_frames_bucket_total{bucket="3_10"} 15007
telemt_desync_frames_bucket_total{bucket="gt_10"} 15935
telemt_pool_swap_total 188
telemt_pool_force_close_total 5175
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 57750
telemt_me_writer_removed_unexpected_total 1230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54296
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5001
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52575
telemt_me_writer_teardown_success_total{mode="normal"} 59018
telemt_me_writer_teardown_noop_total 57752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116770
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.251959
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116770
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9801820
telemt_user_connections_current{user="hello"} 1666
telemt_user_octets_from_client{user="hello"} 191806271140 (178.63 GB)
telemt_user_octets_to_client{user="hello"} 4330516657132 (3.94 TB)
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 169991.2 (47h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11300249
telemt_connections_bad_total 1281123
telemt_connections_current 1397
telemt_connections_me_current 1397
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 297132
telemt_upstream_connect_attempt_total 90582
telemt_upstream_connect_success_total 89763
telemt_upstream_connect_fail_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 90376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 613
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9740
telemt_me_reconnect_success_total 2339
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2184
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5587414
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8733923
telemt_me_endpoint_quarantine_total 1299
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1270
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39860
telemt_desync_full_logged_total 12880
telemt_desync_suppressed_total 26980
telemt_desync_frames_bucket_total{bucket="1_2"} 9945
telemt_desync_frames_bucket_total{bucket="3_10"} 14828
telemt_desync_frames_bucket_total{bucket="gt_10"} 15087
telemt_pool_swap_total 178
telemt_pool_force_close_total 4970
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 57562
telemt_me_writer_removed_unexpected_total 2218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53797
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4499
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52592
telemt_me_writer_teardown_success_total{mode="normal"} 59854
telemt_me_writer_teardown_noop_total 57567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.159966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 382
telemt_me_writer_restored_same_endpoint_total 1909
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 8739513
telemt_user_connections_current{user="hello"} 1397
telemt_user_octets_from_client{user="hello"} 154537928337 (143.92 GB)
telemt_user_octets_to_client{user="hello"} 3374694577347 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 154
```