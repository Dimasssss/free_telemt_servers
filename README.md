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

# Server Metrics 2026-03-21 09:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47432.3 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1336477
telemt_connections_bad_total 68910
telemt_connections_current 1647
telemt_connections_me_current 1647
telemt_handshake_timeouts_total 54315
telemt_upstream_connect_attempt_total 18710
telemt_upstream_connect_success_total 18629
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 842
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 731939
telemt_me_route_drop_channel_closed_total 246
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010072
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_active_current 89
telemt_desync_total 4257
telemt_desync_full_logged_total 1460
telemt_desync_suppressed_total 2797
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1663
telemt_desync_frames_bucket_total{bucket="gt_10"} 1703
telemt_pool_swap_total 51
telemt_pool_force_close_total 1431
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 16722
telemt_me_writer_removed_unexpected_total 353
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1315
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15291
telemt_me_writer_teardown_success_total{mode="normal"} 16973
telemt_me_writer_teardown_noop_total 16723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 82.826020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1009291
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 14393540203 (13.41 GB)
telemt_user_octets_to_client{user="hello"} 286887784103 (267.19 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 47433.6 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3386801
telemt_connections_bad_total 365662
telemt_connections_current 4614
telemt_connections_me_current 4614
telemt_handshake_timeouts_total 99906
telemt_upstream_connect_attempt_total 17015
telemt_upstream_connect_success_total 16936
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 16990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 987
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 375
telemt_me_route_drop_no_conn_total 1421080
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2270642
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 366
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
telemt_me_writers_active_current 44
telemt_desync_total 9791
telemt_desync_full_logged_total 3301
telemt_desync_suppressed_total 6490
telemt_desync_frames_bucket_total{bucket="1_2"} 1994
telemt_desync_frames_bucket_total{bucket="3_10"} 3879
telemt_desync_frames_bucket_total{bucket="gt_10"} 3918
telemt_pool_swap_total 51
telemt_pool_force_close_total 1560
telemt_me_writer_close_signal_drop_total 184
telemt_me_draining_writers_reap_progress_total 15233
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1403
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14166
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13673
telemt_me_writer_teardown_success_total{mode="normal"} 15569
telemt_me_writer_teardown_noop_total 15233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30802
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.316044
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30802
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 184
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 307
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2266356
telemt_user_connections_current{user="hello"} 4614
telemt_user_octets_from_client{user="hello"} 32157692688 (29.95 GB)
telemt_user_octets_to_client{user="hello"} 778054536012 (724.62 GB)
telemt_user_unique_ips_current{user="hello"} 1719
telemt_user_unique_ips_recent_window{user="hello"} 698
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 47430.0 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2481851
telemt_connections_bad_total 299647
telemt_connections_current 4442
telemt_connections_me_current 4442
telemt_handshake_timeouts_total 94652
telemt_upstream_connect_attempt_total 18493
telemt_upstream_connect_success_total 18482
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 617
telemt_me_reconnect_success_total 348
telemt_me_reader_eof_total 362
telemt_me_idle_close_by_peer_total 362
telemt_me_route_drop_no_conn_total 998491
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1934248
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 371
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
telemt_me_writers_active_current 47
telemt_desync_total 8378
telemt_desync_full_logged_total 2903
telemt_desync_suppressed_total 5475
telemt_desync_frames_bucket_total{bucket="1_2"} 1767
telemt_desync_frames_bucket_total{bucket="3_10"} 3293
telemt_desync_frames_bucket_total{bucket="gt_10"} 3318
telemt_pool_swap_total 51
telemt_pool_force_close_total 1529
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 16826
telemt_me_writer_removed_unexpected_total 341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15667
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15297
telemt_me_writer_teardown_success_total{mode="normal"} 17049
telemt_me_writer_teardown_noop_total 16837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33886
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.280249
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33886
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1931130
telemt_user_connections_current{user="hello"} 4442
telemt_user_octets_from_client{user="hello"} 30152254752 (28.08 GB)
telemt_user_octets_to_client{user="hello"} 736852224516 (686.25 GB)
telemt_user_unique_ips_current{user="hello"} 1587
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 47431.2 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2034913
telemt_connections_bad_total 233032
telemt_connections_current 2831
telemt_connections_me_current 2831
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 87157
telemt_upstream_connect_attempt_total 23427
telemt_upstream_connect_success_total 23191
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 23316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 997
telemt_me_reconnect_success_total 440
telemt_me_reader_eof_total 407
telemt_me_idle_close_by_peer_total 407
telemt_me_route_drop_no_conn_total 586006
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1418193
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 373
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
telemt_desync_total 6635
telemt_desync_full_logged_total 2274
telemt_desync_suppressed_total 4361
telemt_desync_frames_bucket_total{bucket="1_2"} 1641
telemt_desync_frames_bucket_total{bucket="3_10"} 2639
telemt_desync_frames_bucket_total{bucket="gt_10"} 2355
telemt_pool_swap_total 51
telemt_pool_force_close_total 1391
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 16702
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15311
telemt_me_writer_teardown_success_total{mode="normal"} 17116
telemt_me_writer_teardown_noop_total 16703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.055397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 370
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1420192
telemt_user_connections_current{user="hello"} 2831
telemt_user_octets_from_client{user="hello"} 28627909505 (26.66 GB)
telemt_user_octets_to_client{user="hello"} 680964049275 (634.20 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1090
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 47395.3 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1955868
telemt_connections_bad_total 222572
telemt_connections_current 3583
telemt_connections_me_current 3583
telemt_handshake_timeouts_total 62965
telemt_upstream_connect_attempt_total 19703
telemt_upstream_connect_success_total 19663
telemt_upstream_connect_attempts_per_request{bucket="1"} 19663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 441
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 546253
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1413700
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 364
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
telemt_me_writers_active_current 111
telemt_desync_total 6498
telemt_desync_full_logged_total 2276
telemt_desync_suppressed_total 4222
telemt_desync_frames_bucket_total{bucket="1_2"} 1706
telemt_desync_frames_bucket_total{bucket="3_10"} 2503
telemt_desync_frames_bucket_total{bucket="gt_10"} 2289
telemt_pool_swap_total 50
telemt_pool_force_close_total 1323
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 17658
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1326
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16739
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16335
telemt_me_writer_teardown_success_total{mode="normal"} 18065
telemt_me_writer_teardown_noop_total 17661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.921139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 394
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1411366
telemt_user_connections_current{user="hello"} 3584
telemt_user_octets_from_client{user="hello"} 33120711952 (30.85 GB)
telemt_user_octets_to_client{user="hello"} 699085906612 (651.07 GB)
telemt_user_unique_ips_current{user="hello"} 1470
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47434.6 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5785854
telemt_connections_bad_total 301307
telemt_connections_current 6012
telemt_connections_me_current 6012
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 229100
telemt_upstream_connect_attempt_total 58894
telemt_upstream_connect_success_total 56310
telemt_upstream_connect_fail_total 1915
telemt_upstream_connect_attempts_per_request{bucket="1"} 58225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1915
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2807
telemt_me_reconnect_success_total 975
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 677
telemt_me_route_drop_no_conn_total 9556945
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4883240
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 115
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 115
telemt_me_single_endpoint_shadow_rotate_total 375
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 9864
telemt_desync_full_logged_total 3259
telemt_desync_suppressed_total 6605
telemt_desync_frames_bucket_total{bucket="1_2"} 2179
telemt_desync_frames_bucket_total{bucket="3_10"} 4251
telemt_desync_frames_bucket_total{bucket="gt_10"} 3434
telemt_pool_swap_total 48
telemt_pool_force_close_total 1495
telemt_me_writer_close_signal_drop_total 296
telemt_me_draining_writers_reap_progress_total 16087
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2046
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14911
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14592
telemt_me_writer_teardown_success_total{mode="normal"} 16957
telemt_me_writer_teardown_noop_total 16093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33050
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.574448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33050
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 296
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 674
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 4917925
telemt_user_connections_current{user="hello"} 6012
telemt_user_octets_from_client{user="hello"} 46978728860 (43.75 GB)
telemt_user_octets_to_client{user="hello"} 573249553915 (533.88 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1857
telemt_user_unique_ips_recent_window{user="hello"} 1244
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 47402.4 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1999529
telemt_connections_bad_total 255652
telemt_connections_current 3730
telemt_connections_me_current 3730
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 38948
telemt_upstream_connect_attempt_total 21033
telemt_upstream_connect_success_total 20823
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 21014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_reconnect_attempts_total 1960
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 604779
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1498458
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 369
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
telemt_me_writers_active_current 89
telemt_desync_total 6804
telemt_desync_full_logged_total 2481
telemt_desync_suppressed_total 4323
telemt_desync_frames_bucket_total{bucket="1_2"} 1320
telemt_desync_frames_bucket_total{bucket="3_10"} 2757
telemt_desync_frames_bucket_total{bucket="gt_10"} 2727
telemt_pool_swap_total 49
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 17396
telemt_me_writer_removed_unexpected_total 617
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16469
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16113
telemt_me_writer_teardown_success_total{mode="normal"} 18036
telemt_me_writer_teardown_noop_total 17396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35432
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.581152
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35432
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1494468
telemt_user_connections_current{user="hello"} 3730
telemt_user_octets_from_client{user="hello"} 27303050380 (25.43 GB)
telemt_user_octets_to_client{user="hello"} 691201969246 (643.73 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1583
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 47396.8 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2794230
telemt_connections_bad_total 159876
telemt_connections_current 3108
telemt_connections_me_current 3108
telemt_handshake_timeouts_total 1141643
telemt_upstream_connect_attempt_total 19748
telemt_upstream_connect_success_total 19714
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 520
telemt_me_reconnect_success_total 300
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 518807
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1332398
telemt_me_endpoint_quarantine_total 365
telemt_me_single_endpoint_shadow_rotate_total 374
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 6621
telemt_desync_full_logged_total 2332
telemt_desync_suppressed_total 4289
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 2652
telemt_desync_frames_bucket_total{bucket="gt_10"} 2796
telemt_pool_swap_total 52
telemt_pool_force_close_total 1269
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 17702
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16888
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16433
telemt_me_writer_teardown_success_total{mode="normal"} 18012
telemt_me_writer_teardown_noop_total 17702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35714
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.927010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35714
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1328143
telemt_user_connections_current{user="hello"} 3108
telemt_user_octets_from_client{user="hello"} 23431731884 (21.82 GB)
telemt_user_octets_to_client{user="hello"} 658069817112 (612.88 GB)
telemt_user_unique_ips_current{user="hello"} 1216
telemt_user_unique_ips_recent_window{user="hello"} 525
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45387.9 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 591590
telemt_connections_bad_total 20632
telemt_connections_current 610
telemt_connections_me_current 610
telemt_handshake_timeouts_total 219876
telemt_upstream_connect_attempt_total 22205
telemt_upstream_connect_success_total 22203
telemt_upstream_connect_attempts_per_request{bucket="1"} 22203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 917
telemt_me_reconnect_success_total 366
telemt_me_reader_eof_total 362
telemt_me_idle_close_by_peer_total 362
telemt_me_route_drop_no_conn_total 124517
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305698
telemt_me_endpoint_quarantine_total 439
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 390
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 1936
telemt_desync_full_logged_total 779
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 756
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 50
telemt_pool_force_close_total 1087
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 19839
telemt_me_writer_removed_unexpected_total 343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18754
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18752
telemt_me_writer_teardown_success_total{mode="normal"} 20186
telemt_me_writer_teardown_noop_total 19839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40025
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.859669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40025
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 305866
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 4495664199 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 121735487005 (113.38 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 47406.4 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2079063
telemt_connections_bad_total 185660
telemt_connections_current 3954
telemt_connections_me_current 3954
telemt_handshake_timeouts_total 52376
telemt_upstream_connect_attempt_total 20421
telemt_upstream_connect_success_total 20334
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 20391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 404
telemt_me_idle_close_by_peer_total 404
telemt_me_route_drop_no_conn_total 516324
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1640540
telemt_me_endpoint_quarantine_total 373
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_me_writers_active_current 44
telemt_desync_total 6488
telemt_desync_full_logged_total 2171
telemt_desync_suppressed_total 4317
telemt_desync_frames_bucket_total{bucket="1_2"} 1575
telemt_desync_frames_bucket_total{bucket="3_10"} 2416
telemt_desync_frames_bucket_total{bucket="gt_10"} 2497
telemt_pool_swap_total 52
telemt_pool_force_close_total 1286
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18413
telemt_me_writer_removed_unexpected_total 403
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17465
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17127
telemt_me_writer_teardown_success_total{mode="normal"} 18825
telemt_me_writer_teardown_noop_total 18413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.534720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 391
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1634999
telemt_user_connections_current{user="hello"} 3954
telemt_user_octets_from_client{user="hello"} 37175497792 (34.62 GB)
telemt_user_octets_to_client{user="hello"} 762844152244 (710.45 GB)
telemt_user_unique_ips_current{user="hello"} 1453
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 47403.2 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1949308
telemt_connections_bad_total 160074
telemt_connections_current 3635
telemt_connections_me_current 3635
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 47567
telemt_upstream_connect_attempt_total 29078
telemt_upstream_connect_success_total 28870
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 29036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 2943
telemt_me_reconnect_success_total 602
telemt_me_reader_eof_total 524
telemt_me_idle_close_by_peer_total 524
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 529545
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1565069
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 371
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 5944
telemt_desync_full_logged_total 1989
telemt_desync_suppressed_total 3955
telemt_desync_frames_bucket_total{bucket="1_2"} 1634
telemt_desync_frames_bucket_total{bucket="3_10"} 2196
telemt_desync_frames_bucket_total{bucket="gt_10"} 2114
telemt_pool_swap_total 51
telemt_pool_force_close_total 1260
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 17699
telemt_me_writer_removed_unexpected_total 534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16652
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16439
telemt_me_writer_teardown_success_total{mode="normal"} 18259
telemt_me_writer_teardown_noop_total 17700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.404799
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 133
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1568819
telemt_user_connections_current{user="hello"} 3635
telemt_user_octets_from_client{user="hello"} 26023284899 (24.24 GB)
telemt_user_octets_to_client{user="hello"} 699709673031 (651.66 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1374
telemt_user_unique_ips_recent_window{user="hello"} 527
```