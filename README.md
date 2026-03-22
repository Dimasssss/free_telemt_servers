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

# Server Metrics 2026-03-22 14:37:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63047.8 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2041569
telemt_connections_bad_total 90823
telemt_connections_current 1734
telemt_connections_me_current 1734
telemt_handshake_timeouts_total 82912
telemt_upstream_connect_attempt_total 23471
telemt_upstream_connect_success_total 23470
telemt_upstream_connect_attempts_per_request{bucket="1"} 23470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 949
telemt_me_reconnect_success_total 384
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 1479725
telemt_me_route_drop_channel_closed_total 671
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1738425
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 493
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_warm_current 14
telemt_desync_total 9261
telemt_desync_full_logged_total 2857
telemt_desync_suppressed_total 6404
telemt_desync_frames_bucket_total{bucket="1_2"} 2549
telemt_desync_frames_bucket_total{bucket="3_10"} 3467
telemt_desync_frames_bucket_total{bucket="gt_10"} 3245
telemt_pool_swap_total 69
telemt_pool_force_close_total 2109
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 21414
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2068
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19305
telemt_me_writer_teardown_success_total{mode="normal"} 21612
telemt_me_writer_teardown_noop_total 21418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.788751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1735409
telemt_user_connections_current{user="hello"} 1734
telemt_user_octets_from_client{user="hello"} 27072172412 (25.21 GB)
telemt_user_octets_to_client{user="hello"} 501166929108 (466.75 GB)
telemt_user_unique_ips_current{user="hello"} 668
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 76413.9 (21h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3308173
telemt_connections_bad_total 300140
telemt_connections_current 1846
telemt_connections_me_current 1846
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 78403
telemt_upstream_connect_attempt_total 48825
telemt_upstream_connect_success_total 48239
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 48758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5581
telemt_me_reconnect_success_total 1891
telemt_me_reader_eof_total 1817
telemt_me_idle_close_by_peer_total 1817
telemt_me_route_drop_no_conn_total 3176521
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2616551
telemt_me_endpoint_quarantine_total 625
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 593
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 10225
telemt_desync_full_logged_total 5686
telemt_desync_suppressed_total 4539
telemt_desync_frames_bucket_total{bucket="1_2"} 2417
telemt_desync_frames_bucket_total{bucket="3_10"} 4036
telemt_desync_frames_bucket_total{bucket="gt_10"} 3772
telemt_pool_swap_total 73
telemt_pool_force_close_total 2144
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 30304
telemt_me_writer_removed_unexpected_total 1775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28561
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28160
telemt_me_writer_teardown_success_total{mode="normal"} 32080
telemt_me_writer_teardown_noop_total 30304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62384
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.101002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62384
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2627993
telemt_user_connections_current{user="hello"} 1846
telemt_user_octets_from_client{user="hello"} 31366068739 (29.21 GB)
telemt_user_octets_to_client{user="hello"} 590762706698 (550.19 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1212
telemt_user_unique_ips_recent_window{user="hello"} 785
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 151273.9 (42h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14557611
telemt_connections_bad_total 1292531
telemt_connections_current 5884
telemt_connections_me_current 5884
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 361115
telemt_upstream_connect_attempt_total 69025
telemt_upstream_connect_success_total 68934
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 68951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1650
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2527
telemt_me_reconnect_success_total 1311
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1249
telemt_me_route_drop_no_conn_total 12928379
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11665999
telemt_me_endpoint_quarantine_total 960
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1123
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
telemt_me_writers_warm_current 22
telemt_desync_total 47359
telemt_desync_full_logged_total 14918
telemt_desync_suppressed_total 32441
telemt_desync_frames_bucket_total{bucket="1_2"} 10713
telemt_desync_frames_bucket_total{bucket="3_10"} 18537
telemt_desync_frames_bucket_total{bucket="gt_10"} 18109
telemt_pool_swap_total 162
telemt_pool_force_close_total 5511
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 897
telemt_me_draining_writers_reap_progress_total 49824
telemt_me_writer_removed_unexpected_total 1205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44313
telemt_me_writer_teardown_success_total{mode="normal"} 50349
telemt_me_writer_teardown_noop_total 49873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100222
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.457895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100222
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 897
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1125
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11667805
telemt_user_connections_current{user="hello"} 5884
telemt_user_octets_from_client{user="hello"} 164832290589 (153.51 GB)
telemt_user_octets_to_client{user="hello"} 3049111498819 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 2298
telemt_user_unique_ips_recent_window{user="hello"} 1077
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 151275.3 (42h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10656465
telemt_connections_bad_total 1020538
telemt_connections_current 4726
telemt_connections_me_current 4726
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 316447
telemt_upstream_connect_attempt_total 81059
telemt_upstream_connect_success_total 79913
telemt_upstream_connect_fail_total 823
telemt_upstream_connect_attempts_per_request{bucket="1"} 80736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 823
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3712
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1358
telemt_me_route_drop_no_conn_total 4232886
telemt_me_route_drop_channel_closed_total 461
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7958738
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1145
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 28
telemt_desync_total 35415
telemt_desync_full_logged_total 11911
telemt_desync_suppressed_total 23504
telemt_desync_frames_bucket_total{bucket="1_2"} 8721
telemt_desync_frames_bucket_total{bucket="3_10"} 13635
telemt_desync_frames_bucket_total{bucket="gt_10"} 13059
telemt_pool_swap_total 161
telemt_pool_force_close_total 4976
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 624
telemt_me_draining_writers_reap_progress_total 48033
telemt_me_writer_removed_unexpected_total 1390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44908
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 431
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43057
telemt_me_writer_teardown_success_total{mode="normal"} 49280
telemt_me_writer_teardown_noop_total 48048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.282787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 624
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1259
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 7897920
telemt_user_connections_current{user="hello"} 4726
telemt_user_octets_from_client{user="hello"} 198948957641 (185.29 GB)
telemt_user_octets_to_client{user="hello"} 3558006469822 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1949
telemt_user_unique_ips_recent_window{user="hello"} 651
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 151239.4 (42h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10114003
telemt_connections_bad_total 859467
telemt_connections_current 4381
telemt_connections_me_current 4381
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 325100
telemt_upstream_connect_attempt_total 66472
telemt_upstream_connect_success_total 65553
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 65735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4535
telemt_me_reconnect_success_total 1843
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 5007631
telemt_me_route_drop_channel_closed_total 343
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7640134
telemt_me_endpoint_quarantine_total 1040
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1108
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 3
telemt_desync_total 35245
telemt_desync_full_logged_total 11667
telemt_desync_suppressed_total 23578
telemt_desync_frames_bucket_total{bucket="1_2"} 8924
telemt_desync_frames_bucket_total{bucket="3_10"} 13483
telemt_desync_frames_bucket_total{bucket="gt_10"} 12838
telemt_pool_swap_total 157
telemt_pool_force_close_total 4928
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 48659
telemt_me_writer_removed_unexpected_total 1740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45434
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4399
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 529
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43731
telemt_me_writer_teardown_success_total{mode="normal"} 50308
telemt_me_writer_teardown_noop_total 48729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99037
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3165.441010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99037
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1600
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7633634
telemt_user_connections_current{user="hello"} 4381
telemt_user_octets_from_client{user="hello"} 177853463601 (165.64 GB)
telemt_user_octets_to_client{user="hello"} 3170793940997 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1815
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 21533.9 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9121992
telemt_connections_bad_total 576210
telemt_connections_current 7258
telemt_connections_me_current 7258
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 145876
telemt_upstream_connect_attempt_total 29212
telemt_upstream_connect_success_total 27766
telemt_upstream_connect_fail_total 1033
telemt_upstream_connect_attempts_per_request{bucket="1"} 28799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4760
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1033
telemt_me_keepalive_timeout_total 850
telemt_me_reconnect_attempts_total 5521
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 22513375
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7588968
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 164
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
telemt_me_writers_active_current 44
telemt_desync_total 11298
telemt_desync_full_logged_total 2898
telemt_desync_suppressed_total 8400
telemt_desync_frames_bucket_total{bucket="1_2"} 1972
telemt_desync_frames_bucket_total{bucket="3_10"} 4565
telemt_desync_frames_bucket_total{bucket="gt_10"} 4761
telemt_pool_swap_total 19
telemt_pool_force_close_total 821
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 293
telemt_me_draining_writers_reap_progress_total 5695
telemt_me_writer_removed_unexpected_total 512
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 989
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5181
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 560
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 261
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4874
telemt_me_writer_teardown_success_total{mode="normal"} 6170
telemt_me_writer_teardown_noop_total 5699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.063953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 293
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 428
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7603691
telemt_user_connections_current{user="hello"} 7258
telemt_user_octets_from_client{user="hello"} 43847928427 (40.84 GB)
telemt_user_octets_to_client{user="hello"} 221722476052 (206.50 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2537
telemt_user_unique_ips_recent_window{user="hello"} 1395
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 151245.7 (42h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9839875
telemt_connections_bad_total 818575
telemt_connections_current 5204
telemt_connections_me_current 5204
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 214677
telemt_upstream_connect_attempt_total 90968
telemt_upstream_connect_success_total 90050
telemt_upstream_connect_fail_total 796
telemt_upstream_connect_attempts_per_request{bucket="1"} 90846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 796
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71448
telemt_me_reconnect_success_total 2478
telemt_me_reader_eof_total 2209
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 4870202
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7766069
telemt_me_endpoint_quarantine_total 1014
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1125
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
telemt_me_writers_warm_current 10
telemt_desync_total 39904
telemt_desync_full_logged_total 13663
telemt_desync_suppressed_total 26241
telemt_desync_frames_bucket_total{bucket="1_2"} 8114
telemt_desync_frames_bucket_total{bucket="3_10"} 15479
telemt_desync_frames_bucket_total{bucket="gt_10"} 16311
telemt_pool_swap_total 154
telemt_pool_force_close_total 4592
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 560
telemt_me_draining_writers_reap_progress_total 51455
telemt_me_writer_removed_unexpected_total 2235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5444
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48264
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46863
telemt_me_writer_teardown_success_total{mode="normal"} 53708
telemt_me_writer_teardown_noop_total 51456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.972999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 560
telemt_me_refill_failed_total 4255
telemt_me_writer_restored_same_endpoint_total 2083
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 7766783
telemt_user_connections_current{user="hello"} 5204
telemt_user_octets_from_client{user="hello"} 177736245271 (165.53 GB)
telemt_user_octets_to_client{user="hello"} 2930207411285 (2.67 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2112
telemt_user_unique_ips_recent_window{user="hello"} 670
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 88081.7 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10042832
telemt_connections_bad_total 366024
telemt_connections_current 4495
telemt_connections_me_current 4495
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4230627
telemt_upstream_connect_attempt_total 43034
telemt_upstream_connect_success_total 42724
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 43027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 47941
telemt_me_reconnect_success_total 1454
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 3750612
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4830920
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 661
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 26393
telemt_desync_full_logged_total 8905
telemt_desync_suppressed_total 17488
telemt_desync_frames_bucket_total{bucket="1_2"} 5348
telemt_desync_frames_bucket_total{bucket="3_10"} 10440
telemt_desync_frames_bucket_total{bucket="gt_10"} 10605
telemt_pool_swap_total 92
telemt_pool_force_close_total 2860
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 295
telemt_me_draining_writers_reap_progress_total 30324
telemt_me_writer_removed_unexpected_total 1189
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27464
telemt_me_writer_teardown_success_total{mode="normal"} 31541
telemt_me_writer_teardown_noop_total 30331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.291007
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 295
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1301
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4825089
telemt_user_connections_current{user="hello"} 4495
telemt_user_octets_from_client{user="hello"} 104613995884 (97.43 GB)
telemt_user_octets_to_client{user="hello"} 1820734055106 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1834
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69052.9 (19h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850342
telemt_connections_bad_total 10756
telemt_connections_current 946
telemt_connections_me_current 946
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 16335
telemt_upstream_connect_attempt_total 34667
telemt_upstream_connect_success_total 34581
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 34651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 1565
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 643
telemt_me_idle_close_by_peer_total 643
telemt_me_route_drop_no_conn_total 292554
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757702
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
telemt_desync_total 4211
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 2942
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 1676
telemt_desync_frames_bucket_total{bucket="gt_10"} 1534
telemt_pool_swap_total 73
telemt_pool_force_close_total 1825
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 28537
telemt_me_writer_removed_unexpected_total 622
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26988
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1747
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26712
telemt_me_writer_teardown_success_total{mode="normal"} 29182
telemt_me_writer_teardown_noop_total 28539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57721
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.183578
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57721
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 758886
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 13972743969 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 353286271675 (329.02 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 151250.3 (42h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12019745
telemt_connections_bad_total 1402946
telemt_connections_current 6196
telemt_connections_me_current 6196
telemt_handshake_timeouts_total 328881
telemt_upstream_connect_attempt_total 56754
telemt_upstream_connect_success_total 56531
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 56704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2212
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1150
telemt_me_idle_close_by_peer_total 1150
telemt_me_route_drop_no_conn_total 3901365
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9057524
telemt_me_endpoint_quarantine_total 1029
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1130
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 15
telemt_desync_total 37235
telemt_desync_full_logged_total 12182
telemt_desync_suppressed_total 25053
telemt_desync_frames_bucket_total{bucket="1_2"} 8873
telemt_desync_frames_bucket_total{bucket="3_10"} 13800
telemt_desync_frames_bucket_total{bucket="gt_10"} 14562
telemt_pool_swap_total 167
telemt_pool_force_close_total 4614
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 587
telemt_me_draining_writers_reap_progress_total 51092
telemt_me_writer_removed_unexpected_total 1106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48031
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46478
telemt_me_writer_teardown_success_total{mode="normal"} 52228
telemt_me_writer_teardown_noop_total 51094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103322
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.318197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103322
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 587
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1042
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 9027397
telemt_user_connections_current{user="hello"} 6196
telemt_user_octets_from_client{user="hello"} 173626980916 (161.70 GB)
telemt_user_octets_to_client{user="hello"} 4028366502216 (3.66 TB)
telemt_user_unique_ips_current{user="hello"} 2333
telemt_user_unique_ips_recent_window{user="hello"} 821
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 151246.6 (42h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10389543
telemt_connections_bad_total 1161752
telemt_connections_current 5307
telemt_connections_me_current 5307
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 270041
telemt_upstream_connect_attempt_total 82290
telemt_upstream_connect_success_total 81680
telemt_upstream_connect_fail_total 528
telemt_upstream_connect_attempts_per_request{bucket="1"} 82208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2010
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 528
telemt_me_reconnect_attempts_total 8717
telemt_me_reconnect_success_total 1971
telemt_me_reader_eof_total 1834
telemt_me_idle_close_by_peer_total 1834
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4897450
telemt_me_route_drop_channel_closed_total 330
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8013687
telemt_me_endpoint_quarantine_total 1149
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1134
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 12
telemt_desync_total 36668
telemt_desync_full_logged_total 11894
telemt_desync_suppressed_total 24774
telemt_desync_frames_bucket_total{bucket="1_2"} 9096
telemt_desync_frames_bucket_total{bucket="3_10"} 13681
telemt_desync_frames_bucket_total{bucket="gt_10"} 13891
telemt_pool_swap_total 160
telemt_pool_force_close_total 4472
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 50377
telemt_me_writer_removed_unexpected_total 1859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47077
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45905
telemt_me_writer_teardown_success_total{mode="normal"} 52303
telemt_me_writer_teardown_noop_total 50381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.710921
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 346
telemt_me_writer_restored_same_endpoint_total 1595
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8020220
telemt_user_connections_current{user="hello"} 5307
telemt_user_octets_from_client{user="hello"} 141285076601 (131.58 GB)
telemt_user_octets_to_client{user="hello"} 3105897820363 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2099
telemt_user_unique_ips_recent_window{user="hello"} 727
```