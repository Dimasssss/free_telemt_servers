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

# Server Metrics 2026-03-23 01:41:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 102906.4 (28h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3557088
telemt_connections_bad_total 321032
telemt_connections_current 807
telemt_connections_me_current 807
telemt_handshake_timeouts_total 111482
telemt_upstream_connect_attempt_total 38357
telemt_upstream_connect_success_total 38356
telemt_upstream_connect_attempts_per_request{bucket="1"} 38356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1409
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 629
telemt_me_idle_close_by_peer_total 629
telemt_me_route_drop_no_conn_total 2989838
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2930198
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 727
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 802
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
telemt_me_writers_active_current 43
telemt_desync_total 12588
telemt_desync_full_logged_total 3962
telemt_desync_suppressed_total 8626
telemt_desync_frames_bucket_total{bucket="1_2"} 3375
telemt_desync_frames_bucket_total{bucket="3_10"} 4589
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 114
telemt_pool_force_close_total 3503
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 35110
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32846
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3447
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31607
telemt_me_writer_teardown_success_total{mode="normal"} 35365
telemt_me_writer_teardown_noop_total 35121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.722346
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2919215
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 41688357752 (38.83 GB)
telemt_user_octets_to_client{user="hello"} 799799354788 (744.87 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 116272.6 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4009349
telemt_connections_bad_total 370157
telemt_connections_current 453
telemt_connections_me_current 453
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100848
telemt_upstream_connect_attempt_total 72505
telemt_upstream_connect_success_total 71620
telemt_upstream_connect_fail_total 781
telemt_upstream_connect_attempts_per_request{bucket="1"} 72401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 781
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10164
telemt_me_reconnect_success_total 3655
telemt_me_reader_eof_total 3644
telemt_me_idle_close_by_peer_total 3644
telemt_me_route_drop_no_conn_total 3641895
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3185046
telemt_me_endpoint_quarantine_total 937
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 909
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
telemt_desync_total 12985
telemt_desync_full_logged_total 7285
telemt_desync_suppressed_total 5700
telemt_desync_frames_bucket_total{bucket="1_2"} 2945
telemt_desync_frames_bucket_total{bucket="3_10"} 5095
telemt_desync_frames_bucket_total{bucket="gt_10"} 4945
telemt_pool_swap_total 109
telemt_pool_force_close_total 3095
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 47923
telemt_me_writer_removed_unexpected_total 3573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44828
telemt_me_writer_teardown_success_total{mode="normal"} 51530
telemt_me_writer_teardown_noop_total 47924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.630204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3255
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 3198347
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 43161091259 (40.20 GB)
telemt_user_octets_to_client{user="hello"} 793370924628 (738.88 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 191132.7 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16361822
telemt_connections_bad_total 1657800
telemt_connections_current 801
telemt_connections_me_current 801
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397895
telemt_upstream_connect_attempt_total 85804
telemt_upstream_connect_success_total 85698
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1720
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3018
telemt_me_reconnect_success_total 1594
telemt_me_reader_eof_total 1543
telemt_me_idle_close_by_peer_total 1541
telemt_me_route_drop_no_conn_total 14049034
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12990945
telemt_me_endpoint_quarantine_total 1278
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1440
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
telemt_me_writers_active_current 45
telemt_desync_total 53905
telemt_desync_full_logged_total 17130
telemt_desync_suppressed_total 36775
telemt_desync_frames_bucket_total{bucket="1_2"} 12016
telemt_desync_frames_bucket_total{bucket="3_10"} 21047
telemt_desync_frames_bucket_total{bucket="gt_10"} 20842
telemt_pool_swap_total 207
telemt_pool_force_close_total 6763
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1064
telemt_me_draining_writers_reap_progress_total 65132
telemt_me_writer_removed_unexpected_total 1484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58369
telemt_me_writer_teardown_success_total{mode="normal"} 65894
telemt_me_writer_teardown_noop_total 65185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.806911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1064
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1379
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 12990959
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 193610111825 (180.31 GB)
telemt_user_octets_to_client{user="hello"} 3494942919331 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 191133.9 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11901800
telemt_connections_bad_total 1239308
telemt_connections_current 520
telemt_connections_me_current 520
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344666
telemt_upstream_connect_attempt_total 100167
telemt_upstream_connect_success_total 98839
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 99714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4444
telemt_me_reconnect_success_total 1894
telemt_me_reader_eof_total 1761
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 4558483
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8832157
telemt_me_endpoint_quarantine_total 1286
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1459
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 44
telemt_desync_total 38910
telemt_desync_full_logged_total 13095
telemt_desync_suppressed_total 25815
telemt_desync_frames_bucket_total{bucket="1_2"} 9642
telemt_desync_frames_bucket_total{bucket="3_10"} 14942
telemt_desync_frames_bucket_total{bucket="gt_10"} 14326
telemt_pool_swap_total 204
telemt_pool_force_close_total 6119
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 63372
telemt_me_writer_removed_unexpected_total 1790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57253
telemt_me_writer_teardown_success_total{mode="normal"} 65019
telemt_me_writer_teardown_noop_total 63397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128416
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.445476
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128416
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1621
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8769910
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 217929707228 (202.96 GB)
telemt_user_octets_to_client{user="hello"} 3966706524127 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 191097.7 (53h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11072517
telemt_connections_bad_total 977556
telemt_connections_current 499
telemt_connections_me_current 499
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345641
telemt_upstream_connect_attempt_total 84461
telemt_upstream_connect_success_total 82902
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 83107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5763
telemt_me_reconnect_success_total 2385
telemt_me_reader_eof_total 2130
telemt_me_idle_close_by_peer_total 2129
telemt_me_route_drop_no_conn_total 5339550
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8368648
telemt_me_endpoint_quarantine_total 1345
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1417
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38209
telemt_desync_full_logged_total 12655
telemt_desync_suppressed_total 25554
telemt_desync_frames_bucket_total{bucket="1_2"} 9649
telemt_desync_frames_bucket_total{bucket="3_10"} 14623
telemt_desync_frames_bucket_total{bucket="gt_10"} 13937
telemt_pool_swap_total 200
telemt_pool_force_close_total 6019
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 743
telemt_me_draining_writers_reap_progress_total 63758
telemt_me_writer_removed_unexpected_total 2280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6392
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57739
telemt_me_writer_teardown_success_total{mode="normal"} 65970
telemt_me_writer_teardown_noop_total 63829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129799
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.820664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129799
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 743
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2075
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8360601
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 192819312211 (179.58 GB)
telemt_user_octets_to_client{user="hello"} 3473706410101 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61377.4 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11277627
telemt_connections_bad_total 669271
telemt_connections_current 960
telemt_connections_me_current 960
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 276506
telemt_upstream_connect_attempt_total 58863
telemt_upstream_connect_success_total 55775
telemt_upstream_connect_fail_total 2036
telemt_upstream_connect_attempts_per_request{bucket="1"} 57811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6017
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2036
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7797
telemt_me_reconnect_success_total 1267
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 25294726
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9354450
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_desync_total 16402
telemt_desync_full_logged_total 4481
telemt_desync_suppressed_total 11921
telemt_desync_frames_bucket_total{bucket="1_2"} 3115
telemt_desync_frames_bucket_total{bucket="3_10"} 6688
telemt_desync_frames_bucket_total{bucket="gt_10"} 6599
telemt_pool_swap_total 64
telemt_pool_force_close_total 2042
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 489
telemt_me_draining_writers_reap_progress_total 19380
telemt_me_writer_removed_unexpected_total 1153
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17861
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17338
telemt_me_writer_teardown_success_total{mode="normal"} 20477
telemt_me_writer_teardown_noop_total 19399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39876
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.912344
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39876
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 489
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9380316
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 87492284702 (81.48 GB)
telemt_user_octets_to_client{user="hello"} 615527764974 (573.25 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 191104.0 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11019973
telemt_connections_bad_total 958700
telemt_connections_current 487
telemt_connections_me_current 487
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242515
telemt_upstream_connect_attempt_total 113315
telemt_upstream_connect_success_total 112146
telemt_upstream_connect_fail_total 995
telemt_upstream_connect_attempts_per_request{bucket="1"} 113141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 995
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73016
telemt_me_reconnect_success_total 3102
telemt_me_reader_eof_total 2794
telemt_me_idle_close_by_peer_total 2792
telemt_me_route_drop_no_conn_total 5265871
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8689424
telemt_me_endpoint_quarantine_total 1298
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1446
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
telemt_me_writers_active_current 42
telemt_desync_total 46310
telemt_desync_full_logged_total 15876
telemt_desync_suppressed_total 30434
telemt_desync_frames_bucket_total{bucket="1_2"} 9409
telemt_desync_frames_bucket_total{bucket="3_10"} 17727
telemt_desync_frames_bucket_total{bucket="gt_10"} 19174
telemt_pool_swap_total 196
telemt_pool_force_close_total 5731
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 67861
telemt_me_writer_removed_unexpected_total 2818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6910
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63809
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62130
telemt_me_writer_teardown_success_total{mode="normal"} 70719
telemt_me_writer_teardown_noop_total 67862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.282771
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 4303
telemt_me_writer_restored_same_endpoint_total 2615
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8692371
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 194776734209 (181.40 GB)
telemt_user_octets_to_client{user="hello"} 3323348250280 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 127940.3 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11719767
telemt_connections_bad_total 482567
telemt_connections_current 714
telemt_connections_me_current 714
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762453
telemt_upstream_connect_attempt_total 61766
telemt_upstream_connect_success_total 61310
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 61754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_reconnect_attempts_total 49057
telemt_me_reconnect_success_total 1841
telemt_me_reader_eof_total 1515
telemt_me_idle_close_by_peer_total 1514
telemt_me_route_drop_no_conn_total 4095809
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5632827
telemt_me_endpoint_quarantine_total 873
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31718
telemt_desync_full_logged_total 10827
telemt_desync_suppressed_total 20891
telemt_desync_frames_bucket_total{bucket="1_2"} 6313
telemt_desync_frames_bucket_total{bucket="3_10"} 12512
telemt_desync_frames_bucket_total{bucket="gt_10"} 12893
telemt_pool_swap_total 136
telemt_pool_force_close_total 3924
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 47188
telemt_me_writer_removed_unexpected_total 1563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44948
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3483
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43264
telemt_me_writer_teardown_success_total{mode="normal"} 48797
telemt_me_writer_teardown_noop_total 47195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95992
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.708318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95992
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 2743
telemt_me_writer_restored_same_endpoint_total 1627
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5624977
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 120025883916 (111.78 GB)
telemt_user_octets_to_client{user="hello"} 2183320201018 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 108911.0 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1535503
telemt_connections_bad_total 36782
telemt_connections_current 408
telemt_connections_me_current 408
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31267
telemt_upstream_connect_attempt_total 51395
telemt_upstream_connect_success_total 51235
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 51367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 792
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2264
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 519906
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1364917
telemt_me_endpoint_quarantine_total 901
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 899
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
telemt_me_writers_active_current 45
telemt_desync_total 9194
telemt_desync_full_logged_total 2662
telemt_desync_suppressed_total 6532
telemt_desync_frames_bucket_total{bucket="1_2"} 2647
telemt_desync_frames_bucket_total{bucket="3_10"} 3498
telemt_desync_frames_bucket_total{bucket="gt_10"} 3049
telemt_pool_swap_total 117
telemt_pool_force_close_total 2982
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 43528
telemt_me_writer_removed_unexpected_total 882
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3327
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41124
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2894
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40546
telemt_me_writer_teardown_success_total{mode="normal"} 44451
telemt_me_writer_teardown_noop_total 43532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87983
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.345445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87983
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 790
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1360724
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 26124275925 (24.33 GB)
telemt_user_octets_to_client{user="hello"} 578515599851 (538.78 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 191108.9 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13342977
telemt_connections_bad_total 1606997
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 389710
telemt_upstream_connect_attempt_total 75646
telemt_upstream_connect_success_total 75294
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 75510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3025
telemt_me_reconnect_success_total 1506
telemt_me_reader_eof_total 1492
telemt_me_idle_close_by_peer_total 1492
telemt_me_route_drop_no_conn_total 4484843
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10059369
telemt_me_endpoint_quarantine_total 1381
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1447
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 45
telemt_desync_total 42154
telemt_desync_full_logged_total 13766
telemt_desync_suppressed_total 28388
telemt_desync_frames_bucket_total{bucket="1_2"} 10223
telemt_desync_frames_bucket_total{bucket="3_10"} 15488
telemt_desync_frames_bucket_total{bucket="gt_10"} 16443
telemt_pool_swap_total 212
telemt_pool_force_close_total 5624
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 68403
telemt_me_writer_removed_unexpected_total 1429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64520
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5450
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62779
telemt_me_writer_teardown_success_total{mode="normal"} 69885
telemt_me_writer_teardown_noop_total 68405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138290
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.799514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138290
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1322
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10026064
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 194877736788 (181.49 GB)
telemt_user_octets_to_client{user="hello"} 4443314823452 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 191105.3 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11661990
telemt_connections_bad_total 1363162
telemt_connections_current 559
telemt_connections_me_current 559
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311834
telemt_upstream_connect_attempt_total 103111
telemt_upstream_connect_success_total 102219
telemt_upstream_connect_fail_total 684
telemt_upstream_connect_attempts_per_request{bucket="1"} 102903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 684
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10512
telemt_me_reconnect_success_total 2604
telemt_me_reader_eof_total 2414
telemt_me_idle_close_by_peer_total 2413
telemt_me_seq_mismatch_total 100
telemt_me_route_drop_no_conn_total 5652407
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8972200
telemt_me_endpoint_quarantine_total 1558
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1450
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41832
telemt_desync_full_logged_total 13470
telemt_desync_suppressed_total 28362
telemt_desync_frames_bucket_total{bucket="1_2"} 10808
telemt_desync_frames_bucket_total{bucket="3_10"} 15384
telemt_desync_frames_bucket_total{bucket="gt_10"} 15640
telemt_pool_swap_total 202
telemt_pool_force_close_total 5399
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 68418
telemt_me_writer_removed_unexpected_total 2457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6733
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63019
telemt_me_writer_teardown_success_total{mode="normal"} 70961
telemt_me_writer_teardown_noop_total 68423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139384
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.487613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139384
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 409
telemt_me_writer_restored_same_endpoint_total 2095
telemt_me_writer_restored_fallback_total 135
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 8976777
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 157482408652 (146.67 GB)
telemt_user_octets_to_client{user="hello"} 3493399522986 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 78
```