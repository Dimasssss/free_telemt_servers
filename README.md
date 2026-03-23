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

# Server Metrics 2026-03-23 05:41:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 117296.7 (32h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4170572
telemt_connections_bad_total 396541
telemt_connections_current 1506
telemt_connections_me_current 1506
telemt_handshake_timeouts_total 138872
telemt_upstream_connect_attempt_total 43668
telemt_upstream_connect_success_total 43667
telemt_upstream_connect_attempts_per_request{bucket="1"} 43667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1537
telemt_me_reconnect_success_total 682
telemt_me_reader_eof_total 705
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 3436425
telemt_me_route_drop_channel_closed_total 1330
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3414576
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 918
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
telemt_me_writers_active_current 44
telemt_desync_total 14104
telemt_desync_full_logged_total 4477
telemt_desync_suppressed_total 9627
telemt_desync_frames_bucket_total{bucket="1_2"} 3655
telemt_desync_frames_bucket_total{bucket="3_10"} 5237
telemt_desync_frames_bucket_total{bucket="gt_10"} 5212
telemt_pool_swap_total 130
telemt_pool_force_close_total 3976
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 758
telemt_me_draining_writers_reap_progress_total 40017
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37427
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36041
telemt_me_writer_teardown_success_total{mode="normal"} 40295
telemt_me_writer_teardown_noop_total 40030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 435.589919
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 758
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 3401978
telemt_user_connections_current{user="hello"} 1506
telemt_user_octets_from_client{user="hello"} 45494457428 (42.37 GB)
telemt_user_octets_to_client{user="hello"} 893129913020 (831.79 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 130663.2 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4161374
telemt_connections_bad_total 386547
telemt_connections_current 898
telemt_connections_me_current 898
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 108211
telemt_upstream_connect_attempt_total 81363
telemt_upstream_connect_success_total 80381
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 81251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10971
telemt_me_reconnect_success_total 3934
telemt_me_reader_eof_total 3904
telemt_me_idle_close_by_peer_total 3903
telemt_me_route_drop_no_conn_total 3672916
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3299853
telemt_me_endpoint_quarantine_total 1063
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1026
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
telemt_me_writers_active_current 62
telemt_me_writers_warm_current 26
telemt_desync_total 13573
telemt_desync_full_logged_total 7652
telemt_desync_suppressed_total 5921
telemt_desync_frames_bucket_total{bucket="1_2"} 3089
telemt_desync_frames_bucket_total{bucket="3_10"} 5321
telemt_desync_frames_bucket_total{bucket="gt_10"} 5163
telemt_pool_swap_total 123
telemt_pool_force_close_total 3417
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54701
telemt_me_writer_removed_unexpected_total 3826
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6911
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2932
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51284
telemt_me_writer_teardown_success_total{mode="normal"} 58569
telemt_me_writer_teardown_noop_total 54702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113271
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.953759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113271
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 278
telemt_me_writer_restored_same_endpoint_total 3481
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 3314281
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 44611573911 (41.55 GB)
telemt_user_octets_to_client{user="hello"} 836547474325 (779.10 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 205523.3 (57h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16690447
telemt_connections_bad_total 1689945
telemt_connections_current 1482
telemt_connections_me_current 1482
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 408941
telemt_upstream_connect_attempt_total 92281
telemt_upstream_connect_success_total 92169
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3266
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1653
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 14122539
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13259880
telemt_me_endpoint_quarantine_total 1396
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 55347
telemt_desync_full_logged_total 17697
telemt_desync_suppressed_total 37650
telemt_desync_frames_bucket_total{bucket="1_2"} 12339
telemt_desync_frames_bucket_total{bucket="3_10"} 21693
telemt_desync_frames_bucket_total{bucket="gt_10"} 21315
telemt_pool_swap_total 223
telemt_pool_force_close_total 7150
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1106
telemt_me_draining_writers_reap_progress_total 71071
telemt_me_writer_removed_unexpected_total 1586
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65979
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63921
telemt_me_writer_teardown_success_total{mode="normal"} 71943
telemt_me_writer_teardown_noop_total 71125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.327341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1106
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1466
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13259681
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 200678834709 (186.90 GB)
telemt_user_octets_to_client{user="hello"} 3600635492795 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 205524.6 (57h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12192416
telemt_connections_bad_total 1293262
telemt_connections_current 1064
telemt_connections_me_current 1064
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 353100
telemt_upstream_connect_attempt_total 106703
telemt_upstream_connect_success_total 105290
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 106190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4714
telemt_me_reconnect_success_total 2026
telemt_me_reader_eof_total 1890
telemt_me_idle_close_by_peer_total 1890
telemt_me_route_drop_no_conn_total 4614397
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9017195
telemt_me_endpoint_quarantine_total 1404
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1574
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 39673
telemt_desync_full_logged_total 13389
telemt_desync_suppressed_total 26284
telemt_desync_frames_bucket_total{bucket="1_2"} 9844
telemt_desync_frames_bucket_total{bucket="3_10"} 15224
telemt_desync_frames_bucket_total{bucket="gt_10"} 14605
telemt_pool_swap_total 220
telemt_pool_force_close_total 6493
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 69194
telemt_me_writer_removed_unexpected_total 1920
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64914
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5981
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62701
telemt_me_writer_teardown_success_total{mode="normal"} 70977
telemt_me_writer_teardown_noop_total 69219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.714357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1731
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8954730
telemt_user_connections_current{user="hello"} 1064
telemt_user_octets_from_client{user="hello"} 220552985948 (205.41 GB)
telemt_user_octets_to_client{user="hello"} 4035180271935 (3.67 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 205488.4 (57h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11342327
telemt_connections_bad_total 1041458
telemt_connections_current 956
telemt_connections_me_current 956
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 358856
telemt_upstream_connect_attempt_total 91134
telemt_upstream_connect_success_total 89557
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5916
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2237
telemt_me_route_drop_no_conn_total 5383773
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8525676
telemt_me_endpoint_quarantine_total 1454
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1538
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 38786
telemt_desync_full_logged_total 12883
telemt_desync_suppressed_total 25903
telemt_desync_frames_bucket_total{bucket="1_2"} 9786
telemt_desync_frames_bucket_total{bucket="3_10"} 14853
telemt_desync_frames_bucket_total{bucket="gt_10"} 14147
telemt_pool_swap_total 216
telemt_pool_force_close_total 6381
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 763
telemt_me_draining_writers_reap_progress_total 69814
telemt_me_writer_removed_unexpected_total 2383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5807
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63433
telemt_me_writer_teardown_success_total{mode="normal"} 72134
telemt_me_writer_teardown_noop_total 69885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.978862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 763
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2172
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8517440
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 194323241859 (180.98 GB)
telemt_user_octets_to_client{user="hello"} 3532457652701 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 75768.4 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11709417
telemt_connections_bad_total 708311
telemt_connections_current 2019
telemt_connections_me_current 2019
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 320742
telemt_upstream_connect_attempt_total 67799
telemt_upstream_connect_success_total 64212
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 66531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2319
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8464
telemt_me_reconnect_success_total 1578
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 25384914
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9674345
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 611
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
telemt_me_writers_active_current 42
telemt_desync_total 17404
telemt_desync_full_logged_total 4876
telemt_desync_suppressed_total 12528
telemt_desync_frames_bucket_total{bucket="1_2"} 3366
telemt_desync_frames_bucket_total{bucket="3_10"} 7125
telemt_desync_frames_bucket_total{bucket="gt_10"} 6913
telemt_pool_swap_total 78
telemt_pool_force_close_total 2418
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 532
telemt_me_draining_writers_reap_progress_total 25124
telemt_me_writer_removed_unexpected_total 1455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23274
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22706
telemt_me_writer_teardown_success_total{mode="normal"} 26531
telemt_me_writer_teardown_noop_total 25143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.136115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 532
telemt_me_refill_failed_total 350
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 9701857
telemt_user_connections_current{user="hello"} 2019
telemt_user_octets_from_client{user="hello"} 91035164499 (84.78 GB)
telemt_user_octets_to_client{user="hello"} 735559724517 (685.04 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 205494.8 (57h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11311510
telemt_connections_bad_total 995041
telemt_connections_current 1115
telemt_connections_me_current 1115
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 254998
telemt_upstream_connect_attempt_total 120103
telemt_upstream_connect_success_total 118840
telemt_upstream_connect_fail_total 1086
telemt_upstream_connect_attempts_per_request{bucket="1"} 119926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1086
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73586
telemt_me_reconnect_success_total 3282
telemt_me_reader_eof_total 2967
telemt_me_idle_close_by_peer_total 2964
telemt_me_route_drop_no_conn_total 5327156
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8905087
telemt_me_endpoint_quarantine_total 1399
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 47
telemt_me_single_endpoint_outage_reconnect_success_total 45
telemt_me_single_endpoint_quarantine_bypass_total 47
telemt_me_single_endpoint_shadow_rotate_total 1563
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 47445
telemt_desync_full_logged_total 16317
telemt_desync_suppressed_total 31128
telemt_desync_frames_bucket_total{bucket="1_2"} 9646
telemt_desync_frames_bucket_total{bucket="3_10"} 18188
telemt_desync_frames_bucket_total{bucket="gt_10"} 19611
telemt_pool_swap_total 212
telemt_pool_force_close_total 6096
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 73903
telemt_me_writer_removed_unexpected_total 2984
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67807
telemt_me_writer_teardown_success_total{mode="normal"} 76934
telemt_me_writer_teardown_noop_total 73904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.388707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 4323
telemt_me_writer_restored_same_endpoint_total 2760
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7371
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8907680
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 199343731613 (185.65 GB)
telemt_user_octets_to_client{user="hello"} 3409933536640 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 142331.2 (39h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12100459
telemt_connections_bad_total 494211
telemt_connections_current 1373
telemt_connections_me_current 1373
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4881908
telemt_upstream_connect_attempt_total 69062
telemt_upstream_connect_success_total 68572
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 69049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_reconnect_attempts_total 49387
telemt_me_reconnect_success_total 1973
telemt_me_reader_eof_total 1659
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 4149077
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5815058
telemt_me_endpoint_quarantine_total 982
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1098
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32718
telemt_desync_full_logged_total 11192
telemt_desync_suppressed_total 21526
telemt_desync_frames_bucket_total{bucket="1_2"} 6585
telemt_desync_frames_bucket_total{bucket="3_10"} 12872
telemt_desync_frames_bucket_total{bucket="gt_10"} 13261
telemt_pool_swap_total 152
telemt_pool_force_close_total 4265
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 53819
telemt_me_writer_removed_unexpected_total 1696
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4251
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3821
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49554
telemt_me_writer_teardown_success_total{mode="normal"} 55573
telemt_me_writer_teardown_noop_total 53826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.837135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 2754
telemt_me_writer_restored_same_endpoint_total 1743
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5806899
telemt_user_connections_current{user="hello"} 1373
telemt_user_octets_from_client{user="hello"} 121962077328 (113.59 GB)
telemt_user_octets_to_client{user="hello"} 2260856902102 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 123301.5 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1711931
telemt_connections_bad_total 37624
telemt_connections_current 754
telemt_connections_me_current 754
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37369
telemt_upstream_connect_attempt_total 58013
telemt_upstream_connect_success_total 57821
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 57975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 851
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2517
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 1017
telemt_me_idle_close_by_peer_total 1017
telemt_me_route_drop_no_conn_total 577978
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1520379
telemt_me_endpoint_quarantine_total 1046
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1017
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
telemt_desync_total 10437
telemt_desync_full_logged_total 2950
telemt_desync_suppressed_total 7487
telemt_desync_frames_bucket_total{bucket="1_2"} 3302
telemt_desync_frames_bucket_total{bucket="3_10"} 3908
telemt_desync_frames_bucket_total{bucket="gt_10"} 3227
telemt_pool_swap_total 133
telemt_pool_force_close_total 3361
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49469
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3732
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46764
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46108
telemt_me_writer_teardown_success_total{mode="normal"} 50496
telemt_me_writer_teardown_noop_total 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.715174
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1515936
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 27758182865 (25.85 GB)
telemt_user_octets_to_client{user="hello"} 618231870423 (575.77 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 205499.6 (57h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13592232
telemt_connections_bad_total 1641782
telemt_connections_current 1418
telemt_connections_me_current 1418
telemt_handshake_timeouts_total 398561
telemt_upstream_connect_attempt_total 82941
telemt_upstream_connect_success_total 82574
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 82804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3284
telemt_me_reconnect_success_total 1631
telemt_me_reader_eof_total 1623
telemt_me_idle_close_by_peer_total 1623
telemt_me_route_drop_no_conn_total 4535405
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10250800
telemt_me_endpoint_quarantine_total 1526
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1562
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 43064
telemt_desync_full_logged_total 14049
telemt_desync_suppressed_total 29015
telemt_desync_frames_bucket_total{bucket="1_2"} 10482
telemt_desync_frames_bucket_total{bucket="3_10"} 15811
telemt_desync_frames_bucket_total{bucket="gt_10"} 16771
telemt_pool_swap_total 228
telemt_pool_force_close_total 5946
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 75099
telemt_me_writer_removed_unexpected_total 1552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70946
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5772
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69153
telemt_me_writer_teardown_success_total{mode="normal"} 76712
telemt_me_writer_teardown_noop_total 75101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151813
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.055334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151813
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1433
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10217193
telemt_user_connections_current{user="hello"} 1418
telemt_user_octets_from_client{user="hello"} 197185359304 (183.64 GB)
telemt_user_octets_to_client{user="hello"} 4558085424760 (4.15 TB)
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 205496.3 (57h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11905535
telemt_connections_bad_total 1389378
telemt_connections_current 1224
telemt_connections_me_current 1224
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 320662
telemt_upstream_connect_attempt_total 110855
telemt_upstream_connect_success_total 109903
telemt_upstream_connect_fail_total 743
telemt_upstream_connect_attempts_per_request{bucket="1"} 110646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 743
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11121
telemt_me_reconnect_success_total 2768
telemt_me_reader_eof_total 2572
telemt_me_idle_close_by_peer_total 2571
telemt_me_seq_mismatch_total 108
telemt_me_route_drop_no_conn_total 5703818
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9171193
telemt_me_endpoint_quarantine_total 1701
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1568
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42671
telemt_desync_full_logged_total 13743
telemt_desync_suppressed_total 28928
telemt_desync_frames_bucket_total{bucket="1_2"} 11083
telemt_desync_frames_bucket_total{bucket="3_10"} 15673
telemt_desync_frames_bucket_total{bucket="gt_10"} 15915
telemt_pool_swap_total 218
telemt_pool_force_close_total 5695
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 686
telemt_me_draining_writers_reap_progress_total 75490
telemt_me_writer_removed_unexpected_total 2607
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7182
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71017
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5224
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69795
telemt_me_writer_teardown_success_total{mode="normal"} 78199
telemt_me_writer_teardown_noop_total 75495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.850188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 686
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 2207
telemt_me_writer_restored_fallback_total 143
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 9175554
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 159799053168 (148.82 GB)
telemt_user_octets_to_client{user="hello"} 3592118211162 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 167
```