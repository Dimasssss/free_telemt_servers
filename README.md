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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 11:33:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 53876.3 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1643839
telemt_connections_bad_total 83000
telemt_connections_current 1484
telemt_connections_me_current 1484
telemt_handshake_timeouts_total 65451
telemt_upstream_connect_attempt_total 21019
telemt_upstream_connect_success_total 20912
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 20981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1061
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 1002523
telemt_me_route_drop_channel_closed_total 388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1265429
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_desync_total 5160
telemt_desync_full_logged_total 1809
telemt_desync_suppressed_total 3351
telemt_desync_frames_bucket_total{bucket="1_2"} 1089
telemt_desync_frames_bucket_total{bucket="3_10"} 1992
telemt_desync_frames_bucket_total{bucket="gt_10"} 2079
telemt_pool_swap_total 58
telemt_pool_force_close_total 1699
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 300
telemt_me_draining_writers_reap_progress_total 18778
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1531
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17540
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1638
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17079
telemt_me_writer_teardown_success_total{mode="normal"} 19071
telemt_me_writer_teardown_noop_total 18782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 123.018703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 300
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1264544
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 17886546359 (16.66 GB)
telemt_user_octets_to_client{user="hello"} 346224473179 (322.45 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1767.5 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122565
telemt_connections_bad_total 6584
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_handshake_timeouts_total 4291
telemt_upstream_connect_attempt_total 591
telemt_upstream_connect_success_total 589
telemt_upstream_connect_attempts_per_request{bucket="1"} 589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 79888
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104795
telemt_me_endpoint_quarantine_total 11
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 390
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 455
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 434
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 423
telemt_me_writer_teardown_success_total{mode="normal"} 466
telemt_me_writer_teardown_noop_total 455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 921
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.151646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 921
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 9
telemt_user_connections_total{user="hello"} 104759
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 1268151324 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 25780806636 (24.01 GB)
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 53874.0 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3150458
telemt_connections_bad_total 339967
telemt_connections_current 4400
telemt_connections_me_current 4400
telemt_handshake_timeouts_total 115030
telemt_upstream_connect_attempt_total 20503
telemt_upstream_connect_success_total 20490
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 694
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 1367312
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2508214
telemt_me_endpoint_quarantine_total 351
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_desync_total 10975
telemt_desync_full_logged_total 3701
telemt_desync_suppressed_total 7274
telemt_desync_frames_bucket_total{bucket="1_2"} 2294
telemt_desync_frames_bucket_total{bucket="3_10"} 4295
telemt_desync_frames_bucket_total{bucket="gt_10"} 4386
telemt_pool_swap_total 58
telemt_pool_force_close_total 1771
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 18650
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17353
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16879
telemt_me_writer_teardown_success_total{mode="normal"} 18886
telemt_me_writer_teardown_noop_total 18663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.785759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 2504733
telemt_user_connections_current{user="hello"} 4400
telemt_user_octets_from_client{user="hello"} 41091275092 (38.27 GB)
telemt_user_octets_to_client{user="hello"} 911876424276 (849.25 GB)
telemt_user_unique_ips_current{user="hello"} 1734
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 53875.4 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2608918
telemt_connections_bad_total 287794
telemt_connections_current 3514
telemt_connections_me_current 3514
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 107596
telemt_upstream_connect_attempt_total 25423
telemt_upstream_connect_success_total 25164
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1070
telemt_me_reconnect_success_total 499
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 769130
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1842810
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 8421
telemt_desync_full_logged_total 2889
telemt_desync_suppressed_total 5532
telemt_desync_frames_bucket_total{bucket="1_2"} 2107
telemt_desync_frames_bucket_total{bucket="3_10"} 3286
telemt_desync_frames_bucket_total{bucket="gt_10"} 3028
telemt_pool_swap_total 58
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 18393
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1542
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16786
telemt_me_writer_teardown_success_total{mode="normal"} 18861
telemt_me_writer_teardown_noop_total 18394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37255
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.170346
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37255
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1844304
telemt_user_connections_current{user="hello"} 3514
telemt_user_octets_from_client{user="hello"} 35261724021 (32.84 GB)
telemt_user_octets_to_client{user="hello"} 885225113863 (824.43 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1367
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 53839.2 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2546383
telemt_connections_bad_total 288117
telemt_connections_current 3554
telemt_connections_me_current 3554
telemt_handshake_timeouts_total 76218
telemt_upstream_connect_attempt_total 21847
telemt_upstream_connect_success_total 21787
telemt_upstream_connect_attempts_per_request{bucket="1"} 21787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 786
telemt_me_reconnect_success_total 533
telemt_me_reader_eof_total 474
telemt_me_idle_close_by_peer_total 474
telemt_me_route_drop_no_conn_total 741935
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1834152
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 410
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
telemt_me_writers_active_current 44
telemt_desync_total 8589
telemt_desync_full_logged_total 2907
telemt_desync_suppressed_total 5682
telemt_desync_frames_bucket_total{bucket="1_2"} 2275
telemt_desync_frames_bucket_total{bucket="3_10"} 3272
telemt_desync_frames_bucket_total{bucket="gt_10"} 3042
telemt_pool_swap_total 57
telemt_pool_force_close_total 1584
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 160
telemt_me_draining_writers_reap_progress_total 19569
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1557
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1467
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17985
telemt_me_writer_teardown_success_total{mode="normal"} 20051
telemt_me_writer_teardown_noop_total 19572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39623
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.444673
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39623
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 160
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1831340
telemt_user_connections_current{user="hello"} 3554
telemt_user_octets_from_client{user="hello"} 41952290564 (39.07 GB)
telemt_user_octets_to_client{user="hello"} 892476884828 (831.18 GB)
telemt_user_unique_ips_current{user="hello"} 1338
telemt_user_unique_ips_recent_window{user="hello"} 529
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 53878.5 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8107523
telemt_connections_bad_total 546952
telemt_connections_current 5197
telemt_connections_me_current 5197
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 285605
telemt_upstream_connect_attempt_total 63807
telemt_upstream_connect_success_total 60098
telemt_upstream_connect_fail_total 2945
telemt_upstream_connect_attempts_per_request{bucket="1"} 63043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2945
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3167
telemt_me_reconnect_success_total 1094
telemt_me_reader_eof_total 791
telemt_me_idle_close_by_peer_total 790
telemt_me_route_drop_no_conn_total 14133650
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6750731
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_me_writers_active_current 45
telemt_desync_total 12817
telemt_desync_full_logged_total 4130
telemt_desync_suppressed_total 8687
telemt_desync_frames_bucket_total{bucket="1_2"} 2778
telemt_desync_frames_bucket_total{bucket="3_10"} 5652
telemt_desync_frames_bucket_total{bucket="gt_10"} 4387
telemt_pool_swap_total 54
telemt_pool_force_close_total 1694
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 350
telemt_me_draining_writers_reap_progress_total 17946
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2300
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16599
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16252
telemt_me_writer_teardown_success_total{mode="normal"} 18899
telemt_me_writer_teardown_noop_total 17955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.440735
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 350
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 6786435
telemt_user_connections_current{user="hello"} 5197
telemt_user_octets_from_client{user="hello"} 56281660000 (52.42 GB)
telemt_user_octets_to_client{user="hello"} 646350286947 (601.96 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1883
telemt_user_unique_ips_recent_window{user="hello"} 1112
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 53846.2 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2563222
telemt_connections_bad_total 312531
telemt_connections_current 3604
telemt_connections_me_current 3604
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 56651
telemt_upstream_connect_attempt_total 23286
telemt_upstream_connect_success_total 23042
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 23261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 2231
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 749
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 879569
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1939822
telemt_me_endpoint_quarantine_total 342
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 412
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
telemt_me_writers_active_current 45
telemt_desync_total 8860
telemt_desync_full_logged_total 3195
telemt_desync_suppressed_total 5665
telemt_desync_frames_bucket_total{bucket="1_2"} 1704
telemt_desync_frames_bucket_total{bucket="3_10"} 3573
telemt_desync_frames_bucket_total{bucket="gt_10"} 3583
telemt_pool_swap_total 55
telemt_pool_force_close_total 1511
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 19380
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1810
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18319
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17869
telemt_me_writer_teardown_success_total{mode="normal"} 20129
telemt_me_writer_teardown_noop_total 19380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.157802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1925163
telemt_user_connections_current{user="hello"} 3604
telemt_user_octets_from_client{user="hello"} 34973000300 (32.57 GB)
telemt_user_octets_to_client{user="hello"} 863295738618 (804.01 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1473
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 53840.6 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3793580
telemt_connections_bad_total 198059
telemt_connections_current 3554
telemt_connections_me_current 3554
telemt_handshake_timeouts_total 1637803
telemt_upstream_connect_attempt_total 21860
telemt_upstream_connect_success_total 21826
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 775
telemt_me_reconnect_success_total 391
telemt_me_reader_eof_total 390
telemt_me_idle_close_by_peer_total 390
telemt_me_route_drop_no_conn_total 729402
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1719878
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 422
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 8419
telemt_desync_full_logged_total 3006
telemt_desync_suppressed_total 5413
telemt_desync_frames_bucket_total{bucket="1_2"} 1549
telemt_desync_frames_bucket_total{bucket="3_10"} 3346
telemt_desync_frames_bucket_total{bucket="gt_10"} 3524
telemt_pool_swap_total 58
telemt_pool_force_close_total 1458
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 19557
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18647
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1411
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18099
telemt_me_writer_teardown_success_total{mode="normal"} 19956
telemt_me_writer_teardown_noop_total 19557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.042766
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1713861
telemt_user_connections_current{user="hello"} 3554
telemt_user_octets_from_client{user="hello"} 30362090348 (28.28 GB)
telemt_user_octets_to_client{user="hello"} 831491516484 (774.39 GB)
telemt_user_unique_ips_current{user="hello"} 1411
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 51832.2 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786415
telemt_connections_bad_total 47103
telemt_connections_current 691
telemt_connections_me_current 691
telemt_handshake_timeouts_total 287578
telemt_upstream_connect_attempt_total 24927
telemt_upstream_connect_success_total 24925
telemt_upstream_connect_attempts_per_request{bucket="1"} 24925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1077
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 164350
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390081
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 444
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 2670
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 1644
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 955
telemt_desync_frames_bucket_total{bucket="gt_10"} 1286
telemt_pool_swap_total 57
telemt_pool_force_close_total 1267
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 22327
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21087
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21060
telemt_me_writer_teardown_success_total{mode="normal"} 22718
telemt_me_writer_teardown_noop_total 22327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.573442
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 331
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 390154
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 6303773295 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 150570165869 (140.23 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 53850.5 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2718623
telemt_connections_bad_total 253908
telemt_connections_current 4251
telemt_connections_me_current 4251
telemt_handshake_timeouts_total 70396
telemt_upstream_connect_attempt_total 22637
telemt_upstream_connect_success_total 22541
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 22606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 922
telemt_me_reconnect_success_total 505
telemt_me_reader_eof_total 471
telemt_me_idle_close_by_peer_total 471
telemt_me_route_drop_no_conn_total 722842
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2150383
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_me_writers_active_current 45
telemt_desync_total 8584
telemt_desync_full_logged_total 2858
telemt_desync_suppressed_total 5726
telemt_desync_frames_bucket_total{bucket="1_2"} 2041
telemt_desync_frames_bucket_total{bucket="3_10"} 3215
telemt_desync_frames_bucket_total{bucket="gt_10"} 3328
telemt_pool_swap_total 59
telemt_pool_force_close_total 1479
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 20353
telemt_me_writer_removed_unexpected_total 463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19287
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18874
telemt_me_writer_teardown_success_total{mode="normal"} 20832
telemt_me_writer_teardown_noop_total 20353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.488608
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2143894
telemt_user_connections_current{user="hello"} 4251
telemt_user_octets_from_client{user="hello"} 45054405896 (41.96 GB)
telemt_user_octets_to_client{user="hello"} 1003636841216 (934.71 GB)
telemt_user_unique_ips_current{user="hello"} 1535
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 53847.3 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2492590
telemt_connections_bad_total 195682
telemt_connections_current 4200
telemt_connections_me_current 4200
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 65273
telemt_upstream_connect_attempt_total 38780
telemt_upstream_connect_success_total 38545
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 38737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_reconnect_attempts_total 3207
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 725090
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2007634
telemt_me_endpoint_quarantine_total 465
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 418
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
telemt_desync_total 7567
telemt_desync_full_logged_total 2590
telemt_desync_suppressed_total 4977
telemt_desync_frames_bucket_total{bucket="1_2"} 1984
telemt_desync_frames_bucket_total{bucket="3_10"} 2814
telemt_desync_frames_bucket_total{bucket="gt_10"} 2769
telemt_pool_swap_total 58
telemt_pool_force_close_total 1435
telemt_me_writer_close_signal_drop_total 131
telemt_me_draining_writers_reap_progress_total 19508
telemt_me_writer_removed_unexpected_total 593
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1343
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18073
telemt_me_writer_teardown_success_total{mode="normal"} 20129
telemt_me_writer_teardown_noop_total 19509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.138239
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 131
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 505
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2018505
telemt_user_connections_current{user="hello"} 4200
telemt_user_octets_from_client{user="hello"} 36334057057 (33.84 GB)
telemt_user_octets_to_client{user="hello"} 887171515032 (826.24 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1512
telemt_user_unique_ips_recent_window{user="hello"} 562
```