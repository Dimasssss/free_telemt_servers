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

# Server Metrics 2026-03-23 04:29:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 112976.0 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3849218
telemt_connections_bad_total 378107
telemt_connections_current 1304
telemt_connections_me_current 1304
telemt_handshake_timeouts_total 128670
telemt_upstream_connect_attempt_total 42112
telemt_upstream_connect_success_total 42111
telemt_upstream_connect_attempts_per_request{bucket="1"} 42111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 94
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1461
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 676
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 3037414
telemt_me_route_drop_channel_closed_total 1244
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3134659
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 885
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
telemt_me_writers_active_current 45
telemt_desync_total 13414
telemt_desync_full_logged_total 4283
telemt_desync_suppressed_total 9131
telemt_desync_frames_bucket_total{bucket="1_2"} 3530
telemt_desync_frames_bucket_total{bucket="3_10"} 4929
telemt_desync_frames_bucket_total{bucket="gt_10"} 4955
telemt_pool_swap_total 125
telemt_pool_force_close_total 3805
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 693
telemt_me_draining_writers_reap_progress_total 38583
telemt_me_writer_removed_unexpected_total 652
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36108
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34778
telemt_me_writer_teardown_success_total{mode="normal"} 38865
telemt_me_writer_teardown_noop_total 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77460
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 386.563709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77460
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 693
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3123174
telemt_user_connections_current{user="hello"} 1304
telemt_user_octets_from_client{user="hello"} 43898847652 (40.88 GB)
telemt_user_octets_to_client{user="hello"} 851456620636 (792.98 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 126342.3 (35h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4094121
telemt_connections_bad_total 381714
telemt_connections_current 732
telemt_connections_me_current 732
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 103441
telemt_upstream_connect_attempt_total 79108
telemt_upstream_connect_success_total 78164
telemt_upstream_connect_fail_total 837
telemt_upstream_connect_attempts_per_request{bucket="1"} 79001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 837
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10697
telemt_me_reconnect_success_total 3834
telemt_me_reader_eof_total 3815
telemt_me_idle_close_by_peer_total 3815
telemt_me_route_drop_no_conn_total 3657060
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3250186
telemt_me_endpoint_quarantine_total 1016
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 995
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
telemt_me_writers_active_current 92
telemt_desync_total 13341
telemt_desync_full_logged_total 7504
telemt_desync_suppressed_total 5837
telemt_desync_frames_bucket_total{bucket="1_2"} 3038
telemt_desync_frames_bucket_total{bucket="3_10"} 5241
telemt_desync_frames_bucket_total{bucket="gt_10"} 5062
telemt_pool_swap_total 119
telemt_pool_force_close_total 3292
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 258
telemt_me_draining_writers_reap_progress_total 52723
telemt_me_writer_removed_unexpected_total 3738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6717
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49431
telemt_me_writer_teardown_success_total{mode="normal"} 56501
telemt_me_writer_teardown_noop_total 52724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.762402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 258
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3400
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3264658
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 43917512203 (40.90 GB)
telemt_user_octets_to_client{user="hello"} 817411894817 (761.27 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 201202.2 (55h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16547919
telemt_connections_bad_total 1677585
telemt_connections_current 1393
telemt_connections_me_current 1393
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 403132
telemt_upstream_connect_attempt_total 90611
telemt_upstream_connect_success_total 90504
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3119
telemt_me_reconnect_success_total 1660
telemt_me_reader_eof_total 1615
telemt_me_idle_close_by_peer_total 1613
telemt_me_route_drop_no_conn_total 14085211
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13140875
telemt_me_endpoint_quarantine_total 1364
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1522
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
telemt_me_writers_active_current 44
telemt_desync_total 54674
telemt_desync_full_logged_total 17438
telemt_desync_suppressed_total 37236
telemt_desync_frames_bucket_total{bucket="1_2"} 12202
telemt_desync_frames_bucket_total{bucket="3_10"} 21393
telemt_desync_frames_bucket_total{bucket="gt_10"} 21079
telemt_pool_swap_total 218
telemt_pool_force_close_total 7021
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1088
telemt_me_draining_writers_reap_progress_total 69572
telemt_me_writer_removed_unexpected_total 1551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6551
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62551
telemt_me_writer_teardown_success_total{mode="normal"} 70406
telemt_me_writer_teardown_noop_total 69625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140031
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.324919
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140031
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1088
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 13140836
telemt_user_connections_current{user="hello"} 1393
telemt_user_octets_from_client{user="hello"} 199063078845 (185.39 GB)
telemt_user_octets_to_client{user="hello"} 3558982346603 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 201203.7 (55h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12082587
telemt_connections_bad_total 1279332
telemt_connections_current 911
telemt_connections_me_current 911
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 348550
telemt_upstream_connect_attempt_total 104870
telemt_upstream_connect_success_total 103520
telemt_upstream_connect_fail_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 104411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 891
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4592
telemt_me_reconnect_success_total 1969
telemt_me_reader_eof_total 1836
telemt_me_idle_close_by_peer_total 1836
telemt_me_route_drop_no_conn_total 4583208
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8939377
telemt_me_endpoint_quarantine_total 1374
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1543
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
telemt_desync_total 39295
telemt_desync_full_logged_total 13235
telemt_desync_suppressed_total 26060
telemt_desync_frames_bucket_total{bucket="1_2"} 9738
telemt_desync_frames_bucket_total{bucket="3_10"} 15106
telemt_desync_frames_bucket_total{bucket="gt_10"} 14451
telemt_pool_swap_total 215
telemt_pool_force_close_total 6365
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67643
telemt_me_writer_removed_unexpected_total 1863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63446
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61278
telemt_me_writer_teardown_success_total{mode="normal"} 69365
telemt_me_writer_teardown_noop_total 67668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.597149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 1685
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 8877029
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 219047064060 (204.00 GB)
telemt_user_octets_to_client{user="hello"} 4005615189115 (3.64 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 201167.9 (55h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11222370
telemt_connections_bad_total 1013304
telemt_connections_current 778
telemt_connections_me_current 778
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 349836
telemt_upstream_connect_attempt_total 89353
telemt_upstream_connect_success_total 87781
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5868
telemt_me_reconnect_success_total 2458
telemt_me_reader_eof_total 2205
telemt_me_idle_close_by_peer_total 2204
telemt_me_route_drop_no_conn_total 5361557
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8454233
telemt_me_endpoint_quarantine_total 1422
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1501
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 38515
telemt_desync_full_logged_total 12780
telemt_desync_suppressed_total 25735
telemt_desync_frames_bucket_total{bucket="1_2"} 9726
telemt_desync_frames_bucket_total{bucket="3_10"} 14753
telemt_desync_frames_bucket_total{bucket="gt_10"} 14036
telemt_pool_swap_total 211
telemt_pool_force_close_total 6252
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 758
telemt_me_draining_writers_reap_progress_total 68214
telemt_me_writer_removed_unexpected_total 2351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6686
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63815
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61962
telemt_me_writer_teardown_success_total{mode="normal"} 70501
telemt_me_writer_teardown_noop_total 68285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138786
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.938274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138786
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 758
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2140
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8446115
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 193552894679 (180.26 GB)
telemt_user_octets_to_client{user="hello"} 3508222202097 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 71448.1 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11505876
telemt_connections_bad_total 674861
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 302721
telemt_upstream_connect_attempt_total 64610
telemt_upstream_connect_success_total 61198
telemt_upstream_connect_fail_total 2208
telemt_upstream_connect_attempts_per_request{bucket="1"} 63406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2208
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8266
telemt_me_reconnect_success_total 1460
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 25337876
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9536113
telemt_me_endpoint_quarantine_total 560
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 576
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
telemt_me_writers_active_current 44
telemt_desync_total 16992
telemt_desync_full_logged_total 4692
telemt_desync_suppressed_total 12300
telemt_desync_frames_bucket_total{bucket="1_2"} 3279
telemt_desync_frames_bucket_total{bucket="3_10"} 6937
telemt_desync_frames_bucket_total{bucket="gt_10"} 6776
telemt_pool_swap_total 74
telemt_pool_force_close_total 2314
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 23630
telemt_me_writer_removed_unexpected_total 1331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21861
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21316
telemt_me_writer_teardown_success_total{mode="normal"} 24912
telemt_me_writer_teardown_noop_total 23649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.627673
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9562538
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 89598819738 (83.45 GB)
telemt_user_octets_to_client{user="hello"} 680090526169 (633.38 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 201174.2 (55h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11187546
telemt_connections_bad_total 987013
telemt_connections_current 1238
telemt_connections_me_current 1238
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246461
telemt_upstream_connect_attempt_total 118243
telemt_upstream_connect_success_total 117013
telemt_upstream_connect_fail_total 1053
telemt_upstream_connect_attempts_per_request{bucket="1"} 118066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1053
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73459
telemt_me_reconnect_success_total 3229
telemt_me_reader_eof_total 2924
telemt_me_idle_close_by_peer_total 2921
telemt_me_route_drop_no_conn_total 5296299
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8808407
telemt_me_endpoint_quarantine_total 1370
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1532
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
telemt_me_writers_active_current 46
telemt_desync_total 46956
telemt_desync_full_logged_total 16131
telemt_desync_suppressed_total 30825
telemt_desync_frames_bucket_total{bucket="1_2"} 9526
telemt_desync_frames_bucket_total{bucket="3_10"} 18010
telemt_desync_frames_bucket_total{bucket="gt_10"} 19420
telemt_pool_swap_total 207
telemt_pool_force_close_total 5982
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 72252
telemt_me_writer_removed_unexpected_total 2942
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7224
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68016
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66270
telemt_me_writer_teardown_success_total{mode="normal"} 75240
telemt_me_writer_teardown_noop_total 72253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147493
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.344334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147493
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 4320
telemt_me_writer_restored_same_endpoint_total 2719
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8811188
telemt_user_connections_current{user="hello"} 1238
telemt_user_octets_from_client{user="hello"} 197968775405 (184.37 GB)
telemt_user_octets_to_client{user="hello"} 3370438675540 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 138010.6 (38h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11937412
telemt_connections_bad_total 492124
telemt_connections_current 956
telemt_connections_me_current 956
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4819890
telemt_upstream_connect_attempt_total 67145
telemt_upstream_connect_success_total 66666
telemt_upstream_connect_fail_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 67132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 466
telemt_me_reconnect_attempts_total 49240
telemt_me_reconnect_success_total 1939
telemt_me_reader_eof_total 1621
telemt_me_idle_close_by_peer_total 1620
telemt_me_route_drop_no_conn_total 4122173
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5736296
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1065
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32262
telemt_desync_full_logged_total 11027
telemt_desync_suppressed_total 21235
telemt_desync_frames_bucket_total{bucket="1_2"} 6464
telemt_desync_frames_bucket_total{bucket="3_10"} 12721
telemt_desync_frames_bucket_total{bucket="gt_10"} 13077
telemt_pool_swap_total 147
telemt_pool_force_close_total 4175
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 52106
telemt_me_writer_removed_unexpected_total 1661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49681
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47931
telemt_me_writer_teardown_success_total{mode="normal"} 53821
telemt_me_writer_teardown_noop_total 52113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.774149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1715
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5728267
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 121168705884 (112.85 GB)
telemt_user_octets_to_client{user="hello"} 2233483929122 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 118981.4 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631898
telemt_connections_bad_total 37194
telemt_connections_current 639
telemt_connections_me_current 639
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33783
telemt_upstream_connect_attempt_total 56245
telemt_upstream_connect_success_total 56069
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 56217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 821
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2447
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 985
telemt_me_idle_close_by_peer_total 985
telemt_me_route_drop_no_conn_total 544493
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1450290
telemt_me_endpoint_quarantine_total 1012
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 983
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
telemt_me_writers_active_current 43
telemt_desync_total 10111
telemt_desync_full_logged_total 2849
telemt_desync_suppressed_total 7262
telemt_desync_frames_bucket_total{bucket="1_2"} 3205
telemt_desync_frames_bucket_total{bucket="3_10"} 3808
telemt_desync_frames_bucket_total{bucket="gt_10"} 3098
telemt_pool_swap_total 129
telemt_pool_force_close_total 3222
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 47902
telemt_me_writer_removed_unexpected_total 949
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3615
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45279
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44680
telemt_me_writer_teardown_success_total{mode="normal"} 48894
telemt_me_writer_teardown_noop_total 47906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.559762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 1445952
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 26993421529 (25.14 GB)
telemt_user_octets_to_client{user="hello"} 602330745375 (560.96 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 201178.8 (55h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13480316
telemt_connections_bad_total 1628683
telemt_connections_current 1198
telemt_connections_me_current 1198
telemt_handshake_timeouts_total 394204
telemt_upstream_connect_attempt_total 80941
telemt_upstream_connect_success_total 80581
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 80804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3165
telemt_me_reconnect_success_total 1599
telemt_me_reader_eof_total 1588
telemt_me_idle_close_by_peer_total 1588
telemt_me_route_drop_no_conn_total 4509006
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10160627
telemt_me_endpoint_quarantine_total 1482
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1529
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
telemt_me_writers_active_current 43
telemt_desync_total 42624
telemt_desync_full_logged_total 13918
telemt_desync_suppressed_total 28706
telemt_desync_frames_bucket_total{bucket="1_2"} 10377
telemt_desync_frames_bucket_total{bucket="3_10"} 15658
telemt_desync_frames_bucket_total{bucket="gt_10"} 16589
telemt_pool_swap_total 223
telemt_pool_force_close_total 5833
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 695
telemt_me_draining_writers_reap_progress_total 73278
telemt_me_writer_removed_unexpected_total 1520
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5655
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69201
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5659
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67445
telemt_me_writer_teardown_success_total{mode="normal"} 74856
telemt_me_writer_teardown_noop_total 73280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.926787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 695
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1408
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10127125
telemt_user_connections_current{user="hello"} 1198
telemt_user_octets_from_client{user="hello"} 196067868224 (182.60 GB)
telemt_user_octets_to_client{user="hello"} 4510103918676 (4.10 TB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 201175.5 (55h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11798572
telemt_connections_bad_total 1382293
telemt_connections_current 1026
telemt_connections_me_current 1026
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 317142
telemt_upstream_connect_attempt_total 108766
telemt_upstream_connect_success_total 107830
telemt_upstream_connect_fail_total 728
telemt_upstream_connect_attempts_per_request{bucket="1"} 108558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 728
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10977
telemt_me_reconnect_success_total 2726
telemt_me_reader_eof_total 2529
telemt_me_idle_close_by_peer_total 2528
telemt_me_seq_mismatch_total 105
telemt_me_route_drop_no_conn_total 5676641
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9078915
telemt_me_endpoint_quarantine_total 1657
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1534
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42285
telemt_desync_full_logged_total 13615
telemt_desync_suppressed_total 28670
telemt_desync_frames_bucket_total{bucket="1_2"} 10992
telemt_desync_frames_bucket_total{bucket="3_10"} 15527
telemt_desync_frames_bucket_total{bucket="gt_10"} 15766
telemt_pool_swap_total 213
telemt_pool_force_close_total 5595
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 73604
telemt_me_writer_removed_unexpected_total 2564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7045
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69222
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68009
telemt_me_writer_teardown_success_total{mode="normal"} 76267
telemt_me_writer_teardown_noop_total 73609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149876
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.620301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149876
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 2176
telemt_me_writer_restored_fallback_total 141
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 9083421
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 158595238124 (147.70 GB)
telemt_user_octets_to_client{user="hello"} 3552911703494 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 121
```