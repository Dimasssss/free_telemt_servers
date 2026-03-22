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

# Server Metrics 2026-03-22 14:42:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63366.6 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2060888
telemt_connections_bad_total 96280
telemt_connections_current 1598
telemt_connections_me_current 1598
telemt_handshake_timeouts_total 83153
telemt_upstream_connect_attempt_total 23625
telemt_upstream_connect_success_total 23624
telemt_upstream_connect_attempts_per_request{bucket="1"} 23624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 974
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 1486268
telemt_me_route_drop_channel_closed_total 674
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1750798
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 501
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 9313
telemt_desync_full_logged_total 2873
telemt_desync_suppressed_total 6440
telemt_desync_frames_bucket_total{bucket="1_2"} 2561
telemt_desync_frames_bucket_total{bucket="3_10"} 3487
telemt_desync_frames_bucket_total{bucket="gt_10"} 3265
telemt_pool_swap_total 70
telemt_pool_force_close_total 2139
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 21564
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1557
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19425
telemt_me_writer_teardown_success_total{mode="normal"} 21773
telemt_me_writer_teardown_noop_total 21568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.084046
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1747752
telemt_user_connections_current{user="hello"} 1598
telemt_user_octets_from_client{user="hello"} 27592514208 (25.70 GB)
telemt_user_octets_to_client{user="hello"} 504037428868 (469.42 GB)
telemt_user_unique_ips_current{user="hello"} 641
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 76732.7 (21h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3351961
telemt_connections_bad_total 304708
telemt_connections_current 2227
telemt_connections_me_current 2227
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 79127
telemt_upstream_connect_attempt_total 48979
telemt_upstream_connect_success_total 48387
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 48911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5589
telemt_me_reconnect_success_total 1897
telemt_me_reader_eof_total 1821
telemt_me_idle_close_by_peer_total 1821
telemt_me_route_drop_no_conn_total 3250412
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2652410
telemt_me_endpoint_quarantine_total 630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 597
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
telemt_me_writers_active_current 43
telemt_desync_total 10291
telemt_desync_full_logged_total 5723
telemt_desync_suppressed_total 4568
telemt_desync_frames_bucket_total{bucket="1_2"} 2427
telemt_desync_frames_bucket_total{bucket="3_10"} 4066
telemt_desync_frames_bucket_total{bucket="gt_10"} 3798
telemt_pool_swap_total 74
telemt_pool_force_close_total 2144
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 30411
telemt_me_writer_removed_unexpected_total 1779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28662
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28267
telemt_me_writer_teardown_success_total{mode="normal"} 32191
telemt_me_writer_teardown_noop_total 30411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.135237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1609
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2663850
telemt_user_connections_current{user="hello"} 2227
telemt_user_octets_from_client{user="hello"} 31881501551 (29.69 GB)
telemt_user_octets_to_client{user="hello"} 592348500706 (551.67 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1451
telemt_user_unique_ips_recent_window{user="hello"} 854
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 151592.6 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14681896
telemt_connections_bad_total 1301562
telemt_connections_current 5067
telemt_connections_me_current 5067
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 361936
telemt_upstream_connect_attempt_total 69149
telemt_upstream_connect_success_total 69055
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1655
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2532
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 1255
telemt_me_idle_close_by_peer_total 1254
telemt_me_route_drop_no_conn_total 13198917
telemt_me_route_drop_channel_closed_total 132
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11775243
telemt_me_endpoint_quarantine_total 965
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1128
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 47571
telemt_desync_full_logged_total 14980
telemt_desync_suppressed_total 32591
telemt_desync_frames_bucket_total{bucket="1_2"} 10757
telemt_desync_frames_bucket_total{bucket="3_10"} 18632
telemt_desync_frames_bucket_total{bucket="gt_10"} 18182
telemt_pool_swap_total 163
telemt_pool_force_close_total 5547
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 904
telemt_me_draining_writers_reap_progress_total 49959
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4355
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5099
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 448
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44412
telemt_me_writer_teardown_success_total{mode="normal"} 50489
telemt_me_writer_teardown_noop_total 50008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100497
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 286.395217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100497
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 904
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1130
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11776937
telemt_user_connections_current{user="hello"} 5067
telemt_user_octets_from_client{user="hello"} 165451504869 (154.09 GB)
telemt_user_octets_to_client{user="hello"} 3055121999679 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1847
telemt_user_unique_ips_recent_window{user="hello"} 1055
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 151594.3 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10697436
telemt_connections_bad_total 1028316
telemt_connections_current 4606
telemt_connections_me_current 4606
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 317140
telemt_upstream_connect_attempt_total 81167
telemt_upstream_connect_success_total 80021
telemt_upstream_connect_fail_total 823
telemt_upstream_connect_attempts_per_request{bucket="1"} 80844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 823
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3779
telemt_me_reconnect_success_total 1492
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1365
telemt_me_route_drop_no_conn_total 4243490
telemt_me_route_drop_channel_closed_total 463
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7986204
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1151
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
telemt_desync_total 35532
telemt_desync_full_logged_total 11939
telemt_desync_suppressed_total 23593
telemt_desync_frames_bucket_total{bucket="1_2"} 8752
telemt_desync_frames_bucket_total{bucket="3_10"} 13683
telemt_desync_frames_bucket_total{bucket="gt_10"} 13097
telemt_pool_swap_total 162
telemt_pool_force_close_total 5012
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 48166
telemt_me_writer_removed_unexpected_total 1397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4396
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43154
telemt_me_writer_teardown_success_total{mode="normal"} 49420
telemt_me_writer_teardown_noop_total 48181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97601
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 96.545397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97601
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 1263
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 7925246
telemt_user_connections_current{user="hello"} 4606
telemt_user_octets_from_client{user="hello"} 199748568633 (186.03 GB)
telemt_user_octets_to_client{user="hello"} 3569549391842 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1849
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 151561.6 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10146870
telemt_connections_bad_total 861901
telemt_connections_current 4419
telemt_connections_me_current 4419
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 325668
telemt_upstream_connect_attempt_total 66622
telemt_upstream_connect_success_total 65701
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 65883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4537
telemt_me_reconnect_success_total 1844
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 5023795
telemt_me_route_drop_channel_closed_total 345
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7667169
telemt_me_endpoint_quarantine_total 1047
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1110
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 35337
telemt_desync_full_logged_total 11698
telemt_desync_suppressed_total 23639
telemt_desync_frames_bucket_total{bucket="1_2"} 8945
telemt_desync_frames_bucket_total{bucket="3_10"} 13527
telemt_desync_frames_bucket_total{bucket="gt_10"} 12865
telemt_pool_swap_total 158
telemt_pool_force_close_total 4960
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 48785
telemt_me_writer_removed_unexpected_total 1741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4885
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45550
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 532
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43825
telemt_me_writer_teardown_success_total{mode="normal"} 50435
telemt_me_writer_teardown_noop_total 48855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99290
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3167.357302
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99290
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1601
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7660545
telemt_user_connections_current{user="hello"} 4419
telemt_user_octets_from_client{user="hello"} 178336738661 (166.09 GB)
telemt_user_octets_to_client{user="hello"} 3179398596677 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 608
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 21841.4 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9249605
telemt_connections_bad_total 581560
telemt_connections_current 6460
telemt_connections_me_current 6460
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 147620
telemt_upstream_connect_attempt_total 29352
telemt_upstream_connect_success_total 27897
telemt_upstream_connect_fail_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 28931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4760
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1034
telemt_me_keepalive_timeout_total 862
telemt_me_reconnect_attempts_total 5524
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 22842376
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7700038
telemt_me_endpoint_quarantine_total 137
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 11475
telemt_desync_full_logged_total 2942
telemt_desync_suppressed_total 8533
telemt_desync_frames_bucket_total{bucket="1_2"} 2021
telemt_desync_frames_bucket_total{bucket="3_10"} 4623
telemt_desync_frames_bucket_total{bucket="gt_10"} 4831
telemt_pool_swap_total 20
telemt_pool_force_close_total 855
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 305
telemt_me_draining_writers_reap_progress_total 5820
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1009
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5289
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4965
telemt_me_writer_teardown_success_total{mode="normal"} 6298
telemt_me_writer_teardown_noop_total 5824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12122
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.469164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12122
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 305
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7714703
telemt_user_connections_current{user="hello"} 6460
telemt_user_octets_from_client{user="hello"} 44307670831 (41.26 GB)
telemt_user_octets_to_client{user="hello"} 225038759876 (209.58 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2339
telemt_user_unique_ips_recent_window{user="hello"} 2025
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 151564.7 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9872873
telemt_connections_bad_total 819976
telemt_connections_current 4323
telemt_connections_me_current 4323
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 215558
telemt_upstream_connect_attempt_total 91103
telemt_upstream_connect_success_total 90183
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 90980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71500
telemt_me_reconnect_success_total 2481
telemt_me_reader_eof_total 2213
telemt_me_idle_close_by_peer_total 2212
telemt_me_route_drop_no_conn_total 4887567
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7794321
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1129
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 40033
telemt_desync_full_logged_total 13712
telemt_desync_suppressed_total 26321
telemt_desync_frames_bucket_total{bucket="1_2"} 8139
telemt_desync_frames_bucket_total{bucket="3_10"} 15539
telemt_desync_frames_bucket_total{bucket="gt_10"} 16355
telemt_pool_swap_total 155
telemt_pool_force_close_total 4625
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 565
telemt_me_draining_writers_reap_progress_total 51574
telemt_me_writer_removed_unexpected_total 2239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5462
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3973
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 652
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46949
telemt_me_writer_teardown_success_total{mode="normal"} 53831
telemt_me_writer_teardown_noop_total 51575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.047967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 565
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2084
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7794894
telemt_user_connections_current{user="hello"} 4323
telemt_user_octets_from_client{user="hello"} 178232185215 (165.99 GB)
telemt_user_octets_to_client{user="hello"} 2938863727977 (2.67 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1658
telemt_user_unique_ips_recent_window{user="hello"} 660
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 88400.9 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10094569
telemt_connections_bad_total 368985
telemt_connections_current 5311
telemt_connections_me_current 5311
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4251261
telemt_upstream_connect_attempt_total 43182
telemt_upstream_connect_success_total 42868
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 43173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_reconnect_attempts_total 47950
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1131
telemt_me_idle_close_by_peer_total 1131
telemt_me_route_drop_no_conn_total 3767576
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4857001
telemt_me_endpoint_quarantine_total 581
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 664
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 26510
telemt_desync_full_logged_total 8943
telemt_desync_suppressed_total 17567
telemt_desync_frames_bucket_total{bucket="1_2"} 5369
telemt_desync_frames_bucket_total{bucket="3_10"} 10481
telemt_desync_frames_bucket_total{bucket="gt_10"} 10660
telemt_pool_swap_total 93
telemt_pool_force_close_total 2861
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 297
telemt_me_draining_writers_reap_progress_total 30430
telemt_me_writer_removed_unexpected_total 1196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28899
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 413
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27569
telemt_me_writer_teardown_success_total{mode="normal"} 31654
telemt_me_writer_teardown_noop_total 30437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62091
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.293153
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62091
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 297
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1307
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4851128
telemt_user_connections_current{user="hello"} 5311
telemt_user_octets_from_client{user="hello"} 105047201932 (97.83 GB)
telemt_user_octets_to_client{user="hello"} 1829436840338 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2191
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69371.5 (19h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857513
telemt_connections_bad_total 10850
telemt_connections_current 1088
telemt_connections_me_current 1088
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 16637
telemt_upstream_connect_attempt_total 34786
telemt_upstream_connect_success_total 34700
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 34770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 463
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 1565
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 643
telemt_me_idle_close_by_peer_total 643
telemt_me_route_drop_no_conn_total 295061
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763593
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 575
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_writers_warm_current 27
telemt_desync_total 4250
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2967
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1687
telemt_desync_frames_bucket_total{bucket="gt_10"} 1551
telemt_pool_swap_total 73
telemt_pool_force_close_total 1825
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 28624
telemt_me_writer_removed_unexpected_total 622
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2196
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27073
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1747
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26799
telemt_me_writer_teardown_success_total{mode="normal"} 29269
telemt_me_writer_teardown_noop_total 28626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57895
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.185825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57895
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 764777
telemt_user_connections_current{user="hello"} 1088
telemt_user_octets_from_client{user="hello"} 14308285553 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 355942017491 (331.50 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 151569.3 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12071955
telemt_connections_bad_total 1408175
telemt_connections_current 6050
telemt_connections_me_current 6050
telemt_handshake_timeouts_total 330407
telemt_upstream_connect_attempt_total 56865
telemt_upstream_connect_success_total 56642
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 56815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2212
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1150
telemt_me_idle_close_by_peer_total 1150
telemt_me_route_drop_no_conn_total 3930047
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9100544
telemt_me_endpoint_quarantine_total 1029
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1133
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 37348
telemt_desync_full_logged_total 12229
telemt_desync_suppressed_total 25119
telemt_desync_frames_bucket_total{bucket="1_2"} 8897
telemt_desync_frames_bucket_total{bucket="3_10"} 13837
telemt_desync_frames_bucket_total{bucket="gt_10"} 14614
telemt_pool_swap_total 168
telemt_pool_force_close_total 4647
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 51221
telemt_me_writer_removed_unexpected_total 1106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4476
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 171
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46574
telemt_me_writer_teardown_success_total{mode="normal"} 52357
telemt_me_writer_teardown_noop_total 51223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103580
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.521806
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103580
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1042
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 9070267
telemt_user_connections_current{user="hello"} 6050
telemt_user_octets_from_client{user="hello"} 175208254380 (163.18 GB)
telemt_user_octets_to_client{user="hello"} 4040613432912 (3.67 TB)
telemt_user_unique_ips_current{user="hello"} 2178
telemt_user_unique_ips_recent_window{user="hello"} 773
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 151565.9 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10432187
telemt_connections_bad_total 1164765
telemt_connections_current 4983
telemt_connections_me_current 4983
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 270813
telemt_upstream_connect_attempt_total 82429
telemt_upstream_connect_success_total 81815
telemt_upstream_connect_fail_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 82347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2012
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 532
telemt_me_reconnect_attempts_total 8754
telemt_me_reconnect_success_total 1974
telemt_me_reader_eof_total 1838
telemt_me_idle_close_by_peer_total 1838
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4935674
telemt_me_route_drop_channel_closed_total 332
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8050192
telemt_me_endpoint_quarantine_total 1155
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1140
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 36818
telemt_desync_full_logged_total 11939
telemt_desync_suppressed_total 24879
telemt_desync_frames_bucket_total{bucket="1_2"} 9145
telemt_desync_frames_bucket_total{bucket="3_10"} 13717
telemt_desync_frames_bucket_total{bucket="gt_10"} 13956
telemt_pool_swap_total 161
telemt_pool_force_close_total 4504
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 585
telemt_me_draining_writers_reap_progress_total 50518
telemt_me_writer_removed_unexpected_total 1863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5249
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47199
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46014
telemt_me_writer_teardown_success_total{mode="normal"} 52448
telemt_me_writer_teardown_noop_total 50523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102971
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.789374
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102971
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 585
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 8056548
telemt_user_connections_current{user="hello"} 4983
telemt_user_octets_from_client{user="hello"} 141839890773 (132.10 GB)
telemt_user_octets_to_client{user="hello"} 3113798841211 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1945
telemt_user_unique_ips_recent_window{user="hello"} 749
```