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

# Server Metrics 2026-03-22 19:18:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 79955.3 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2976880
telemt_connections_bad_total 193574
telemt_connections_current 1158
telemt_connections_me_current 1158
telemt_handshake_timeouts_total 97722
telemt_upstream_connect_attempt_total 29215
telemt_upstream_connect_success_total 29214
telemt_upstream_connect_attempts_per_request{bucket="1"} 29214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1179
telemt_me_reconnect_success_total 494
telemt_me_reader_eof_total 499
telemt_me_idle_close_by_peer_total 499
telemt_me_route_drop_no_conn_total 2655050
telemt_me_route_drop_channel_closed_total 1053
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2524972
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 537
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 621
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
telemt_desync_total 10957
telemt_desync_full_logged_total 3482
telemt_desync_suppressed_total 7475
telemt_desync_frames_bucket_total{bucket="1_2"} 2943
telemt_desync_frames_bucket_total{bucket="3_10"} 4066
telemt_desync_frames_bucket_total{bucket="gt_10"} 3948
telemt_pool_swap_total 88
telemt_pool_force_close_total 2736
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 569
telemt_me_draining_writers_reap_progress_total 26704
telemt_me_writer_removed_unexpected_total 483
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24990
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23968
telemt_me_writer_teardown_success_total{mode="normal"} 26927
telemt_me_writer_teardown_noop_total 26714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.534944
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 569
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 436
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2517628
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 36903453592 (34.37 GB)
telemt_user_octets_to_client{user="hello"} 658521045560 (613.30 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 93321.7 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3798694
telemt_connections_bad_total 339468
telemt_connections_current 984
telemt_connections_me_current 984
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97005
telemt_upstream_connect_attempt_total 56642
telemt_upstream_connect_success_total 55951
telemt_upstream_connect_fail_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 56560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 609
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6392
telemt_me_reconnect_success_total 2348
telemt_me_reader_eof_total 2282
telemt_me_idle_close_by_peer_total 2282
telemt_me_route_drop_no_conn_total 3593974
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3020995
telemt_me_endpoint_quarantine_total 728
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 720
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
telemt_me_writers_active_current 44
telemt_desync_total 12057
telemt_desync_full_logged_total 6746
telemt_desync_suppressed_total 5311
telemt_desync_frames_bucket_total{bucket="1_2"} 2775
telemt_desync_frames_bucket_total{bucket="3_10"} 4714
telemt_desync_frames_bucket_total{bucket="gt_10"} 4568
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37041
telemt_me_writer_removed_unexpected_total 2232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4355
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34930
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34384
telemt_me_writer_teardown_success_total{mode="normal"} 39285
telemt_me_writer_teardown_noop_total 37041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76326
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.956814
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76326
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2035
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3031795
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 39292928131 (36.59 GB)
telemt_user_octets_to_client{user="hello"} 712598191162 (663.66 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 168181.6 (46h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15845191
telemt_connections_bad_total 1526466
telemt_connections_current 2357
telemt_connections_me_current 2357
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 390903
telemt_upstream_connect_attempt_total 74930
telemt_upstream_connect_success_total 74833
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1685
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2771
telemt_me_reconnect_success_total 1426
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1365
telemt_me_route_drop_no_conn_total 13945688
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12627920
telemt_me_endpoint_quarantine_total 1061
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1253
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
telemt_desync_total 52090
telemt_desync_full_logged_total 16376
telemt_desync_suppressed_total 35714
telemt_desync_frames_bucket_total{bucket="1_2"} 11614
telemt_desync_frames_bucket_total{bucket="3_10"} 20290
telemt_desync_frames_bucket_total{bucket="gt_10"} 20186
telemt_pool_swap_total 181
telemt_pool_force_close_total 6118
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 993
telemt_me_draining_writers_reap_progress_total 55192
telemt_me_writer_removed_unexpected_total 1319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49074
telemt_me_writer_teardown_success_total{mode="normal"} 55804
telemt_me_writer_teardown_noop_total 55243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111047
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 309.721221
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111047
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 993
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1230
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12628502
telemt_user_connections_current{user="hello"} 2357
telemt_user_octets_from_client{user="hello"} 184204523493 (171.55 GB)
telemt_user_octets_to_client{user="hello"} 3333709044259 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 919
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 168183.2 (46h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11438437
telemt_connections_bad_total 1132368
telemt_connections_current 1564
telemt_connections_me_current 1564
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 340227
telemt_upstream_connect_attempt_total 87427
telemt_upstream_connect_success_total 86199
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 87042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4126
telemt_me_reconnect_success_total 1704
telemt_me_reader_eof_total 1574
telemt_me_idle_close_by_peer_total 1574
telemt_me_route_drop_no_conn_total 4471029
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8526175
telemt_me_endpoint_quarantine_total 1059
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1272
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
telemt_desync_total 37786
telemt_desync_full_logged_total 12736
telemt_desync_suppressed_total 25050
telemt_desync_frames_bucket_total{bucket="1_2"} 9327
telemt_desync_frames_bucket_total{bucket="3_10"} 14557
telemt_desync_frames_bucket_total{bucket="gt_10"} 13902
telemt_pool_swap_total 178
telemt_pool_force_close_total 5526
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 53640
telemt_me_writer_removed_unexpected_total 1612
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4951
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48114
telemt_me_writer_teardown_success_total{mode="normal"} 55098
telemt_me_writer_teardown_noop_total 53665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.406858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8464473
telemt_user_connections_current{user="hello"} 1564
telemt_user_octets_from_client{user="hello"} 211831145129 (197.28 GB)
telemt_user_octets_to_client{user="hello"} 3816972627598 (3.47 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 168147.8 (46h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10758455
telemt_connections_bad_total 927117
telemt_connections_current 1392
telemt_connections_me_current 1392
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343024
telemt_upstream_connect_attempt_total 72500
telemt_upstream_connect_success_total 71421
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4927
telemt_me_reconnect_success_total 1987
telemt_me_reader_eof_total 1736
telemt_me_idle_close_by_peer_total 1735
telemt_me_route_drop_no_conn_total 5241020
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8132933
telemt_me_endpoint_quarantine_total 1144
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1233
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
telemt_me_writers_active_current 44
telemt_desync_total 37329
telemt_desync_full_logged_total 12351
telemt_desync_suppressed_total 24978
telemt_desync_frames_bucket_total{bucket="1_2"} 9442
telemt_desync_frames_bucket_total{bucket="3_10"} 14288
telemt_desync_frames_bucket_total{bucket="gt_10"} 13599
telemt_pool_swap_total 176
telemt_pool_force_close_total 5468
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 707
telemt_me_draining_writers_reap_progress_total 53773
telemt_me_writer_removed_unexpected_total 1878
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4920
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 548
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48305
telemt_me_writer_teardown_success_total{mode="normal"} 55568
telemt_me_writer_teardown_noop_total 53844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.727301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 707
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1712
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8125343
telemt_user_connections_current{user="hello"} 1392
telemt_user_octets_from_client{user="hello"} 188487542869 (175.54 GB)
telemt_user_octets_to_client{user="hello"} 3382835575285 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 38427.0 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10703785
telemt_connections_bad_total 652628
telemt_connections_current 1939
telemt_connections_me_current 1939
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 226097
telemt_upstream_connect_attempt_total 44287
telemt_upstream_connect_success_total 42059
telemt_upstream_connect_fail_total 1541
telemt_upstream_connect_attempts_per_request{bucket="1"} 43600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5953
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1541
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6463
telemt_me_reconnect_success_total 866
telemt_me_reader_eof_total 538
telemt_me_idle_close_by_peer_total 538
telemt_me_route_drop_no_conn_total 25157507
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8890092
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 300
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
telemt_me_writers_active_current 41
telemt_desync_total 14344
telemt_desync_full_logged_total 3750
telemt_desync_suppressed_total 10594
telemt_desync_frames_bucket_total{bucket="1_2"} 2661
telemt_desync_frames_bucket_total{bucket="3_10"} 5821
telemt_desync_frames_bucket_total{bucket="gt_10"} 5862
telemt_pool_swap_total 38
telemt_pool_force_close_total 1411
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 421
telemt_me_draining_writers_reap_progress_total 10864
telemt_me_writer_removed_unexpected_total 782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9946
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9453
telemt_me_writer_teardown_success_total{mode="normal"} 11599
telemt_me_writer_teardown_noop_total 10883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.633591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 421
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8912323
telemt_user_connections_current{user="hello"} 1939
telemt_user_octets_from_client{user="hello"} 81313945023 (75.73 GB)
telemt_user_octets_to_client{user="hello"} 453342205067 (422.21 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 168153.6 (46h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10619980
telemt_connections_bad_total 894648
telemt_connections_current 1868
telemt_connections_me_current 1868
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233630
telemt_upstream_connect_attempt_total 101776
telemt_upstream_connect_success_total 100700
telemt_upstream_connect_fail_total 917
telemt_upstream_connect_attempts_per_request{bucket="1"} 101617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 917
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72278
telemt_me_reconnect_success_total 2790
telemt_me_reader_eof_total 2479
telemt_me_idle_close_by_peer_total 2477
telemt_me_route_drop_no_conn_total 5173492
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8387301
telemt_me_endpoint_quarantine_total 1110
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1254
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
telemt_me_writers_active_current 90
telemt_desync_total 44625
telemt_desync_full_logged_total 15188
telemt_desync_suppressed_total 29437
telemt_desync_frames_bucket_total{bucket="1_2"} 9039
telemt_desync_frames_bucket_total{bucket="3_10"} 17119
telemt_desync_frames_bucket_total{bucket="gt_10"} 18467
telemt_pool_swap_total 171
telemt_pool_force_close_total 5090
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 57412
telemt_me_writer_removed_unexpected_total 2517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53838
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52322
telemt_me_writer_teardown_success_total{mode="normal"} 59955
telemt_me_writer_teardown_noop_total 57413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.923044
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2343
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8390772
telemt_user_connections_current{user="hello"} 1868
telemt_user_octets_from_client{user="hello"} 190412639513 (177.34 GB)
telemt_user_octets_to_client{user="hello"} 3185905466908 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 104989.8 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11172827
telemt_connections_bad_total 437923
telemt_connections_current 1362
telemt_connections_me_current 1362
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4615596
telemt_upstream_connect_attempt_total 49921
telemt_upstream_connect_success_total 49548
telemt_upstream_connect_fail_total 364
telemt_upstream_connect_attempts_per_request{bucket="1"} 49912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 364
telemt_me_reconnect_attempts_total 48453
telemt_me_reconnect_success_total 1652
telemt_me_reader_eof_total 1307
telemt_me_idle_close_by_peer_total 1306
telemt_me_route_drop_no_conn_total 4016745
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5378092
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 792
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30151
telemt_desync_full_logged_total 10188
telemt_desync_suppressed_total 19963
telemt_desync_frames_bucket_total{bucket="1_2"} 6046
telemt_desync_frames_bucket_total{bucket="3_10"} 11922
telemt_desync_frames_bucket_total{bucket="gt_10"} 12183
telemt_pool_swap_total 110
telemt_pool_force_close_total 3376
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 36441
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3255
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2936
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33065
telemt_me_writer_teardown_success_total{mode="normal"} 37842
telemt_me_writer_teardown_noop_total 36448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74290
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.372392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74290
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5371036
telemt_user_connections_current{user="hello"} 1362
telemt_user_octets_from_client{user="hello"} 115967117756 (108.00 GB)
telemt_user_octets_to_client{user="hello"} 2055300164850 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 85960.6 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1277619
telemt_connections_bad_total 27869
telemt_connections_current 1193
telemt_connections_me_current 1193
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24413
telemt_upstream_connect_attempt_total 40970
telemt_upstream_connect_success_total 40847
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 40943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1884
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 446093
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132844
telemt_me_endpoint_quarantine_total 722
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 709
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
telemt_me_writers_active_current 44
telemt_desync_total 6632
telemt_desync_full_logged_total 2045
telemt_desync_suppressed_total 4587
telemt_desync_frames_bucket_total{bucket="1_2"} 1492
telemt_desync_frames_bucket_total{bucket="3_10"} 2614
telemt_desync_frames_bucket_total{bucket="gt_10"} 2526
telemt_pool_swap_total 92
telemt_pool_force_close_total 2380
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 34080
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32172
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2295
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31700
telemt_me_writer_teardown_success_total{mode="normal"} 34850
telemt_me_writer_teardown_noop_total 34084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.268116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1129030
telemt_user_connections_current{user="hello"} 1193
telemt_user_octets_from_client{user="hello"} 21591439665 (20.11 GB)
telemt_user_octets_to_client{user="hello"} 479612387875 (446.67 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 168158.2 (46h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12938015
telemt_connections_bad_total 1511737
telemt_connections_current 1760
telemt_connections_me_current 1760
telemt_handshake_timeouts_total 368759
telemt_upstream_connect_attempt_total 63348
telemt_upstream_connect_success_total 63019
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 63213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2461
telemt_me_reconnect_success_total 1305
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1268
telemt_me_route_drop_no_conn_total 4396950
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9787610
telemt_me_endpoint_quarantine_total 1122
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1255
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 40331
telemt_desync_full_logged_total 13149
telemt_desync_suppressed_total 27182
telemt_desync_frames_bucket_total{bucket="1_2"} 9636
telemt_desync_frames_bucket_total{bucket="3_10"} 14884
telemt_desync_frames_bucket_total{bucket="gt_10"} 15811
telemt_pool_swap_total 186
telemt_pool_force_close_total 5123
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 57066
telemt_me_writer_removed_unexpected_total 1220
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51943
telemt_me_writer_teardown_success_total{mode="normal"} 58324
telemt_me_writer_teardown_noop_total 57068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.136867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 1141
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 9755457
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 191109535264 (177.98 GB)
telemt_user_octets_to_client{user="hello"} 4309736632192 (3.92 TB)
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 168154.8 (46h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11246694
telemt_connections_bad_total 1274960
telemt_connections_current 1516
telemt_connections_me_current 1516
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 295695
telemt_upstream_connect_attempt_total 89746
telemt_upstream_connect_success_total 88934
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9658
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 2159
telemt_me_idle_close_by_peer_total 2158
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5574884
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8690468
telemt_me_endpoint_quarantine_total 1287
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1255
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
telemt_desync_total 39672
telemt_desync_full_logged_total 12818
telemt_desync_suppressed_total 26854
telemt_desync_frames_bucket_total{bucket="1_2"} 9900
telemt_desync_frames_bucket_total{bucket="3_10"} 14748
telemt_desync_frames_bucket_total{bucket="gt_10"} 15024
telemt_pool_swap_total 176
telemt_pool_force_close_total 4922
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 56827
telemt_me_writer_removed_unexpected_total 2193
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6000
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53093
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4451
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51905
telemt_me_writer_teardown_success_total{mode="normal"} 59093
telemt_me_writer_teardown_noop_total 56832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115925
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.105690
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115925
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 379
telemt_me_writer_restored_same_endpoint_total 1889
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8696117
telemt_user_connections_current{user="hello"} 1516
telemt_user_octets_from_client{user="hello"} 153302491961 (142.77 GB)
telemt_user_octets_to_client{user="hello"} 3349404622919 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 193
```