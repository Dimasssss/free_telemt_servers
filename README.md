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

# Server Metrics 2026-03-22 16:55:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71317.8 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2542003
telemt_connections_bad_total 136695
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_handshake_timeouts_total 89349
telemt_upstream_connect_attempt_total 26298
telemt_upstream_connect_success_total 26297
telemt_upstream_connect_attempts_per_request{bucket="1"} 26297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1060
telemt_me_reconnect_success_total 450
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 2046026
telemt_me_route_drop_channel_closed_total 854
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2166495
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 560
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10279
telemt_desync_full_logged_total 3237
telemt_desync_suppressed_total 7042
telemt_desync_frames_bucket_total{bucket="1_2"} 2748
telemt_desync_frames_bucket_total{bucket="3_10"} 3840
telemt_desync_frames_bucket_total{bucket="gt_10"} 3691
telemt_pool_swap_total 79
telemt_pool_force_close_total 2457
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 481
telemt_me_draining_writers_reap_progress_total 24028
telemt_me_writer_removed_unexpected_total 439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21571
telemt_me_writer_teardown_success_total{mode="normal"} 24244
telemt_me_writer_teardown_noop_total 24034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 229.781736
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 481
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 2162950
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 32473631288 (30.24 GB)
telemt_user_octets_to_client{user="hello"} 575590300344 (536.06 GB)
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 84684.6 (23h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3632270
telemt_connections_bad_total 329565
telemt_connections_current 1152
telemt_connections_me_current 1152
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 90745
telemt_upstream_connect_attempt_total 52915
telemt_upstream_connect_success_total 52266
telemt_upstream_connect_fail_total 577
telemt_upstream_connect_attempts_per_request{bucket="1"} 52843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 577
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6111
telemt_me_reconnect_success_total 2216
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2155
telemt_me_route_drop_no_conn_total 3540945
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2880037
telemt_me_endpoint_quarantine_total 672
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 651
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_warm_current 18
telemt_desync_total 11301
telemt_desync_full_logged_total 6304
telemt_desync_suppressed_total 4997
telemt_desync_frames_bucket_total{bucket="1_2"} 2632
telemt_desync_frames_bucket_total{bucket="3_10"} 4432
telemt_desync_frames_bucket_total{bucket="gt_10"} 4237
telemt_pool_swap_total 79
telemt_pool_force_close_total 2375
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 199
telemt_me_draining_writers_reap_progress_total 33740
telemt_me_writer_removed_unexpected_total 2108
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4032
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31824
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2017
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31365
telemt_me_writer_teardown_success_total{mode="normal"} 35856
telemt_me_writer_teardown_noop_total 33740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69596
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.020441
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69596
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 199
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 1923
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 2891290
telemt_user_connections_current{user="hello"} 1152
telemt_user_octets_from_client{user="hello"} 36222040235 (33.73 GB)
telemt_user_octets_to_client{user="hello"} 651083793762 (606.37 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 159543.9 (44h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15412870
telemt_connections_bad_total 1447961
telemt_connections_current 2088
telemt_connections_me_current 2088
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 375725
telemt_upstream_connect_attempt_total 71947
telemt_upstream_connect_success_total 71851
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2680
telemt_me_reconnect_success_total 1371
telemt_me_reader_eof_total 1310
telemt_me_idle_close_by_peer_total 1308
telemt_me_route_drop_no_conn_total 13827889
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12308149
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1191
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
telemt_desync_total 50226
telemt_desync_full_logged_total 15780
telemt_desync_suppressed_total 34446
telemt_desync_frames_bucket_total{bucket="1_2"} 11224
telemt_desync_frames_bucket_total{bucket="3_10"} 19615
telemt_desync_frames_bucket_total{bucket="gt_10"} 19387
telemt_pool_swap_total 172
telemt_pool_force_close_total 5849
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 943
telemt_me_draining_writers_reap_progress_total 52500
telemt_me_writer_removed_unexpected_total 1264
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5389
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46651
telemt_me_writer_teardown_success_total{mode="normal"} 53055
telemt_me_writer_teardown_noop_total 52550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.809189
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 943
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12309239
telemt_user_connections_current{user="hello"} 2088
telemt_user_octets_from_client{user="hello"} 175862083769 (163.78 GB)
telemt_user_octets_to_client{user="hello"} 3190297382627 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 792
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 159546.1 (44h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11118396
telemt_connections_bad_total 1080786
telemt_connections_current 1551
telemt_connections_me_current 1551
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 330720
telemt_upstream_connect_attempt_total 84156
telemt_upstream_connect_success_total 82998
telemt_upstream_connect_fail_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 83832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 834
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3950
telemt_me_reconnect_success_total 1613
telemt_me_reader_eof_total 1485
telemt_me_idle_close_by_peer_total 1485
telemt_me_route_drop_no_conn_total 4374972
telemt_me_route_drop_channel_closed_total 480
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8291866
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1207
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
telemt_me_writers_active_current 43
telemt_desync_total 36858
telemt_desync_full_logged_total 12394
telemt_desync_suppressed_total 24464
telemt_desync_frames_bucket_total{bucket="1_2"} 9047
telemt_desync_frames_bucket_total{bucket="3_10"} 14209
telemt_desync_frames_bucket_total{bucket="gt_10"} 13602
telemt_pool_swap_total 170
telemt_pool_force_close_total 5273
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 50797
telemt_me_writer_removed_unexpected_total 1513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47488
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4795
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45524
telemt_me_writer_teardown_success_total{mode="normal"} 52171
telemt_me_writer_teardown_noop_total 50815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.290257
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1375
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8230461
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 205636985245 (191.51 GB)
telemt_user_octets_to_client{user="hello"} 3708684259874 (3.37 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 159510.9 (44h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10507967
telemt_connections_bad_total 906734
telemt_connections_current 1020
telemt_connections_me_current 1020
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 335990
telemt_upstream_connect_attempt_total 69346
telemt_upstream_connect_success_total 68369
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2088
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4750
telemt_me_reconnect_success_total 1916
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 5150332
telemt_me_route_drop_channel_closed_total 363
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7928997
telemt_me_endpoint_quarantine_total 1093
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1175
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36322
telemt_desync_full_logged_total 12026
telemt_desync_suppressed_total 24296
telemt_desync_frames_bucket_total{bucket="1_2"} 9198
telemt_desync_frames_bucket_total{bucket="3_10"} 13881
telemt_desync_frames_bucket_total{bucket="gt_10"} 13243
telemt_pool_swap_total 167
telemt_pool_force_close_total 5215
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 51125
telemt_me_writer_removed_unexpected_total 1809
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5138
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47709
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45910
telemt_me_writer_teardown_success_total{mode="normal"} 52847
telemt_me_writer_teardown_noop_total 51196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104043
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.809181
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104043
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 150
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 7921882
telemt_user_connections_current{user="hello"} 1020
telemt_user_octets_from_client{user="hello"} 183163724949 (170.58 GB)
telemt_user_octets_to_client{user="hello"} 3293863646645 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 29790.0 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10245796
telemt_connections_bad_total 625489
telemt_connections_current 2315
telemt_connections_me_current 2315
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 194605
telemt_upstream_connect_attempt_total 36405
telemt_upstream_connect_success_total 34596
telemt_upstream_connect_fail_total 1258
telemt_upstream_connect_attempts_per_request{bucket="1"} 35854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5308
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1258
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5903
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 24971143
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8526371
telemt_me_endpoint_quarantine_total 179
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_warm_current 35
telemt_desync_total 13362
telemt_desync_full_logged_total 3459
telemt_desync_suppressed_total 9903
telemt_desync_frames_bucket_total{bucket="1_2"} 2402
telemt_desync_frames_bucket_total{bucket="3_10"} 5427
telemt_desync_frames_bucket_total{bucket="gt_10"} 5533
telemt_pool_swap_total 28
telemt_pool_force_close_total 1097
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 8203
telemt_me_writer_removed_unexpected_total 625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1315
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 817
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7106
telemt_me_writer_teardown_success_total{mode="normal"} 8793
telemt_me_writer_teardown_noop_total 8208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17001
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.452354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17001
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8544439
telemt_user_connections_current{user="hello"} 2315
telemt_user_octets_from_client{user="hello"} 65834359994 (61.31 GB)
telemt_user_octets_to_client{user="hello"} 328830287820 (306.25 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 811
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 159516.2 (44h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10304221
telemt_connections_bad_total 865575
telemt_connections_current 1480
telemt_connections_me_current 1480
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228698
telemt_upstream_connect_attempt_total 98107
telemt_upstream_connect_success_total 97093
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 97957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1310
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72052
telemt_me_reconnect_success_total 2634
telemt_me_reader_eof_total 2337
telemt_me_idle_close_by_peer_total 2335
telemt_me_route_drop_no_conn_total 5079249
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8126650
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1189
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 42418
telemt_desync_full_logged_total 14474
telemt_desync_suppressed_total 27944
telemt_desync_frames_bucket_total{bucket="1_2"} 8612
telemt_desync_frames_bucket_total{bucket="3_10"} 16399
telemt_desync_frames_bucket_total{bucket="gt_10"} 17407
telemt_pool_swap_total 163
telemt_pool_force_close_total 4850
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 54270
telemt_me_writer_removed_unexpected_total 2380
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5801
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50870
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49420
telemt_me_writer_teardown_success_total{mode="normal"} 56671
telemt_me_writer_teardown_noop_total 54271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110942
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.523991
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110942
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2206
telemt_me_writer_restored_fallback_total 45
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8130503
telemt_user_connections_current{user="hello"} 1480
telemt_user_octets_from_client{user="hello"} 183856278193 (171.23 GB)
telemt_user_octets_to_client{user="hello"} 3064137666136 (2.79 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 96352.4 (26h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10739196
telemt_connections_bad_total 405279
telemt_connections_current 1842
telemt_connections_me_current 1842
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4500491
telemt_upstream_connect_attempt_total 46280
telemt_upstream_connect_success_total 45942
telemt_upstream_connect_fail_total 329
telemt_upstream_connect_attempts_per_request{bucket="1"} 46271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 329
telemt_me_reconnect_attempts_total 48149
telemt_me_reconnect_success_total 1525
telemt_me_reader_eof_total 1191
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 3931972
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5149634
telemt_me_endpoint_quarantine_total 623
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 723
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
telemt_me_writers_warm_current 10
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28322
telemt_desync_full_logged_total 9575
telemt_desync_suppressed_total 18747
telemt_desync_frames_bucket_total{bucket="1_2"} 5712
telemt_desync_frames_bucket_total{bucket="3_10"} 11168
telemt_desync_frames_bucket_total{bucket="gt_10"} 11442
telemt_pool_swap_total 101
telemt_pool_force_close_total 3106
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 33188
telemt_me_writer_removed_unexpected_total 1254
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2974
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2687
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30082
telemt_me_writer_teardown_success_total{mode="normal"} 34472
telemt_me_writer_teardown_noop_total 33195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67667
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.920088
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67667
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 2710
telemt_me_writer_restored_same_endpoint_total 1356
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5143106
telemt_user_connections_current{user="hello"} 1842
telemt_user_octets_from_client{user="hello"} 110955673380 (103.34 GB)
telemt_user_octets_to_client{user="hello"} 1944200543614 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 77323.0 (21h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059033
telemt_connections_bad_total 15854
telemt_connections_current 1254
telemt_connections_me_current 1254
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20124
telemt_upstream_connect_attempt_total 37737
telemt_upstream_connect_success_total 37635
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 37716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 1730
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 370308
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943073
telemt_me_endpoint_quarantine_total 657
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 637
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5371
telemt_desync_full_logged_total 1644
telemt_desync_suppressed_total 3727
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 2125
telemt_desync_frames_bucket_total{bucket="gt_10"} 1990
telemt_pool_swap_total 82
telemt_pool_force_close_total 2085
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 31281
telemt_me_writer_removed_unexpected_total 673
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29196
telemt_me_writer_teardown_success_total{mode="normal"} 31980
telemt_me_writer_teardown_noop_total 31284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.769732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 615
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 939592
telemt_user_connections_current{user="hello"} 1254
telemt_user_octets_from_client{user="hello"} 16994514529 (15.83 GB)
telemt_user_octets_to_client{user="hello"} 410423026655 (382.24 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 159521.0 (44h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12580622
telemt_connections_bad_total 1458487
telemt_connections_current 1566
telemt_connections_me_current 1566
telemt_handshake_timeouts_total 348488
telemt_upstream_connect_attempt_total 59943
telemt_upstream_connect_success_total 59683
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 59868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_reconnect_attempts_total 2368
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 1213
telemt_me_idle_close_by_peer_total 1213
telemt_me_route_drop_no_conn_total 4200764
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9515317
telemt_me_endpoint_quarantine_total 1072
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1191
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
telemt_me_writers_active_current 42
telemt_desync_total 39049
telemt_desync_full_logged_total 12748
telemt_desync_suppressed_total 26301
telemt_desync_frames_bucket_total{bucket="1_2"} 9286
telemt_desync_frames_bucket_total{bucket="3_10"} 14467
telemt_desync_frames_bucket_total{bucket="gt_10"} 15296
telemt_pool_swap_total 177
telemt_pool_force_close_total 4891
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 624
telemt_me_draining_writers_reap_progress_total 53972
telemt_me_writer_removed_unexpected_total 1165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4439
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4717
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49081
telemt_me_writer_teardown_success_total{mode="normal"} 55171
telemt_me_writer_teardown_noop_total 53974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.354937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 624
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1091
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9484504
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 186089037924 (173.31 GB)
telemt_user_octets_to_client{user="hello"} 4188906661068 (3.81 TB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 159517.2 (44h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10906869
telemt_connections_bad_total 1217501
telemt_connections_current 1727
telemt_connections_me_current 1727
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 281361
telemt_upstream_connect_attempt_total 85791
telemt_upstream_connect_success_total 85103
telemt_upstream_connect_fail_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 85671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 568
telemt_me_reconnect_attempts_total 9029
telemt_me_reconnect_success_total 2091
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5446086
telemt_me_route_drop_channel_closed_total 349
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8436796
telemt_me_endpoint_quarantine_total 1219
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38465
telemt_desync_full_logged_total 12426
telemt_desync_suppressed_total 26039
telemt_desync_frames_bucket_total{bucket="1_2"} 9569
telemt_desync_frames_bucket_total{bucket="3_10"} 14328
telemt_desync_frames_bucket_total{bucket="gt_10"} 14568
telemt_pool_swap_total 169
telemt_pool_force_close_total 4699
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 53434
telemt_me_writer_removed_unexpected_total 1972
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5539
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49937
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4260
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48735
telemt_me_writer_teardown_success_total{mode="normal"} 55476
telemt_me_writer_teardown_noop_total 53439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108915
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.610307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108915
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 8442749
telemt_user_connections_current{user="hello"} 1727
telemt_user_octets_from_client{user="hello"} 148561063321 (138.36 GB)
telemt_user_octets_to_client{user="hello"} 3226360984183 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 687
telemt_user_unique_ips_recent_window{user="hello"} 298
```