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

# Server Metrics 2026-03-23 01:51:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 103516.0 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3570479
telemt_connections_bad_total 324836
telemt_connections_current 924
telemt_connections_me_current 924
telemt_handshake_timeouts_total 112200
telemt_upstream_connect_attempt_total 38553
telemt_upstream_connect_success_total 38552
telemt_upstream_connect_attempts_per_request{bucket="1"} 38552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1409
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 629
telemt_me_idle_close_by_peer_total 629
telemt_me_route_drop_no_conn_total 2991575
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2938694
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 727
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 806
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
telemt_me_writers_active_current 44
telemt_desync_total 12631
telemt_desync_full_logged_total 3979
telemt_desync_suppressed_total 8652
telemt_desync_frames_bucket_total{bucket="1_2"} 3380
telemt_desync_frames_bucket_total{bucket="3_10"} 4605
telemt_desync_frames_bucket_total{bucket="gt_10"} 4646
telemt_pool_swap_total 114
telemt_pool_force_close_total 3503
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 35292
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33028
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3447
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31789
telemt_me_writer_teardown_success_total{mode="normal"} 35547
telemt_me_writer_teardown_noop_total 35303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.729187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2927704
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 41829943124 (38.96 GB)
telemt_user_octets_to_client{user="hello"} 801916621644 (746.84 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 116882.2 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4012564
telemt_connections_bad_total 370789
telemt_connections_current 429
telemt_connections_me_current 429
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100908
telemt_upstream_connect_attempt_total 72828
telemt_upstream_connect_success_total 71942
telemt_upstream_connect_fail_total 781
telemt_upstream_connect_attempts_per_request{bucket="1"} 72723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 781
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10170
telemt_me_reconnect_success_total 3660
telemt_me_reader_eof_total 3648
telemt_me_idle_close_by_peer_total 3648
telemt_me_route_drop_no_conn_total 3642233
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3187454
telemt_me_endpoint_quarantine_total 938
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 913
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
telemt_me_writers_active_current 44
telemt_desync_total 12994
telemt_desync_full_logged_total 7292
telemt_desync_suppressed_total 5702
telemt_desync_frames_bucket_total{bucket="1_2"} 2947
telemt_desync_frames_bucket_total{bucket="3_10"} 5100
telemt_desync_frames_bucket_total{bucket="gt_10"} 4947
telemt_pool_swap_total 109
telemt_pool_force_close_total 3119
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 48241
telemt_me_writer_removed_unexpected_total 3577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45559
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45122
telemt_me_writer_teardown_success_total{mode="normal"} 51852
telemt_me_writer_teardown_noop_total 48242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100094
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.634419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100094
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3259
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 3200751
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 43209380083 (40.24 GB)
telemt_user_octets_to_client{user="hello"} 794042138664 (739.51 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 191742.1 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16368640
telemt_connections_bad_total 1657901
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397975
telemt_upstream_connect_attempt_total 86071
telemt_upstream_connect_success_total 85965
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3021
telemt_me_reconnect_success_total 1597
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1544
telemt_me_route_drop_no_conn_total 14049889
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12996153
telemt_me_endpoint_quarantine_total 1278
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1442
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_warm_current 14
telemt_desync_total 53919
telemt_desync_full_logged_total 17139
telemt_desync_suppressed_total 36780
telemt_desync_frames_bucket_total{bucket="1_2"} 12020
telemt_desync_frames_bucket_total{bucket="3_10"} 21055
telemt_desync_frames_bucket_total{bucket="gt_10"} 20844
telemt_pool_swap_total 207
telemt_pool_force_close_total 6763
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1064
telemt_me_draining_writers_reap_progress_total 65361
telemt_me_writer_removed_unexpected_total 1487
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58598
telemt_me_writer_teardown_success_total{mode="normal"} 66126
telemt_me_writer_teardown_noop_total 65414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.813377
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1064
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1382
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 12996167
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 197191094137 (183.65 GB)
telemt_user_octets_to_client{user="hello"} 3497839999927 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 191743.4 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11908769
telemt_connections_bad_total 1240685
telemt_connections_current 516
telemt_connections_me_current 516
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344685
telemt_upstream_connect_attempt_total 100426
telemt_upstream_connect_success_total 99098
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 99973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4450
telemt_me_reconnect_success_total 1900
telemt_me_reader_eof_total 1766
telemt_me_idle_close_by_peer_total 1766
telemt_me_route_drop_no_conn_total 4559344
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8836712
telemt_me_endpoint_quarantine_total 1286
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1461
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 12
telemt_desync_total 38944
telemt_desync_full_logged_total 13117
telemt_desync_suppressed_total 25827
telemt_desync_frames_bucket_total{bucket="1_2"} 9649
telemt_desync_frames_bucket_total{bucket="3_10"} 14949
telemt_desync_frames_bucket_total{bucket="gt_10"} 14346
telemt_pool_swap_total 204
telemt_pool_force_close_total 6119
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 63579
telemt_me_writer_removed_unexpected_total 1795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5644
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57460
telemt_me_writer_teardown_success_total{mode="normal"} 65231
telemt_me_writer_teardown_noop_total 63604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.448037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1626
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8774465
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 217977590068 (203.01 GB)
telemt_user_octets_to_client{user="hello"} 3968190404999 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 191707.4 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11079069
telemt_connections_bad_total 979569
telemt_connections_current 559
telemt_connections_me_current 559
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345655
telemt_upstream_connect_attempt_total 84726
telemt_upstream_connect_success_total 83167
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 83372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5768
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2133
telemt_me_idle_close_by_peer_total 2132
telemt_me_route_drop_no_conn_total 5340211
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8372202
telemt_me_endpoint_quarantine_total 1345
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1420
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38217
telemt_desync_full_logged_total 12658
telemt_desync_suppressed_total 25559
telemt_desync_frames_bucket_total{bucket="1_2"} 9653
telemt_desync_frames_bucket_total{bucket="3_10"} 14626
telemt_desync_frames_bucket_total{bucket="gt_10"} 13938
telemt_pool_swap_total 200
telemt_pool_force_close_total 6019
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 743
telemt_me_draining_writers_reap_progress_total 63996
telemt_me_writer_removed_unexpected_total 2283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57977
telemt_me_writer_teardown_success_total{mode="normal"} 66211
telemt_me_writer_teardown_noop_total 64067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.823164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 743
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2078
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8364155
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 192847379955 (179.60 GB)
telemt_user_octets_to_client{user="hello"} 3475168775885 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61987.6 (17h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11288006
telemt_connections_bad_total 669285
telemt_connections_current 916
telemt_connections_me_current 916
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 278301
telemt_upstream_connect_attempt_total 59129
telemt_upstream_connect_success_total 56036
telemt_upstream_connect_fail_total 2036
telemt_upstream_connect_attempts_per_request{bucket="1"} 58072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2036
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7799
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 798
telemt_me_route_drop_no_conn_total 25295828
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9362491
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 497
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
telemt_me_writers_active_current 45
telemt_desync_total 16428
telemt_desync_full_logged_total 4490
telemt_desync_suppressed_total 11938
telemt_desync_frames_bucket_total{bucket="1_2"} 3119
telemt_desync_frames_bucket_total{bucket="3_10"} 6697
telemt_desync_frames_bucket_total{bucket="gt_10"} 6612
telemt_pool_swap_total 64
telemt_pool_force_close_total 2065
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 19639
telemt_me_writer_removed_unexpected_total 1155
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2622
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17574
telemt_me_writer_teardown_success_total{mode="normal"} 20738
telemt_me_writer_teardown_noop_total 19658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40396
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.926843
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40396
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 815
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9388352
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 87526723710 (81.52 GB)
telemt_user_octets_to_client{user="hello"} 617907883622 (575.47 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 191714.1 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11030006
telemt_connections_bad_total 963644
telemt_connections_current 771
telemt_connections_me_current 771
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242581
telemt_upstream_connect_attempt_total 113533
telemt_upstream_connect_success_total 112364
telemt_upstream_connect_fail_total 995
telemt_upstream_connect_attempts_per_request{bucket="1"} 113359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 995
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73020
telemt_me_reconnect_success_total 3105
telemt_me_reader_eof_total 2798
telemt_me_idle_close_by_peer_total 2796
telemt_me_route_drop_no_conn_total 5266720
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8694033
telemt_me_endpoint_quarantine_total 1299
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1448
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
telemt_me_writers_active_current 41
telemt_desync_total 46318
telemt_desync_full_logged_total 15882
telemt_desync_suppressed_total 30436
telemt_desync_frames_bucket_total{bucket="1_2"} 9411
telemt_desync_frames_bucket_total{bucket="3_10"} 17728
telemt_desync_frames_bucket_total{bucket="gt_10"} 19179
telemt_pool_swap_total 196
telemt_pool_force_close_total 5731
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 68049
telemt_me_writer_removed_unexpected_total 2822
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62318
telemt_me_writer_teardown_success_total{mode="normal"} 70911
telemt_me_writer_teardown_noop_total 68050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.284160
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 4303
telemt_me_writer_restored_same_endpoint_total 2618
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 8696980
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 194819686425 (181.44 GB)
telemt_user_octets_to_client{user="hello"} 3325198691684 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 128550.4 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11728495
telemt_connections_bad_total 482679
telemt_connections_current 494
telemt_connections_me_current 494
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4763514
telemt_upstream_connect_attempt_total 62058
telemt_upstream_connect_success_total 61602
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 62046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_reconnect_attempts_total 49066
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1523
telemt_me_idle_close_by_peer_total 1522
telemt_me_route_drop_no_conn_total 4096550
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5637104
telemt_me_endpoint_quarantine_total 873
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 987
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31738
telemt_desync_full_logged_total 10834
telemt_desync_suppressed_total 20904
telemt_desync_frames_bucket_total{bucket="1_2"} 6318
telemt_desync_frames_bucket_total{bucket="3_10"} 12522
telemt_desync_frames_bucket_total{bucket="gt_10"} 12898
telemt_pool_swap_total 136
telemt_pool_force_close_total 3946
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 47466
telemt_me_writer_removed_unexpected_total 1571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3865
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45218
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43520
telemt_me_writer_teardown_success_total{mode="normal"} 49083
telemt_me_writer_teardown_noop_total 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96556
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.710467
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96556
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 2743
telemt_me_writer_restored_same_endpoint_total 1635
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5629249
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 120049878204 (111.81 GB)
telemt_user_octets_to_client{user="hello"} 2185569733494 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 109521.1 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1539734
telemt_connections_bad_total 36786
telemt_connections_current 429
telemt_connections_me_current 429
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31395
telemt_upstream_connect_attempt_total 51737
telemt_upstream_connect_success_total 51576
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 51709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2288
telemt_me_reconnect_success_total 935
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 520710
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1368733
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 907
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
telemt_desync_total 9252
telemt_desync_full_logged_total 2674
telemt_desync_suppressed_total 6578
telemt_desync_frames_bucket_total{bucket="1_2"} 2682
telemt_desync_frames_bucket_total{bucket="3_10"} 3521
telemt_desync_frames_bucket_total{bucket="gt_10"} 3049
telemt_pool_swap_total 118
telemt_pool_force_close_total 3003
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 43833
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41414
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40830
telemt_me_writer_teardown_success_total{mode="normal"} 44763
telemt_me_writer_teardown_noop_total 43837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.353343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1364532
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 26172815525 (24.38 GB)
telemt_user_octets_to_client{user="hello"} 581153699991 (541.24 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 191718.7 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13349212
telemt_connections_bad_total 1609170
telemt_connections_current 616
telemt_connections_me_current 616
telemt_handshake_timeouts_total 389886
telemt_upstream_connect_attempt_total 75970
telemt_upstream_connect_success_total 75618
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 75834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3029
telemt_me_reconnect_success_total 1510
telemt_me_reader_eof_total 1494
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 4485439
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10062561
telemt_me_endpoint_quarantine_total 1381
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1451
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 47
telemt_desync_total 42196
telemt_desync_full_logged_total 13779
telemt_desync_suppressed_total 28417
telemt_desync_frames_bucket_total{bucket="1_2"} 10243
telemt_desync_frames_bucket_total{bucket="3_10"} 15501
telemt_desync_frames_bucket_total{bucket="gt_10"} 16452
telemt_pool_swap_total 212
telemt_pool_force_close_total 5624
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 68703
telemt_me_writer_removed_unexpected_total 1431
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64814
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5450
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63079
telemt_me_writer_teardown_success_total{mode="normal"} 70187
telemt_me_writer_teardown_noop_total 68705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138892
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.801299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138892
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1324
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10029256
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 194898219292 (181.51 GB)
telemt_user_octets_to_client{user="hello"} 4444427964092 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 191715.3 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11667260
telemt_connections_bad_total 1364228
telemt_connections_current 519
telemt_connections_me_current 519
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312044
telemt_upstream_connect_attempt_total 103495
telemt_upstream_connect_success_total 102603
telemt_upstream_connect_fail_total 684
telemt_upstream_connect_attempts_per_request{bucket="1"} 103287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 684
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10521
telemt_me_reconnect_success_total 2613
telemt_me_reader_eof_total 2422
telemt_me_idle_close_by_peer_total 2421
telemt_me_seq_mismatch_total 100
telemt_me_route_drop_no_conn_total 5652989
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8976040
telemt_me_endpoint_quarantine_total 1558
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1453
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 50
telemt_desync_total 41844
telemt_desync_full_logged_total 13476
telemt_desync_suppressed_total 28368
telemt_desync_frames_bucket_total{bucket="1_2"} 10809
telemt_desync_frames_bucket_total{bucket="3_10"} 15389
telemt_desync_frames_bucket_total{bucket="gt_10"} 15646
telemt_pool_swap_total 202
telemt_pool_force_close_total 5399
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 68763
telemt_me_writer_removed_unexpected_total 2465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63364
telemt_me_writer_teardown_success_total{mode="normal"} 71314
telemt_me_writer_teardown_noop_total 68768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140082
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.490338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140082
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 409
telemt_me_writer_restored_same_endpoint_total 2103
telemt_me_writer_restored_fallback_total 135
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 8980617
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 157504848040 (146.69 GB)
telemt_user_octets_to_client{user="hello"} 3494863254970 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 62
```